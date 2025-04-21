# 🧠 Clustering Models: KMeans (Iris) & KModes (Mushroom)

This repository contains two unsupervised machine learning models implemented in Python using clustering techniques:

- 📊 **KMeans** applied to the **Iris dataset**
- 🍄 **KModes** applied to the **Mushroom dataset**

These models showcase the difference between clustering **numerical** and **categorical** data.

---

## 📁 Files in This Repository

| File Name     | Description                                         |
|---------------|-----------------------------------------------------|
| `KMeans.py`   | Performs KMeans clustering on the Iris dataset      |
| `K_Modes.py`  | Performs KModes clustering on the Mushroom dataset  |

---

## 📊 KMeans Clustering on Iris Dataset

- Uses Scikit-Learn's `KMeans` algorithm
- Dataset contains numerical features of flowers (sepal/petal length and width)
- Performs **Elbow method** to determine the optimal number of clusters
- Visualizes the clustered output using Matplotlib
- Calculates and prints the **WCSS (Within Cluster Sum of Squares)**

### ✅ Results
- Cluster plot with centroids
- Optimal number of clusters
- WCSS values

---

## 🍄 KModes Clustering on Mushroom Dataset

- Mushroom dataset contains **categorical features** like cap shape, color, odor, etc.
- Uses the `KModes` algorithm from the `kmodes` package
- Categorical features are encoded using `LabelEncoder`
- Clusters mushrooms based on feature similarity

### ✅ Results
- Cluster assignments for each mushroom
- Count of mushrooms in each cluster
- Comparison with original class labels (edible/poisonous)

---

## 🧠 What I Learned

- Difference between clustering on numerical vs categorical data
- Use of **KMeans** for numeric features and **KModes** for categorical features
- Importance of preprocessing, especially encoding for categorical data
- How to determine cluster quality using metrics like **WCSS**
- Visualization techniques to interpret clustering results

---

## 📦 Requirements

Install the following libraries before running the scripts:

```bash
pip install pandas scikit-learn matplotlib kmodes

## now you can understand whatever i wrote
 - read again if you dont understand anything
 