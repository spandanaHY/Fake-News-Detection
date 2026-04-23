# Fake News Detection System

##  Project Description
This project detects whether a news article is **Fake or Real** using machine learning techniques.  
It combines datasets, performs text preprocessing, applies feature extraction using TF-IDF, and compares multiple models to select the best one.

---

##  Features
- Dataset merging (Fake + Real news)
- Text preprocessing (cleaning, stopword removal, lemmatization)
- Exploratory Data Analysis (EDA)
- TF-IDF feature extraction
- Multiple model training:
  - Naive Bayes
  - Logistic Regression
  - SVM
  - Random Forest
- Model comparison and best model selection
- News prediction system

---

##  Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Dataset
This project uses two datasets:
- Fake.csv → Fake news articles
- True.csv → Real news articles  

Both datasets are merged and labeled:
- Fake → 0  
- Real → 1  

---

##  How to Run

### Option 1: Run in Google Colab (Recommended)
1. Open the `.ipynb` file in Google Colab  
2. Upload `Fake.csv` and `True.csv` when prompted  
3. Click **Runtime → Run all**  
4. The model will train and display outputs (graphs + accuracy + predictions)

---

### Option 2: Run on Local Machine
1. Install required libraries:
   pip install pandas numpy nltk scikit-learn matplotlib seaborn

2. Download NLTK resources (first time only)

3. Run the notebook using Jupyter Notebook:
   jupyter notebook

4. Open the `.ipynb` file and run all cells

---

##  Output
- Graphs showing Fake vs Real distribution
- Text length analysis
- Model accuracy comparison
- Best model selection
- Confusion matrix and classification report
- Final prediction results (Fake / Real)

---

## 🔗 GitHub Repository
https://github.com/spandanaHY/Fake-News-Detection
---

## 👩‍💻 Author
Spandana H Y
