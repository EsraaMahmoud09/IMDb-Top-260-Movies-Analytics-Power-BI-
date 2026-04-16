# IMDb-Top-260-Movies-Analytics-Power-BI
# 🎬 IMDb Top 260 Movies Analysis Dashboard

## 📌 Project Overview
This project features an interactive **Power BI Dashboard** designed to analyze a dataset of the top 260 movies according to IMDb ratings. The analysis explores historical trends in movie quality, director performance, and genre dominance from 1921 to 2025.

---

## 🚀 Key Visualizations & Insights

### 1️⃣ KPI Cards (Key Performance Indicators)
These cards provide an instantaneous summary of the dataset's high-level metrics:
* **Average IMDb Rating (8.10)**: Represents the central tendency of movie scores in this curated list.
* **Total Movies (257)**: The final count of films analyzed after the data cleaning process.
* **Average Runtime (122.56 min)**: Indicates that the majority of top-rated movies are approximately 2 hours long.
* **Top IMDb Rating (9.30)**: Highlights the highest score achieved by a single movie in the dataset.

### 2️⃣ Scatter Plot (Rating by Movie and Year)
* **Description**: This chart maps each movie as a data point based on its release year (X-axis) and rating (Y-axis).
* **Trend Analysis**: Older classics (1920–1960) show high concentration in top ratings, while modern movies (2000–2025) are more numerous with higher variance.
* **Outlier Handling**: A critical data cleaning step involved identifying a movie with a **1.6 rating** in 2020. This extreme **Outlier** was excluded to prevent it from negatively skewing the average rating of the "Top" movie report.

### 3️⃣ Area Chart (Rating Trends by Decade)
* **Description**: Visualizes the "Flow" and trends of movie quality across different decades.
* **Key Insights**:
    * **The Peaks**: Noticeable peaks in the **1930s-1940s** and the **1990s** represent the "Golden Eras" of cinema where average ratings were at their highest.
    * **The Dips**: A slight decline toward 2020 suggests that while movie volume has increased, the average rating in this specific top list is slightly lower than the highly-vetted classics of the past.

### 4️⃣ Bar Charts (Rankings)
* **Director by Rating**: Compares directors based on the quality of their work; directors like **Adam Elliot** lead due to their exceptionally high average scores.
* **Movie by Rating**: Directly compares individual titles, featuring **12 Angry Men** as one of the highest-rated films in the collection.

### 5️⃣ Dynamic Highlights (Left Sidebar)
* **Most Popular Genre**: **Action** (The most frequent and dominant category in the dataset).
* **Most Popular Actor**: **Aaron Eckhart** (The actor appearing most frequently in high-rated films within this specific data).
* **Clear All Button**: A custom-built **Bookmark Action** that allows users to reset all filters with a single click.

---

## 🛠️ Technical Skills Demonstrated
* **Data Cleaning & ETL**: Using Power Query to handle skewed data and remove statistical outliers.
* **DAX Measures**: Creating custom calculations for averages, totals, and dynamic labels.
* **UI/UX Design**: Developing a cohesive dark-themed interface with high-contrast visuals for better readability.
* **Interactivity**: Implementing Slicers and Bookmarks for an app-like user experience.

---
**Author:** Esraa Shawky  
**Focus:** Applied AI & Data Analytics

