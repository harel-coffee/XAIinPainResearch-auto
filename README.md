# Explainable Artificial Intelligence (XAI) in Pain Research:Understanding the Role of Electrodermal Activity for Automated Pain Recognition

## Description
This is a repository to implement machine learning techniques focusing on the EDA channel of the PainMonit and BioVid datasets.

## How to use this repository
- Clone the project (git clone https://github.com/gouverneurp/XAIinPainResearch.git).
- Install Python (tested under 'Python 3.9.7').
- Create a python environment (python -m venv venv) and activate it (windows: .\venv\Scripts\activate).
- Install the requirements (pip install -r requirements.txt).
- Place the datasaets in the directories under "datasets" following the description in the readme files.
- Run "create_np_files.py" to create the Numpy dataset.
- Run "hcf.py" to create hand-crafted features (HCF).
- Run "main.py" or other scripts to evaluate the implemented methods.