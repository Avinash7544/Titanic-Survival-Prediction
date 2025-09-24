# Titanic-Survival-Prediction
This project analyzes the Titanic dataset and builds a machine learning model (Random Forest) to predict survival.
## Features
- Data cleaning and preprocessing
- Feature engineering (Family Size, Title extraction)
- Model training with Random Forest
- Evaluation using accuracy, confusion matrix, classification report
- Visualizations: confusion heatmap & feature importance

-## 🔧 Tools & Environment
- Python (via **Anaconda** distribution)
- Conda virtual environment for dependency management
- VS Code with Jupyter (`.ipynb`) extension
- Libraries: pandas, matplotlib, seaborn, scikit-learn
- Folder Structure
- Titanic-Analysis/
│-- titanic_analysis.ipynb # Jupyter Notebook with code and outputs
│-- titanic_analysis.py # Python script version of the workflow
│-- train.csv # Titanic dataset (optional, not recommended to push large raw data)
│-- requirements.txt # Python dependencies
│-- README.md # Project documentation

Create Environment
conda create -n titanic_env python=3.9 -y
conda activate titanic_env

