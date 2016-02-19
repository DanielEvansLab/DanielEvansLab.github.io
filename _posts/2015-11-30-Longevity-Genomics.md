---
layout: post
title: Longevity genomics
---

### Welcome

You have reached the website for the Longevity Genomics research project, a resource-related cooperative agreement project with the National Institute on Aging (NIA). Here you will find a description of the project and its overall goals. Pages accessed via the navigation menu **☰** in the top corner list the members and describe the organizational structure, describe the specific research projects, and provide access to open source data, tools, and resources used and developed by this project.

### Project Summary

Human longevity is heritable, and statistically and biologically compelling genetic associations with longevity and age-related traits have been identified.  The translation of these genetic associations into insights that can lead to pharmacological interventions designed to promote healthy aging requires an approach and infrastructure that integrates multiple genomic resources. 

To address this challenge, we have established the [Longevity Genomics](http://www.longevitygenomics.org/) research group, an [NIA funded research project]({{site.baseurl}}/funding/) with **two primary goals**. 

1. Create a research resource that is publicly available through this website to enable scientists to develop translational strategies to promote human longevity. Our publicly-available infrastructure will include the following.
  + **Software tools** in the form of R packages and analysis walkthroughs in the form of vignettes that will enable researchers to adopt and extend our analytical methods. 
  + **Datasets** used by our project. Datasets will include genome-wide single nucleotide polymorphism (SNP) association results for human age-related traits, functional human genomic annotation, information from tissue-specific expression quantitative trait locus (eQTL) studies, and datasets of chemical properties and protein targets of small molecule compounds. We will also share our phenotype harmonization approaches that will enable us and others to analyze meaningful human aging traits. These resources will be provided directly through this website or through links to external resources. We will direct users to external resources that store data collected from longitudinal cohort studies with genome-wide genotype and sequence data.   
  + **Results** generated through our research. Results will include annotated genome-wide SNP association results, genetic instrumental variables that can be used in Mendelian Randomization analysis, expression profiles associated with traits relevant to human aging, and small molecule compounds targeting genes of interest and expression profiles associated with human aging.
  + Armed with our data resources and software tools, outside researchers will be able to reproduce our results and extend our approaches to their own datasets. For those who prefer to browse results, our results will be available as [downloadable files]({{site.baseurl}}/downloads/) and through web-based solutions such as [Shiny](http://shiny.rstudio.com/) and [ReportingTools](http://bioconductor.org/packages/release/bioc/html/ReportingTools.html), where appropriate. 

2. Develop translational strategies to promote human longevity using our research resource. Our translational strategies are based on the identification of modifiable factors that can be pharmacologically targeted and that are causally related to healthy human aging. Together with our Research Planning Committee, we will design pilot studies to test the feasibility of prioritized translational strategies and we will provide small funding opportunities for scientists to perform these pilot studies. 

### Approach

A central theme in our project is to develop insights relating molecular and physiologic factors that can be pharmacologically manipulated to promote healthy aging based on hypotheses rooted in genetic association studies of longevity. To develop causal associations with human longevity, we employ a Mendelian Randomization approach.

The Mendelian Randomization (MR) approach has been described in Davey Smith G, Ebrahim S. 'Mendelian randomization': can genetic epidemiology contribute to understanding environmental determinants of disease? Int J Epidemiol. 2003; 32:1-22. The appeal of MR is that this approach can be used to identify causal associations between a potentially modifiable risk factor and an outcome. A major challenge for observational studies is to identify causal associations, which is due, at least in part, to the influence of confounding factors. A confounder is a third factor that is a common cause of a risk factor and the outcome.

![confounded](public/images/confounded.svg){: .center-image }

MR is an approach that is designed to largely avoid the influence of confounders by employing genetic variants associated with the risk factor of interest. Genetic variants are determined at conception, and as such, are not subject to the effects of confounders. In other words, very few potential confounders can alter a person's DNA in all of the tissues relevant to the disease under study. The term Mendelian Randomization refers to the fact that the random assortment of a risk-factor associated allele at conception is analogous to the random assignment of treatment in a randomized controlled trial. Genetic predictors of risk factors can be used as instrumental variables to approximate a lifetime exposure to a risk factor of interest, e.g., increased HDL levels or increased expression of a particular gene, and these genetic instrumental variables (gIVs) can then be used to estimate the unconfounded association between the risk factor and the outcome. 

![MR](public/images/MR.svg){: .center-image }

Details of our projects and our use of MR can be found on the [Projects]({{site.baseurl}}/projects/) page.

### Updates

Users should be aware that this site is still a work in progress due to the early stage of the project. Many components of this site are under heavy development. In the coming months, genomic resources and analytical approaches will be made available on this website that will enable others in the field to perform in-depth integrative genomic analyses using their own data. Results from our analyses will be made available for [download]({{site.baseurl}}/downloads).

### Contact

Researchers interested in learning more about the Longevity Genomics project can contact Dan Evans <devans@psg.ucsf.edu>
