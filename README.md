# 🎵 Amazon Music Clustering

## 📖 Project Overview
With millions of tracks available online, manually categorizing songs into genres is nearly impossible.  
This project uses **unsupervised machine learning** (clustering) to automatically group similar songs based on their **audio features** such as tempo, energy, and danceability.

By the end of the project, we can identify musical clusters that represent genres or moods — helping improve **playlist recommendations**, **artist analysis**, and **user discovery**.

---

## 🎯 Objectives
- Perform **data exploration and preprocessing**
- Select key **audio features**
- Normalize data for clustering
- Use **K-Means** and **PCA** for grouping and visualization
- Evaluate clusters using **Elbow Method** and **Silhouette Score**
- Export results and interpret cluster meaning

---

## 📊 Dataset
**File:** `single_genre_artists.csv`  
**Features:**
- `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`,  
  `instrumentalness`, `liveness`, `valence`, `tempo`, `duration_ms`
- Text columns: `track_id`, `track_name`, `artist_name`

---

## 🧠 Approach
1. **Data Preprocessing:** Remove unnecessary columns, handle missing values  
2. **Feature Scaling:** Use `StandardScaler`  
3. **K-Means Clustering:** Find best number of clusters using Elbow Method  
4. **Cluster Evaluation:** Silhouette Score and Inertia  
5. **PCA Visualization:** 2D visualization of clusters  
6. **Interpretation:** Analyze mean feature values per cluster

---

## 🧩 Key Libraries
- Python (3.8+)
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

---

## Author
Name : <Aswathy B>
