# oncoPredict 
(Predict Response from Expression Data and Identify Cell line/Clinical Targets and Trends)

An R package for drug response prediction and drug-gene association prediction. The prepared GDSC and CTRP matrices for the calcPhenotype() are here: [GDSC and CTRP Data](https://osf.io/c6tfx/)
 *  For drug response prediction, use **calcPhenotype**. This code is based on the paper: [pRRophetic](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0107468)
 *  For pre-clinical biomarker discovery, use **GLDS**. This code is based on the paper: [GLDS](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-1050-9)
 * For clinical biomarker discovery, use **IDWAS** (for CNV or somatic mutation association with drug response) or indicate **cc=TRUE** (for gene expression association with drug response) in calcPhenotype(). The IDWAS code is based on the paper: [IDWAS](https://pubmed.ncbi.nlm.nih.gov/28847918/)
 
## R <h2>
 * This directory contains all the R functions included in this package. 

## vignettes <h2> 
  *  This directory contains vignettes which display detailed examples of the functionalities available in this package.
  *  **IDWAS** This directory contains examples of IDWAS code application for clinical drug-gene association prediction. 
      + **cnv.Rmd** Example as to how to download CNV (copy number variation) data from the GDC database, then apply map_cnv() and test().
      + **mut.Rmd** Example as to how to download stomatic mutation data from the GDC database, then apply test(). 

  * **GLDS** This directory contains examples of GLDS code application for pre-clinical drug-gene association prediction. 
      + **glds_GDSC.Rmd** Example of GLDS application to GDSC data. 

  * **calcPhenotype.Rmd** Example of calcPhenotype() application.

## man <h2>
 * This directory contains .Rd (R documentation) files for each function. These files were automatically generated upon creation of the package. 

## NAMESPACE <h2>
 * This file lists the functions to be imported and exported from this package. 

## DESCRIPTION <h2>
 * This file contains the description documentation and metadata for this package. 
![Figure 1_ Overview of pRRophetic_plus (a flow chart or similar diagram to highlight the package’s abilities)   (1)](https://user-images.githubusercontent.com/62571435/114938024-35868c00-9e04-11eb-82ae-ea9dbfa0a0a7.jpg)
