# Simulation and visualization of controlled crosses

## Project Summary

The simulation of controlled crosses has been useful in both applied breeding and genetic mapping. Current open-source packages have expanded the realism and utility of simulated schemes by incorporating elements such as variation in recombination frequencies, novel transgenic approaches, and genomic selection, among others.  Still, this realism comes at a significant cost, both, in terms of computational efficacy and difficulty of use.  

Currently, nearly every agronomically important crop has a reference genome and gene annotation information.  In the very near future, most large-scale breeding programs will also have access to genome sequences for many founder lines within a program as well as extensive genotypic information to impute this information onto their progeny populations.  Indeed, to our knowledge, no simulation framework appropriately supports the integration of empirical data, such as genome sequences and annotations, that are currently available for most crop species.  

To address this need, we are working on a breeding simulation language, called “crossword” that runs through the R statistical programming framework.  Crossword has native support for importing FASTA, GFF, VCF, and HAPMAP file formats and uses these files to make realistic simulations much more applicable and feasible.  In addition, the crossword language is built on the concept of family-structure in breeding population, given users an intuitive and powerful way to rapidly brainstorm and simulate complex pedigrees, while exploring the required scale of an experiment.

## Relevant publications

Korani W, Vaughn JN. Crossword: A data-driven simulation language for the design of genetic-mapping experiments and breeding strategies. Scientific Reports. 2019;9: 4386. doi:10.1038/s41598-018-38348-y

[Return to home page](http://genemachine.net)
