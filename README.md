#  Netflix Analytics: Exploring Content Growth and Patterns

##  Objective
This project analyzes Netflix content data to identify patterns, trends, and insights using Exploratory Data Analysis (EDA).

The goal is to understand:
- Content growth over time
- Genre and rating patterns
- Country-wise content distribution

##  Dataset Information
- Source: Kaggle  
- Data upto: 2025  
- Rows: 16000  
- Columns: 18  

### Key Columns:
- Title  
- Type (Movie / TV Show)  
- Genre  
- Release Year  
- Rating  
- Country  
- Popularity  
- Revenue  

##  Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Power BI

##  Data Cleaning & Preprocessing
- Handled missing values using:
  - "Unknown"
  - "Not Available"
- Dropped unnecessary columns
- Converted date column to datetime
- Created new column: `year_added`
- Checked duplicates (none found)
- No major outliers detected

## Exploratory Data Analysis (EDA)

### 1. Rating Distribution
- Most content ratings between 5–7  
- Very few high-rated items  

### 2. Average Rating Over Years
- Ratings are stable across years  
- Slight improvement after 2016  

### 3. Top Countries
- USA produces highest content  
- Few countries dominate  

### 4. Popularity vs Rating
- Higher rating → higher popularity  

### 5. Correlation Insights
- Budget & Revenue strongly related  
- Vote count impacts revenue  

##  Key Insights
- Most Netflix content has moderate ratings  
- Content quality is consistent over time  
- Revenue depends on budget and engagement  
- Only few titles become highly popular  

##  Project Report
[View Full Report](https://drive.google.com/file/d/1KiEn9npLeqh356Ju8LiYeLqJrv3ZcYbc/view?usp=sharing)

##  Future Improvements
- Use larger datasets  
- Add predictive models  
- Improve dashboard interactivity  

##  Conclusion
Netflix content shows consistent quality over time.  
A few countries dominate production, and only a small number of titles achieve high popularity and revenue.
