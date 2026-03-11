# 🎬 Netflix Shows Data Analysis

📊 **Dataset:** Netflix Shows  
🔗 **Source:** https://www.kaggle.com/datasets/ahmedosman220/netflix-shows  

---

## 📌 Project Overview

This project performs **data cleaning, feature engineering, exploratory data analysis (EDA), and visualization** on the Netflix Shows dataset.

The objective is to transform raw Netflix content data into structured insights about trends, ratings, countries, directors, and actors.

---

# 🧹 Data Cleaning

- `show_id` (unique identifier).
- Handled missing values across the dataset.
- Ensured 100% accurate handling of missing values in `type`.
- Identified and treated the top 3 columns with the highest null values.
- Cleaned `date_added` and created:
  - `year_added`
  - `month_added`
- Generated `season` column from `duration` (for TV Shows only).

### 🔹 Bonus
- Created `actor1` and `actor2` from the `cast` column.

---

# 📊 Analysis

- Most common `year_added`
- Most common `rating`
- Content growth trends over time
- Rating distribution patterns

---

# 📈 Visualizations

- Movies vs TV Shows distribution (percentage)
- Top countries producing Netflix content
- Top 10 most common ratings
- Top 10 directors with most movies
- TV Show season distribution
- Bonus: Top 10 actors (based on appearances)

---

# 🛠 Tools Used

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

# 🚀 Key Insights

- Identified peak years for content additions.
- Determined dominant rating category.
- Highlighted top-producing countries.
- Identified most active directors and actors.
