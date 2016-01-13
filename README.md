# Wild_Barley_Diversity-2013
These scripts were written by Tom Kono and used for read mapping for Wild Barley Diversity Collection samples.

The WBDC_103_2013-11-20.job script takes fastq.gz files and outputs .sam files.

Process_SAM.job takes .sam files and outputs Finished.bam files.

GATK_RTC.job takes .bam files and outputs Realigned.bam files.

GATK_HaplotypeCaller.job takes .bam files and creates RawVCF_Long_Calhoun.vcf files.

Merge_BAMs.job merges all the .bam files.
