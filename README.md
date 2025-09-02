# Country Clustering for Humanitarian Aid

This project uses unsupervised machine learning to **cluster countries** based on socio-economic and health indicators to identify regions most in need of **humanitarian aid**. It applies clustering techniques such as **K-Means** and **Hierarchical Clustering** to group countries with similar development and humanitarian profiles, allowing aid organizations to **prioritize and allocate resources more effectively**.

---

## 📊 Dataset

The dataset includes indicators for 167 countries, with features such as:

- `child_mort`: Child mortality
- `total_fer`: Total fertility
- `income`: Per capita income
- `gdpp`: GDP per capita
- `life_expec`: Life expectancy
- `exports`, `imports`, `health`, `inflation`

> Source: [Country-data.csv](./Country-data.csv)

---

## 🔍 Project Objectives

- Explore and clean the data
- Visualize socio-economic indicators
- Identify countries most in need based on a composite need score
- Cluster countries using:
  - K-Means Clustering
  - Hierarchical Clustering
- Analyze and compare cluster results
- Label clusters as "In Need", "Emerging", or "Developed"
- Export results for humanitarian planning

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (KMeans, PCA, StandardScaler)
- Scipy (Hierarchical Clustering)
- Jupyter Notebook

---

## 📈 Visualizations

- Histograms, Boxplots, Heatmaps
- Top 10 countries by key metrics
- PCA-based cluster visualizations
- Dendrogram for hierarchical clustering

---

## 💡 Key Results

- Countries were successfully clustered into **2 (K-Means)** and **3 (Hierarchical)** meaningful groups.
- A "Need Score" was created using standardized indicators.
- **57 countries** were found in common between both clustering methods as being **most in need**.
- Final results were saved to:
  - `country_level_need_ranking.csv`
  - `countries_with_clusters_combined.csv`

---

## 📁 Output Files

- `country_level_need_ranking.csv` – Ranked list of countries by individual need score
- `countries_with_clusters_combined.csv` – Final labeled dataset with clustering labels and priorities

---
