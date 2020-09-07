# Abstracting away the machine  
The history of the Fortran programming language  
by Mark Jones Lorenzo
published 2019
read 2020-08-26
## Errata

p 87
... and floating-point numbers, which could be between 10e-38 and 10e38 ~~decimal digits in length~~

p 183
FACT(N) = ~~FACT(N)~~ *N* * FACT(N-1)

p 196
According to one observer, the concept of an "undefinition" was an attempt to bridge "two worlds" so they could "coexist": the world of ~~multi-processing~~ *multi-programming* environments that "saved the last-used-state of a subprogram" and those that loaded the "initial-state without preserving the last-used state and therefore all local values were lost."  
Replace "multi-processing" by "multi-programming".
Saving and restoring the state is the concept of "context-switch" in "multi-programming".

p 213
~~Before she left, though, she helped develop a FORTRAN compiler that the Computer Sciences Corporation had contracted with Remington Rand to build ...~~  
This happened *after* she left Remington Rand.
The compiler was the LARC scientific compiler, an upgraded variant of the FORTRAN II language.
Betty Holberton, née Snyder, was already working at the David Taylor Model Basin and this was one of the two sites where the LARC, Livermore Automatic Research Computer, was installed.
The two LARC computers were built by Sperry Rand but the provision of a Fortran compiler was beyond the resources of the company, so that project was farmed out to Computer Science Corporation (CSC).
The Navy's LARC was completed in October 1960 and passed its acceptance test in February *1961*.
She was indeed not happy with the CSC compiler as initially delivered : "They delivered the compiler, which was beautifully designed, very poorly documented, and patched at the machine level so we couldn't recompile it or reassemble it."  
Source : LARC Scientific Compiler article on hopl.info https://hopl.info/showlanguage2.prx?exp=2193
