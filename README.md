# Environmental determinants differentiate metabolically active soil microorganisms from the total community: the influence of pH and soil moisture


#### Karl J. Romanowicz, Zachary B. Freedman, Rima A. Upchurch, William A. Argiroff, and Donald R. Zak



##### Submitted for review in ***FEMS Microbiology Ecology*** on March 22, 2016


***************

This repository is associated with the manuscript ***"Environmental determinants differentiate metabolically active soil microorganisms from the total community: the influence of pH and soil moisture"*** written by Karl J. Romanowicz, Zachary B. Freedman, Rima A. Upchurch, William A. Argiroff, and Donald R. Zak at the University of Michigan. Links are provided to the original raw sequencing data stored in the Sequence Read Archive at NCBI. Data stored in this repository include all .oligos files for extracting sample plot data from barcoded sequencing runs, final output files generated from the MOTHUR bioinformatic pipeline and used in all downstream statistics, and the RMarkdown dynamic document with rendered statistical code. The full MOTHUR batch files and associated reference databases are also included for reproducibility purposes.

Link to the rendered code file for production of all figures and statistical analyses: ___ *(created with MI-Gradient-Romanowicz-2016.Rmd)*

Direct any questions regarding this repository to lead author [Karl J. Romanowicz](mailto:kjromano@umich.edu).

***************

####Information about this repository

##### **Original .fastq files:**
The original .fastq files were submitted to the NCBI Sequence Read Archive under BioProject [PRJNA222775](http://www.ncbi.nlm.nih.gov/bioproject/PRJNA222775) with SRA accession numbers [SRR1944476](http://trace.ncbi.nlm.nih.gov/Traces/sra/?run=SRR1944476) and [SRR1944477](http://trace.ncbi.nlm.nih.gov/Traces/sra/?run=SRR1944477).

##### **Directories:**
1. **Data:** Includes final output files from **MOTHUR** necessary to run statistics in **R** as well as the environmental metadata `env.txt` necessary for correlation analyses.
	- **Bacteria:** all `.oligos` files for separating bacterial reads by plot
	- **Fungi:** all `.oligos` files for separating fungal reads by plot
	- **mothur.reference:** 16S and 28S reference database files used for alignment and taxonomy assignment purposes for bacteria and fungi.
	- **mothur.output:** final MOTHUR files created from pipeline and used in all downstream statistics. Provided here for reproducibility.
		- MOTHUR `cons.tax.summary` files
		- MOTHUR `groups.summary` files
		- MOTHUR `.shared` files

	*ZIP files need to be extracted and all resulting files placed directly in their* **corresponding directory folder** *for batch files to operate correctly.*

2. **MOTHUR_batch:** includes two batch files for processing raw PacBio sequencing data through a custom MOTHUR bioinformatic pipeline.
	- `bacteria.master.list.subsample.batch` Bacteria MOTHUR batch file
	- `fungi.master.list.subsample.batch` Fungi MOTHUR batch file

3. **Romanowicz-2016.Rmd:** RMarkdown dynamic document with rendered code for complete statistical reproducibility.


**Note:** This project is under the General MIT Public License.
