# Porto Seguro Safe Driver - Unsupervised Learning

This project explores the **Porto Seguro Safe Driver Prediction** dataset using **unsupervised learning techniques** to identify patterns and clusters of safe vs risky drivers.

> 🔍 Unlike the original Kaggle competition which used supervised learning, this project applies clustering and anomaly detection methods to group drivers without labeled outcomes.

---
## 🧠 Techniques Used

- **Data Preprocessing**
  - Missing value handling
  - Feature scaling
  - Dimensionality reduction (PCA)

- **Unsupervised Learning Models**
  - KMeans Clustering
  - DBSCAN
  - Isolation Forest (Anomaly Detection)
  - t-SNE for Visualization

---

## 📊 Project Structure

porto-seguro-safe-driver-unsupervised/ │ ├── data/ │ └── train.csv │ ├── notebooks/ │ └── 01_exploratory_analysis.ipynb │ └── 02_kmeans_clustering.ipynb │ └── 03_isolation_forest.ipynb │ ├── src/ │ └── preprocess.py │ └── models.py │ ├── results/ │ └── cluster_visualizations/ │ └── README.md


---

## 📈 Results

- Drivers were grouped into clusters based on risk profile.
- Potential risky drivers were identified using **Isolation Forest** and **DBSCAN**.
- Visualizations reveal distinct separation in behavior across clusters.

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/<your-username>/porto-seguro-safe-driver-unsupervised.git
cd porto-seguro-safe-driver-unsupervised

    Install dependencies:

pip install -r requirements.txt

    Run the notebooks in the notebooks/ folder.

📌 To Do

Add autoencoder-based anomaly detection

Evaluate clustering performance using silhouette score

    Build a Streamlit dashboard (optional)

📚 References

    Kaggle Competition Page

    Scikit-learn Clustering Documentation

💡 Author

Aman Chaurasia
📧 Let's connect on LinkedIn

