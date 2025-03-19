
---

## **Data Science Explorations and Modeling**  

### **Overview**  
This repository contains Python notebooks for **Exploratory Data Analysis (EDA)**, **Statistical Analysis**, and **Machine Learning Modeling** using datasets related to **air quality** and **lightning strikes**. The focus is on data visualization, statistical inference, and predictive modeling with `scikit-learn`.  

---

## **Notebooks and Their Contents**  

### 1. demo1_lightning_yearly_monthly_locationly.ipynb
- Conduct **Exploratory Data Analysis (EDA)** on multiple datasets.  
- Use `info()` to understand data structure and column types.  
- Convert **date columns** to `datetime` format for time-series analysis.  
- Create **new features** for better insights.  
- Visualize data using `matplotlib` and `seaborn`:  
  - **Bar plots** 📊  
  - **Box plots** 📦  

---

###  2. Demo_statistics.ipynb
- Analyze an **air quality dataset** and compute its **statistical properties**:  
  - Mean, confidence levels, z-values, and confidence intervals.  
- Perform **statistical hypothesis testing** and **A/B Testting**:  
  - "Samples with replacement" using the **Central Limit Theorem (CLT)**.  
  - Compute **p-values** to determine the validity of the null hypothesis.  
- Visualize **statistical distributions** using `matplotlib`.  

---

###  3. Naive_Bayes_binary_modelling.ipynb
- Use `scikit-learn` to build and evaluate machine learning models.  
- Train a **Gaussian Naive Bayes (GaussianNB) classifier** and analyze model scores.  
- Compute and visualize the **confusion matrix** to check false negatives.  
- Train and optimize a **Decision Tree Classifier**:  
  - Tune `max_depth` and `min_samples_leaf` hyperparameters.  
  - Visualize the decision tree.  
  - Compute the **average validation score** to find the best model.  

---

## **Requirements**  
To run these notebooks, install the following dependencies:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## **Usage**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the directory:  
   ```bash
   cd your-repo-name
   ```
3. Open Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
4. Run the notebooks to explore datasets and models.  

---

## **Contributing**  
Feel free to open issues or submit pull requests if you have improvements or additional insights to add.  

---

## **License**  
This project is open-source and available under the **MIT License**.  

---

Would you like any modifications or additional details? 
