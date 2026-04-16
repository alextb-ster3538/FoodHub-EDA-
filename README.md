# FoodHub-EDA

<img width="1760" height="500" alt="foodhub_banner" src="https://github.com/user-attachments/assets/8429c4bc-d341-4b8f-9af8-068a8df398e8" />

---

# **FoodHub Customer Behavior — Exploratory Data Analysis (Python)**  

## **📌 Project Overview**  
This project analyzes **1,898 food delivery orders** from FoodHub to understand customer behavior, restaurant performance, delivery efficiency, and cuisine trends. Using Python, I performed a full EDA covering data quality checks, univariate and multivariate analysis, and business‑focused insights.

## **🧰 Tools & Skills Used**  
- **Python:** pandas, numpy  
- **Visualization:** seaborn, matplotlib  
- **EDA:** descriptive statistics, distribution analysis, correlation analysis, categorical comparisons  
- **Business Analysis:** customer demand patterns, cuisine performance, delivery efficiency  

## **📂 Project Structure**  
```
/data
    foodhub_order.csv
/notebooks
    foodhub_eda.ipynb
/images
    exported charts
README.md
```

## **🔍 Key Questions Explored**  
- What does the dataset look like (shape, types, quality)?  
- How are cost, delivery time, and preparation time distributed?  
- Which restaurants and cuisines receive the most orders?  
- How do weekend vs weekday patterns differ?  
- What percentage of orders exceed $20?  
- How do ratings vary by cuisine?  
- What relationships exist between cost, prep time, delivery time, and total time?

## **📊 Key Insights**  
- Dataset contains **1,898 rows and 9 columns** with **no missing values**.  
- **39%** of orders have no rating (“Not given”).  
- **29.24%** of orders cost more than **$20**.  
- Median times: **27 min** food prep, **25 min** delivery.  
- **American, Japanese, and Italian** are the most frequently ordered cuisines.  
- Weekend demand is more than **double** weekday demand.  
- **Shake Shack** is the top restaurant with **219 orders**.  
- Ratings are consistently high across cuisines; Spanish and Thai show the highest averages but with low sample sizes.  
- Higher‑priced orders tend to have **slightly faster delivery times**, while preparation time remains consistent across price bins.  
- Correlation heatmap shows strong relationships between **prep time**, **delivery time**, and **total time**, but **no correlation** between cost and time.

## **📈 Visuals Included**  
- Histograms & boxplots for cost, delivery time, prep time  
- Countplots for cuisine and day of week  
- Barplots for ratings by cuisine  
- Correlation heatmap  
- Cost‑bin comparisons for delivery & prep time  

## **💡 Business Impact**  
This analysis helps FoodHub:  
- Identify high‑demand restaurants and cuisines  
- Optimize weekend staffing and delivery capacity  
- Understand delivery performance and timing patterns  
- Prioritize cuisines/restaurants with strong customer satisfaction  
- Explore pricing vs delivery efficiency dynamics  

---

## **▶ How to Reproduce**  
1. Clone or download this repository.  
2. Open the notebook in `/notebooks/foodhub_eda.ipynb`.  
3. Place `foodhub_order.csv` inside the `/data` folder.  
4. Run the notebook in Jupyter or VS Code (Python 3.9+ recommended).  
5. Exported charts will appear in the `/images` folder.

---

## **📘 Project Context **  
This project was completed as part of my Python Foundations coursework, where I performed the full exploratory data analysis, visualizations, and interpretations as required. I earned a 60/60 score on the assignment. I am including it in my portfolio because it demonstrates my ability to work through a complete Python‑based EDA workflow using pandas, seaborn, and matplotlib.

---

