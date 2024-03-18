# Molecular Solubility Predictor
## Overview
This repository contains code for a Molecular Solubility Predictor, a project aimed at predicting the solubility of chemical compounds using molecular descriptors and regression modeling techniques.

## Features
Utilizes RDKit and Mordred libraries for molecular descriptor calculation.

Performs data preprocessing, including molecule embedding and feature extraction.

Implements regression modeling using statsmodels for solubility prediction.

Provides functionality to visualize and analyze model performance.

## Requirements

Python 3.x
RDKit
Mordred
Pandas
NumPy
Seaborn
Matplotlib
Statsmodels

## Data
The dataset used for training and testing the model should be provided separately. Ensure that the dataset contains the following columns:

SMILES: Chemical structure represented as a SMILES string.
Solubility: Target variable representing the solubility of the compounds.
