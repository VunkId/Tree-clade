PHYLOGENETIC TREE DISTANCE CALCULATOR WITH A GRAPHIC OUTPUT                

This repository contains a phylogenetic tree distance calculator between clades (different species) using Biopython with dictated distances given in lower triangular distance matrix.
In order to use this, you just need to import Phylo from Biopython library as shown below: 

#Creating the phylogenetic tree distance calculator with Biopy
from Bio import Phylo
from Bio.Phylo.TreeConstruction import DistanceTreeConstructor, DistanceMatrix

Naturally, you can adapt your distance matrix to desired values, both the values and the amount of values for quantification, whereas it is important to keep in mind that this is a lower triangular matrix (necessary for the program to run as intended, due to the nature of the library input conditions and properties).
