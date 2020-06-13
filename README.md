Phylogenetics and Phylogenomics toolKIT

Currently, the following functions are implemented in PhyKIT:
• treeness
• total tree length
• internode labeler
• LB score
• alignment length calculation
• number of variable sites calculation; percent variable sites
• number of parsimony informative sites calculation; percent parsimony informative sites
• Average internal branch length
• Aln. length after removing any site with gaps
• dvmc
• average bipartition support
• patristic distance determination
• rcv
• plain robinson-foulds distance; normalized robinson-foulds distance
• treeness / rcv
• protein-to-nucleotide (pal2nal) alignment conversion
• long termini (terminal branches with tips longer than xx the median terminal branch length)
• create concatenation matrix
• print ascii tree
• print tree tip names
• rename tree tips
• rename names in alignments
• GC content calculation

Functions to add include:
• correlated gene-gene evolution
• compare two trees
• the ratio of the mean internal branch lengths to the mean terminal branch lengths -- this would be a new statistic so test it!
• A proxy of evolutionary rate https://academic.oup.com/gbe/article/9/8/1998/4060518
• tree and alignment file format conversion
• branch length multiplier
• including a outlier branch length detection method like treeShrink https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-4620-2#Sec22


Consider writing a function that conducts objective desirability-based integration of multiple statistics