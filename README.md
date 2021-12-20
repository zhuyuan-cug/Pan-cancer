Code for our paper "Identifying Pan-cancer Candidate Driver Genes via Integrative Network Analysis"


## Datasets

- The Protein-Protein Interaction Network: The human protein-protein interactions network (PPIN) is downloaded from the HPRD (http://www.hprd.org/) database.
- Gene Expression Datasets: The gene expression data of cancers were obtained from the GEO database (ID: GSE5364), which contains 6 types of cancers: breast, colon, liver, lung, esophageal and thyroid cancers.)


## Prerequisites

* Original code is tested on *Matlab 2020b* 64bit, Windows 10. 


## Usage

Run experiments.

The codes could be divided into to parts, one is for pancaner network generation, and another is used to ensemble classifier training.

You should run the test.m in the folder of Pancaner Network Generation firstly and then you can obtain an integrated network, then run the test.m in the folder of Ensemble Classifier, then the required ensemble classifier is completed.
