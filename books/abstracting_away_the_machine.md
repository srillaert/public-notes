# Abstracting away the machine  
The history of the Fortran programming language  
by Mark Jones Lorenzo  
published 2019  
read 2020-08-26
## Errata

p 64
In ~~1962~~ *1961* at Bell Telephone Laboratories, John L. Kelly, Jr., along with Max Mathews, would create a recording of a computer-synthesized voice singing a song: "Daisy Bell (Bicycle Built for Two)", written in 1892 by British songwriter Harry Dacre.
Which proved inspirational to Arthur C. Clarke, who saw a demonstration of the ~~704~~ *7094* "singing" and integrated the idea into the novelization and the movie script of 2001: A Space Odyssey (1968).  
The sources are not univocal on this but it seems that Max Mathews created his first music synthesizer, MUSIC I, on an IBM 704 in 1957. However, "Daisy Bell" was probably generated on a IBM 7094 in 1961. The visit of Arthur C. Clarke was probably in 1962.  
Sources :  
Daisy Bell on wikipedia at https://en.wikipedia.org/wiki/Daisy_Bell  
MUSIC, a program written by Max Mathews at https://en.wikipedia.org/wiki/MUSIC-N  
The IBM 7094 is the first computer to sing at https://www.historyofinformation.com/detail.php?entryid=4445

p 87
... and floating-point numbers, which could be between 10e-38 and 10e38 ~~decimal digits in length~~

p 181
And the DOUBLE PRECISION data type was a ~~subset~~ *superset* of the REAL data type.  
A real constant consists of 1-9 significant decimal digits written with a decimal point.
A double-precision constant consists of 1-17 significant decimal digits written with a decimal point.  
Source : IBM 7090/7094 Programming Systems FORTRAN IV Language p.7 http://atwww.bitsavers.org/pdf/ibm/7090/C28-6274-1_7090_FORTRANIV.pdf

p 183
FACT(N) = ~~FACT(N)~~ *N* * FACT(N-1)

p 190
~~Although it had never been done with any programming language before,~~ standardization was indeed the next step in FORTRAN's evolution.  
ALGOL and COBOL were the first languages to seek standardization, around 1960.  
Sources :  
ALGOL 60 Standardization on wikipedia : https://en.wikipedia.org/wiki/ALGOL_60#Standardization  
COBOL 60 on wikipedia : https://en.wikipedia.org/wiki/COBOL#COBOL_60

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
