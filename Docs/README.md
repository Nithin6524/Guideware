# Guideware - Node Failure and Resource Exhaustion Prediction System

## Project Overview
This project implements a machine learning-based system for predicting node failures and resource exhaustion in a computing environment. The system uses Random Forest models to analyze and predict potential issues before they occur.

## Project Structure
```
Guideware/
├── src/                    # Source code directory
│   ├── preprocess.ipynb    # Data preprocessing notebook
│   ├── RandomForest_NodeFailure.ipynb
│   └── RandomForest_resourceExhaustion.ipynb
├── models/                 # Trained model files
│   ├── RF_nodeFailure.pkl
│   └── RF_resourceExhaustion.pkl
├── Docs/                   # Documentation
├── TestDataSets/          # Test datasets
└── .git/                  # Git repository
```
## Dataset
The project uses the [Google 2019 Cluster Sample](https://www.kaggle.com/datasets/derrickmwiti/google-2019-cluster-sample) dataset.

## Components

### 1. Data Preprocessing (`preprocess.ipynb`)
- Handles data cleaning and preparation
- Prepares data for model training

### 2. Node Failure Prediction (`RandomForest_NodeFailure.ipynb`)
- Implements Random Forest model for node failure prediction
- Includes model training and evaluation
- Saves trained model to `models/RF_nodeFailure.pkl`

### 3. Resource Exhaustion Prediction (`RandomForest_resourceExhaustion.ipynb`)
- Implements Random Forest model for resource exhaustion prediction
- Includes model training and evaluation
- Saves trained model to `models/RF_resourceExhaustion.pkl`

## Usage
1. Ensure all required dependencies are installed
2. Use either the node failure or resource exhaustion prediction notebooks to train and evaluate models
3. The trained models will be saved in the `models` directory

## Dependencies
- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- numpy

## Getting Started
1. Clone the repository
2. Install required dependencies
3. Open the notebooks in Jupyter
4. Model Notebooks are already run on the preprocessed dataset and you can see the outputs of each cell for better understanding.

## Model Files
The trained models are stored in the `models` directory:
- `RF_nodeFailure.pkl`: Model for predicting node failures
- `RF_resourceExhaustion.pkl`: Model for predicting resource exhaustion

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
