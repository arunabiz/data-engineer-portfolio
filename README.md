# Data Science Portfolio  

Welcome to my portfolio! This repository showcases a collection of data science and data engineering projects that demonstrate my skills in extracting insights from data, solving real-world problems, and making data-driven decisions. Below, you'll find project details and their associated files.

---

## Table of Contents  

1. [Web Scraping: Amazon PC Monitors Data](#web-scraping-amazon-pc-monitors-data)
2. [ML and AI: Credit Scoring with Machine Learning and Uncertainty Estimation](#ml-and-ai-credit-scoring-with-machine-learning-and-uncertainty-estimation)

---

## Web Scraping: Amazon PC Monitors Data  

**Public Repository**: [Amazon Monitors Web Scraping](https://github.com/arunabiz/amazon-monitors-web-scraping.git)  

### Project Overview  
This project involves scraping data about computer monitors from Amazon.com, including details such as title, price, rating, reviews, and availability.  

- The raw data was collected using web scraping techniques.
- The data was cleaned to remove sponsored products and out-of-stock items.
- The cleaned data was saved into a CSV file for further use and analysis.
- Two key notebooks are included:
  - `amazon_web_scraping.ipynb`: Initial notebook to test web scraping on a single product.  
  - `amazon_web_scraping_final.ipynb`: Finalized notebook to scrape details for all relevant products. 

**Goal**: To create a dataset of available PC monitors, focusing on key attributes such as title, price, ratings, and customer reviews.
  
### Skills Demonstrated  
- **Web Scraping**: Extracting data from dynamic web pages using automation.
- **Data Cleaning**: Removing irrelevant or incomplete entries for a more accurate dataset.
- **Data Analysis**: Interpreting trends in monitor prices, ratings, and reviews 
- **Data Visualization**: Summarizing the data using charts and graphs for better insights.

### Technologies Used  
- **Programming**: Python  
- **Libraries**:
  - Pandas: For data manipulation and analysis.
  - Beautiful Soup: For parsing and extracting HTML content.
  - Requests: For sending HTTP requests to Amazon.
- **Visualization Tools**: Matplotlib and Seaborn for creating visual insights.

### Results  
The project successfully scraped and analyzed data on PC monitors from Amazon. While machine learning was not a part of this specific project, the processed dataset is well-prepared for potential predictive modeling or deeper analysis in the future.  

---

## ML and AI: Credit Scoring with Machine Learning and Uncertainty Estimation

**Public Repository**: [Credit Scoring with Machine Learning and Uncertainty Estimation](https://github.com/arunabiz/Credit-Scoring-Using-Machine-Learning-Techniques.git)  

### Project Overview
A machine learning-based **credit scoring system** that predicts the likelihood of loan default using the **German Credit Dataset (numeric version)**. The project combines **ensemble models** with **uncertainty estimation** and a **human-in-the-loop framework** to make safer, more reliable financial decisions.

**Goal**: To develop a **highly accurate** and **risk-aware** credit scoring model that Improves predictive performance over traditional scoring methods, Quantifies model uncertainty to avoid risky automated decisions and Defers low-confidence predictions to human analysts for review.
  
### Skills Demonstrated
- **Data Preprocessing:** Feature scaling, encoding, and stratified sampling.
- **Machine Learning Modeling:** Logistic Regression, Decision Tree, Random Forest, XGBoost.
- **Hyperparameter Tuning:** GridSearchCV for optimal model parameters.
- **Uncertainty Estimation:** Deep Ensembles, Monte Carlo Dropout.
- **Model Interpretability:** SHAP values for feature importance analysis.
- **Risk Analysis:** Coverage–Risk trade-off evaluation.
- **Human-in-the-Loop Systems:** Rejection mechanism for decision safety.

### Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)
- **TensorFlow/Keras** (for Monte Carlo Dropout model)
- **Matplotlib / Seaborn** (visualizations)
- **SHAP** (model explainability)
- **Jupyter Notebook** (experimentation and documentation)

### Results
- **Best Model:** XGBoost  
- **Accuracy:** 88.4%  
- **ROC-AUC:** 0.92  
- **Top Predictors:** Repayment history, income, and age.  
- **Risk Control:** Rejection mechanism reduced risky automated decisions by deferring uncertain cases.
- **Interpretability:** SHAP analysis confirmed the model uses multiple relevant features, improving trust and transparency.

---

### Thank You for Your Attention!  
Feel free to explore the repository and reach out if you have any questions or feedback!  
