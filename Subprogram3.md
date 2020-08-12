# Identify the exchange of parameters in subprograms:

## - By Value

*Passing parameters by value means that the function is passed a copy of the value that contains the current parameter.
The values of the call parameters are copied to the parameters of the function header. The function works with a copy of the values so any modification to these values does not affect the value of the variables used in the call.
Although the current parameters (those that appear in the function call) and the formal parameters (those that appear in the function header) have the same name are distinct variables that occupy different positions of memory.
By default, all arguments except arrays are passed by value.*

## - By Reference
*When parameters are passed by reference, the function is sent the memory address of the current parameter and not its value. The function is actually working with the original data and any modification of the value that is made within the function will be made with the current parameter.
To receive the address of the current parameter, the formal parameter must be a pointer.*
~~~c
#include <stdio.h>
int a,b;
void MiSub1 (int x, int *y)
{
 int h = x*4;
 *y = h + x + 3 + a;
}
void MiSub2 (int x)
{
 int b = 2*x;
 a = b + 3;
}
int main ()
{
 a=3;
 b=4;
 MiSub1(a,&b);
 printf(“%d %d”,a,b);
 MiSub2(32);
 printf(“%d %d”,a,b);
} 
~~~
# Describe concepts and characteristics of recursive processes:

## - Direct
*It is the most common, it occurs when a function calls itself one or more times.*
## - Indirect
*It occurs when a function is called indirectly, that is, by another function.*
exaplmes of recursivity:
~~~c++
#include<iostream>
#include<cstdlib>
using namespace std;
int binario(int n){
if(n>1)      binario(n/2);
cout<<n%2;
}
int main( void ){
system(“color 0a”);
int nro;
cout<<“\n\t\t[     RECURSIVIDAD     ]\n“;
cout<<“\t\t————————\n\n“;
cout<<” EJERCICIO 2: Convertir a binario un numero decimal “<<endl<<endl;
do{
cout<<” INGRESE NUMERO: “;
cin>>nro;
if(nro<0) cout<<“\nINGRESE UN NUMERO ENTERO Y POSITIVO… \n“;
}while(nro<0);
cout<<endl;
cout<<“\n Numero:”<<nro<<endl;
cout<<“\n Binario:”;
    binario(nro);
return 0;
}
