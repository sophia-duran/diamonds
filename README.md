# 💎 Diamonds Dataset Analysis in R

This project explores the popular `diamonds` dataset using `dplyr` and `ggplot2` in R to analyze pricing trends based on carat, cut, clarity, and color. The goal was to uncover insights into what features influence diamond prices and to present those findings using clear data visualizations.

---

## 📌 Overview

- **Dataset Used:** Built-in `diamonds` dataset from the `ggplot2` package
- **Language:** R
- **Tools & Libraries:** `dplyr`, `ggplot2`

---

## 🧪 Process

### 1. **Setup and Data Exploration**
- Installed and loaded `dplyr` and `ggplot2`
- Loaded the `diamonds` dataset and reviewed structure with `str()` and `summary()`
- Checked for missing values and identified data types

### 2. **Data Cleaning**
- Removed diamonds with prices > $15,000 or carats > 3.5 to eliminate extreme outliers
- Dropped duplicate rows to ensure clean analysis

### 3. **Analysis**
- **Average Price by Cut**  
  Calculated and sorted the average price for each cut; found **Premium** diamonds to have the highest average price (~$4,042)

- **Average Price by Carat**  
  Created a summary of average diamond prices at each carat level

- **Average Price by Color and Clarity**  
  Grouped by both `color` and `clarity` to find combinations with the highest average pricing.  
  Result: Diamonds with color **I** and clarity **SI2** had the highest average price (~$6,031)

---

## 📊 Visualizations

- **Bar Plot – Average Price by Cut**

  ![Average Price by Cut](![Screenshot 2025-05-27 170931](https://github.com/user-attachments/assets/f7aeed83-d4ae-4093-9747-4615b79a6090)
)

- **Scatter Plot – Carat vs. Price**

  ![Carat vs Price](![Screenshot 2025-05-27 170940](https://github.com/user-attachments/assets/ffcf0847-b8b6-47d6-a989-9be638850049)
)

- **Boxplot – Price Distribution by Color**

  ![Price by Color](![Screenshot 2025-05-27 170947](https://github.com/user-attachments/assets/c75f6de3-b971-4f1b-b89f-e2e804360523)
)

---

## 🔍 Insights

- Carat has a strong positive correlation with price.
- Premium cuts are priced highest on average, followed by Fair and Very Good.
- Color and clarity combinations impact pricing, with certain lower-clarity, lower-color diamonds priced higher due to carat size.

---

## 🧠 Skills Demonstrated

- Data cleaning with `dplyr`
- Grouped summarization and feature-based pricing analysis
- Data visualization using `ggplot2`
- Analytical storytelling and trend identification

---

## 📁 File Structure

diamonds-data-analysis/
├── Diamonds.ipynb (or diamonds_eda.R)
├── images/
│ ├── avg_price_by_cut.png
│ ├── carat_vs_price.png
│ └── price_by_color.png
├── README.md


---

## 🚀 Next Steps

- Build a regression model to predict diamond prices
- Apply similar workflows to other retail pricing datasets

---

*Completed as part of Advanced Business Analytics coursework at Syracuse University.*

