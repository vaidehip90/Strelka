# Strelka

Strelka is small variant calling tool for analysis of germline mutation in small cohorts and also somatic mutations in tumor/normal sample pairs.The tools accepts bam file as input alignment file.


# Installation with bioconda

conda install -c bioconda strelka

# Usuage

> Example (Running Strelka to find variants present in the samples)
This analysis example is for germine mutation variants detection.

/home/envs/strelka/configurestrelkaGermlineWorkflow.py --bam VCA.bam --referenceFasta ref.fasta --runDir ./runWorkflow.py -m local -j 8










