```markdown
# MoMA Artists Dataset Analysis 🖌️📊

## Overview  
This project focuses on analyzing and cleaning data from the **Museum of Modern Art (MoMA) Artists Collection**. The goal was to prepare the dataset for advanced analysis, uncover insights, and create an interactive dashboard for better visualization of artist distributions across countries.

---

## Features  
- **Data Cleaning:**  
  - Removed null values and inconsistencies.  
  - Filled missing values where possible using logical imputation.  
  - Exported a clean and structured dataset in CSV and Excel formats.  

- **Data Analysis:**  
  - Explored artist distributions across different countries.  
  - Identified trends and insights through detailed exploratory data analysis (EDA).  

- **Data Visualization:**  
  - Developed an interactive dashboard using **Power BI**, showcasing key insights:  
    - Distribution of artists by country.  
    - Highlights of global art patterns.  

---

## Project Structure  

```plaintext
📁 MoMA_Artists_Analysis/
├── Artists.csv                      # Original dataset
├── Artists Cleaned Data.xlsx        # Cleaned dataset
├── Distribution of artists in different countries chart.pbix # Power BI dashboard
├── data_cleaning_script.py          # Python script for data cleaning
├── README.md                        # Project documentation
```

---

## How to Run the Project  

### Step 1: Clone the Repository  
```bash
git clone https://github.com/asomaarooufiniyaa/MoMA-Artists-Analysis.git
```

### Step 2: Install Dependencies  
Make sure you have Python and necessary libraries installed:  
```bash
pip install pandas numpy
```

### Step 3: Run the Data Cleaning Script  
Execute the `data_cleaning_script.py` to generate the cleaned dataset:  
```bash
python data_cleaning_script.py
```

### Step 4: Explore the Dashboard  
Open the Power BI file (`Distribution of artists in different countries chart.pbix`) to interact with the visualized data insights.

---

## Preview  

### Cleaned Dataset (Snapshot)  
| Artist Name      | Nationality | Birth Year | Death Year | Artworks |  
|-------------------|-------------|------------|------------|----------|  
| Pablo Picasso    | Spanish     | 1881       | 1973       | 2,000+   |  
| Vincent van Gogh | Dutch       | 1853       | 1890       | 800+     |  


---

## Technologies Used  
- **Python:** Pandas, NumPy  
- **Power BI:** Interactive data visualization  
- **Excel:** Manual adjustments during data cleaning  

---

## About Me  
I am a data enthusiast passionate about transforming raw datasets into actionable insights. My focus lies in combining data analysis and visualization to tell impactful stories.  

Let’s connect and discuss how data can drive innovative solutions!  

---
--- 

اگر مشکلی یا سوالی در مورد نحوه استفاده از این فایل دارید، من اینجا هستم! 😊
