***Developed by Cunxi Yu at University of Massachusetts, Amherst **
**Formal Analysis of Galois Field Arithmetic**

[1] Efficient Parallel Verification of Galois Feild Multipliers. (Best Paper Nomination)
Cunxi Yu and Maciej Ciesielski
IEEE/ACM 22nd Asia and South Pacific Design Automation Conference (ASP-DAC'17), Jan. 16-19, Chiba/Tokyo, Japan.

Tool and examples are in /tool_examples.

Example:
Usage: ./gen_irreducible_poly file.eqn #bitwidth #threads
e.g. ./gen_irreducible_poly Mas64.eqn 64 10 (see log file bellow)

cunxi@xxx:~$ ./gen_irreducible_poly Mas64.eqn 64 20
USAGE: ./gen_eqns somefile.eqn (int)bits (int)threads
Number of results: 64

*** Report starts here ***** (Developed by Cunxi Yu at UMass Amherst. Last modified by Nov. 20 2016)

Successfully reverse engineer P(x) in this GF design
[1] ---------- This is a Galois Feild 64-bit (GF(2^64) multiplication) implemented by P(x) showing bellow ---------

[2] ---------- Irreducible polynomial P(x): x^64+x^21+x^19+x^4+1

[3] --------- Z[63:0] = (A[63:0] X B[63:0]) mod x^64+x^21+x^19+x^4+1

*** Report ends here ******(contact: ycunxi@umass.edu)
