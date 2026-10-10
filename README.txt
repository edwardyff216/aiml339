README

Environment Requirements

Install the required dependencies:

pip install pandas numpy scikit-learn matplotlib torch joblib scipy statsmodels pyarrow jupyter

Instructions

1. Ensure the raw dataset is located in the following directory:
AIML339_Toxicity/data/raw/dota2_matches/

2. Update the `PROJECT_ROOT` variable in the notebooks to point to your local project directory.

3. Run the notebooks in the following order:
01_data_exploration.ipynb - Data exploration
02_context_features.ipynb - Context feature extraction
03_labeling.ipynb - Data labeling
04_baseline_models.ipynb - Baseline model training
05_context_model.ipynb - Context model training
06_evaluation.ipynb - Model evaluation

Notes
Git LFS is required to download the full data files.