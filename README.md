# TB-Stacking Ensemble: Repository Contents

This repository contains the implementation, features, and results of a Two-Level Tree-Based Stacking (TB-Stacking) ensemble model developed for predicting refactoring opportunities at the class, method, and variable levels.

## 📁 Repository Structure and Content

### 1. Code
- A Jupyter notebook `TBStacking_Ensemble v8.ipynb` implementing the TB-Stacking ensemble model.
- Performs binary classification for refactoring prediction at three levels: class, method, and variable.
- Uses tree-based classifiers as base and meta learners.
- Includes cross-validation and feature selection.

### 2. `Features.xlsx`
- Excel file containing a list and descriptions of software metrics (features) used for prediction.
- Organized by refactoring level (class, method, variable).

### 3. Detailed Results 

| File | Description |
|------|-------------|
| `AllDatasetDet_class.csv` | Raw detection results at the class level (before FS). |
| `AllDatasetDet_method.csv` | Raw detection results at the method level (before FS). |
| `AllDatasetDet_variable.csv` | Raw detection results at the variable level (before FS). |
| `AllDatasetDetFS_class.csv` | Detection results at the class level after feature selection. |
| `AllDatasetDetFS_method.csv` | Detection results at the method level after feature selection. |
| `AllDatasetDetFS_variable.csv` | Detection results at the variable level after feature selection. |

### 4. Evaluation Results

| File | Description |
|------|-------------|
| `AllDatasetResults_class.csv` | Evaluation metrics (e.g., accuracy, F1) at the class level (with FS). |
| `AllDatasetResults_method.csv` | Evaluation metrics at the method level (with FS). |
| `AllDatasetResults_variable.csv` | Evaluation metrics at the variable level (with FS). |
| `AllDatasetResultsNoFS_class.csv` | Evaluation metrics at the class level (no FS). |
| `AllDatasetResultsNoFS_method.csv` | Evaluation metrics at the method level (no FS). |
| `AllDatasetResultsNoFS_variable.csv` | Evaluation metrics at the variable level (no FS). |

### 5. Statistical Analysis Files

| File | Description |
|------|-------------|
| `AllDatasetStatisticalAnalysis_class.csv` | Statistical comparison of models at the class level (with FS). |
| `AllDatasetStatisticalAnalysis_method.csv` | Statistical comparison at the method level (with FS). |
| `AllDatasetStatisticalAnalysis_variable.csv` | Statistical comparison at the variable level (with FS). |
| `AllDatasetStatisticalAnalysisNoFS_class.csv` | Statistical comparison at the class level (no FS). |
| `AllDatasetStatisticalAnalysisNoFS_method.csv` | Statistical comparison at the method level (no FS). |
| `AllDatasetStatisticalAnalysisNoFS_variable.csv` | Statistical comparison at the variable level (no FS). |

---

This README provides a brief overview of all repository files and their purpose. Please refer to the notebook for full implementation details.

### 6. The Preprocessed dataset
Preprocessed dataset, can be downloaded from here (https://www.dropbox.com/s/p5l4kmr9ac38q0k/datasets.zip?dl=0)
