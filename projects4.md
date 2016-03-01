---
layout: page
title: Project 4 - Genetic Instumental Variables and Mendelian Randomization
---

### Background

A central theme in our project is to develop insights relating molecular and physiologic factors that can be pharmacologically manipulated to promote healthy aging based on hypotheses rooted in genetic association studies of longevity. To develop causal associations with human longevity, we employ a Mendelian Randomization approach.

The Mendelian Randomization (MR) approach has been described in Davey Smith G, Ebrahim S. 'Mendelian randomization': can genetic epidemiology contribute to understanding environmental determinants of disease? Int J Epidemiol. 2003; 32:1-22. The appeal of MR is that this approach can be used to identify causal associations between a potentially modifiable risk factor and an outcome. A major challenge for observational studies is to identify causal associations, which is due, at least in part, to the influence of confounding factors. A confounder is a third factor that is a common cause of a risk factor and the outcome.

![confounded](/public/images/confounded.svg){: .center-image }

MR is an approach that is designed to largely avoid the influence of confounders by employing genetic variants associated with the risk factor of interest. Genetic variants are determined at conception, and as such, are not subject to the effects of confounders. In other words, very few potential confounders can alter a person's DNA in all of the tissues relevant to the disease under study. The term Mendelian Randomization refers to the fact that the random assortment of a risk-factor associated allele at conception is analogous to the random assignment of treatment in a randomized controlled trial. Genetic predictors of risk factors can be used as instrumental variables to approximate a lifetime exposure to a risk factor of interest, e.g., increased HDL levels or increased expression of a particular gene, and these genetic instrumental variables (gIVs) can then be used to estimate the unconfounded association between the risk factor and the outcome. 

![MR](/public/images/MR.svg){: .center-image }

### Approach

Our approach is composed of 3 steps.

1. Identify genetic Instumental Variables related to LAGs

Studies with genotype and gene expression data collected from the same individuals (eQTL studies) are extremely useful in linking genetic variation to the molecular consequence of RNA abundance. It has been shown that SNPs that influence gene expression are enriched for associations in GWAS. The Genotype-Tissue Expression [GTEx](http://www.gtexportal.org/home/){:target="_blank"} Project is a collection of eQTL studies across multiple tissue types that includes non-immortalized cells, including brain, heart, blood, thyroid, muscle, lung, skin, and adipose tissue. Analysis of eQTLs at an extremely detailed level is made possible by a recent study employing transcriptome and genome sequencing of lymphoblastoid cell lines (LCLs) of individuals from the 1000 Genomes Project. LAVs can also be connected to protein abundances from a protein quantitative trait loci (pQTL) study in LCLs from HapMap individuals and blood metabolites (mQTLs) from 7824 adults of European ancestry. LAVs will be linked with publicly available eQTL and pQTL results from the studies above and others to identify molecular intermediate phenotypes associated with associated variants.

We will link LAVs to other intermediate traits by using the GWAS catalog and the GRASP database, a database curated and maintained by Dr. Andrew Johnson, a scientist on the project. The GRASP database includes more genetic associations than the GWAS catalog because SNP associations even at a significance level of 0.05 are included when available. GRASP also includes results from eQTL, mQTL (metabolomics QTLs), meQTLs (DNA methylation QTLs), gQTLs (glycosylation QTLs), pQTLs (protein QTLs), and mirQTLs (miRNA QTLs).

2. Construct predicted values of intermediate traits using allelic risk scores.

Alleles of each gIV associated with the intermediate trait of interest are summed for each person, potentially weighted by the effect size of each gIV and other factors of interest associated with each gIV. The person-specific summed gIV allelic risk score represents the combined genetic effect of multiple gIVs on a particular intermediate trait.

3. The person-specific gIV allelic risk score is then tested for association with longevity and aging-related traits. Associations with continuous traits will be assessed using linear regression, case-control traits with logistic regression, time-to-event with Cox Proportional Hazard regression, and longitudinal change in quantitative traits with linear mixed-effect models. 

### Data

Individual-level genetic data from the following large prospective longitudinal cohorts of elderly individuals will be used: the Health, Aging, and Body Composition Study (Health ABC), the Osteoporotic Fractures in Men (MrOS) Study, the Study of Osteoporotic Fractures (SOF), the Health and Retirement Study (HRS), Cardiovascular Health Study (CHS), Framingham Heart Study (FHS), Women’s Health Initiative (WHI), and the Long Life Family Study (LLFS) totaling 50,760 participants with genome-wide SNP genotypes. Genotype data for each study will be imputed to the 1000 genomes reference panel to provide comprehensive coverage of common and less common genetic variation in the human genome.

Human longevity can be defined using age attained, but trajectories of health and function can be heterogeneous, even among those achieving exceptional lifespan. Thus, in addition to age at death, we propose to examine measures of disability, such as activities of daily living (ADL) and instrumental activities of daily living (IADL). 

Also measured are physical performance measures, such as grip strength, walking speed, and chair stands, which are associated with morbidity and mortality in the elderly. Measures of cognitive performance (MMSE and 3MS) are also available in most cohorts. Information on incidence of age-related diseases (T2D, CVD, cancer, and dementia) has been collected in most cohorts. Measures contributing to healthy aging indices that reflect the aging process are also available.

We will also share our phenotype harmonization approaches that will enable us and others to analyze meaningful human aging traits. These resources will be provided directly through this website or through links to external resources. We will direct users to external resources that store data collected from longitudinal cohort studies with genome-wide genotype and sequence data. 

### Software

[longevityTools (R Package on GitHub)](https://github.com/tgirke/longevityTools){:target="_blank"}

### Expected results

Causal associations between intermediate phenotypes and human longevity. These associations will form the basis of translational strategies. 
