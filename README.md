# Codes_CellFateSpecification
This repository contains the scripts used for the analysis of blastomere-specific transcripts localisation during early embryogenesis. The notebooks also generates figures summarising main results.

In **Integration_transcriptomes.nbs** are the files and scripts used:
To run RNA-seq expressioon quantification for each blastomere-specific library. The blastomer IDs for 4-cell embryos are Emr, Eml, Epen and Mavg; 8-cell blastomeres are named El, Er, Ep, Mr, Ml, Mav, g and en. Raw treads were previously mapped to reference genome using *HISTA2*
To estimate libraries statistics
To run Principal component analysis
Integration of quantification matrix from 4- and 8- cell stages
Annotation of quantified transcripts using FlyBase gene IDs
To visualise the mRNA fate during the transition form 4 to 8 cell embryos. This part can also includes the option to interactively display the figure using plotly function.

In **Identification_Parhyale_germline_transcripts.nb** are the files and scripts used: 


In **coevolving_coordination** are the files for Fig.S4: */codes* contains source codes for running time series and the heatmap, while */data* contains raw data and plotting codes. In terms of the source codes, please *do not* change the relative location of these files as the random number generators files (dSFMT) are required for running, and **please read** the notes at the beginning of each file, containing the key parameters and notes. For the data files, the two heatmaps of coordination levels and proportion of helpers are plotted from *level_sumary.csv*, you may use the files in *R_files* to replot the figures. If you wish to generate your own *level_summary.csv*, please assign the folders as in *data/Fig4_levelplot* and run *cord_ss.c* for each group size separately. The *merge_summaries.R* would help you create the *level_summary.csv* file. 

Please email *alexjapes@gmail.com* if there is any problem, thanks! (Manuel)
