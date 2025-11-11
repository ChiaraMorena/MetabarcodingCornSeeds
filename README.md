This repository allow the analysis of data obtained from the Illumina sequencing of ITS region of fungi in an enviromental sample.
Qiime2 need a linux enviroment to work.
1) download WSL for windows and Ubuntu distro.
2) install conda for linux
3) clone the repo
   git clone git clone https://github.com/ChiaraMorena/MetabarcodingCornSeeds
5) create an enviroment with the .yml file of the repo
    conda env create -f MetabarcodingCornSeeds/snakemake-qiime2.yml
   and activate
   conda activate snakemake
