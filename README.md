# 🧠 Multimodal Alzheimer Prediction Project  

This project combines **MRI image data** and **clinical text/tabular data** to predict **Alzheimer's Disease** using a multimodal fusion approach.  

---

## 📘 Project Overview  
The model integrates:  
- 🩻 **CNN (VGG16 Fine-tuned)** for MRI feature extraction  
- 📊 **Random Forest** for tabular clinical features  
- 🔗 A **fusion layer** combining both representations to improve diagnostic accuracy  

---

## ⚙️ Key Steps  

### 🧹 Data Preprocessing  
- MRI images resized and normalized  
- Clinical text data cleaned and standardized  

### 🧠 Model Training  
- CNN fine-tuned on MRI data  
- Tabular model trained and predictions generated  
- Both combined in the fusion stage  

### 📈 Evaluation Metrics  
- Accuracy, Precision, Recall, F1-Score, ROC AUC  
- Visualization: Confusion Matrix, ROC Curve, PR Curve, Feature Importance  

---

## 📊 Model Performance (Fusion Model)

| Metric | Score |
|--------|--------|
| **Accuracy** | 0.81 |
| **ROC AUC** | 0.871 |
| **Precision** | 0.82 |
| **Recall** | 0.81 |
| **F1-Score** | 0.81 |

---

## 🖼️ Visualizations  

| Visualization | File Path |
|----------------|-----------|
| Confusion Matrix | `outputs/confusion_matrix_fusion.png` |
| ROC Curve | `outputs/roc_curve_fusion.png` |
| Precision-Recall Curve | `outputs/pr_curve_fusion.png` |
| Feature Importance | `outputs/feature_importance_fusion.png` |

---

## 🧩 Technologies Used  
- **Python**, **TensorFlow**, **Keras**  
- **Scikit-learn**, **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **JupyterLab**  

---

## 🗂️ Dataset Information  
- Alzheimer’s Disease Dataset (Kaggle – Rabie El Kharoua)  
- Alzheimer MRI Dataset (Kaggle – Legend Ahmed)  

---

## 👩‍💻 Author  
**İrem Çelik**  
Software Engineering Student – Istanbul Aydın University  

