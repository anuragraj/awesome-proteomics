# awesome-proteomics  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
   
 <img src="./media/logo.png"/>    
   
   
A curated list of awesome Proteomics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to [contribute](CONTRIBUTING.md)!   

<!-- -->
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [awesome-proteomics  ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-proteomics--)
  - [Table of Contents](#table-of-contents)
  - [Proteomics Databases](#proteomics-databases)
    - [Protein Databases](#protein-databases)
    - [Mass Spectrometry Databases](#mass-spectrometry-databases)
  - [Proteomics Tools](#proteomics-tools)
    - [Database search algorithms](#database-search-algorithms)
    - [MS/MS peptide quantification](#msms-peptide-quantification)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


 ----
## Proteomics  
Proteomics is the study of proteins in biological systems. It involves the large-scale study of proteins, their structure and physiological role or functions. The word proteome is actually a combination of protein and genome and was coined by Mark Wilkins in 1994. The proteome is a broad term that also encompasses the alterations or modifications produced in native protein when organisms are subjected to a plethora of changes.


## Proteomics Databases

### Mass Spectrometry Databases
* **[ProteomeXchange](http://www.proteomexchange.org/)**  
  The ProteomeXchange Consortium provide globally coordinated standard data submission and dissemination pipelines involving the main proteomics repositories, and encourage open data policies in the field. It provide the ability to search for datasets in all participating PX resources at once. The submitted dataset files remain in the receiving resources but are then linked from ProteomeCentral. 
* **[omicsDI](https://www.omicsdi.org/)**  
  The Omics Discovery Index (OmicsDI) is an integrated and open source platform facilitating the access and dissemination of omics datasets. It provides a unique infrastructure to integrate datasets coming from multiple omics studies, including at present proteomics, genomics, transcriptomics and metabolomics. It stores metadata coming from the public datasets from every resource using an efficient indexing system, which is able to integrate different biological entities including genes, proteins and metabolites with the relevant life science literature. 
* **[PRIDE](https://www.ebi.ac.uk/pride/)**  
  The PRIDE PRoteomics IDEntifications (PRIDE) Archive database is a centralized, standards compliant, public data repository for mass spectrometry proteomics data, including protein and peptide identifications and the corresponding expression values, post-translational modifications and supporting mass spectra evidence.
* **[MassIVE](https://massive.ucsd.edu/ProteoSAFe/static/massive.jsp)**  
  MassIVE is a community resource developed by the NIH-funded Center for Computational Mass Spectrometry to promote the global, free exchange of mass spectrometry data. It is integrated into a flexible, scalable, user-friendly framework offering a diverse set of data analysis algorithms.
* **[jPOSTdb](https://globe.jpostdb.org/)**  
  jPOSTdb (Japan ProteOme STandard DataBase) is a database containing re-analysis results with unified criteria for proteome data from jPOSTrepo. It provides viewers showing the frequency of detected post-translational modifications, the co-occurrence of phosphorylation sites on a peptide and peptide sharing among proteoforms.
* **[iProX](https://www.iprox.cn/)**  
  iProX is an integrated proteome resources center in China, which is built to accelerate the worldwide data sharing in proteomics. iProX is composed of a data submission system and a proteome database.
* **[Peptide Atlas](http://www.peptideatlas.org/)**   
  PeptideAtlas is a multi-organism, publicly accessible compendium of peptides identified in a large set of tandem mass spectrometry proteomics experiments. Mass spectrometer output files are collected for human, mouse, yeast, and several other organisms, and searched using the latest search engines and protein sequences.
* **[ProteomicsDB](https://www.proteomicsdb.org/)**  
  ProteomicsDB is a protein-centric in-memory database for the exploration of large collections of quantitative mass spectrometry-based proteomics data. It is dedicated to expedite the identification of the human proteome and its use across the scientific community.
* **[Panorma](https://panoramaweb.org/)**
  Panorama is a freely-available, open-source repository server application for targeted mass spectrometry assays that integrates into a Skyline mass spec workflow. It has been implemented as a module within LabKey Server, an open-source bioinformatics data management platform with extensive support for proteomics and small molecule data and a security model rich enough to support clinical studies.   

### Protein Databases
* **[UniProt](https://www.uniprot.org/)**   
  The Universal Protein Resource (UniProt) is a comprehensive resource for protein sequence and annotation data. The UniProt databases are the UniProt Knowledgebase (UniProtKB), the UniProt Reference Clusters (UniRef), and the UniProt Archive (UniParc).   
  The UniProt Knowledgebase, the centrepiece of the UniProt Consortium’s activities, is an expertly and richly curated protein database, consisting of two sections called UniProtKB/Swiss-Prot and UniProtKB/TrEMBL. UniProtKB/Swiss-Prot contains high-quality manually annotated and non-redundant protein sequence records. UniProtKB/TrEMBL contains high-quality computationally analysed records enriched with automatic annotation and classification.   
  Three UniRef databases – UniRef100, UniRef90 and UniRef50 – merge sequences automatically across species. UniRef100 is based on all UniProtKB records. It also contains selected UniParc records, including Ensembl protein translations from chicken, cow, dog, fly, Fugu, human, mouse, rat, Tetraodon, Xenopus and zebrafish.  
  UniParc is designed to capture all publicly available protein sequence data and contains all the protein sequences from the main publicly available protein sequence databases. This makes UniParc the most comprehensive publicly accessible non-redundant protein sequence database.   
* **[neXtProt](https://www.nextprot.org/)**  
  neXtProt is a comprehensive human-centric discovery platform, offering its users a seamless integration of and navigation through protein-related data. It is a knowledgebase focusing exclusively on human proteins, leverages the expert manual annotation carried out at specialist resources and in-house to provide a single point of reference. Information concerning human protein function, cellular localization, tissular expression, interactions, variants and their phenotypic effect, post-translational modifications (PTMs), as well as peptide identified in mass spectrometry experiments and epitopes recognized by antibodies have been integrated from a number of resources. The current neXtProt release was built using human genome assembly GRCh38 and UniProtKB. The data from UniProtKB is currently supplemented with data from Bgee, HPA, PeptideAtlas, SRMAtlas, GOA, dbSNP, Ensembl, COSMIC, DKF GFP-cDNA localization, Weizmann Institute of Science's Kahn Dynamic Proteomics Database, IntAct, GlyConnect, gnomAD, as well as in-house curated data.   
* **[Human Protein Atlas](https://www.proteinatlas.org/)**  
  The Human Protein Atlas is a Swedish-based program initiated in 2003 with the aim to map all the human proteins in cells, tissues, and organs using an integration of various omics technologies, including antibody-based imaging, mass spectrometry-based proteomics, transcriptomics, and systems biology. The Human Protein Atlas consists of ten separate sections, each focusing on a particular aspect of the genome-wide analysis of the human proteins. The Tissue section, showing the distribution of the proteins across all major tissues and organs in the human body. The Brain section, exploring the distribution of proteins in various regions of the mammalian brain. The Single Cell Type section, showing expression of protein-coding genes in single human cell types based on scRNA-seq. The Tissue Cell Type section, showing expression of protein-coding genes in human cell types based on bulk RNAseq data. The Pathology section, showing the impact of protein levels for the survival of patients with cancer. The Immune Cell section, showing expression of protein-coding genes in immune cell types. The Blood Protein section, describing proteins detected in blood and proteins secreted by human tissues. The Subcellular section, showing the subcellular localization of proteins in single cells. The Cell Line section, showing expression of protein-coding genes in human cell lines. The Metabolic section, exploring expression of protein-coding genes in the context of the human metabolic network.   
* **[NCBI-RefSeq](https://www.ncbi.nlm.nih.gov/refseq/)**   
  The Reference Sequence (RefSeq) collection provides a comprehensive, integrated, non-redundant, well-annotated set of sequences, including genomic DNA, transcripts, and proteins. RefSeq sequences form a foundation for medical, functional, and diversity studies. They provide a stable reference for genome annotation, gene identification and characterization, mutation and polymorphism analysis, expression studies, and comparative analyses. RefSeq genomes are copies of selected assembled genomes available in GenBank. RefSeq transcript and protein records are generated by several processes including: Computation, Manual curation, Propagation from annotated genomes that are submitted to members of the International Nucleotide Sequence Database Collaboration (INSDC).  

## Proteomics Tools

### Database search algorithms
* OMSSA (2004)  
  **Purpose** - Efficient MS/MS search algorithm  
  **Advantage** - Specificity is calculated by a classic probability score using an explicit model for matching experimental spectra to sequences  
  **Publication** - Geer LY, Markey SP, Kowalak JA, Wagner L, Xu M, Maynard DM, Yang X, Shi W, Bryant SH. Open mass spectrometry search algorithm. Journal of proteome research. 2004 Oct 11;3(5):958-64. PMID: 15473683    
  **License** - Free   
  **Links** -   
     Website - ftp://ftp.ncbi.nih.gov/pub/lewisg/omssa/  
  
* MassWiz  
  **Purpose** - MS/MS search algorithm  
  **Advantage** - A novel empirical scoring function that gives appropriate weights to major ions, continuity of b-y ions, intensities, and the supporting neutral losses based on the instrument type  
  **Publication** - Yadav AK, Kumar D, Dash D. MassWiz: a novel scoring algorithm with target-decoy based analysis pipeline for tandem mass spectrometry. Journal of proteome research. 2011 May 6;10(5):2154-60.    
  **License** - Free   
  **Links** -   
     Website - https://sourceforge.net/projects/masswiz/
* InsPecT
* X!Tandem
* Mascot
* SEQUEST
* MSFragger	(2017)  
  **Purpose** - Peptide identification in mass spectrometry-based proteomics.   
  **Advantage** - Fragment-ion indexing method enabling high speed search  
  **Publication** - 28394336  
  **License** - Free  
  **Links** -   
     Website - https://msfragger.nesvilab.org/  
     GitHub - https://github.com/Nesvilab/MSFragger  
      
* PGA	(2016)   
  **Purpose** - R package for novel peptides identification using RNA-Seq  
  **Advantage** - Customized protein database and can generate an HTML-based report with a visualized interface	  
  **Publication** - 27316337  
  **License** - Free  
  **Links** -  
     Website - http://wenbostar.github.io/PGA/, https://bioconductor.org/packages/PGA  
     GitHub - https://github.com/wenbostar/PGA  
     
* MS-GF+ (2014)  
  **Purpose** - Database search tool for proteomics  
  **Advantage** - Identifies more PSMs as compared with Mascot, X!Tandem, OMSSA, Crux, Comet and InsPecT and integrated in various pipelines  
  **Publication** - 25358478  
  **License** - Free  
  **Links** -   
     Website - https://omics.pnl.gov/software/ms-gf  
     GitHub - https://github.com/MSGFPlus/msgfplus  	
     
* Open-pFind (2018)  
  **Purpose** - Sequence-tag-based search engine to identify peptides	  
  **Advantage** - Improves peptide and protein identification by matching MS/MS spectra to a substantially expanded search space  
  **Publication** - 30295672  
  **License** - Free (License required for installation)  
  **Links** -   
     Website - http://pfind.ict.ac.cn/software/pFind3   
     GitHub - https://github.com/pFindStudio/pFind3  			
    
### MS/MS peptide quantification
* MaxQuant
* msInspect
* OpenMS/TOPP
* pView 2
* mzMine 2
* Census


