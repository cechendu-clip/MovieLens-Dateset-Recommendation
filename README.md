# 🎬 MovieLens Recommendation System

This repository contains a movie-recommendation assignment implemented for ITCS 8162 - Data Mining at UNC Charlotte.  
It uses the **MovieLens 100K** dataset and implements three distinct recommendation strategies:

- **User-Based Collaborative Filtering**  
- **Item-Based Collaborative Filtering**  
- **Pixie-Inspired Graph Random Walk Recommendation**

---

# 📘 Project Overview 

This project demonstrates three different approaches to building a movie 
recommendation system using the MovieLens 100K dataset. The goal is to compare 
traditional collaborative filtering methods with a graph-based Pixie-inspired random 
walk algorithm and evaluate how well each technique identifies relevant movie recommendations.

# 📑 Table of Contents 

- Project Overview

- Repository Structure

- Features Implemented

- Dataset

- Getting Started

- Run the Notebook

## 📂 Repository Structure

MovieLens-Dateset-Recommendation/

├── u.data

├── u.item

├── u.user

├── ratings.csv

├── movies.csv

├── users.csv

├── Explanation of Pixie-Inspired Algorithms.pdf

├── Recommendation Report.pdf

└── README.md

---

## 🔧 Features Implemented

### ✔ User-Based Collaborative Filtering  
- Builds a **user–movie rating matrix**  
- Computes cosine similarity between users  
- Recommends movies liked by similar users  

### ✔ Item-Based Collaborative Filtering  
- Builds a **movie–user matrix**  
- Computes similarity between movies  
- Recommends movies similar to ones the user already liked  

### ✔ Pixie-Inspired Graph Random Walk  
- Constructs a **bipartite graph** of users and movies  
- Performs random walks starting from a given movie  
- Ranks movies by how often they are visited during the walk  
- Recommends the top-visited movies  

---

## 📊 Dataset

- **Dataset used:** MovieLens 100K (100,000 ratings)  
- **Users:** 943  
- **Movies:** 1,682  
- **Files used:** `u.data`, `u.item`, `u.user` and their CSV equivalents  

---

## 🚀 Getting Started

Follow these steps to set up and run the notebook.

### 1. Clone the repository
```bash
git clone https://github.com/cechendu-clip/MovieLens-Dateset-Recommendation.git
cd MovieLens-Dateset-Recommendation
```

### 2. Create a Python Environment 
```bash
python -m venv venv
```
Activate the environment:

On macOS / Linux:
```bash
source venv/bin/activate
```
On Windows:
```bash
venv\Scripts\activate
```
### 3. Install Dependencies 

Install the required Python packages: 
```bash
pip install pandas numpy scikit-learn jupyter
```

### 4. Launch Jupyter Notebook 

Start Jupyter Notebook: 
```bash
jupyter notebook
```
### 5. Run the Notebook 

In the Jupyter Interface, open or upload: 
```text
Movie_Recommendation.ipynb
```
Run all cells in order, from **Top to Bottom**, 
or select the **Run** Tab and click **Run ALL Cells **






