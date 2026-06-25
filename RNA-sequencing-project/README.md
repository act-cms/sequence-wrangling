Lesson 01: RNA-sequencing project
=======================

The purpose of this lesson is to introduce students to the analysis and interpretation of RNA-seq differential expression data using a real-world dataset examining immune responses in purple sea urchin (*Strongylocentrotus purpuratus*) larvae.

## Lesson Information
### Lesson Learning Outcomes
At the end of this lesson, students will be able to...
1. perform analysis of differential gene expression using R and necessary packages.
2. Integrate multiple biological databases and reference files to annotate and classify differentially expressed genes.
3. explain how environmental conditions can influence gene expression responses to pathogen infection
4. interpret differential gene expression results to identify biological pathways and cellular processes associated with immune responses.
5. evaluate how host-pathogen interactions may differ across environmental treatments based on transcriptomic evidence.
6. Use gene annotation and ontology resources to infer potential functions of differentially expressed genes.
7. Assess the limitations of genomic annotations and explain how researchers infer gene function when information is incomplete.

### Cyberinfrastructure Prerequisites

Before beginning this lesson, students are expected to have the following skills:

* Basic skills in R programming and syntax, including package installation and library loading
* Ideally, students should have prior exposure to variables, functions, and reading scripts.

### Content Prerequisites

Before beginning this lesson, students are expected to be familiar with the
following content topics:

* Central dogma and gene expression (gene -> mRNA -> protein)
* Regulation of gene expression
* RNA-sequencing workflow (Illumina reads, quality control, alignment, differential gene expression)
* Host-pathogen interactions
* Gene ontology concepts
* Basic statistical concepts (significance testing, p-values, multiple testing correction)

### Resources

* [Download R](https://cran.r-project.org/bin/windows/base/)
* [Download RStudio IDE](https://posit.co/downloads)
* [Posit Cloud](https://posit.cloud/)
* [Prewritten R script](https://github.com/amyltan/CURE_scripts)
* [Echinobase](https://echinobase.org/echinobase/)


## Additional files

The following files include the reference files as well as the datasets that resulted from DESeq2.

| File name     | File content          | 
|--------------|-------------------------|
| refseqLocus_spu_IDmapping.txt | Old and new gene names |
| Tu_Ontology_SuppTableS2.csv  | Gene ontology list from Tu et al. 2012  |
| res14lmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 14 ºC LMR |   
| res18lmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 18 ºC LMR |
| res14hmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 14 ºC HMR |   
| res18hmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 18 ºC HMR |

## Instructional Notes
This activity works best when students have previously been introduced to RNA-seq concepts but have limited experience analyzing transcriptomic datasets. Because the dataset is derived from an authentic research project, students encounter realistic challenges including inconsistent gene nomenclature, incomplete annotations, and interpretation of large gene lists.

Instructors may wish to provide:

* A brief review of RNA-seq workflows
* An overview of fold change and adjusted p-values
* A tutorial on gene ontology databases
* Guidance on interpreting volcano plots or differential expression visualizations
* Examples of how to investigate poorly annotated genes using multiple databases



