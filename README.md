# Alphafold-pLDDT-Analysis
Code to run analysis of alphafold confidence metrics for S.cerevisiae and E.coli.
VERY IMPORTANT: Keep very close track of your folders on your computer and keep everything very organized to ensure that there are no issues with the code running

To run the analysis, clone this github repo and initialize the enviornment: 
```
git clone https://github.com/tharunr2007/Alphafold-pLDDT-Analysis
cd Alphafold-pLDDT-Analysis
conda env create -f environment.yml
```

Code needs to be run in this order:
Unzipper
JSON Formatter
db_downloader (running this will download the necessary databases to your local machine)
extract_plddt_length
CIS to PDB
Sorter
Comparer
Please let me know if there are any issues 
