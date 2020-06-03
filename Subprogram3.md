# Identify the exchange of parameters in subprograms:

## - By Value

*Passing parameters by value means that the function is passed a copy of the value that contains the current parameter.
The values of the call parameters are copied to the parameters of the function header. The function works with a copy of the values so any modification to these values does not affect the value of the variables used in the call.
Although the current parameters (those that appear in the function call) and the formal parameters (those that appear in the function header) have the same name are distinct variables that occupy different positions of memory.
By default, all arguments except arrays are passed by value.*

## - By Reference
*When parameters are passed by reference, the function is sent the memory address of the current parameter and not its value. The function is actually working with the original data and any modification of the value that is made within the function will be made with the current parameter.
To receive the address of the current parameter, the formal parameter must be a pointer.*

# Describe concepts and characteristics of recursive processes:

## - Direct
*It is the most common, it occurs when a function calls itself one or more times.*
## - Indirect
*It occurs when a function is called indirectly, that is, by another function.*
