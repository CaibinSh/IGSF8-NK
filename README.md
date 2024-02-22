# IGSF8-NK
This repository contains the scripts to reproduce the figures for our paper titled 'IGSF8 is an Innate Immune Checkpoint and Cancer Immunotherapy Target'

# Requirements
The self-contained [OncoMarkAI](OncoMarkAI/README.md) package is required to run the scripts. The package can be installed by running the following command:
```
git clone https://github.com/gv20-therapeutics/IGSF8-NK.git

cd IGSF8-NK

pip install -e .
```
In addition, lifelines 0.27.7 is required for the survival analysis.

# Usage
The scripts to reproduce the figures are located in the `notebooks` folder. The `figures` folder contains the figures generated by the scripts. See the following table for the description of each script.

| File Name         | Description                        |
|-------------------|------------------------------------|
| [01_pan-cancer_analysis_of_IGSF8.ipynb](/notebooks/01_pan-cancer_analysis_of_IGSF8.ipynb)   | Related to Fig.3A, Fig.3C, Fig.S3D, Fig.S3E, Fig.S3K-N              |
| [02_scRNAseq_of_IGSF8.ipynb](/notebooks/02_scRNAseq_of_IGSF8.ipynb) | Related to Fig.3B and Fig.3D  |
| [03_prognostic_association_of_IGSF8_with_survival.ipynb](/notebooks/03_prognostic_association_of_IGSF8_with_survival.ipynb) | Related to Fig.3F and Fig.S3P |
| [04_prognostic_association_of_IGSF8_with_ICB_response.ipynb](/notebooks/04_prognostic_association_of_IGSF8_with_ICB_response.ipynb) | Related to Fig.3G and Fig.S3Q |
| [05_pan-cancer_analysis_of_KIR3DL2.ipynb](/notebooks/05_pan-cancer_analysis_of_KIR3DL2.ipynb) | Related to Fig.S3F and Fig.S3G |
| [06_association_between_IGSF8_and_MHCI.ipynb](/notebooks/06_association_between_IGSF8_and_MHCI.ipynb) | Related to Fig.3H, Fig.S3I, Fig.S1H |
