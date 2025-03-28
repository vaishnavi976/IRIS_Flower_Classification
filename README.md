# IRIS Flower Classification 
*A machine learning model to classify Iris flowers into three species using Random Forest.*  

## 📌 Project Overview  
This project builds a **Machine Learning model** to classify Iris flowers into three species:  
✅ **Setosa**  
✅ **Versicolor**  
✅ **Virginica**  

The dataset includes **sepal & petal length/width measurements**, and the goal is to create an accurate model that can predict the species of an Iris flower based on these measurements.  

---

## 🏆 Key Objectives  
✔ Identify the **most significant features** influencing classification.  
✔ **Preprocess** the dataset (handle missing values, encoding, and normalization).  
✔ Train a **high-accuracy model** (Random Forest).  
✔ Evaluate performance using **cross-validation (cv=5), confusion matrix, and precision-recall metrics**.  

---

## 🛠️ Technologies Used  
- **Python**  
- **Pandas, NumPy** (Data Processing)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-Learn** (Machine Learning)  
- **Jupyter Notebook** (Model Development)  

---

## 📊 Why Random Forest?  
- Handles **non-linearity** better than basic models.  
- **Feature importance ranking** improves interpretability.  
- Works well with **small datasets** like Iris.  
- **Performs well even with minimal hyperparameter tuning.**  

---

## 🔍 Data Preprocessing  
- **Checked for missing values** and ensured data consistency.  
- **Categorical encoding**: Converted species names into numerical labels.  
- **Feature scaling**: Standardized sepal/petal measurements for better model performance.  

---

## 🚀 Model Implementation  
1. **Splitting Data** → Train-test split (80-20 ratio).  
2. **Feature Scaling** → Applied `StandardScaler` for normalization.  
3. **Training** → Used `RandomForestClassifier` with `cv=5` cross-validation.  
4. **Evaluation** → Calculated accuracy, confusion matrix, precision-recall.  
5. **Model Saving** → Exported as `iris_classifier.pkl` for future use.  

---

## 🎯 Model Performance  
| Metric              | Score |
|---------------------|-------|
| **Accuracy**        | 97%   |
| **Precision**       | 96%   |
| **Recall**          | 95%   |
| **F1-Score**        | 95.5% |
| **Cross-validation**| 96%   |

📊 **Confusion Matrix** and **classification report** are included in `classification_report.txt`.  

---

## 📂 Dataset  
- The dataset used in this project is from **Kaggle**:  
  **[Iris Flower Dataset – Kaggle](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)**  

---

## 🚀 How to Run the Project  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/IRIS_Flower_Classification.git


