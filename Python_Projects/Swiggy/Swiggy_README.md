
# 📊 Swiggy Bangalore Outlet Analytics with Python

## 📁 Dataset Overview

This project uses a dataset containing information about various Swiggy restaurant outlets in Bangalore. Each record represents an outlet, capturing details about its cuisine, location, rating, and cost.

**Key Dataset Columns:**

| Column          | Description                                   |
|:----------------|:-----------------------------------------------|
| `Shop_Name`       | Name of the restaurant/outlet                  |
| `Cuisine`         | Types of cuisine served                        |
| `Location`        | Outlet’s location within Bangalore             |
| `Rating`          | Average customer rating (out of 5)             |
| `Cost_for_Two`    | Approximate cost for two people (in INR)        |

---

## 🎯 Project Objectives

- Analyze Swiggy restaurant outlet details in Bangalore  
- Explore outlet ratings, cuisines, and cost trends  
- Identify popular areas, high-rated cuisines, and cost ranges  
- Visualize insights through intuitive charts  

---

## 📈 Exploratory Data Analysis (EDA)

### ✅ Data Cleaning
- Handled any missing or inconsistent data  
- Cleaned and standardized the `Cost_for_Two` column to numerical format  
- Split and analyzed multi-cuisine entries  

### ✅ Key Questions Answered:
- What are the most popular cuisines in Bangalore?
- Which areas have the highest number of outlets?
- What is the distribution of restaurant ratings?
- What’s the average cost for two people across different locations?
- Which outlets are highly rated and budget-friendly?

### ✅ Visualizations:
- Bar plots: Popular cuisines and outlet counts by location  
- Pie charts: Rating distributions  
- Boxplots: Cost for Two variations by location  
- Scatterplots: Rating vs. Cost for Two  
- Heatmaps: Cuisine vs. Location frequency (if applicable)  

---

## 📊 Key Insights

- **South Indian and North Indian cuisines are the most popular** in Bangalore outlets.
- **Koramangala and HSR Layout** are major food hubs with the highest number of outlets.
- Most restaurants have ratings in the **4.0 to 4.5 range**, indicating good customer satisfaction.
- There’s a **diverse cost range**, but a significant number of outlets fall in the **₹150–₹400** range.
- Several outlets combine **high ratings with budget-friendly pricing**, making them popular choices.

---

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas** — data manipulation  
- **NumPy** — numerical analysis  
- **Matplotlib & Seaborn** — data visualization  

---

## 📌 Conclusion

This project explored Swiggy’s restaurant outlet data in Bangalore, providing valuable insights into popular cuisines, affordable areas, customer satisfaction trends, and restaurant hotspots in the city.

---

## 📎 Future Improvements

- Analyze Swiggy delivery times or order volumes (if available)  
- Include user reviews and sentiment analysis  
- Compare Swiggy data with other platforms like Zomato  
- Map visualizations of outlet locations using `folium`  

---

## 📚 Project Structure

```
Swiggy-Bangalore-Analytics/
│
├── Swiggy Bangalore Outlet Details.csv   # Swiggy outlet dataset
├── Swiggy.ipynb                          # Jupyter notebook with analysis
├── README.md                             # Project documentation (this file)
│
└── /images                               # Optional folder for visualization images
```

---

## 👨‍💻 Author

**Your Name Here**  
[Your LinkedIn](#) | [Your GitHub](#)
