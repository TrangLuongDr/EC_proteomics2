# EC_proteomics2
This repository contains the code and dataset for our research on applying machine learning to proteomics data for predicting endometrial cancer (EC) molecular subtypes and tumor mutational burden (TMB) status.

🧬 Research Overview

Endometrial cancer (EC) is a heterogeneous disease with clinically relevant molecular subtypes (CNV-high, CNV-low, MSI-H, POLE). Accurate classification, along with prediction of tumor mutational burden (TMB ≥10 vs <10), is critical for guiding treatment and immunotherapy decisions.

In this project, we use proteomic signatures from tumor biopsy samples to:

Classify EC into molecular subtypes.

Predict TMB status using protein expression profiles.

## 📂 Repository Contents
EC_proteomics2/
- `README.md` – Project documentation (this file) 
- `src/` – protein_combined_dataset.csv   (Preprocessed proteomics dataset)
         – EC_proteomic.ipynb (Jupyter notebooks for exploratory data analysis and visualization)

⚙️ Installation

Clone this repository and install required dependencies:

git clone https://github.com/username/EC_proteomics2.git
cd EC_proteomics2/src
pip install -r requirements.txt


📌 Note: If running in Google Colab, the notebook includes drive mounting code. You can remove or edit these lines when running locally.

🚀 Usage

Open the Jupyter Notebook:

jupyter notebook src/EC_proteomic.ipynb


The notebook steps include:

Loading the dataset (protein_combined_dataset.csv).

Preprocessing and feature selection.

Training machine learning models.

Evaluating performance for genomic subtype classification and TMB prediction.

📊 Dataset

File: protein_combined_dataset.csv

Features: Proteomic expression values (after preprocessing).

Labels:

Genomics Subtype: CNV-high, CNV-low, MSI-H, POLE.

TMB: high (≥10) vs low (<10).

📈 Results (Summary)

Subtype classification and TMB prediction achieved promising performance (see notebook for detailed metrics: accuracy, AUC, precision-recall).

Model interpretability was explored using feature importance to highlight key proteomic signatures.
