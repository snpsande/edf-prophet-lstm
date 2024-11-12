# Wintertime Energy Demand Forecasting in the Netherlands with Prophet-LSTM

This repository supports a master thesis project for the University of Amsterdam (UvA) on Wintertime Energy Demand Forecasting in the Netherlands, using an ensemble model combining Prophet and LSTM. This research investigates forecasting energy demand under winter-specific conditions in the Netherlands, addressing seasonal energy patterns and the influence of climate and economic factors.

The full paper can be accessed in MDPI: [Wintertime Energy Demand Forecasting in the Netherlands](https://www.mdpi.com/2227-9717/12/11/2519).

## Repository Contents

This repository contains:

- **Notebooks** for the modeling process, ready to be run with preprocessed datasets.
- **Preprocessed data**: The datasets have been preprocessed and saved in this repository; only the modeling notebook requires execution.
- **README.md**: This document provides guidance on repository structure and usage.

### Main Components

1. **EDA** - _Exploratory Data Analysis_: Summary statistics and visual insights for each dataset.
   
2. **Preprocessing** - _Data Preparation_: The datasets have been cleaned, preprocessed, and merged for modeling. Preprocessed data is saved in this repository.

3. **Modeling** - _Prophet-LSTM Ensemble Model_: The modeling notebook guides the setup, training, and evaluation of the Prophet-LSTM ensemble model used for wintertime energy demand forecasting. Only this notebook needs to be run to execute the modeling phase.

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/snpsande/edf-prophet-lstm.git
    ```
   
2. **Navigate to the repository folder**:
    ```bash
    cd edf-prophet-lstm
    ```
   
3. **Run the Modeling Notebook**:
    Open and execute the modeling notebook to reproduce the forecasting results outlined in the thesis.

---

Refer to the publication or the notebooks for further details on methodology, data sources, and findings.
