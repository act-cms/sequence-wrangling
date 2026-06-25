Lesson 01: RNA-sequencing project
=======================

The purpose of this lesson is to perform differential gene expression analysis in sea urchin samples exposed to different environmental conditions.

## Lesson Information
### Lesson Learning Outcomes
At the end of this lesson, students will be able to...
1. perform analysis of differential gene expression using R and necessary packages.
2. identify differentially expressed genes (both up- and downregulated) in sea urchin larval samples infected with a pathogen (*Vibrio diazotrophicus*) in ambient and elevated temperatures.
3. propose mechanisms that may lead to differences in the immune reaction of the echinoderms in different temperatures.

### Cyberinfrastructure Prerequisites

Before beginning this lesson, students are expected to have the following skills:

* Basic skills in R programming and syntax, including package installation and library loading

### Content Prerequisites

Before beginning this lesson, students are expected to be familiar with the
following content topics:

* Central dogma and gene expression (gene -> mRNA -> protein)
* Regulation of gene expression
* RNA-sequencing workflow (Illumina reads, quality control, alignment, differential gene expression) 

### Resources

* [Download R](https://cran.r-project.org/bin/windows/base/)
* [Download RStudio IDE](https://posit.co/downloads)
* [Posit Cloud](https://posit.cloud/)
* [Prewritten R script](https://github.com/amyltan/CURE_scripts)
* [Echinobase](https://echinobase.org/echinobase/)


## Additional files

Three versions of this lesson are provided, each with a different intended
modality of instruction and associated implementation strategies.

| File name     | File content          | 
|--------------|-------------------------|
| refseqLocus_spu_IDmapping.txt | Old and new gene names |
| Tu_Ontology_SuppTableS2.csv  | Gene ontology list from Tu et al. 2012  |
| res14lmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 14 ºC LMR |   
| res18lmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 18 ºC LMR |
| res14hmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 14 ºC HMR |   
| res18hmr24-MM-DEG-Oct25.csv  | Results for the larvae raised in 18 ºC HMR |



Also provided to support adopting instructors are
- `instructor-key.ipynb`: Instructor "key" notebook with completed code cells and full instructor commentary in Markdown cells
- `instructor-notes.ipynb`: Author notes for adopting instructors, including implementation strategies, common issues & workarounds, piloting notes, etc.

See the `instructor-notes.ipynb` For more information about implementation
strategies from the lesson author.



