# 🎬 Movie Watch Behavior Clustering

This project segments users based on their movie-watching behavior using the **K-Means clustering algorithm**. By grouping users into clusters, we can understand different viewing patterns and genre preferences to enable **personalized recommendations** and **content strategies**.

---

## 📁 Dataset

The dataset used in this project is `movie_watch.csv`, which contains:

- `watch_time_hour`: Total number of hours watched by the user
- `avg_rating_given`: Average rating the user gives to movies
- `genre_preference`: User's favorite genre (categorical)

---

## 🧠 Objective

To cluster users into distinct groups using K-Means clustering based on:
- Viewing time
- Rating behavior
- Genre preference

This will help in:
- Understanding audience segments
- Personalized movie recommendations
- Data-driven marketing strategies

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas** – for data loading and manipulation
- **NumPy** – for numerical operations
- **Matplotlib & Seaborn** – for visualization
- **Scikit-learn** – for preprocessing, clustering, and evaluation

---

## ⚙️ Methodology

1. **Load and preprocess the data**  
   - Standardize numerical features using `StandardScaler`
   - One-hot encode `genre_preference` using `OneHotEncoder`

2. **Determine the optimal number of clusters**  
   - Elbow Method (WCSS)
   - Silhouette Score

3. **Apply K-Means Clustering**  
   - Choose optimal `k` (e.g., 4)
   - Assign users to clusters

4. **Analyze Results**  
   - Visualize cluster distributions
   - Compare average watch time, rating, and genre dominance in each cluster

---

## 📊 Visualizations

- **Elbow Plot** – To find the best `k` for clustering
- **Silhouette Score Plot** – To evaluate the quality of clusters
- **Boxplots** – Watch time and ratings across clusters
- **Genre Distribution Bar Chart** – Genre breakdown by cluster

---

## 📌 Output

- A new column `cluster` added to the DataFrame to indicate user segment
- Clustered data saved as: `clustered_movie_watch.csv`

---

## 🗂 Files Included

- `movie_watch.csv` – Input dataset
- `movie_clustering.py` / `notebook.ipynb` – Source code
- `clustered_movie_watch.csv` – Final clustered output
- `README.md` – This documentation
- `Project_Report.pdf` – Formatted project report

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org)
- [Matplotlib](https://matplotlib.org)
- [Seaborn](https://seaborn.pydata.org)

---

## 📌 Author

**Nikhil**  
B.Tech – Computer Science & Engineering (AI)  
KIET Group of Institutions, Ghaziabad

---

