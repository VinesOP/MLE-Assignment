# MLE-Assignment

# README  

## **Project Overview**  
This project predicts DON concentration in corn using hyperspectral data. The workflow includes data preprocessing, model training with a neural network, and prediction explanation using SHAP. The model is trained using TensorFlow and Optuna for hyperparameter tuning.  

---

## **Setup Instructions**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/VinesOP/MLE-Assignment.git
cd MLE-Assignment
```

### **2. Install Dependencies**  
Use the requirements file:  
```bash
pip install -r requirements.txt
```

### **3. Open the Colab Notebook**  
Upload `MLE-Assignment.ipynb` to Google Colab and run the cells sequentially.  

---

## **Repository Structure**  
```
├── MLE-Assignment.csv          # Hyperspectral dataset
├── MLE-Assignment.ipynb        # Colab notebook
├── model/                      # Saved model files
├── README.md                   # Project documentation
```

---

## **Usage**  
1. Load the dataset and preprocess it.  
2. Train the model using the Colab notebook.  
3. Evaluate performance and explain predictions with SHAP.  

---
