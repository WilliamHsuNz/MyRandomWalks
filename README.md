# MyRandomWalksEd
These programs extend the TreeTraitMap class in the Beast-classic package (part of Beast2, a cross platform program for phylogenetic analysis). The programs simulate various geographical population spreads including simple isotropic random walk, baised random walk, correlated random walk, random walk with boundaries and long-range dispersal. Using the inference framework developed by Lemey et al. 2010 (http://mbe.oxfordjournals.org/content/27/8/1877.long), the program then performs MCMC sampling method to estimate the location of the root of the phylogenetic tree from the locations of the leaves.

To run the programs dependencies have to be built between beast2, beast-classic, beast-geo, BEASTLabs and external library mason1.9

Each program takes its corresponding examples/test...xml file as input argument and is run through the main at beast.app.beastapp.BeastMain
