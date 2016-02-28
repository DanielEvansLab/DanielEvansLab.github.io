---
layout: page
title: Project 5 - LAD
---

# Lifespan-affecting Drugs (LAD)

### Background

**Drug identification for translational strategies**

Convincing evidence linking longevity-affecting genes (LAGs) to longevity will serve as a foundation for the search for small molecule compounds that might mimic the effect of LAGs. By identifying small molecules based on therapeutic hypotheses relating molecular function to healthy aging, effective translational research strategies can be developed and pilot studies can be designed. These findings will be disseminated to the research community.

Candidate chemical interventions could either modulate the activity of the protein encoded by a LAG or could induce a gene expression pattern associated with healthy aging. 

### Approach

This component of the Longevity Genomics project will focus on the analysis and integration of existing community data related to drug-like small molecules with longevity promoting properties. The assembly of this **Longevity Drug** data set will be based on the following activities:

1. Identify target proteins, pathways and biological networks associated with longevity in humans and other organisms. The candidate set of LAGs will be obtained from existing community data sets including the research outcomes from the other projects of the Longevity Genomics consortium (projects 1-4).
2. Systematically identify LAG-modulating small molecules by integrating several large-scale community data sources such as data from drug databases (_e.g._ Drugbank), bioassay databases (_e.g._ PubChem Bioassay, ChEMBL), literature, drug-related gene expression fingerprints (_e.g._ LINCS), genetic (_e.g._ GWAS) and phenotype resources. This will also include nearest neighbors of LADs sharing with them structural, physicochemical or biological properties. 
3. The **Longevity Drugs** collection will be shared with the community in form of a Bioconductor data package (portable SQLite database) containing the LAD structures, activity data, property descriptors and evidence classifications.  

4. As integral part of this project we are developing the [longevityTools R Package](https://github.com/tgirke/longevityTools){:target="_blank"}, and preliminary analysis workflows in from of online vignettes are available at the [longevityTools website](http://girke.bioinformatics.ucr.edu/longevityTools/mydoc/home.html){:target="_blank"}. Finalized components of the software will be submitted to the Bioconductor project.

Below is an illustration demonstrating the linkage between small molecule bioactivity, structure and gene expression using non-supervised clustering. The three data types can be obtained from public databases including PubChem, PubChem Bioassay and GEO, respectively. 

![Cluster Image](/public/images/cluster_image.svg){: .center-image }


### Project example: identify LAD candidates using gene expression data

Here we analyze drug- and age-related genome-wide expression data from public microarray and RNA-Seq experiments. One of the main objective is the identification drug candidates modulating the expression of longevity genes and pathways. For this, we compare age-related expression signatures with those from drug treamtments. The age-related query signatures are from recent publications such as [Peters et al. (2015)](http://www.ncbi.nlm.nih.gov/pubmed/26490707){:target="_blank"} and  [Sood et al. (2015)](http://www.ncbi.nlm.nih.gov/pubmed/26343147){:target="_blank"}, while the drug-related reference signatures are from the Connectivity Map (CMAP) and LINCS projects [(Lamb et al. (2006)](http://www.ncbi.nlm.nih.gov/pubmed/17008526){:target="_blank"}.







