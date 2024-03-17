# EOS30GR Validation Toolkit

## Overview

This EOS30GR Validation Toolkit provides a suite for validating and analyzing the performance and bias of chemical compound prediction models. Designed with reproducibility and robustness in mind, this toolkit offers datasets, notebooks for analysis, and source code for processing chemical compound data.

**Model link** - [eos30gr](https://github.com/ersilia-os/eos30gr)

## Contents

- **Data**: This folder contains three key datasets for the validation process:
  - `predictions.csv`: Contains prediction scores from the model for various compounds.
  - `smiles_to_inchikeys_conversion.csv`: Offers a mapping between SMILES representations and InChIKeys of compounds.
  - `reference_library.csv`: A reference dataset containing 1000 SMILES strings.
- **Notebooks**: Jupyter notebooks provided for detailed analysis and validation steps:

  - `00_model_bias.ipynb`: Investigates potential biases in the model's predictions.
  - `01_model_reproducibility.ipynb`: Ensures the reproducibility of the model's predictions.
  - `02_external_validation.ipynb`: Conducts validation against external datasets.

- **Src (Source Code)**: Contains Python scripts essential for data processing and analysis:
  - `smiles_processing.py`: A utility script for processing SMILES strings of chemical compounds.

## Requirements

The toolkit requires the following Python libraries:

- RDKit
- pandas
- numpy
- standardiser
- scikit-learn
- matplotlib
- ersilia.

A `requirements.txt` file is included for easy installation of dependencies.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
