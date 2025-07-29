# 🍽️ Zomato Restaurant Data Analysis & Clustering

This project involves a complete end-to-end analysis of restaurant data from Zomato, focusing on **data cleaning**, **exploratory data analysis**, **feature engineering**, and **clustering** similar restaurants based on reviews, metadata, and popularity indicators.

---

## 📁 Dataset Description

The project uses two datasets:

1. `restaurant_reviews.csv`  
   - User ratings  
   - Review dates  
   - Pictures, Followers, Verification status  
   - Reviewer names

2. `restaurant_metadata.csv`  
   - Restaurant names  
   - Cost for two  
   - Cuisines, Collections  
   - Timings

---

## 📌 Project Objectives

- Clean and preprocess both datasets
- Merge review and metadata intelligently
- Analyze distributions and relationships
- Handle missing values and outliers
- Engineer features from multi-label categories (e.g., cuisines)
- Perform hypothesis testing
- Prepare data for clustering
- Discover groups of similar restaurants

---

## 🔧 Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – Encoding, scaling, clustering  
  - `scipy` – Statistical hypothesis testing

---

## 📊 Key Steps

### ✔️ Data Cleaning
- Checked nulls using heatmaps
- Dropped or imputed missing values
- Removed irrelevant or inconsistent entries

### ✔️ Feature Engineering
- One-hot encoded cuisines, collections, day of week
- Converted multi-label columns to binary flags
- Capped outliers using 99th percentile

### ✔️ Hypothesis Testing
- Compared ratings between verified/unverified users  
- Checked if photo count affects rating  
- Explored correlation between followers and ratings

### ✔️ Clustering Prep
- Standardized numerical features
- Dropped high-cardinality non-numeric fields
- Prepared input for clustering algorithms (e.g., KMeans)

---

## 🚀 Results & Use Case

The clustering output allows:
- Segmenting restaurants by cuisine, cost, and review behavior
- Identifying top-performing or niche segments
- Enabling restaurant recommendations or targeting strategies

---

## 📽️ Demo

📎 [Click here to view project explanation video](https://your-drive-or-youtube-link-here)

---

## 🧠 Author

**Nameless (Jayanth M)**  
ML & Data Science Enthusiast  
[Your GitHub link] | [Your LinkedIn link]

---

## 📌 Note

This project is for academic and learning purposes only and does not represent any commercial affiliation with Zomato.

