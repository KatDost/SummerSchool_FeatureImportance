# Tutorial: Feature Importance

by Sašo Džeroski & Katharina Dost, Jožef Stefan Institute, Ljubljana, Slovenia

This tutorial walks through different techniques to understand and interpret machine learning models:

0. **[0_data_exploration.ipynb](0__data_exploration.ipynb)**  
   Load and explore the datasets used in the tutorial (Adult, Student Performance, Digits).

1. **[1_feature_importance_with_ensembles.ipynb](1__feature_importance_with_ensembles.ipynb)**  
   Use tree-based ensemble models (e.g., Random Forests) to identify globally important features.

2. **[2_feature_importance_with_shap.ipynb](2__feature_importance_with_shap.ipynb)**  
   Apply SHAP values for fine-grained explanations of both tabular and image-based predictions.

3. **[3_feature_importance_with_lime.ipynb](3__feature_importance_with_lime.ipynb)**  
   Use LIME for local, interpretable approximations — including explanations for image classifiers.

Each notebook is self-contained and can be run independently.



## Installation & Setup

Built using Python 3.13.0

### Creating a virtual environment (Recommended):
```bash
# clone repository
git clone https://github.com/KatDost/SummerSchool_FeatureImportance.git

# Navigate to the folder where the repository is downloaded
cd SummerSchool_FeatureImportance

# Verify that Python 3.13.x is installed
#  (if not: download and install from https://www.python.org/downloads/)
py --list

# Create the virtual environment
py -3.13 -m venv .venv

# Activating the virtual environment
#  For MacOS/Linux
source .venv/bin/activate
#  For Windows
.venv\Scripts\activate

# Install the dependencies
pip install -r requirements.txt

# [OPTIONAL] If you wish to use Jupyter Notebook, register the virtual environment
#  as a kernel for Jupyter Notebook (make sure to activate it in your notebook)
pip install ipykernel
python -m ipykernel install --user --name=.venv --display-name "mynewvirtualenvironment"

# [OPTIONAL] Start up Jupyter Notebook
jupyter notebook
```
