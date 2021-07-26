# CRUK Bioinformatics Summer School 2021: Functional Genomics
<img src="CRUK_CC_web.jpg" alt="CRUK Cambdridge Centre" width="200" align="right"/>.  
**21st - 27th July 2021: Zoom virtual school, University of Cambridge**

Site short-cut: [https://tinyurl.com/crukss2021](https://tinyurl.com/crukss2021)

## Overview

Functional genomics looks at the dynamic aspects of how the genome functions within cells,
particularly in the form of gene expression (transcription) and gene regulation. This workshop surveys
current methods for functional genomics using high-throughput technologies. 

High-throughput technologies such as next generation sequencing (NGS) can routinely produce massive amounts of data. However, such datasets pose new challenges in the way the data have to be analyzed, annotated and interpreted which are not trivial and are daunting to the wet-lab biologist. This course covers state-of-the-art and best-practice tools for bulk RNA-seq and ChIP-seq data analysis, and will also introduce approaches in prognostic gene signatures.
 

### Audience

Enthusiastic and motivated wet-lab biologists who want to gain more of an understanding of NGS data and eventually progress to analysing their own data

### Pre-requisites

**The course will include a great deal of hands-on work in R and at the command line. In order for you to make the most of the course we <u>strongly recommend</u> that you take an introductory course, or have sufficient experience in the following areas:**

- R
- Unix
- Introductory statistics

**More specific requirements and references can be found [here](Pre-requisites.md)**   


### Instructors & helpers

- [Rory Stark (CRUK CI)](https://www.cruk.cam.ac.uk/author/rory-stark).  
- [Shamith Samarajiwa (MRC CU)](https://www.samarajiwa-lab.org/shamithsamarajiwa)
- [Izzy Newsham (MRC CU)](https://www.samarajiwa-lab.org/izzynewsham). 
- [Junfan Huang (MRC CU)](https://www.samarajiwa-lab.org/junfanhuang).  
- [Ashley Sawle (CRUK CI)](https://www.cruk.cam.ac.uk/author/ashley-sawle).  
- [Abigail Edwards (CRUK CI)](https://www.cruk.cam.ac.uk/author/abigail-edwards).  
- [Jon Price (Gurdon Institute, Cambridge)](https://www.ericmiskalab.org/people/).  
- [Kamal Kishore (CRUK CI)](https://www.cruk.cam.ac.uk/author/kamal-kishore).
- [Stephane Ballereau (CRUK CI)](https://www.cruk.cam.ac.uk/author/stephane-ballereau).      
- [Zeynep Kalender Atak(CRUK CI)](http://www.miller-lab.org/cv_zka.html).  
- [Chandra Sekhar Reddy Chilamakuri (CRUK CI)](https://www.cruk.cam.ac.uk/author/chandra-chilamakuri).  
- [Hugo Tavares (Bioinformatics Training Facility, Dept of Genetics, CU)](https://www.slcu.cam.ac.uk/people/tavares-hugo)
- [Katarzyna Kania (CRUK CI)](https://www.cruk.cam.ac.uk/author/katarzyna-kania).  
- [Mark Fernandes (CRUK CI)](https://www.cruk.cam.ac.uk/author/mark-fernandes). 
- [Matthew Eldridge (CRUK CI)](https://www.cruk.cam.ac.uk/author/matthew-eldridge).  


### Support Team

**Craik-Marshall team**.  
- Alexia Cordona.  
- Cathy Hemmings. 
- Paul Judge.  
**CRUK Cambridge Centre**.  
- Birgitta Olofsson.     
- Justin Holt.    


### Aims
During this course you will learn about:-

- How aligned sequencing reads, genome sequences and genomic regions are represented in R.
- How to handle NGS data and read sequencing data with R, perform quality assessment and execute standard pipelines for (bulk) RNA-Seq and ChIP-Seq analysis
- How to do downstream analysis of transcription factor (TF) and epigenomic (histone mark) ChIP-seq data.  

### Objectives
After the course you should be able to:-

- Know what tools are available in Bioconductor for HTS analysis and understand the basic object-types that are utilised.
- Process and quality control short read sequencing data 
- Given a set of gene identifiers, find out whereabouts in the genome they are located, and vice-versa 
- Produce a list of differentially expressed genes from an RNA-Seq experiment.
- Import a set of ChIP-Seq peaks and investigate their biological context.

# Day 0 (July 20th )

**SOCIAL
18:00 - ..
Informal get-together on Zoom with optional pub-quiz. Meet fellow attendees and some of your trainers.    

School Shared document is [here](https://docs.google.com/document/d/10WM0ZPMbgnTyGgqXO8N7XNSDGQxXGzQCVvSTfjES3tk/edit) **

# Day 1 (July 21st)

__Zoom Virtual Training room__.  
 **July 221st - 27th 2021**
- 09:00 - 09:40; Welcome (Paul & Mark)  &  [What is Functional Genomics?](Introduction/What%20is%20Functional%20Genomics.pdf) (Rory)
- 09:40 - 12:30; Data Processing for Next Generation Sequencing (Shamith, Izzy & Junfan)
  + Lecture 1: [Introduction to next generation sequencing](Introduction/slides/L1-summerSchool.pdf) 
  + Lecture 2: [Quality control and trimming](Introduction/slides/L2-summerSchool.pdf) 
  + Practical 1: [QC and quality trimming of raw sequencing reads](Introduction/practicals/P1_Preprocessing.html) 
  + Lecture 3: [Short read alignment and Quality Control](Introduction/slides/L3-summerSchool.pdf) 
  + Practical 2: [Short read alignment with STAR](Introduction/practicals/P2_Alignment.html)   
  + [Practical 2 Solutions](Introduction/practicals/P2_Alignment_answers.html) 
- 12:30 - 13:30; LUNCH BREAK

- 13:30 - 17:00; Bulk RNAseq  

- 13:30 - 14:00  [Introduction to RNAseq Methods](RNAseq/Markdowns/A_Introduction_to_RNAseq_Methods_SummerSchool.html) \([pdf](RNAseq/Markdowns/A_Introduction_to_RNAseq_Methods_SummerSchool.pdf)\) - Ashley Sawle  
- 14:00 - 15:00 [Quantification of Gene Expression with Salmon](RNAseq/Markdowns/05_Quantification_with_Salmon_introduction.html) \([pdf](RNAseq/Markdowns/05_Quantification_with_Salmon_introduction.pdf)\) - Ashley Sawle  
    + [Practical](RNAseq/Markdowns/05_Quantification_with_Salmon_practical.html)  ([pdf](RNAseq/Markdowns/05_Quantification_with_Salmon_practical.pdf))  
    + [Practical solutions](RNAseq/Markdowns/05_Quantification_with_Salmon_practical.Solutions.html) ([pdf](RNAseq/Markdowns/05_Quantification_with_Salmon_practical.Solutions.pdf))
 - 15:00 - 17:00 - [RNA-seq 
Data Exploration](RNAseq/Markdowns/07_Data_Exploration.html) ([pdf](RNAseq/Markdowns/07_Data_Exploration.pdf)) - Ashley Sawle   
   + [Practical solutions](RNAseq/Markdowns/07_Data_Exploration.Solutions.html) ([pdf](RNAseq/Markdowns/07_Data_Exploration.Solutions.pdf))
   + [Ashley's Live Script](RNAseq/live_scripts/Data_Exploration.R)

  + [Extended Material](RNAseq/Extended_index.md)

<hr>
 
# Day 2 (July 22nd) - Bulk RNAseq
    
- 09:30 - 13:00 Statistical Analysis of Bulk RNAseq Data
    + Part I: [Statistics of RNA-seq analysis](RNAseq/Markdowns/08_Stats.pdf) - Zeynep Kalender Atak  
    + Part II: [Linear Models in R and DESeq2](RNAseq/Markdowns/09_Linear_Models.html) ([pdf](RNAseq/Markdowns/09_Linear_Models.pdf)) - Hugo Tavares  
        + [Slides](https://docs.google.com/presentation/d/1FTP_gdOQ7sBQWZqTbkB97uUzZ57O9FTyVTgfQrqHPeg/edit?usp=sharing) 
        + Find the worksheet in 
          `Course_Materials/RNAseq/stats/models_in_r_worksheet.R`

- 13:00 - 14:00; LUNCH BREAK

- 14:00 - 17:00 [Differential Expression for RNA-seq](RNAseq/Markdowns/10_DE_analysis_with_DESeq2.html) ([pdf](RNAseq/Markdowns/10_DE_analysis_with_DESeq2.pdf)) - Ashley Sawle
    + [practical solutions](RNAseq/Markdowns/10_DE_analysis_with_DESeq2.Solutions.html) ([pdf](RNAseq/Markdowns/10_DE_analysis_with_DESeq2.Solutions.html))  
    [Ash's Live Script](RNAseq/live_scripts/Differential_Expression_Analysis.R)  
 
<hr>

# Day 3 (July 23rd)

- 09:30 - 12:30;  Bulk RNAseq
- 09:30 - 11:15 [Annotation and Visualisation of RNA-seq
results](RNAseq/Markdowns/11_Annotation_and_Visualisation.html) ([pdf](RNAseq/Markdowns/11_Annotation_and_Visualisation.pdf)) - Abbi Edwards    
    + [practical solutions](RNAseq/Markdowns/11_Annotation_and_Visualisation_Solutions.html)   
    + [Abbi's Live Script](RNAseq/live_scripts/AandV_liveScript.R)   
- 11:15 - 12:30 [Gene-set testing](RNAseq/Markdowns/12_Gene_set_testing_introduction.html) - Stephane Ballereau    
    + [Practical (html)](RNAseq/Markdowns/12_Gene_set_testing.html) [(pdf)](RNAseq/Markdowns/12_Gene_set_testing.pdf)
    <!-- + [Practical solutions (html)](12_Gene_set_testing.Solutions.html) [(rmd)](RNAseq/Markdowns/12_Gene_set_testing.Solutions.Rmd) [(pdf)](RNAseq/Markdowns/12_Gene_set_testing.Solutions.pdf) -->

- 12:30 - 13:30; LUNCH

- 13:30 - 17:00; Single Cell RNAseq  
- 13:30 - 14:15 Introduction
    + [Slides](scRNAseq/Slides/Introduction_to_Single_Cell_RNAseq_CRUK_Kania_23rd_July_2021.pdf) - Katarzyna Kania 
- 14:15 - 14:30 Preamble: data set and workflow - Stephane Ballereau
    + [Slides](scRNAseq/Slides/dataSetSlides.html) \([pdf](scRNAseq/Slides/dataSetSlides.pdf)\)  
- 14:30 - 15:55 Library structure, cellranger for alignment and cell calling, preprocessing - Ashley Sawle
    + [Slides](scRNAseq/Slides/CellRangerSlides.html)  \([pdf](scRNAseq/Slides/CellRangerSlides.pdf)\) 
    + [Alignment with Cell Ranger](scRNAseq/Markdowns/cellRanger.html)
    + [QC and preprocessing](scRNAseq/Markdowns/preProc.html)     
    + [Exercise Solutions](scRNAseq/Markdowns/preProc.Exercise.Solution.html)
- 15:55 - 16:05 **10 min break**
- 16:05 - 17:30 Normalisation - Stephane Ballereau
    + [Slides](scRNAseq/Slides/normalisationSlides.html) \([pdf](scRNAseq/Slides/normalisationSlides.pdf)\)  
    + [Practical](scRNAseq/Markdowns/normalisation_5hCellPerSpl_caron.html)     
    + [Exercise Solutions](scRNAseq/Markdowns/normalisation_exercise_solutions.html)
    
    
**6pm SOCIAL: Zoom Talk: “Perspectives on AI by Rory Stark”. **
 
<hr>

# Weekend - recharge your batteries!

[SOCIAL: Punting tour of Cambridge](https://www.youtube.com/watch?v=78LWxvCA-fM)

[SOCIAL: Virtual tour of Cambridge University Botanical Gardens](https://youtu.be/MyCGUi0WKN4)

[SOCIAL/WORK: Virtual tour of CRUK Cambridge Institute](https://www.cruk.cam.ac.uk/operations/scientific-administration/institute-virtual-tour)

[SOCIAL: Aeriel 360 panoramas of Cambridge venues](https://www.xcopters.co.uk/virtualtours.html)

[WORK: For those who feel the need to brush up on their linux skills](https://datacarpentry.org/shell-genomics/)

[WORK: For those wanting an R course with extensive use of Tidyverse](https://bioinformatics-core-shared-training.github.io/bite-size-r-intermediate/)


# Day 4 (July 26th) Single Cell RNAseq continued   

- 09:30 - 10:55 Dimensionality reduction, feature selection - Zeynep Kalender Atak  
    + [Slides](scRNAseq/Slides/FeatureSelectionAndDimensionalityReductionSlides.html)
    + [Dimensionality reduction, feature selection](scRNAseq/Markdowns/dimRedFeatSel_2021.html)
    + [Exercise Solutions](scRNAseq/CourseMaterials/Challenges/DimRedChallengeSolutions.html)
- 10:55 - 11:05 **10 min break**
- 11:05 - 12:30 Batch correction and data set integration - Abigail Edwards
    + [Slides](scRNAseq/Slides/DataIntergrationAndBatchCorrectionSlides.html)  
    + [Data set integration](scRNAseq/Markdowns/dataSetIntegration_PBMMC_ETV6-RUNX1.html)     
  Extended Materials
    + [Batch correction](scRNAseq/Markdowns/batchCorrection.html)     
    <!--  + [Extended Data Integration Workflow](scRNAseq/Markdowns/dataSetIntegration_PBMMC_ETV6-RUNX1_Extended.html)     -->
- **12:30 - 13:30 LUNCH**
- 13:30 - 14:30 Clustering - Stephane Ballereau
    + [Slides](scRNAseq/Slides/clusteringSlides.html)
    + [Practical](scRNAseq/Markdowns/clusteringPostDsi.html)     
    + [Exercise Solutions](scRNAseq/Markdowns/clusteringPostDsi_exercise_solutions.html)

- 14:30 - 15:25 Cluster marker genes - Zeynep Kalender Atak  
    + [Slides](scRNAseq/Slides/MarkerIdentificationSlides.html)
    + [Cluster marker genes](scRNAseq/Markdowns/ClusterMarkerGenes2021.html)
- 15:25 - 15:35 **10 min break**
- 15:35 - 16:30 Differential expression and abundance between conditions - Stephane Ballereau
    + [Slides](scRNAseq/Slides/multiSplCompSlides.html)
    + [Practical](scRNAseq/Markdowns/multiSplComp.html)     
    <!-- + [Exercise Solutions](scRNAseq/Markdowns/multiSplComp_exercise_solutions.html) -->

- 16:30 - 17:30 Trajectories - Zeynep Kalender Atak
    + [Slides](scRNAseq/Slides/TrajectoryInferenceSlides.html)
    + [Trajectories](scRNAseq/Markdowns/pseudoTime_2021.html)
    
<hr>
# Day 5 (July 27th)

- 09:30 - 17:00; 
- ChIP-seq data analysis (Shamith, Izzy & Junfan)
    + Lecture 1: [Introduction to ChIP-seq](ChIPSeq/slides/Introduction.pdf) 
    + Lecture 2: [Introduction to Peak Calling](ChIPSeq/slides/PeakCalling.pdf) 
    + Practical 1: [Peak calling with MACS2](ChIPSeq/scripts/ChIP_Practical1_peakcall.html)
    + Lecture 3: [Quality control methods for ChIP-seq](ChIPSeq/slides/EvaluatingChIPseqData.pdf)
    + Practical 2: [QC & Integrative Genome Viewer](ChIPSeq/scripts/ChIP_Practical2_qc.html) 
    + Lecture 4: [Downstream analysis of ChIP-seq](ChIPSeq/slides/DownstreamAnalysis.pdf) 
    + Practical 3: [Differential binding analysis: Diffbind](ChIPSeq/scripts/ChIP_Practical3_DiffBind.html) 
    + Practical 4: [Downstream analysis of ChIP-seq](ChIPSeq/scripts/ChIP_Practical4_downstream.html) 
 
- 12:30 - 13:30; LUNCH BREAK

# Course Feedback.  
Please don't forget to fill in the [survey]( https://www.surveymonkey.co.uk/r/XHGS7P6 )  

<hr>

<!--
## Data
- Mouse mammary data (counts): [https://figshare.com/s/1d788fd384d33e913a2a](https://figshare.com/s/1d788fd384d33e913a2a)
-->
