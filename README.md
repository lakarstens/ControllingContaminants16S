## Controlling Contaminants in 16S rRNA Gene Sequencing Experiments

We recently performed a study to understand the impact of decreasing microbial biomass on 16S rRNA gene sequencing experiments and evaluate the current computational strategies to control for contaminants (preprint available [here](https://www.biorxiv.org/content/early/2018/05/25/329854)).

This repository contains the compiled R Markdown documents to reproduce the analysis presented in the manuscript, divided into 4 primary sections:

* [Introduction and evaluating contaminants](./Analyses/ControllingConatminants16S.Rmd)
* [Removing contaminant ASVs with decontam](./Analyses/ControllingConatminants16S_decontam.Rmd)
* [Removing contaminant ASVs with SourceTracker](./Analyses/ControllingConatminants16S_SourceTrackerPrep.Rmd)
* [Evaluating SourceTracker results](./Analyses/ControllingConatminants16S_SourceTracker.Rmd)

We hope that this will serve as a resource and tutorial for those wishing to use these computational approaches on their own data. 
