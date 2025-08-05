# Smart-Text-Classifier

## 🧭 Introduction
**Smart Text Classifier** is a machine learning project focused on classifying SMS text messages as **spam** or **ham** (not spam). It leverages classical ML algorithms—**Logistic Regression**, **Random Forest**, and **Multinomial Naive Bayes**—to compare performance and identify the most effective method for spam detection. The project addresses challenges in automated text classification and showcases clear evaluation metrics for each model.

## 🛠️ Project Type
Backend

## 🚀 Deployed App
- Frontend: *Not applicable*  
- Backend: Jupyter Notebook / Python Script
- Database: Static CSV

## 📁 Directory Structure
smart-text-classifier/                                                                                  
├── data/                  
│   ├── spam.csv  
├── notebooks/             
│   ├── Smart Text Classifier.ipynb                
├── Visuals/                                  
├── README.md                               
  

## 🎥 Video Walkthrough of the project


## 🎥 Video Walkthrough of the codebase


## ✨ Features
- Spam vs. ham classification using multiple ML models
- Data preprocessing, label encoding, and train-test splitting
- Performance visualization (precision, recall, F1-score, confusion matrix)
- Results comparison across algorithms

## 🎯 Design Decisions or Assumptions
- Selected classical ML algorithms for interpretability and simplicity
- Used default hyperparameters for baseline model performance
- Applied standard text preprocessing (lowercasing, punctuation removal)
- Focused on model evaluation instead of app deployment
- Assumed labeled dataset with "spam" and "ham" categories

## 🧪 Installation & Getting Started
Install dependencies and launch the notebook:

```bash
git clone https://github.com/Shaileshahire06/Smart-Text-Classifier.git
cd smart-text-classifier
pip install -r requirements.txt
jupyter notebook
```
## Usage
Step-by-step:
1. Load and preprocess the data
2. Train models using provided notebook
3. Evaluate and visualize model performance

## 🔐 Credentials
*No login or credentials

## 🌐 APIs Used 
None – analysis is entirely local using SQL + Pandas

## 🛰️ API Endpoints 
Not applicable – this is a non-service-based analytical project


## 🛠 Technology Stack

- Python: Data analysis with Pandas
- NumPy / Pandas — Data manipulation and preprocessing
- Scikit-learn — Machine learning algorithms and model evaluation
- Matplotlib / Seaborn — Data visualization and analysis
- Jupyter Notebook: Code, commentary, and charts
