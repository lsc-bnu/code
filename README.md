# Code for core analytical methods in:
# Global decline in livestock feed efficiency despite structural optimization

This repository contains the core analytical code used in the manuscript entitled **"Global decline in livestock feed efficiency despite structural optimization"**.

The repository includes the main algorithmic notebooks for the three core components of the study:
- **LMDI decomposition**
- **Machine-learning analysis**
- **LiNGAM-based causal analysis**

Please note that this repository contains the **core method code only**.  
It does **not** include the full data-processing pipeline, figure-generation scripts, or all intermediate files required to reproduce every result in the manuscript exactly.

## Repository contents

- `LMDI.ipynb`  
  Notebook for Logarithmic Mean Divisia Index (LMDI) decomposition analysis.

- `ML.ipynb`  
  Notebook for machine-learning analysis of key drivers.

- `LinGAM.ipynb`  
  Notebook for causal analysis based on the LiNGAM framework.

- `README.md`  
  Documentation for this repository.

## Scope of this repository

This repository is intended to provide the **main analytical logic and implementation** of the core methods used in the study.

It is suitable for:
- understanding the analytical workflow,
- inspecting the model structure,
- reviewing the main computational procedures,
- adapting the methods to similarly structured datasets.

It is **not intended as a complete end-to-end reproduction package** for all manuscript results.

## System requirements

The notebooks were developed for use in **Python 3.12** within a Jupyter Notebook environment.

They can be run on standard desktop or laptop computers using common operating systems such as:
- Windows
- macOS
- Linux

Typical Python packages required may include:
- numpy
- pandas
- scipy
- scikit-learn
- xgboost
- shap
- lingam
- dowhy
- jupyter

Depending on the local environment and notebook configuration, additional packages may be required.

## Hardware requirements

No non-standard hardware is required.

## Installation guide

1. Install Python 3.12.
2. Install Jupyter Notebook or JupyterLab.
3. Install the required Python packages in your local environment.
4. Download or clone this repository.
5. Open the notebooks in Jupyter and run them interactively.

Typical setup time on a standard desktop computer is within several minutes, depending on package installation status and internet speed.

## Input data

The notebooks are designed for structured input data corresponding to the variables described in the manuscript.

Because this repository provides the **core analytical code only**, users may need to prepare their own input data in a compatible format before running the notebooks.

## How to run

Open the notebooks in Jupyter Notebook or JupyterLab and run the cells sequentially.

Suggested notebooks:
1. `LMDI.ipynb`
2. `ML.ipynb`
3. `LinGAM.ipynb`

Users may need to modify file paths, variable names, or input-table structure depending on their local setup and data organization.

## Expected output

Running the notebooks should generate the primary analytical outputs associated with each method, such as:
- decomposition results from LMDI,
- model outputs and feature-importance-related results from machine-learning analysis,
- causal-structure and causal-effect-related results from LiNGAM analysis.

Exact outputs may depend on the input data supplied by the user.

## Use on your own data

To apply the notebooks to your own data:
1. Prepare input data with a structure compatible with the notebooks.
2. Update file paths and data-loading sections as needed.
3. Run all cells sequentially.
4. Check intermediate outputs to ensure that the input format matches the expected structure.

## Reproducibility note

This repository provides the **core computational methods** underlying the study, but does not contain the complete workflow needed to regenerate all manuscript figures and processed datasets exactly.

For the full study design, variable definitions, and interpretation of results, please refer to the manuscript.
