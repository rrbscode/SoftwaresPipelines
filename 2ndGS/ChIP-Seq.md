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
(14) PRINSEQ: http://prinseq.sourceforge.net/   
                                
#### 3. Remove Duplicates based on FASTQ files, and Correct raw reads
(1)  ParDRe: https://sourceforge.net/projects/pardre/   
(2)  Clumpify in BBMap: https://www.biostars.org/p/225338/ , https://sourceforge.net/projects/bbmap/   
(3)  PRINSEQ: http://prinseq.sourceforge.net/          
(4)  Lighter: https://github.com/mourisl/Lighter  
(5)  RECKONER: http://sun.aei.polsl.pl/REFRESH/reckoner   
(6)  BLESS2: https://sourceforge.net/projects/bless-ec/  

#### 4. Trim and Filter
(1)  Trimmomatic: http://www.usadellab.org/cms/?page=trimmomatic     
(2)  cutadapt： https://pypi.python.org/pypi/cutadapt     
(3)  Galore: http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/         
(4)  AdapterRemoval:  https://github.com/MikkelSchubert/adapterremoval              
(5)  Flexbar: https://github.com/seqan/flexbar                   
(6)  SeqPrep: https://github.com/jstjohn/SeqPrep                     
(7)  SeqPurge: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1069-7       
(8)  NxTrim: https://github.com/sequencing/NxTrim   
(9)  Atropos: https://github.com/jdidion/atropos    
                       
                   
#### 5. Reads mapping (Mappers or Aligners)
(1)  BWA-mem and BWA-aln:    https://github.com/lh3/bwa           
(2)  Bowtie2:      https://github.com/BenLangmead/bowtie2      
(3)  Stampy:   www.well.ox.ac.uk/bioinformatics/Software/Stampy-latest.tgz      
(4)  Novoalign: http://www.novocraft.com/support/download/     
(5)  Subread: http://subread.sourceforge.net/        
(6)  Yara: https://github.com/seqan/seqan/tree/master/apps/yara , http://packages.seqan.de/                    
(7)  RazerS 3: https://github.com/seqan/seqan/tree/master/apps/razers3  ,  http://packages.seqan.de/                  
(8)  mrsFAST-Ultra:  http://sfu-compbio.github.io/mrsfast/          
(9)  BBMap: https://sourceforge.net/projects/bbmap/                
(10) GMAP-GSNAP: http://research-pub.gene.com/gmap/                     
(11) deBGA:  https://github.com/hitbc/deBGA       
(12) Edlib: https://github.com/Martinsos/edlib                           

                             


