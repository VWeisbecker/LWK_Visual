# Not like night and day: the nocturnal Letter-winged Kite does not differ from diurnal congeners in orbit or endocast morphology - data and code
Code authors: Vera Weisbecker, Jeroen Smaers, Aubrey Keirnan, Andrew Iwaniuk

Accompanies the publication: Aubrey Keirnan, Trevor H. Worthy, Jeroen Smaers, Karine Mardon, Andrew Iwaniuk, Vera Weisbecker (2022): Not like night and day: the nocturnal Letter-winged Kite does not differ from diurnal congeners in orbit or endocast morphology. Royal Society Open Science. 

The release to go with the publication is on <a href="https://zenodo.org/badge/latestdoi/455048747"><img src="https://zenodo.org/badge/455048747.svg" alt="DOI"></a>



*All scripts are in RMarkdown format (.Rmd) and can be opened in RStudio. There, you can edit and run code chunks as normal. After cloning this repo, remember to either set your working directory to the LWK_Visual folder on your computer or open an RStudio project from that folder.*

## Data

**Raw**

* [Raptor_Data_Full.csv](/Data/Raw/Raptor_Data_Full.csv) Loads measurements, computes left-right means and species averages, matches phylogeny with data, and saves the .rda file for analyses.
* [Consensus_tree_Circus_Elanus_resolved.nex](Data/Raw/Phylogeny/Consensus_tree_Circus_Elanus_resolved.nex) 50% consensus tree from Birdtree, with additional resolution of _Circus_ as per [LWK_data_frames.Rmd](/Analysis/LWK_data_frames.Rmd)
* [Facilities.txt](/Data/Raw/Facilities.txt) provides the full names of abbreviated CT scanning facilities used.
* MorphoSource Project P918 will publically provide CT scans and 3D meshes of all specimens studied
* [Data_header_legend.pdf](/Data/Raw/Data_header_legend.pdf) provides extended captions for each data column
    
 **Processed**
 
 Receives rda file for analysis from 
 [LWK_data_frames.Rmd](/Analyses/LWK_data_frames.Rmd)
 
## Analyses

* [LWK_data_frames.Rmd](/Analyses/LWK_data_frames.Rmd) Loads measurements, computes left-right means and species averages, matches phylogeny with data, and saves the .rda file for analyses.
* [LWK_analysis.Rmd](/Analyses/LWK_analysis.Rmd) Computes all results, including table outputs and figures.
* [LWK_analysis_Neurocr](/Analyses/LWK_analysis_Neurocr.Rmd) Replicates analyses, using neurocranial length instead of geometric mean

## Figures

Receives figure outputs from the code

## Tables

Receives table outputs from the code
