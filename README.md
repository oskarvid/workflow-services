# Workflow Services
Building and optimizing workflows since 2016

## Services offered
- Turning a set of scripts into a push-and-play workflow
- Analysis and optimization of already existing workflows
- Automation of indirectly related tasks
- And more

## Contact details
Contact me at oskarvidarsson @ gmail dot com and we will figure out what we can do.

## Past projects
Disclaimer: These projects are in various states of usefullness, they are not maintained and may thus not work, they serve to illustrate what I have worked on rather than being intended for active use.
* [snakemake_germline](https://github.com/oskarvid/snakemake_germline_legacy)
  * Takes fastq files as input, returns vcf files
  * Was based on a workflow that required over 70 hours to finish, I cut it down to 12-16 hours
* [Happy Snake](https://github.com/oskarvid/happy-snake)
  * A workflow that compares vcf files against a gold standard to analyze the performance of the snp and indel predictions
* [GRS workflow](https://github.com/oskarvid/GRSworkflow)
  * A parallelized Genome Risk Score workflow
* [snakeImp](https://github.com/oskarvid/snakeImp)
  * A proof of concept workflow for imputing missing genetic sequences (?)
* [splitFastQ](https://github.com/oskarvid/splitFastq)
  * Split fastq files by lane in parallel! Hacky and hard-coded.
* [VCF-GrowR](https://github.com/oskarvid/VCF-growR)
  * A brute force method of making your vcf files larger
* [wdl_germline_pipeline](https://github.com/oskarvid/wdl_germline_pipeline)
  * A germline variant calling workflow implemented in wdl
* [wdl_deepvariant](https://github.com/oskarvid/wdl_deepvariant)
  * Deepvariant in wdl
* [wdl_hap.py_pipeline](https://github.com/oskarvid/wdl_hap.py_pipeline)
  * The hap.py tool implemented in wdl
* [slurm-germline](https://github.com/oskarvid/slurm-germline)
  * An experiment I threw together to optimize the germline variant calling workflow 100%, it reduced the running time from 70+ hours to about 9 hours
  * It used a large slurm cluster and was able to always use the resources it required immediately
  * It highlights the cost/benefit of adding more and more servers to squeeze every last second out of the execution time by using more and more compute nodes
