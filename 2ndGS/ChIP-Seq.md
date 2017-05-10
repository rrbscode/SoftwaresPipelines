## Organize various softwares into ChIP-seq data analysis pipeline.
                       
                       
#### 1. Convert SRA to FASTQ, extract compressed files, and merge technical replicates.
(1)  SRA Toolkit: https://www.ncbi.nlm.nih.gov/sra/docs/toolkitsoft/    
(2)  Extract compressed files by using commands 'bzip2', 'gunzip', 'unzip', 'tar', 'xz' or 'unrar'.
(3)  Merge single-end FASTQ files by using command 'cat'.       
(4)  Merge paired-end files by using 'seqtk mergepe'. https://github.com/lh3/seqtk              

#### 2. Check quality for FASTQ files

