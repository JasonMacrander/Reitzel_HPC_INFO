#Bowtie2
###INTRO:
[Bowtie 2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml "Bowtie2") is an "ultrafast" 


###CRASH COURSE:

There are three steps involved with this program that use scripts known as ["wrappers"](http://bowtie-bio.sourceforge.net/bowtie2/manual.shtml#wrapper-scripts "Vanilla ICE") that automatically go through a series of scripts based on data type/format that is automatically interpreted by the program. 

1. First you need to make an index file for the transcriptome or genome your are mapping the raw reads to:

Command:
```
~bowtie2DIR/bowtie2-build <FILE_NAME> <INDEX_NAME>
```
Example:
```
~bowtie2DIR/bowtie2-build Nematostella.fa Stella
```
> The Nematostella genome scaffolding contains 10,804 scaffolds and the index build step took approximately 6 minutes.
