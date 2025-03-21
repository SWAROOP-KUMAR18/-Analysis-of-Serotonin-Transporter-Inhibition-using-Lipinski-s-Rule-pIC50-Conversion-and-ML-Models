# Serotonin Transporter Inhibition Analysis in Rattus norvegicus using Lipinski's Rule, pIC50 Conversion, and Machine Learning Models
## Project Overview

This project aims to predict the inhibition of the serotonin transporter in *Rattus norvegicus* using various machine learning models. The data analysis involves the application of **Lipinski’s Rule** for drug-like properties, **pIC50 Conversion** for bioactivity values, and training multiple classifiers to predict the inhibitory activity of compounds.

### Key Models Used:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
Data
The dataset for this project is sourced from the ChEMBL database, specifically the Rattus norvegicus Serotonin Transporter ('CHEMBL313').

The dataset includes:

Compound identifiers
pIC50 values
Molecular descriptors
Other relevant features for classification
Methods
Lipinski’s Rule:
Lipinski’s Rule of Five was applied to filter out compounds that are unlikely to be orally bioavailable. This rule is used to assess the drug-likeness of molecules based on properties like molecular weight, hydrophobicity, hydrogen bonding, etc.

pIC50 Conversion:
The pIC50 values were converted from IC50 values using the formula:

pIC50
=
−
log
⁡
10
(
IC50
)
pIC50=−log 
10
​
 (IC50)
This conversion helps in analyzing the inhibitory activity of compounds.

Models
Four machine learning models were trained on the data:

Logistic Regression: A simple linear classifier used for binary classification tasks.
Decision Tree Classifier: A non-linear classifier used to make predictions based on decision trees.
Random Forest Classifier: An ensemble model consisting of multiple decision trees to improve predictive performance.
K-Nearest Neighbors (KNN): A non-parametric method used for classification based on proximity to neighbors in feature space.
Results
The models were evaluated based on accuracy, precision, recall, and F1-score. The best performing model achieved an overall accuracy of X%, with detailed evaluation metrics included in the results.txt file.


Usage
After installing the required packages and dependencies, you can run the project using the following command:
python main.py

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/SWAROOP-KUMAR18/Serotonin-Transporter-CHEMBL313.git
cd Serotonin-Transporter-CHEMBL313
pip install -r requirements.txt
