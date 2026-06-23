# Centroid_Base_Clustering_on_Pokemon_Data_Set
centroid-based clustering techniques — primarily the K-Means algorithm — to analyze and group Pokemon based on their battle statistics. 
Project Overview

The notebook analyzes Pokémon attributes such as:

HP
Attack
Defense
Special Attack
Special Defense
Speed
Type
Generation
Legendary Status

Using unsupervised machine learning techniques, Pokémon are grouped into clusters with similar characteristics.
The project uses a dataset named:

Pokemon.csv

The dataset contains information about Pokémon species, stats, types, generations, and legendary status.

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
📊 Exploratory Data Analysis

The notebook includes:

Data Inspection
Dataset preview
Shape of dataset
Statistical summary
Missing value analysis
Data Cleaning
Missing values in Type 2 are replaced with "None"
Visualizations
Distribution of secondary Pokémon types
Legendary Pokémon across generations
Histograms of battle statistics
⚙️ Feature Engineering
Numerical Features
HP
Attack
Defense
Sp. Atk
Sp. Def
Speed
Categorical Features
Type 1
Generation

Categorical variables are encoded using one-hot encoding.

🔄 Data Preprocessing

Features are standardized using:

StandardScaler

This ensures all features contribute equally to clustering.

🤖 K-Means Clustering

The project uses K-Means clustering to group Pokémon with similar attributes.

Selecting Optimal Number of Clusters

Two evaluation methods are applied:

1. Elbow Method

Measures:

WCSS (Within Cluster Sum of Squares)

to identify the optimal cluster count.

2. Silhouette Analysis

Measures clustering quality using:

Silhouette Score

The value with the highest score is selected as the best number of clusters.

📉 Dimensionality Reduction
PCA (Principal Component Analysis)

Used to visualize clusters in:

2D space
3D space

Visualizations include:

PCA Scatter Plot
3D Cluster Visualization
📈 Cluster Analysis

The notebook analyzes:

Cluster Statistics
Average HP
Average Attack
Average Defense
Average Special Attack
Average Special Defense
Average Speed
Legendary Pokémon Distribution

Identifies which cluster contains the highest number of legendary Pokémon.

Type Distribution

Shows how Pokémon types are distributed across clusters.

Generation Distribution

Examines how Pokémon generations are represented within clusters.

📁 Project Structure
├── Pokemon.ipynb
├── Pokemon.csv
└── README.md
