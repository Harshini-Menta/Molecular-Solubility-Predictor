# Molecular Solubility Predictor
## Overview
This repository contains code for a Molecular Solubility Predictor, a project aimed at predicting the solubility of chemical compounds using molecular descriptors and regression modeling techniques.

Solubility refers to the ability of a substance (solute) to dissolve in a solvent to form a homogeneous mixture, known as a solution. It is a physical property that describes the extent to which a substance can dissolve in a given solvent under specific conditions, such as temperature and pressure.

Solubility is typically expressed in terms of the amount of solute that can dissolve in a certain amount of solvent, often measured in grams of solute per 100 grams of solvent or in moles of solute per liter of solvent. The solubility of a substance can vary widely depending on factors such as the nature of the solute and solvent, temperature, and pressure

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
