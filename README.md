# breast_cancer_deeplearningproject1
# 🧠 Breast Cancer Prediction using Deep Learning

This project uses a neural network built with **TensorFlow and Keras** to predict whether a tumor is **malignant** (cancerous) or **benign** (non-cancerous), using a real-world dataset from **scikit-learn**.

---

## 📊 Dataset Details

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Total Records**: 569
- **Features**: 30 numeric features describing cell characteristics
- **Target**:
  - `0` = Malignant (cancerous)
  - `1` = Benign (non-cancerous)

---

## 🧰 Tools & Libraries Used

- Python
- NumPy & Pandas
- Matplotlib
- Scikit-learn
- TensorFlow & Keras

---

## 🏗️ Project Workflow

1. **Data Loading** – Loaded the breast cancer dataset using scikit-learn  
2. **Data Exploration** – Checked data shape, labels, and visual patterns  
3. **Preprocessing** – Standardized features using `StandardScaler`  
4. **Model Building** – Constructed a basic neural network using Keras  
5. **Training** – Trained the model with `validation_split=0.1` and `epochs=10`  
6. **Evaluation** – Plotted accuracy over epochs for training and validation  
7. **Prediction** – Used the trained model to predict outcomes on test data

---

