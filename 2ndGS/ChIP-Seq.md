## Organize various softwares into ChIP-seq data analysis pipeline.
                       
                                    
#### 1. Convert SRA to FASTQ, extract compressed files, and merge technical replicates.                    
(1)  SRA Toolkit: https://www.ncbi.nlm.nih.gov/sra/docs/toolkitsoft/                     
(2)  Extract compressed files by using commands `bzip2`, `gunzip`, `unzip`, `tar`, `xz` or `unrar`.                   
(3)  Merge single-end FASTQ files (two lanes on a flow cell for the same library) by using command `cat`.    
(4)  Merge the same end of paired-end FASTQ files (two lanes) by using command `cat`.  
(5)  Merge the two ends of paired-end FASTQ into one file by using `seqtk mergepe`.   https://github.com/lh3/seqtk                        
                                                                                          
#### 2. Check quality for FASTQ files       
(1)  FastQC: http://www.bioinformatics.babraham.ac.uk/projects/fastqc/                          
(2)  FastQ Screen: http://www.bioinformatics.babraham.ac.uk/projects/fastq_screen/                            
(3)  fastqp: https://pypi.python.org/pypi/fastqp                                                
(4)  Rqc: https://bioconductor.org/packages/release/bioc/html/Rqc.html                                         
(5)  seqTools: http://www.bioconductor.org/packages/release/bioc/html/seqTools.html                       
(6)  ShortRead: http://bioconductor.org/packages/release/bioc/html/ShortRead.html  
(7)  systemPipeR: https://bioconductor.org/packages/release/bioc/html/systemPipeR.html                                        
(8)  fastools: https://pypi.python.org/pypi/fastools                          
(9)  NGSUtils: https://github.com/ngsutils/ngsutils                               
(10) ngs-bits: https://github.com/imgag/ngs-bits                       
(11) SolexaQA++: http://solexaqa.sourceforge.net/                                         
(12) QC3: https://github.com/slzhao/QC3     
(13) MultiQC: https://github.com/ewels/MultiQC  ,  https://pypi.python.org/pypi/multiqc/                      
                                
#### 3. Remove Duplicates based on FASTQ files, and Correct raw reads



