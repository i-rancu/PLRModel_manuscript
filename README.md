## **Pairwise Logistic Regression Application in Moldova**
This repository contains code and data to recreate the findings from our manuscript (under review at Access Microbiology) that explores cluster memebership of unsequenced strains in the Republic of Moldova:

*Rancu, I. et al. Classification of unsequenced Mycobacterium tuberculosis strains in a high-burden setting using a pairwise logistic regression approach. Access Microbiol. (2024) doi:10.1099/acmi.0.000964.v1.*

Please note that details of model construction and package implementation for our analyses can be found in the original methods publication: 

*Susvitasari, K. et al. Epidemiological cluster identification using multiple data sources: an approach using logistic regression. Microb. Genomics 9, 000929 (2023).*

## **Folder Structure** 
The folder contains two files: 
1. A data file with all pairwise data comparision for all individuals included within our analyses: **PairwiseData_Sample.xlsx**
   Please note that when implementing the methods with project specific code, functions for the 'l2cluster' package can compute a pairwise data matrix intrinsically. 
2. A .rmd file that ourlines our methods as described in the manuscript: **Manuscript_PLRModelCode.Rmd**

## **Packages**
These analyses utilize R package 'lr2cluster'

## **Data Source**
All sequences used in this analysis are available in BioProject: https://www.ncbi.nlm.nih.gov/bioproject/PRJNA736718. Individual accession numbers for sequences used in this analysis (n = 1582) are included in a supplementary file (Supplementary Table 1)

