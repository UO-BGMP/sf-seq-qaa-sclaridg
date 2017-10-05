# SF-seq_QAA

This assignment is due Wednesday, Oct 4 by 11:59 PM.

Be sure to upload all relevant materials by the deadline and **double check** to be sure that your off-line repository is up-to-date with your on-line repository. Answers to the questions can be submitted as ```html```, Github markdown, or ```pdf```.

## Files in this Repository

- `cutadapt_out/`: Read length distributions of the trimmed reads for both libraries
- `fastqc_out/`: All files output by FastQC
- `problemset1.Rmd`: All of my comments, responses, plots, and non-script code in an R markdown format (not knitted, so in raw format)
- `problemset1.html`: Same as above, but this will open as a webpage
  - If you use the GitHub web address for this file [here](https://htmlpreview.github.io/), you can view it.
- `scripts/`
  - `cutadapt.srun`: Slurm script for running cutadapt
  - `fastqc.srun`: Slurm script for running FastQC
  - `gsnap.srun`: Slurm script for running GSNAP
  - `stats.py`: Python script that produces mean quality score distributions for a single FASTQ file (unmodified from the script used in the index hopping assignment)
  - `stats.srun`: Slurm script for running my Python script `stats.py`
- `stats_out/`: All files output by my `stats.py` script
  - `rq` files were not needed for this assignment, but these contain counts for mean read quality scores for each FASTQ file
  - `bp` files contain the per-base mean quality across each FASTQ file
