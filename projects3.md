---
layout: page
title: Project 3 - LAG identification from gene expression or model organisms
---

### LAG identification from gene expression

### Rationale

Based on muscle gene expression from 15 young (25 year old) and 15 old (65 year old) participants, [Sood et al.](http://www.ncbi.nlm.nih.gov/pubmed/26343147){:target="_blank"} identified a 150 probe set that accurately classified young and old individuals in external studies with gene expression data collected from tissues other than muscle (Sood, Gallagher et al. 2015). A gene score based on the classifier was associated with better renal function, increased survival time over follow-up, and decreased Alzheimer’s Disease prevalence.

A large-scale [study](http://www.ncbi.nlm.nih.gov/pubmed/26490707){:target="_blank"} of gene expression from whole blood in 14,983 individuals of European ancestry identified 1497 genes that are differentially expressed with chronological age. 

### Approach

Once LAGs are identified using gene expression, at least two analyses are performed:

1. Create genetic Instrumental Variables (gIVs) using GTEx for the Sood 150 probe set or the Peters 1497 gene set to test using Mendelian Randomization. See [Project 4]({{site.baseurl}}/projects4/). 

2. Identify candidate Longevity-Associated Drugs (LADs) associated with the gene expression pattern found in younger individuals. See [Project 5]({{site.baseurl}}/projects5/). 

### Data

[Sood 150 probe set]({{site.baseurl}}/data#Sood150)

[Peters 1497 gene set](http://www.ncbi.nlm.nih.gov/pubmed/26490707){:target="_blank"}

### Software

[longevityTools (R Package on GitHub)](https://github.com/tgirke/longevityTools){:target="_blank"}

### Expected results

Prioritized LAGs.

---

### LAG identification from model organisms

Human orthologs of genes associated with lifespan extension in model organisms are candidate LAGs.

**More updates to come**


