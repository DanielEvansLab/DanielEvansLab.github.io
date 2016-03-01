---
layout: page
title: Project 2 - Functional annotation based gene prioritization
---

### Rationale

Association regions marked by LAVs and SNPs in linkage disequilibrium (LD) are typically broad and encompass multiple genes. Approximately 88% of SNPs identified through GWAS are intronic or intergenic, making it challenging to interpret their function. Many SNPs associated with longevity are also in non-coding regions. The ENCODE project and the Roadmap Epigenomics Mapping Consortium have identified functional genomic elements in multiple tissue types. We will employ established methods, including the [SG-Adviser](http://genomics.scripps.edu/ADVISER/){:target="_blank"} variant annotation website developed by Dr. Schork’s group, to identify the overlap between associated variants and functional genomic elements. When performing functional annotation of summary SNP association statistics from HapMap-based imputed data, we will use ImgG software to impute SNP summary statistics to the 1000 Genomes reference panel to increase the coverage of genetic variation and to enhance the analysis of SNP overlap with functional genomic elements.  

Expression quantitative trait loci (eQTL) studies can be used to provide additional information on the potential functional impact of associated variants. A well-known limitation of eQTL studies is that the tissue of interest is not always available. The tissue in which LAVs might act is essentially unknown. It has been observed that SNPs associated with a given trait tend to overlap with chromatin markers of active gene regulation (trimethylation of histone H3 at lysine 4 [H3K4me3]) in a cell-specific manner. This observation can be used to identify tissues that are enriched for overlap between associated SNPs and H3K4me3 peaks, which provides information about tissues relevant to the genetic association. Identification of tissues relevant to genetic associations with longevity can help us to select tissue-specific eQTL studies that are likely to be the most informative for longevity associations. 

### Approach

Prioritize candidate LAGs in association regions using tissue-specific eQTL results and using methods like [DEPICT](http://www.broadinstitute.org/mpg/depict/){:target="_blank"} that prioritizes genes in association regions that significantly share predicted functions with genes from other associated loci in a GWAS. 

Identify tissues that are enriched for overlap between associated SNPs and functional genomic regulatory peaks, which can prioritize eQTL results.

### Data

[GTEx](http://www.gtexportal.org/home/){:target="_blank"}

[ENCODE](https://www.encodeproject.org/){:target="_blank"}

[Roadmap Epigenomics](http://www.roadmapepigenomics.org/){:target="_blank"}

### Software

[Epigwas](https://www.broadinstitute.org/mpg/epigwas/){:target="_blank"}

[GoShifter](https://www.broadinstitute.org/mpg/goshifter/){:target="_blank"}

[SG-Adviser](http://genomics.scripps.edu/ADVISER/){:target="_blank"}

[DEPICT](https://github.com/perslab/depict){:target="_blank"} and also [here](http://www.broadinstitute.org/mpg/depict/){:target="_blank"}

[RegulomeDB](http://regulomedb.org/){:target="_blank"}

[HaploReg](http://www.broadinstitute.org/mammals/haploreg/haploreg.php){:target="_blank"}

### Expected results

Prioritized LAGs from LAVs.

<br>
<p align="center"> 
  <a href="{{ site.baseurl }}/">Home</a> 
</p>
