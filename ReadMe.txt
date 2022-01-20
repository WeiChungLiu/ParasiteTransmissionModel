This is the program code for simulating the spread of multiple parasite species through a food web. 

The program is written in Delphi (or Pascal) and can be found in the file called ParaTransModel.txt. 

It requires a food web data in the form of a square matrix, where if there is a trophic link between a row species (i.e. a prey) and a column species (i.e. a predator), then the corresponding element in the matrix is 1, otherwise 0. 

The food web data included is the Carpinteria food web (Lafferty et al., 2006), which can be found in the file called Carpinteria.txt. 

The output is saved in a text file called Dist_PD.txt, which contains the (frequency) distribution of parasite diversity for one simulation.

Reference
Lafferty, K. D., Dobson, A. P., & Kuris, A. M. (2006). Parasites dominate food web links. Proceedings of the National Academy of Sciences, 103(30), 11211-11216.
