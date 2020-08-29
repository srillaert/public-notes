# Abstracting away the machine  
The history of the Fortran programming language  
by Mark Jones Lorenzo

## Errata

p 87
... and floating-point numbers, which could be between 10e-38 and 10e38 ~~decimal digits in length~~

p 183
FACT(N) = ~~FACT(~~N~~)~~ * FACT(N-1)

p 196
According to one observer, the concept of an "undefinition" was an attempt to bridge "two worlds" so they could "coexist": the world of ~~multi-processing~~ *multi-programming* environments that "saved the last-used-state of a subprogram" and those that loaded the "initial-state without preserving the last-used state and therefore all local values were lost."  
Replace "multi-processing" by "multi-programming".
Saving and restoring the state is the concept of "context-switch" in "multi-programming".
