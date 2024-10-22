# Project Overview
The project applies LSTM and BiLSTM to design trading strategies for BTC and ETH. The goal is to examine whether those RNN models can leverage trading strategies for the cryptocurrency market. 
# Installation
To run this project locally, install the required Python packages:
``pip install -r requirements.txt``
# Project Structure
├── BTC/                       # Directory containing raw and processed datasets
│   ├── Trained mdoels/         # Raw dataset files
│   └── XGBRegressor_BTC.json
│   └── bayesian_bilstm_model_btc.keras
│   └── bayesian_lstm_btc.keras
│   ├── Methodology_BTC(Updated).ipynb 
├── notebooks/                  # Jupyter notebooks for analysis and exploration
│   └── data_analysis.ipynb
├── src/                        # Source code for machine learning models
│   ├── model.py                # Python file for building the model
│   ├── train.py                # Python file for training the model
│   └── utils.py                # Utility functions for preprocessing, evaluation, etc.
├── requirements.txt            # List of Python packages to install
├── README.md                   # This file
└── main.py                     # Entry point to run the project

