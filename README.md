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

## 📊 Exploratory Data Analysis & Visualisation

The EDA and visualisation process helped uncover key trends, clean outliers, and visually communicate insights from the dataset. Using libraries like `seaborn` and `matplotlib`, all visuals were styled for clarity, using color-coding and figure sizing.

---

### 📉 Missing Values Before and After Cleaning  
This bar chart shows missing values across columns before and after cleaning. Most problematic columns were dropped, and 'tbd' values were handled.  
<img src="https://github.com/user-attachments/assets/cff353ae-328e-4969-9b40-76a5158a4d17" alt="Missing Values Chart" width="500"/>


---

### 🧮 Dataset Shape Comparison  
The dataset had 16,719 rows before cleaning and 16,663 after. Several columns were dropped to retain only relevant and usable data.  
<img src="https://github.com/user-attachments/assets/8975ab63-f451-4d39-adf8-e4c7332aa134" alt="Shape Before and After" width="500"/>

---

### 🎯 User Score Breakdown (Before Cleaning)  
This bar chart shows how many `User_Score` entries were valid versus placeholders like 'tbd'.  
<img src="https://github.com/user-attachments/assets/aa5cb51a-3445-47b2-b19d-7b9fa374fdb1" alt="User Score Breakdown" width="500"/>

---

### 🗂️ Columns Kept vs Dropped  
Visual representation of which columns were retained (green) and which were dropped (red) after cleaning.  
<img src="https://github.com/user-attachments/assets/8a5bf895-ab62-4d64-830f-9818ef011fc7" alt="Dropped Columns" width="500"/>


---

### 🔥 Correlation Heatmap  
This visual highlights correlations between numeric features. Global Sales show strong relationships with NA Sales and EU Sales. Critic and User metrics are moderately correlated.  
<img src="https://github.com/user-attachments/assets/e8eb85b1-f37e-47f8-98db-c197a8b7af5e" alt="Correlation Heatmap" width="500"/>

---

## ❓ Project Questions & Answers

| Question | Answer | Visualisation |
|---------|--------|---------------|
| **Q1: What are the top 5 games by global sales?** | The top 5 games are:<br>1. Wii Sports<br>2. Super Mario Bros.<br>3. Mario Kart Wii<br>4. Wii Sports Resort<br>5. Pokémon Red/Pokémon Blue | <img src="https://github.com/user-attachments/assets/9d395f6c-3190-4156-b903-90442103a0ff" alt="top_5_games_by_global_sales" width="300"/> |
| **Q2: What is the distribution of the most popular 4 game genres?** | The most common genres are:<br>- Action (37.7%)<br>- Sports (26.3%)<br>- Misc (19.3%)<br>- Role-Playing (16.8%) | <img src="https://github.com/user-attachments/assets/9d9f8de3-b44e-40cd-b6b9-15abfaedf6c1" alt="distribution_top_4_game_genres" width="300"/> |
| **Q3: Do older games (2005 and earlier) have a higher mean “eu_sales” than newer games?** | Yes. Older games show slightly higher mean EU sales compared to newer titles, possibly due to market saturation or longer shelf life. | <img src="https://github.com/user-attachments/assets/ca122f04-7031-4d36-b939-8dfaf4607423" alt="mean_eu_sales_by_era" width="300"/> |
| **Q4: What are the 3 most common developer names in the dataset?** | The most frequent developers are:<br>1. Ubisoft<br>2. EA Sports<br>3. EA Canada | <img src="https://github.com/user-attachments/assets/b622d811-f795-46ec-9b50-9985ce5c56c6" alt="top_3_developers" width="300"/> |

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



