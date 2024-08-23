# easyTSS
A pipeline for process all TSS related data (CAGE, TSS-seq, TIF-seq etc.) easily.

## tools used
- fastqc
- multiqc
- fastp
- ribodetector
- mapping tools
  - hisat2
  - STAR
- TSSr  

## Install
We recommend install all the tools by conda:
```
conda create -n easyTSS
conda install fastqc multiqc fastp ribodetector hisat2 STAR
# TSSr maybe need update
```
