# 🧩 Personality Analysis — Introvert vs Extrovert

<p align="center">
  <em>Understanding personality traits and predicting whether someone is an <b>introvert</b> or an <b>extrovert</b> using data analysis and machine learning.</em>
</p>

---

## ✨ Project Overview
This project explores how **personality traits, behaviours, and lifestyle choices** can be analyzed to classify people as **introverts** or **extroverts**.  

The main objectives were:
- To **analyze behavioural patterns** (e.g., social interactions, music preference, activity levels).  
- To **visualize personality traits** using various data visualization techniques.  
- To **build predictive models** using `scikit-learn` for personality classification.  

---

## 📖 Problem Statement
Personality is an important factor in areas like education, career, and relationships. Introverts and extroverts often exhibit distinct behavioural patterns. By analyzing personality-related data, we can:
- Identify **factors influencing personality type**.  
- Build a simple **classification model** that predicts whether someone is introverted or extroverted based on their traits.  

---

## 🛠 Tech Stack
- **Programming Language:** Python 🐍  
- **Libraries & Tools:**  
  - `pandas`, `numpy` → Data handling and preprocessing  
  - `matplotlib`, `seaborn` → Data visualization  
  - `scikit-learn` → Machine learning models & evaluation  
  - `jupyter` → Interactive development & documentation  

---

## 📂 Repository Structure

---

## 🔬 Methodology
1. **Data Collection**  
   - Dataset contains behavioural and personality-related features.  
   - Each entry is labelled as either `Introvert` or `Extrovert`.  

2. **Data Preprocessing**  
   - Handled missing values  
   - Encoded categorical features  
   - Normalized numerical features for ML models  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of introverts vs extroverts  
   - Correlation between features  
   - Visualizations (boxplots, violin plots, heatmaps)  

4. **Model Building**  
   - Tried different ML algorithms: Logistic Regression, KNN, Decision Trees  
   - Evaluated models using accuracy, precision, recall, F1-score  
   - Tuned hyperparameters for best performance  

5. **Results & Insights**  
   - Identified **key traits** influencing personality type  
   - Visualized model decision boundaries  

---

## 📊 Visualizations
Examples of plots used in analysis (to be added in `assets/` folder):
- Distribution of introverts vs extroverts  
- Heatmap of correlations  
- Boxplot of social hours per week vs personality  
- Feature importance chart from ML model  

---

## 📘 Learning Outcomes
- How to preprocess and clean real-world personality-related datasets  
- Extracting meaningful insights from survey/behavioural data  
- Building and evaluating ML models using `scikit-learn`  
- Understanding **how lifestyle and habits affect personality classification**  

---

## 🚀 Future Work
- Collect larger and more diverse datasets for improved accuracy  
- Deploy a **Streamlit web app** where users can take a quiz and get predicted personality type  
- Use advanced ML models (Random Forest, SVM, XGBoost)  
- Experiment with NLP to analyze text responses about personality  

---

## ▶️ How to Run
1. Clone this repository:  
```bash
git clone https://github.com/yourusername/personality-analysis.git
cd personality-analysis

