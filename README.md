# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs **customer segmentation** using the **K-Means Clustering** machine learning algorithm.

The customers are grouped based on their:

* Age
* Annual Income
* Spending Score

The project also uses **PCA (Principal Component Analysis)** to visualize the customer clusters in two dimensions.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Dataset

The project uses a dataset named:

`mall.csv`

The following customer features are used:

* `Age`
* `Annual_Income_k`
* `Spending_Score`

## 🔄 Project Workflow

1. Load the customer dataset using Pandas.
2. Select the required customer features.
3. Standardize the data using `StandardScaler`.
4. Use the **Elbow Method** to determine the number of clusters.
5. Apply **K-Means Clustering** with 5 clusters.
6. Add the cluster labels to the dataset.
7. Visualize the customer segments.
8. Apply PCA to reduce the features to 2 dimensions.
9. Visualize the clusters using PCA.

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters.

In this project, the number of clusters is set to **5** after checking the Elbow Method.

## 📊 Visualizations

The project generates:

* Elbow Method graph
* Customer cluster scatter plot
* PCA cluster visualization

## 🚀 How to Run

### 1. Clone the repository

bash
git clone YOUR_GITHUB_REPOSITORY_URL


### 2. Install required libraries

bash
pip install pandas scikit-learn matplotlib seaborn jupyter


### 3. Open the Jupyter Notebook

bash
jupyter notebook


### 4. Run the notebook

Open the .ipynb`file and run the cells step by step.

## 📁 Project Structure

Mall-Customer-Segmentation/
│
├── mall.csv
├── mall_customer_segmentation.ipynb
└── README.md


## 🎯 Objective

The main objective of this project is to identify different groups of customers based on their characteristics and spending behavior using machine learning.

## 👩‍💻 Author

**Akshapritha P**
B.Tech Information Technology
Vivekanandha College of Engineering for Women
