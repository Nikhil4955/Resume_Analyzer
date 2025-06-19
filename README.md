
# 🤖 ML Resume Analyzer

The **ML Resume Analyzer** is a machine learning-based project designed to classify resumes into predefined job categories like **Data Science**, **HR**, **Web Development**, and more. It leverages **Natural Language Processing (NLP)** to extract meaningful insights from resume texts and applies ML algorithms to predict their respective domains.

---

## 📌 Features

- ✅ Clean and preprocess resume text using NLP techniques  
- ✅ Extract important **keywords** and **skills**  
- ✅ Classify resumes into **job categories**  
- ✅ Visualize **category distributions** and **skill frequencies**  
- ✅ Easy to **customize and expand** for more job domains  

---

## 🗃️ Dataset

The dataset used is contained in the file: `UpdatedResumeDataSet.csv`

| Column Name | Description                         |
|-------------|-------------------------------------|
| `Resume`    | Raw text content of the resume      |
| `Category`  | Label indicating job category (e.g., Data Science, HR) |

---

## 🧠 ML Workflow

### 1. Data Cleaning
- Remove HTML tags
- Remove stop words, punctuation, numbers
- Apply lemmatization

### 2. Text Vectorization
- Use **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical vectors

### 3. Model Training
- Train classification models such as:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest

### 4. Model Evaluation
- Evaluate models using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report**

---

## 📊 Visualizations

- 📈 Distribution of resume categories
- 🔍 Frequency of common skills and keywords

---

## 💡 How to Run

1. Clone the repository or open the notebook in Google Colab
2. Ensure `UpdatedResumeDataSet.csv` is available in the working directory
3. Run all cells in the notebook to execute data processing, model training, and evaluation

---

## 📦 Requirements

numpy
pandas
matplotlib
seaborn
scikit-learn
nltk


