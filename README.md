# Yelp User and Business Segmentation

A data mining notebook for Yelp user and business segmentation using K-Means clustering and PCA visualization.

This repository contains a cleaned notebook from a course project. The focus is on exploratory segmentation analysis, user profiling, business profiling, and interpreting interaction patterns between different user and business groups.

## Project Context

This is based on a team course project.
This repository only includes selected and cleaned materials for portfolio reference.

My main contribution focused on user and business segmentation analysis, cluster interpretation, and analytical insight generation.

## Project Overview

The project analyzes Yelp review data to identify meaningful user and business segments. The notebook builds aggregated user-level and business-level features, applies scaling and clustering methods, and visualizes the results using PCA.

The analysis aims to answer questions such as:

* What types of users can be identified from review behaviour?
* What types of businesses can be grouped based on rating and engagement patterns?
* How do different user groups interact with different business groups?
* What insights can be derived for recommendation, customer targeting, or platform operations?

## Methods

* Data preprocessing and feature aggregation
* User-level behaviour feature construction
* Business-level profile construction
* Standardization with `StandardScaler`
* K-Means clustering
* Elbow method and silhouette score for cluster selection
* PCA-based 2D visualization
* Cluster profiling and interpretation
* User-business interaction analysis

## Repository Structure

```text
yelp-user-business-segmentation/
├── README.md
├── requirements.txt
├── .gitignore
└── clustering_models.ipynb
```

## Notes on Data

Raw Yelp data and intermediate merged datasets are not included in this repository because of file size and data-sharing considerations.

The notebook is provided as a portfolio reference to demonstrate the analysis workflow and methodology.

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
