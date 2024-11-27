# NSCLC_ICB_CombBiomarker
This repository includes the code and data for the analysis in the manuscript titled: **"Optimizing T Cell Inflamed Signature through A Combination Biomarker Approach for Predicting Immunotherapy Response in NSCLC"**

**main.ipynb**: the R script notebook for the main analysis

**stabl.ipynb**: the python script notebook for selecting genes to develop immune-altered signatures using a machine learning method Stabl: https://github.com/gregbellan/Stabl

**Figure**: figures in the manuscript generated from main.ipynb

**Table**: supplementary tables in the manuscript generated from main.ipynb

**Data**: input files for running main.ipynb (except for gene expression data)

Gene expression data should be log2-transformed TPM/FPKM counts, formated as a gene-by-sample matrix and saved in CSV format (with genes as row names and sample IDs as column names)

The gene expression data used in the manuscript can be downloaded from the following sites:

- **SU2C-MARK**: Supplementary table from *Ravi et al., "Genomic and transcriptomic analysis of checkpoint blockade response in advanced non-small cell lung cancer", Nat Genet (2023)*

- **NSCLC Kim2020**: [GSE135222](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135222) Reference: *Kim et al., "Genome-wide methylation patterns predict clinical benefit of immunotherapy in lung cancer", Clin Epigenetics (2020)*

- **NSCLC Hwang2020**: [GSE136961](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE136961) Reference: *Hwang et al., "Immune gene signatures for predicting durable clinical benefit of anti-PD-1 immunotherapy in patients with non-small cell lung cancer", Sci Rep (2020)*

- **Gastric cancer Kim2018**: FPKM counts from <http://tiger.canceromics.org/> Reference: *Kim et al., "Comprehensive molecular characterization of clinical responses to PD-1 inhibition in metastatic gastric cancer", Nat Med (2018)*

- **Melanoma Riaz2017**: FPKM counts from <http://tiger.canceromics.org/> Reference: *Riaz et al., "Tumor and Microenvironment Evolution during Immunotherapy with Nivolumab", Cell (2017)*

- **Melanoma Hugo2016**: FPKM counts from <http://tiger.canceromics.org/> Reference: *Hugo et al., "Genomic and Transcriptomic Features of Response to Anti-PD-1 Therapy in Metastatic Melanoma", Cell (2016)*

- **Melanoma Gide2019**: FPKM counts from <http://tiger.canceromics.org/> Reference: *Gide et al., "Distinct Immune Cell Populations Define Response to Anti-PD-1 Monotherapy and Anti-PD-1/Anti-CTLA-4 Combined Therapy", Cancer Cell (2019)*
