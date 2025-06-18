# 📊 Amazon Kindle Reviews Analysis

This project explores and visualizes customer reviews from the Amazon Kindle Store. The aim was to apply data cleaning, exploratory data analysis (EDA), and basic visualisation techniques to uncover trends and insights in user ratings and review behavior.

## 🧰 Tools & Technologies
- **Language:** Python
- **Libraries:** pandas, matplotlib, seaborn
- **IDE:** Jupyter Notebook (Google Colab)
- **Dataset:** Amazon Kindle Store Reviews (CSV format, cleaned version)

---

## 📈 Project Goals
- Clean and prepare review data for analysis
- Explore rating distributions and review volume
- Visualize patterns such as rating trends over time
- Draw initial insights from visual representations

---

## 🔍 Key Steps

### 1. Data Cleaning
- Checked for and removed missing/null values
- Renamed columns for clarity
- Verified data types and converted where needed

### 2. Exploratory Data Analysis (EDA)
- Examined distribution of ratings
- Explored average ratings across top reviewers
- Visualised number of reviews per rating
- Identified frequency of reviews over time

### 3. Visualisation
- Created bar plots, histograms, and scatterplots using `matplotlib` and `seaborn`
- Color-coded visualisations for improved readability
- Used figure styling to enhance chart quality

---

## 📊 Sample Insights
- Most reviews tend to be 4 or 5 stars, suggesting generally positive sentiment.
- A small number of users contribute a large volume of reviews.
- The distribution of ratings is skewed positively.

---

## 📁 File Structure
```ca1_DATA_VISUALISATION/
│
├── DataVisualisationCA.ipynb       # Main Jupyter Notebook
├── .gitattributes                  # Git configuration
├── .gitignore                      # Files excluded from Git tracking
└── data/
    └── cleaned_reviews.csv         # Cleaned dataset (not included due to file size)
```

---

## 🚀 How to Run
1. Open the notebook in Jupyter or Google Colab
2. Ensure the dataset (CSV) is loaded into a `data/` folder or modify the path accordingly
3. Run cells sequentially to replicate the analysis

---

## ✅ Status
✔️ Project Completed  
🔜 Possible future updates: Add sentiment analysis or NLP-based keyword extraction



