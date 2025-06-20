<p align="center">
  <img src="MovieGenre.jpg" alt="Sentiment Analysis Output" width="600"/>
</p>

# 🎬 **MOVIE GENRE PREDICTION**


## 🧾 **PROJECT DESCRIPTION**
*Predict the genre of a movie based on its plot summary using Natural Language Processing (NLP) and machine learning.*

This project uses **NLP techniques** to preprocess the plot text, convert it into vectorized form, and apply a **Linear Support Vector Classifier (LinearSVC)** model to predict the movie's genre.

---

## 📚 **TABLE OF CONTENTS**
- 📌 **Project Title**
- 🧾 **Project Description**
- 📚 **Table of Contents**
- 📊 **Dataset Information**
- 🛠️ **Tech Stack Used**
- 🧠 **Workflow & Methodology**
- 📈 **Model Performance**
- 🧪 **How to Use**
- 🏁 **Results**
- 👥 **Author**
---

## 📊 **DATASET INFORMATION**
- **Name**: *Movie Plots Dataset*
- **Format**: CSV  
- **Total Entries**: 9,466 movie records  
- **Columns**:
  - `Title`: Name of the movie  
  - `Plot`: Description/summary of the movie  
  - `Genre`: Genre label (target variable)

---

## 🛠️ **TECH STACK USED**
- **Programming Language**: 🐍 *Python 3*
- **Libraries & Tools**:
  - `pandas`, `numpy`
  - `nltk`, `re`
  - `scikit-learn`
  - `CountVectorizer`, `LabelEncoder`
  - `LinearSVC`

---

## 🧠 **WORKFLOW & METHODOLOGY**
1. **Load and Inspect Data**
2. **Text Preprocessing**:
   - Lowercasing  
   - Removing punctuation and special characters  
   - Stopword removal  
   - Tokenization  
   - Lemmatization  
3. **Label Encoding**: Convert genre labels to numeric form  
4. **Feature Extraction**: *CountVectorizer*  
5. **Model Training**:
   - Linear Support Vector Classifier (*LinearSVC*)  
6. **Model Evaluation**:
   - Accuracy Score  

---

## 📈 **MODEL PERFORMANCE**
| Model      | Accuracy |
|------------|----------|
| LinearSVC  | ~92%     |

---

## 🧪 **HOW TO USE**
- Open the notebook: `Movie_Genre_Prediction.ipynb`  
- Run the cells in order  
- Observe the preprocessing, training, and prediction steps  
- Try predicting genres by changing the input plot manually


## 🏁 **RESULTS**
- ✔️ Successfully built a genre prediction model based on plot summaries  
- ✔️ Achieved around **92% accuracy** with LinearSVC  
- ✔️ Utilized basic NLP + CountVectorizer effectively  
- ✔️ Model generalizes well on unseen plots

## 👥 **AUTHOR**
- **Arghya Chakraborty** 

---
