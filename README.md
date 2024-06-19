# FCC Course: Data Analysis with Python

Doing the course using Jupyter Lab within a Python
virtual environement (module venv) utilising PyEnv
for Python versioning.

## Setup the Virtual Environment

Open up the terminal within Jupyter Lab:

- `cd projRootDir`
- `pyenv local 3.12.2`
- create Venv
  - `pyenv exec python -m venv .myFccDataAnalEnv`
- activate Venv
  - `.\.myFccDataAnalEnv\Scripts\activate`
- `pip install ipykernel`
- `python -m ipykernel install --user --name=.myFccDataAnalEnv`
- select the Venv with Jupyter Lab
  - in Jupyter Lab, kernel -\> change kernel -\> select ".myFccDataAnalEnv"

## Other Pip Installs To Do

Open up the terminal within Jupyter Lab:

- `cd myprojectDir`
- make sure we're in the Venv
  - `.\.myFccDataAnalEnv\Scripts\activate` if necessary
- `pip install numpy`
- `pip install matplotlib`
- `pip install pandas`
- `pip install scipy`
- `pip install requests`
- `pip install bokeh` (alternative visualistion package)
- `pip install openpyxl` (for working with Excel files)
