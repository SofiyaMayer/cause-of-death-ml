# cause-of-death-ml
Exploring the link between GDP, air pollution, and causes of death using ML. We applied PCA, K-Means, Random Forest, SVM, and Logistic Regression to global datasets to uncover any trends.

## 📂 Project Files

- 📄 **[Research Article (PDF)](article_ML.pdf)** – Full study with methodology and findings.
- 📊 **[Jupyter Notebook](Projekt_per_capita.ipynb)** – Code for data preprocessing and ML models.

## 🔍 Summary of Findings
- **Air pollution** was not found to be a strong predictor of causes of death.  
- **GDP per capita** showed a stronger relationship with healthcare challenges faced by different countries.  
- **Higher GDP countries** tend to experience more deaths from **aging-related and incurable diseases** (e.g., cancer, dementia).  
- **Lower GDP countries** have higher mortality from **infectious diseases** and conditions linked to poorer healthcare access (e.g., tuberculosis, malaria, neonatal disorders).  
- The study suggests that **GDP alone may not be the best predictor**, and future research should incorporate more **detailed economic and healthcare accessibility factors**.

## 🛠️ Methods Used
- **Data Processing:** Pandas, NumPy
- **Dimensionality Reduction:** PCA
- **ML Algorithms:** K-Means, Logistic Regression, SVM, Random Forest
- **Visualization:** Matplotlib, Seaborn

## 🚀 How to Use
1. **Read the article** → Check **[article_ML.pdf](article_ML.pdf)** for a full breakdown.
2. **Run the Notebook** → Open **[`Projekt_per_capita.ipynb`](Projekt_per_capita.ipynb)** in Jupyter.
3. **Install dependencies (if needed)**:
   ```bash
    pip install pandas numpy matplotlib seaborn plotly scikit-learn scipy itertools
