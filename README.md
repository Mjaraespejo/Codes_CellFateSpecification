# Codes_CellFateSpecification
This repository contains the scripts used for the analysis of blastomere-specific transcripts localisation during early embryogenesis. The R Markdown notebooks also generates figures summarising main results.

In **Integration_transcriptomes.nb** are the files and scripts used:
- To run RNA-seq expressioon quantification for each blastomere-specific library. The blastomer IDs for 4-cell embryos are Emr, Eml, Epen and Mavg; 8-cell blastomeres are named El, Er, Ep, Mr, Ml, Mav, g and en. Raw treads were previously mapped to reference genome using *HISTA2*
- To estimate libraries statistics
- To run Principal component analysis
- Integration of quantification matrix from 4- and 8- cell stages
- Annotation of quantified transcripts using FlyBase gene IDs
- To visualise the mRNA fate during the transition form 4 to 8 cell embryos. This part can also includes the option to interactively display the figure using plotly function.

In **UTR analysis on asymmetric genes.nb** are the files and scripts used:
- To extract UTR sequences from annotated protein-coding genes and run stats
- To perfomr motif enrichment using MEME suite. Enriched RNA-binding protein (RBP) recognitiion motifs were identified in each set of transcripts.

In **Identification_Parhyale_germline_transcripts.nb** are the files and scripts used: 
- Identify asymmetrically localised transcripts in each 8-cell stage blastomere
- To estimate FoldChange expression between target blastomer and the other 7. The SD was used to define and enrichment threshold
- To use the SD threshold to call enriched transcripts.
- To visualise the expression of blastomere specific genes using clustering methods at both 4- and 8- cell stages
- To visualise the expression of blastomere specific genes using clustering methods acroos multiple developmental time-points
- To summarise and visualise specific genes average expressiona across embryogenesis
- To analyse MEME suite motif enrichment output. This part aimed to summarise the location ot known and unknown RNA-binding sites within blastomer-specific 3UTR

Please email *alexjapes@gmail.com* if there is any problem, thanks! (Manuel)

[This](https://htmlpreview.github.io/) is a tool to view the html files. 
