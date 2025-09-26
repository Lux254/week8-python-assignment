# 📘 CORD-19 Data Exploration

## 📌 Overview  
This project explores the **CORD-19 dataset (metadata.csv)** using **Python, Pandas, Matplotlib, Seaborn, and Streamlit**.  
It demonstrates the full **data science workflow**:  
1. Data loading & exploration  
2. Data cleaning & preparation  
3. Data analysis & visualization  
4. Interactive Streamlit application  

---

## 📊 Steps Completed  

### Part 1: Data Loading & Exploration  
- Loaded `metadata.csv` into a Pandas DataFrame  
- Checked shape, data types, and missing values  
- Generated summary statistics  

### Part 2: Data Cleaning & Preparation  
- Dropped useless columns (`mag_id`)  
- Handled missing values (`title`, `abstract`, `journal`, `publish_time`)  
- Converted `publish_time` to datetime  
- Extracted publication year (`year`)  
- Added `abstract_word_count` column  

### Part 3: Data Analysis & Visualization  
- Counted papers per year  
- Identified top journals publishing COVID-19 research  
- Found most frequent words in titles  
- Created visualizations:  
  - Publications by year  
  - Top journals bar chart  
  - Word cloud of titles  
  - Distribution of papers by source  

### Part 4: Streamlit Application  
- Built an interactive app with:  
  - Year range slider  
  - Journal filter dropdown  
  - Visualizations (bar charts, word cloud)  
  - Data sample display  

---

## ▶️ How to Run the Streamlit App  

1. Install required libraries:  
   ```bash
   pip install pandas matplotlib seaborn streamlit wordcloud

2. Run the app:
   streamlit run app.py

3. Open the link shown in the terminal



