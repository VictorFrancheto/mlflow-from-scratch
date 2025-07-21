# mlflow-from-scratch

<p align="center">
  <img src="https://github.com/VictorFrancheto/mlflow-from-scratch/blob/main/image.jpg">
</p>

# 📊 Experiment with MLflow 3.1.1 — Training, Logging, and Model Loading

This repository demonstrates how to use **MLflow 3.1.1** to track the entire lifecycle of a machine learning experiment — from training to loading the final model.

## 🚀 What Will Be Done

* Train a machine learning model using `XGBoost`;
* Perform hyperparameter optimization with **Optuna**;
* Log hyperparameters, metrics, and visualizations to **MLflow**;
* Save the **best trained model** to MLflow;
* Load the model later using its URI.


## 🧠 Why Use MLflow?

MLflow allows you to:

✅ Automatically track metrics, parameters, and artifacts from experiments;\
✅ Easily compare runs through a clean web interface;\
✅ Save and version trained models, ensuring reproducibility;\
✅ Load saved models effortlessly without manual disk handling;\
✅ Integrate with multiple frameworks like `xgboost`, `sklearn`, `pytorch`, and more.

## 📦 Requirements

- Python 2.1.4
- MLflow 3.1.1
- XGBoost 2.1.4
- Optuna
- Matplotlib / Pandas / Scikit-learn

## 🚀 Initializing the MLflow Server

To start the MLflow tracking server locally, follow the steps based on your environment:

---

### 🐍 **Using Anaconda**

1. Open the **Anaconda Command Prompt**  
2. Navigate to your project directory:

   ```bash
   cd your-project-path
   
3. Run the MLflow server:

   ```bash
   python -m mlflow server --host 127.0.0.1 --port 8282
  
### 💻 **Using VS Code**

1. Open the terminal in VS Code;
2. Run the command below:

   ```bash
   py -m mlflow server --host 127.0.0.1 --port 8282

✅ Make sure you're using the same Python environment or kernel as the one used in your notebook or training script.

---

### 📦 Project Structure

```
project-flow/
├── .ipynb_checkpoints/                      ← Auto-generated folder by Jupyter
├── mlartifacts/                             ← Folder where MLflow stores artifacts (locally)
├── mlruns/                                  ← MLflow tracking directory (for runs metadata)
├── README.md                                ← Project description and instructions
├── Wholesale customers data.csv             ← Dataset used for training or analysis
└── mlops-project.ipynb                      ← Main notebook with full ML pipeline
```




