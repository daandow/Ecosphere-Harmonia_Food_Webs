# Ecosphere-Harmonia_Food_Webs
Obitools scripts and custom R codes
DNA-based methods to identify prey consumed by arthropod predators have revolutionized the study of ecological communities. We used metabarcoding and qPCR to identify prey in the gut contents of four species of coccinellid beetles to construct predator-centric food webs. 

This repository contains an ObiTools script used to filter the Illumina fasta file and assign taxonomic identifications. A key element to the ObiTools workflow is to identify PCR sequencing errors and eliminate them from comsideration. This is done by grouping nearly identical reads and constructing a a tree similar to a phylogenetic tree with branches originating at the various PCR cycles. The head of the tree (the original ancestor) is retained for taxonomic identification.

It also contains two R scripts. The first specifies how the food web graphs were constructed and how the food web statistics were calculated, including an implementation of the randomizaton algorithm described by Watts and Strogarz, 1998, Collective dynamics of ‘small-world’ networks. Nature 393, 440-442. The second contains a simulated annealing script to identify modularity based on Guimerà, R., Sales-Pardo, M. and Amaral, L.A.N., 2007. Module identification in bipartite and directed networks. Physical Review E, 76(3), p.036102. Guimerà, R., Stouffer, D.B., Sales-Pardo, M., Leicht, E.A., Newman, M.E.J. and Amaral, L.A., 2010. Origin of compartmentalization in food webs. Ecology, 91(10), 91(10), pp.2941-2951. This bipartite modularity for predator treatments with prey and unipartite directed food webs for either predators or pry.


