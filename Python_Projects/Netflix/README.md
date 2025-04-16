
# 📊 Netflix Data Analytics with Python

## 📁 Dataset Overview

This project uses a dataset containing detailed information about Netflix’s catalog of movies and TV shows. The dataset includes:

| Column       | Description                          |
|:-------------|:-------------------------------------|
| `show_id`     | Unique identifier for each title      |
| `type`         | Movie or TV Show                     |
| `title`        | Title of the content                  |
| `director`     | Name(s) of the director(s)            |
| `cast`         | Main actors/actresses                 |
| `country`      | Production country                    |
| `date_added`   | Date content was added to Netflix      |
| `release_year` | Year the content was originally released |
| `rating`       | Content maturity rating               |
| `duration`     | Duration (minutes or seasons)         |
| `listed_in`    | Categories/Genres                     |
| `description`  | Brief summary                         |

---

## 🎯 Project Objectives

- Perform exploratory data analysis (EDA) on Netflix content  
- Identify key patterns and trends within the Netflix catalog  
- Visualize findings with clear and informative graphs  
- Provide actionable insights on content types, ratings, countries, and more  

---

## 📈 Exploratory Data Analysis (EDA)

### ✅ Data Cleaning
- Handled missing values and verified data types  
- Converted `date_added` to a proper datetime format  

### ✅ Key Questions Answered:
- How is the content split between Movies and TV Shows?
- What are the most frequent content ratings?
- Which countries produce the most Netflix content?
- How has Netflix’s content library grown over time?
- Who are the most featured directors?
- What genres are the most common?

### ✅ Visualizations:
- Pie chart: Content Type Distribution  
- Bar plots: Content Ratings, Top Countries, Top Directors, Top Genres  
- Line chart: Year-wise Content Additions  
- Heatmap: Data correlations (if applicable)  

---

## 📊 Key Insights

- **Movies make up the majority** of Netflix’s library.
- The **most common content ratings** are `TV-MA`, `TV-14`, and `TV-PG`.
- **United States, India, and the United Kingdom** lead in content production.
- The number of titles **added to Netflix has increased significantly** in recent years.
- **Documentaries, International TV Shows, and Dramas** are among the most listed genres.

---

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas** — data manipulation  
- **NumPy** — numerical analysis  
- **Matplotlib** — data visualization  
- **Seaborn** — advanced visualization  

---

## 📌 Conclusion

This project successfully explored and visualized Netflix's collection of movies and TV shows, uncovering meaningful trends and providing insights about content distribution, genres, production origins, and more.

---

## 📎 Future Improvements

- Sentiment analysis on show descriptions  
- Time-series forecasting for content growth  
- Cross-platform analysis (Netflix vs competitors)
- Integrating user ratings and reviews (if available)

---

## 📚 Project Structure

```
Netflix-Data-Analytics/
│
├── netflix.csv                # Netflix dataset
├── Netflix.ipynb              # Jupyter notebook with analysis
├── README.md                  # Project documentation (this file)
│
└── /images                    # Optional folder for visualization images
```

---

## 👨‍💻 Author

**Your Name Here**  
[Your LinkedIn](#) | [Your GitHub](#)
