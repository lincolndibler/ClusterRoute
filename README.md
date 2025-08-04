# 🏈 ClusterRoute

ClusterRoute is a data science pipeline that transforms raw, unlabeled player tracking data from an NFL game into grouped and labeled receiver routes using unsupervised learning techniques.

---

### 🧠 How It Works

It works by:
- Extracting time-series movement paths for each receiver during plays  
- Comparing route shapes using **Dynamic Time Warping (DTW)**
- Reducing complexity with **Multidimensional Scaling (MDS)**
- Grouping similar routes using **KMeans clustering**
- Assigning meaningful route labels (e.g. “Cluster 3 – Curl”, “Cluster 5 – Go”)

💡 Result: You get an **automated classification** of route types from **unlabeled tracking data**, perfect for scouting, analysis, and visualization.

---

## 📁 Project Structure

The core contents include:
- `01_Clustering.Ipnyb` — Jupyter notebooks detailing the clustering workflow
- `src/` — Utility scripts and functions

---

## 🛠️ Setup Instructions

To get started locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/lincolndibler/ClusterRoute.git
   cd ClusterRoute
