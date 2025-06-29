# Code for Hybrid Deep Learning Models for Generating Innovated Reference Year

This repository contains the source code developed and used for the analyses and experiments presented in the research article:  
**"Hybrid Deep Learning Models for Generating Innovated Reference Year"**, submitted to *PLOS ONE*.

The code is available at: https://github.com/jimmyfloyd91/RY  
A citable version with DOI is archived at Zenodo: https://doi.org/10.5281/zenodo.15768673

## 📂 Repository Structure

- **`datapg.ipynb`**  
  This notebook handles data preprocessing. It includes tasks such as loading raw data, cleaning, transforming, and preparing it for analysis or modeling.

- **`refyearpg.ipynb`**  
  This notebook focuses on analyzing publication years or reference data.

- **`rnnpg.ipynb`**  
  This is the core implementation notebook where a Recurrent Neural Network (RNN) is applied. It includes model architecture, training, evaluation, and predictions.

## ⚙️ Requirements

This codebase was developed in Python using Jupyter Notebook. Below are the required libraries:

```
pandas
numpy
seaborn
matplotlib
tensorflow
scikit-learn
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
   ```

2. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

3. Execute the cells in the following order:
   - `datapg.ipynb` → to prepare the dataset
   - `refyearpg.ipynb` → to analyze reference years
   - `rnnpg.ipynb` → to train and test the model

## 🔓 License

This code is licensed under the MIT License. You are free to use, modify, and distribute it under the terms of the license.

