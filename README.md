# EDMW_2021_python_code
Python notebooks for the EDMW 2021 Satellite Data Training Workshop

## Setup and test your python environment: 

Download this repo and then use a command window to navigate to the repo folder on your computer. Then enter the following commands. This uses the supplied yml file to create a new environment named 'coastwatch' and load the required modules to it. Then it activates the environment runs a script that checks for any missing modules and loads jupyter-lab for displaying the jupyter notebook tutorials.

```
conda env create -f environment.yml
conda activate coastwatch
python check_modules.py
jupyter-lab
```
