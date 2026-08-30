# Customer Segmentation using Machine Learning

This project demonstrates customer segmentation using **unsupervised machine learning**. Customer segmentation involves grouping customers with similar purchasing behavior so that different customer groups can be better understood and analyzed.

In this project, **K-Means clustering** is used to segment customers based on their purchasing patterns, while **Principal Component Analysis (PCA)** is used for dimensionality reduction and visualization.

## Getting Started

### Prerequisites

To run this project, you need to have **Python 3** installed along with the following libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

### Installation

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.

2. Open a command prompt or terminal and navigate to the project directory.

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `customer_segmentation.ipynb` file.

5. Run the notebook cells sequentially to perform the customer segmentation analysis.

## Project Workflow

The project follows these main steps:

1. **Data Exploration** – Understanding the dataset and its features.
2. **Data Preprocessing** – Checking data quality and preparing the features.
3. **Exploratory Data Analysis** – Analyzing customer purchasing patterns and relationships between features.
4. **Feature Scaling** – Standardizing the selected customer spending features.
5. **PCA** – Reducing the feature dimensions for visualization.
6. **K-Means Clustering** – Grouping customers into different segments.
7. **Cluster Evaluation** – Evaluating the resulting clusters using clustering metrics.
8. **Visualization** – Visualizing the identified customer segments and their characteristics.

## Dataset

The project uses the **Wholesale Customers dataset**, which contains customer spending information across different product categories.

The purchasing features used for customer segmentation include:

* Fresh
* Milk
* Grocery
* Frozen
* Detergents_Paper
* Delicassen

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## Machine Learning Techniques

### K-Means Clustering

K-Means is used to group customers according to similarities in their purchasing behavior. The project uses **4 clusters** for the final customer segmentation.

### Principal Component Analysis

PCA is applied to reduce the dimensionality of the customer spending data and represent the resulting clusters in a two-dimensional space for visualization.

### Cluster Evaluation

The clustering results are evaluated using:

* **Silhouette Score**
* **Calinski-Harabasz Index**

##
