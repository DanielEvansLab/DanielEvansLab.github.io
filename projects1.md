---
layout: page
title: Project 1 - LAV identification
---

Two approaches are taken to identify Longevity-Associated Variants (LAVs): using results from [genome-wide association studies (GWAS) of longevity]({{site.baseurl}}/projects1#GWAS) and [analysis of pleiotropy using GWAS summary statistics]({{site.baseurl}}/projects1#pleiotropy).

## <a name="GWAS"></a> Identification of longevity-associated variants (LAVs) from GWAS of longevity

### Rationale/Background

Key genes and genetic networks that modulate human aging can be identified from human genetic studies of longevity. Hypothesis-driven candidate gene association studies based on findings from model organisms have identified several variants associated with longevity or decreased mortality rates in humans, including variants in/near lipoprotein metabolism genes, APOE, FOXO3A, insulin/IGF1 signaling genes, LMNA, RNA editing genes, and HSF2. Identifying genome-wide significant (P≤5x10<sup>-8</sup>) longevity associations from meta-analyses of genome-wide association studies (GWAS) has been challenging, and until recently, variants near the APOE gene represented the only genome-wide significant associations. The longevity associations among variants in the APOE gene region were found to be dependent on the well-characterized APOE ε4 allele, and as these variant alleles were associated with decreased odds of longevity, they did not represent obvious candidates for translation to longevity-promoting therapies. A recent GWAS meta-analysis of longevity, defined as reaching age 90 years or older, conducted by a consortium of European cohorts identified a novel longevity-associated variant (LAV), rs2149954 near the gene EBF1, and the rs2149954 minor allele was associated with increased odds of longevity. A GWAS meta-analysis of longevity performed by the Cohorts for Heart and Aging Research in Genomic Epidemiology (CHARGE) consortium using the same definition of longevity as Deelen et al. but a more precise definition for non-longevity-achieving controls, did not identify a genome-wide significant longevity association in their discovery cohorts. However, the meta-analysis of the CHARGE discovery results with published results for the FOXO3 variant rs2802292 revealed that the G allele was associated with increased odds of longevity at the genome-wide significance level (OR=1.17, P=1.9x10<sup>-10</sup>). 

### Approach

We meta-analyzed discovery-stage GWAS results from [CHARGE, Broer et al.](http://www.ncbi.nlm.nih.gov/pubmed/25199915){:target="_blank"} and [Deelen et al.](http://www.ncbi.nlm.nih.gov/pubmed/24688116){:target="_blank"}. Meta-analysis was performed using METAL software that converted effect direction and P-value into signed Z-scores that were combined from the two studies in a weighted sum, where the weights were proportional to the square-root of the sample size. There was no evidence of P-value inflation (λ=0.99). Our meta-analysis results represent the combined evidence from the two largest GWA studies of human longevity and thus provides a robust set of results to use to prioritize candidate LAVs.

### Data

GWAS summary results from [Broer et al.](http://www.ncbi.nlm.nih.gov/pubmed/25199915){:target="_blank"} and [Deelen et al.](http://www.ncbi.nlm.nih.gov/pubmed/24688116){:target="_blank"}.

### Software

[METAL](http://csg.sph.umich.edu//abecasis/Metal/){:target="_blank"}.

### Expected results

Genome-wide association statistics for reaching age 90. 

---

## <a name="pleiotropy"></a> Identification of LAVs using pleiotropy analysis

### Rationale/Background

LAVs are expected to impact the fundamental process of aging, and as such, should have the property of being associated with multiple age-related traits and diseases.  To further contribute to LAV identification, we will search for variants with evidence of pleiotropic effects on subclinical risk factors for age-associated diseases and for age-related diseases. 

### Approach

The CHARGE Aging and Longevity phenotype working group, led by Dr. Murabito, is comprised of investigators from more than 20 studies across the United States, Europe and Australia examining the genetics of longevity and age-related phenotypes including longevity (survival to age 90 years and older), age at death, morbidity-free survival, hand grip strength as a proxy for frailty, walking speed, healthy aging index, and genome-wide heterozygosity. Many other CHARGE phenotype working groups analyze relevant age-related phenotypes. For example, the Musculoskeletal working group, led by Dr. Kiel, has studied bone mineral density, lean mass, and fractures and the ReproGen working group, led by Dr. Murabito, has studied age at menopause. 

### Data

CHARGE Aging GWAS results
[GEFOS](www.gefos.org){:target="_blank"}
[International Consortium for Blood Pressure](http://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000585.v1.p1&phv=&phd=&pha=3589&pht=&phvf=&phdf=&phaf=1&phtf=&dssp=1&consent=&temp=1){:target="_blank"}
[DIAGRAM, T2D](http://diagram-consortium.org/downloads.html){:target="_blank"}
[MAGIC, diabetes-related traits](http://www.magicinvestigators.org/downloads/){:target="_blank"}
[GIANT, anthropometric traits](http://www.broadinstitute.org/collaboration/giant/index.php/GIANT_consortium_data_files#GIANT_Consortium_2010_GWAS_Metadata_is_Available_Here_for_Download){:target="_blank"}
[Global Lipids Genetics Consortium](http://www.broadinstitute.org/mpg/pubs/lipids2010/){:target="_blank"}
[CARDIoGRAMplusC4D](http://www.cardiogramplusc4d.org/downloads/){:target="_blank"}
[CKDGen Consortium](http://www.type2diabetesgenetics.org/home/portalHome){:target="_blank"}
[Psychiatric Genetics Consortium](https://www.nimhgenetics.org/available_data/data_biosamples/pgc_public.php){:target="_blank"}

### Software

[TATES](http://ctg.cncr.nl/software/tates){:target="_blank"}

### Expected results

SNPs with evidence for pleiotropic effects. 


