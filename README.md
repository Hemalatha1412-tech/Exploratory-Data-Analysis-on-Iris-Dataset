# 🌸 Iris Dataset — Professional EDA + Machine Learning Pipeline

## 📌 Overview

This project demonstrates a **complete end-to-end data science workflow** on the Iris dataset, including:

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature scaling
* Machine Learning model building
* Cross-validation for robust evaluation
* Model comparison and selection

This project is designed to reflect **industry-level practices** and is suitable for portfolio and recruiter review.

---

## 📊 Dataset Information

The Iris dataset is a classic dataset in machine learning.

* Total Samples: **150**
* Features: **4 numerical features**

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* Target Classes:

  * Setosa
  * Versicolor
  * Virginica

📌 Dataset loaded using:

```python
sns.load_dataset('iris')
```

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Key Features of This Project

### 🔍 Exploratory Data Analysis (EDA)

* Feature distributions
* Pairplot visualization
* Correlation heatmap

### 🤖 Machine Learning Pipeline

* Data preprocessing using StandardScaler
* Pipeline-based model building
* Clean and reusable workflow

### 📊 Model Evaluation

* Cross-validation (cv = 5)
* Accuracy comparison across models
* Classification report
* Confusion matrix

### 🧠 Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree

---

## 📈 Key Insights

* Petal features are the most important for classification
* Setosa is clearly separable from other species
* Cross-validation provides more reliable performance estimates
* Pipeline approach improves code modularity and reproducibility

---
## 📸 Visualizations

![Pairplot](images/pairplot.png)
![Model Comparison](images/model.png)
## 📁 Project Structure

```
iris-eda-ml-pipeline/
│
├── Exploratory Data Analysis on Iris Dataset.ipynb   # Main notebook
├── README.md              # Documentation
├── requirements.txt       # Dependencies
```

---

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/iris-eda-ml-pipeline.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook:

* Open in Jupyter Notebook or Google Colab
* Run all cells

---

## 📌 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Add more evaluation metrics (ROC Curve, Precision-Recall)
* Deploy as a Streamlit web app
* Build an interactive dashboard

---

## 👩‍💻 Author

**Hemalatha S**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
