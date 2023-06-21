# Ising model

Here are the codes to study cell organization based on the implementation of Ising Model.

## CPIM

### Background

The Contact Process Ising Model (CPIM) is a stochastic model for surface colony growth and cell-state differentiation based on cell-cell and cell-external field interactions.
 
This is and hybrid model mixing the Contact Process (CP), which is a general stochastic model of discrete surface spreading, and the Ising Model (IM), which is a statistical mechanics model originally developed to describe the ferromagnetic materials bechaviour. 

Contact Process source code:

https://github.com/jekeymer/Contact-Process

Random Number Generator (RNG) source code:

https://github.com/shivakar/rng-reference/blob/master/MT19937/mt64.h

which implement the [Mersenne Twister](https://es.wikipedia.org/wiki/Mersenne_twister) algorithm:


### Included Codes

They are written in C++ <br>
Currently there are 4 versions which works independently:

*Ising_Model_V0.c*  --> Starting working version

*Ising_Model_V1.c*   --> Current version but JUST INCLUDE COUPLING term (J)

*ising_Model_V1_woGTK.c*   --> V1 without the simulation window. It just store an end point image of the simulation

*Ising_Model_V2.c*   --> Current version which includes the INTERNAL COUPLING term (J) together the EXTERNAL FIELD term (F)

### Related Publications

Simpson, K., Keymer, J., & Federici, F. (2023). Spatial biology of Ising-like synthetic genetic networks (p. 2023.05.10.540292). bioRxiv. https://doi.org/10.1101/2023.05.10.540292


