# Data Cleaning & Preprocessing - Example Repo

This repository demonstrates a complete **Data Cleaning & Preprocessing** workflow using Python (Pandas, NumPy, scikit-learn) and visualizations (Matplotlib/Seaborn). The notebook includes:
- Importing and exploring data
- Handling missing values (mean/median/imputation)
- Encoding categorical variables
- Normalizing / standardizing numerical features
- Visualizing and removing outliers (boxplots)
- Saving cleaned dataset

**Files in this repo**
- `data_cleaning_preprocessing.ipynb` - Jupyter notebook with step-by-step code and visualizations.
- `sample_data.csv` - Example dataset used in the notebook.
- `requirements.txt` - Python dependencies.

## How to run
1. (Optional) Create and activate a Python virtual environment.
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter Notebook: `jupyter notebook` and open `data_cleaning_preprocessing.ipynb`.
4. Run the notebook cells sequentially.

## Notes
- This notebook is intended as a tutorial and starting point. Replace `sample_data.csv` with your dataset and adapt preprocessing decisions accordingly.
- For production use, consider persisting preprocessing steps using `sklearn` pipelines and saving encoders/scalers.
