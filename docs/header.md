# Human variation workflow

This repository contains a [nextflow](https://www.nextflow.io/) workflow
for analysing variation in human genomic data. Specifically this workflow can
perform the following:

* basecalling of FAST5 (or POD5) sequencing data
* diploid variant calling
* structural variant calling
* aggregation of modified base counts

The wf-human-variation workflow consolidates the small variant calling from the
previous wf-human-snp with the structual variant calling from wf-human-sv (both
of which are now deprecated). This pipeline performs the steps of the two
pipelines simultaneously and the results are generated and output in the same
way as they would have been had the pipelines been run separately.

