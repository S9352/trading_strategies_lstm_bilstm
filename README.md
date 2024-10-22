# Project Overview
The project applies LSTM and BiLSTM to design trading strategies for BTC and ETH. The goal is to examine whether those RNN models can leverage trading strategies for the cryptocurrency market. 

## :ledger: Table of Contents

- [Usage](#zap-usage)
  - [Installation](#electric_plug-installation)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Developmen Environment](#nut_and_bolt-development-environment)
  - [File Structure](#file_folder-file-structure)

## :zap: Usage

###  :electric_plug: Installation
- To run this project locally, install the required Python packages:

```
$ pip install -r requirements.txt
```
##  :wrench: Development

### :notebook: Pre-Requisites
The pre-requisites need to develop the project.
- keras-tuner
- scikeras
- pandas_ta
- hyperopt
- quantstats
- tensorflow
- yfinance
- numpy
- pandas

###  :nut_and_bolt: Development Environment
- The project is performed by using Google Colab.
- Before running the project, upload functions.py. The file contains all functions for the main notebooks. 
- The folder "Trained models" contains the best trained models. Upload and apply it.  

###  :file_folder: File Structure

```
.
├── BTC
│   ├── Trained models/
│   │   └── XGBRegressor_BTC.json
│   │   └── bayesian_bilstm_model_btc.keras
│   │   └── bayesian_lstm_btc.keras
│   │   ├── Methodology_BTC(Updated).ipynb 
├── ETH
│   ├── Trained models/
│   │   └── XGBRegressor_ETH.json
│   │   └── bayesian_bilstm_model_ETH.keras
│   │   └── bayesian_lstm_ETH.keras
│   │   ├── Methodology_ETH(Updated).ipynb 
├── LICENSE
├── README.md
├── functions.py
└── requirements.text
```


