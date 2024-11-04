# conservation-bio

This project will focuse on the "B" biological replicate of _Candida albicans_. Specifically, this project will analyze the Thi+ version of this replicate; that is, WTB1.  
First quality control was run on the raw data files (WTB1_1.fq.gz and WTB1_2.fq.gz) by running an initial FastQC analysis. This yielded evidence of weakness in the per-base sequence content and sequence duplication.
So, using the albicans.SBATCH script, the raw data files were processed using Trimmomatic.
