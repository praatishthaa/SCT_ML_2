# 🛍️ Customer Segmentation using K-Means Clustering

This project is part of my **Machine Learning Internship at SkilllCraft Tech**.  
The goal was to perform **unsupervised learning** on mall customer data to discover natural groupings based on customer behavior — specifically **Annual Income** and **Spending Score**.


## 📌 Objective

Segment customers of a retail store into distinct groups to enable targeted marketing and personalized services. This is achieved using the **K-Means Clustering** algorithm.

## 🧠 What I Learned

- 📊 **Data Preprocessing** with `pandas` and `StandardScaler`
- 🧮 Understanding the **K-Means algorithm** from the inside out
- 📈 Using the **Elbow Method** to determine the optimal number of clusters
- 🖼️ Creating **visualizations** to interpret clustering results
- 🔁 Incorporating clustering into a reusable machine learning pipeline
- 🌐 Managing projects with **Git & GitHub**


## 🗂️ Dataset

**`Mall_Customers.csv`**  
- 200 samples of mall customers  
- Features: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`


## 🔧 Technologies Used

| Tool | Purpose |
|------|---------|
| `Python` | Programming Language |
| `pandas` | Data loading & manipulation |
| `matplotlib`, `seaborn` | Data visualization |
| `scikit-learn` | Machine learning algorithms |
| `StandardScaler` | Feature scaling |
| `Git & GitHub` | Version control & collaboration |
| `VS Code` | IDE for development |

---

## 🚀 How It Works

1. Load and inspect the dataset.
2. Select key features: **Annual Income** & **Spending Score**.
3. Scale the data for better clustering accuracy.
4. Use the **Elbow Method** to determine the best number of clusters (`k`).
5. Apply the **KMeans** algorithm to assign each customer a cluster.
6. Visualize the clusters using scatter plots and centroids.


> 🎯 Customers are segmented into 5 distinct groups based on income and spending habits.


## 🗃️ Folder Structure


kmeans-clustering-mall/
├── Mall\_Customers.csv
├── kmeans\_mall.py
├── README.md
└── assets/
└── cluster\_plot.png  # optional

## 📈 Results

The model identified 5 key customer types:
- High income, high spending
- Low income, low spending
- High income, low spending (conservative customers)
- Average income, high spending (targetable)
- etc.

These insights can help businesses with **customer profiling** and **targeted advertising**.

## 🤝 Acknowledgements

Thanks to **SkilllCraft Tech** for the internship opportunity and this hands-on project!


## 🧑‍💻 Author

**Praatishthaa**  
