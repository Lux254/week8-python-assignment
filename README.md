# COVID-19 Research Papers Analysis

This project explores a dataset of COVID-19 research papers, cleans the data, performs analysis, and visualizes key insights. Finally, a simple Streamlit application is built to make the results interactive.

---

## 🛠️ Steps Completed

### Part 1: Load and Explore the Dataset
- Loaded dataset (`.csv`) using pandas.  
- Explored dataset using `.head()`, `.info()`, and `.describe()`.

📸 **Screenshots**  
- Dataset head: *[/screenshots/head.png]*  
- Dataset info: *[screenshots/info.png]*  
- Dataset describe: *[screenshots/describe.png]*  

---

### Part 2: Data Cleaning and Preparation
- Handled missing values.  
- Removed irrelevant columns (e.g., `mag_id`).  
- Converted `publish_time` to datetime.  
- Extracted publication year.  
- Created new feature: abstract word count.  

📂 Cleaned dataset saved as: `data/cleaned/covid19_cleaned.csv`

---

### Part 3: Data Analysis and Visualization

#### 1. Publications over Time  
Counts of COVID-19 research papers published each year.  

📊 *[plots/publications.png]*  

---

#### 2. Top Publishing Journals  
Identifying the top journals contributing to COVID-19 research.  

📊 *[plots/journals.png]*  

---

#### 3. Word Cloud of Paper Titles  
Most common words appearing in research paper titles.  

☁️ *[plots/word_cloud.png]*  

---

#### 4. Distribution of Paper Counts by Source  
How research papers are distributed across sources.  

📊 *[plots\sources.png]*  

---

### Part 4: Streamlit Application
A simple Streamlit app was built to:  
- Display a sample of the dataset.  
- Allow interactive filtering.  
- Show visualizations in an interactive way.  
