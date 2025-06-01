# DVC Assignment: Dataset & Model Versioning
Link to Repository: [link](https://github.com/Vishesh-30/mlops-week2)  <br /> 
This project demonstrates how to use **DVC (Data Version Control)** along with **Git** to version datasets and machine learning models. It showcases how different versions of data can be used to train models and how DVC helps in tracking these changes efficiently.

## 📌 Objective

- Import data from two versions (`data_v1`, `data_v2`) of the Iris dataset.
- Track dataset changes using DVC.
- Train a model after each data version.
- Track and version the trained model with DVC.
- Use Git tags to mark versions.
- Demonstrate reproducibility by checking out older versions using DVC and Git.

## 📂 Files Included

- `main.py` – Training script for the model.
- `requirements.txt` – List of required Python packages.
- `commands.txt` – Shell commands used to run the project step-by-step.
- `.dvc/`, `.gitignore`, `*.dvc` – DVC tracking files.

## ✅ Requirements

- Python 3.7+
- Git
- DVC

## 🚀 How to Run

1. Clone the repository
2. Follow the steps in `commands.txt` to:
   - Set up environment
   - Add and version datasets
   - Train models
   - Version the models
   - Reproduce older versions

## 📌 Note

This is a simple demonstration project and not intended for production. It is meant to show how DVC integrates into ML workflows for data and model reproducibility.

## 🙌 Acknowledgements

This assignment is part of the learning module on MLOps and version control using DVC.
