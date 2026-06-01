# RecA QSAR Machine Learning Notebooks

This folder contains cleaned Google Colab and GitHub-ready notebooks for the RecA QSAR machine learning workflow.

The original notebooks are preserved in the parent `A1` folder. These copies have standardized headers, Colab-ready path helper cells, normalized Python 3 metadata, and cleared outputs for easier GitHub rendering.

## Notebook Order

| Step | Notebook | Description |
|---:|---|---|
| 1 | `01_Data_collection_RecA_publication_ready.ipynb` | Data Collection and Curation of RecA EC50 Bioactivity Data |
| 2 | `02_RecA_PaDEL_Fingerprint_Modeling_Matrix_publication_ready.ipynb` | PaDEL Fingerprint and QSAR Modeling Matrix Preparation |
| 3 | `03_RecA_Feature_Selection_RFE_Benchmark_VALIDATED_METHODS.ipynb` | Feature Selection and RFE Benchmark |
| 4 | `04_RecA_Classical_ML_Modeling_VALIDATION_AUDITED_FIXED.ipynb` | Classical Machine Learning QSAR Modeling |
| 5 | `05_RecA_QSAR_FDA_Bayesian_Docking_PUBLICATION_READY.ipynb` | FDA Prediction, Bayesian Fingerprints, and Docking Follow-up |

## How to Use in Google Colab

1. Upload this folder to GitHub or Google Drive.
2. Open a notebook in Google Colab.
3. If using Drive, uncomment `drive.mount('/content/drive')` in the first code cell.
4. Set `PROJECT_ROOT` if your data are stored in a custom folder.
5. Run notebooks in order from `01` to `05`.

## How to Use in GitHub

- Commit this entire folder.
- GitHub will render the notebooks directly.
- Replace `YOUR_GITHUB_USERNAME/YOUR_REPOSITORY` in the Colab badge links after the repository name is finalized.

## Important

Notebook outputs were intentionally cleared. Re-run the notebooks in Colab or Jupyter to regenerate tables, figures, and model files.

