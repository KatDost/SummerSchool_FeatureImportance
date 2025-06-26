# SummerSchool_FeatureImportance

Built using Python 3.13.0

## Creating a virtual environment (Recommended):
```bash
# Navigate to the folder where the repository is downloaded
cd FeCoNi

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
