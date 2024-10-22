# Project Overview
The project applies LSTM and BiLSTM to design trading strategies for BTC and ETH. The goal is to examine whether those RNN models can leverage trading strategies for the cryptocurrency market. 

## :ledger: Table of Contents

- [Usage](#zap-usage)
  - [Installation](#electric_plug-installation)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Developmen Environment](#nut_and_bolt-development-environment)
  - [File Structure](#file_folder-file-structure)
  - [Build](#hammer-build)  
  - [Deployment](#rocket-deployment)  
- [Community](#cherry_blossom-community)
  - [Contribution](#fire-contribution)
  - [Branches](#cactus-branches)
  - [Guideline](#exclamation-guideline)  
- [FAQ](#question-faq)
- [Resources](#page_facing_up-resources)
- [Gallery](#camera-gallery)
- [Credit/Acknowledgment](#star2-creditacknowledgment)
- [License](#lock-license)

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
└── requirements.text
```

| No | File Name | Details 
|----|------------|-------|
| 1  | index | Entry point

###  :hammer: Build
Write the build Instruction here.

### :rocket: Deployment
Write the deployment instruction here.

## :cherry_blossom: Community

If it's open-source, talk about the community here, ask social media links and other links.

 ###  :fire: Contribution

 Your contributions are always welcome and appreciated. Following are the things you can do to contribute to this project.

 1. **Report a bug** <br>
 If you think you have encountered a bug, and I should know about it, feel free to report it [here]() and I will take care of it.

 2. **Request a feature** <br>
 You can also request for a feature [here](), and if it will viable, it will be picked for development.  

 3. **Create a pull request** <br>
 It can't get better then this, your pull request will be appreciated by the community. You can get started by picking up any open issues from [here]() and make a pull request.

 > If you are new to open-source, make sure to check read more about it [here](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source) and learn more about creating a pull request [here](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github).


 ### :cactus: Branches

 I use an agile continuous integration methodology, so the version is frequently updated and development is really fast.

1. **`stage`** is the development branch.

2. **`master`** is the production branch.

3. No other permanent branches should be created in the main repository, you can create feature branches but they should get merged with the master.

**Steps to work with feature branch**

1. To start working on a new feature, create a new branch prefixed with `feat` and followed by feature name. (ie. `feat-FEATURE-NAME`)
2. Once you are done with your changes, you can raise PR.

**Steps to create a pull request**

1. Make a PR to `stage` branch.
2. Comply with the best practices and guidelines e.g. where the PR concerns visual elements it should have an image showing the effect.
3. It must pass all continuous integration checks and get positive reviews.

After this, changes will be merged.


### :exclamation: Guideline
coding guidelines or other things you want people to follow should follow.


## :question: FAQ
You can optionally add a FAQ section about the project.

##  :page_facing_up: Resources
Add important resources here

##  :camera: Gallery
Pictures of your project.

## :star2: Credit/Acknowledgment
Credit the authors here.

##  :lock: License
Add a license here, or a link to it.


