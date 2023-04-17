Integrated pipeline for the in-silico analysis of 16s rRNA raw sequence microbiome data.


This code can be used for performing Taxonomic Classification (Multiple levels (1-6): Phylum-Species), Functional Profiling (Multiple levels:1-3, 4: KO annotation), and vizualization (Bar graph, Spider Chart).


Install Parallel-META 3 from **_http://bioinfo.single-cell.cn/parallel-meta.html_**, extract and install software.


Parallel-Meta Suite is a comprehensive and full-automatic computational toolkit for rapid data mining among metagenomic datasets. Both metagenomic shotgun sequences and 16S/18S/ITS rRNA amplicon sequences are accepted. Based on parallel algorithms and optimizations, Parallel-Meta Suite can achieve a very high speed compared to traditional microbiome analysis pipelines. While both single-end and paired-end sequences are accepted for amplicon sequences, only single-end reads are accepted for metagenomic shotgun sequences. The toolkit is available for both Linux and Mac.


For optimal performance, it is recommended to use a computer with the following specs:

**_RAM: 8+ GB_**

**_CPU: 4+ cores, 3.3+ GHz/core_**


Although Parallel-Meta provides automated visualization generation through Rscripts, the R-code provided in our script can be used for customizaton of the graphs.


Pre-requisites for Linux:
**_gcc compiler, cran-R_**


It is a good idea to update all packages and use build-essential to install gcc before using the toolkit.


**_sudo apt upgrade_**

**_sudo apt update_**

**_sudo apt install build-essential_**

**_sudo apt install R-base-core_**


PM-parallel-meta is the profiling tool for 16S rRNA sequences in FASTA/FASTQ format for taxonomical and predictive functional profiling.


Taxonomic classification and functional profiling command: **_PM-parallel-meta [parameters]_**


Multi-sample feature selection based on the taxonomical profiling results command: **_PM-select-taxa [parameters]_**


Multi-sample feature selection based on the taxonomical profiling results command: **_PM-select-func [parameters]_**


Plot bar chart for taxonomic classification results in R libraries: **_ggplot2, tidyr, viridis, ggsci_**


Plot spider chart for functional profiling results in R libraries: **_custom function, radarchart, fmsb, ggradar_**
