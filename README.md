# 🛒 Product Recommendation System with Web Scraping and Clustering
📌 Product Recommendation System with Web Scraping, Data Processing, and Clustering
🚀 A data-driven machine learning project that recommends products to users based on their preferences!

This project focuses on collecting product data from e-commerce websites, cleaning and processing the dataset, clustering products using machine learning, and finally providing a GUI interface** where users can filter their preferences and receive product recommendations.

---

## 📖 Contents
- 🎯 Project Purpose
- 🔥 Why is it important?
- 📊 Dataset Used
- 📈 Data Processing and Modeling Steps
- 🧠 Algorithms Used
- 💻 GUI Filtering System
- ⚡ Quick Start
- 👥 Team
- 📸 Images

---

## 🎯 Project Purpose
The main goal of this project is to develop a smart product recommendation system.

This project will:

✅ Users can easily find products based on their preferences.

✅ Companies can categorize products more efficiently.

✅ Large e-commerce data can be cleaned and transformed for machine learning tasks.

✅ Recommendation accuracy can be increased using clustering.

---

## 🔥 Why is it important?

🔹 **Personalized Shopping Experience:** Users can filter and receive recommendations tailored to their needs.
🔹 **Data-Driven Insights:** Helps companies better understand their product categories.
🔹 **Efficient Data Processing:** Raw web scraped data is automatically cleaned, structured, and aggregated.
🔹 **Intuitive GUI:** Even non-technical users can filter products and get recommendations.

---

## 📊 Dataset Used
The dataset was obtained by scraping data from an e-commerce platform (Trendyol).

Product details are as follows:
- 📌 Product Name
- 📌 Brand
- 📌 Price
- 📌 Link
- 📌 Image Quality
- 📌 Internal Satellite Receiver
- 📌 Display Technology
- 📌 Warranty Period
- 📌 Screen Size
- 📌 Warranty Type
- 📌 Resolution

The dataset was processed using **pandas, numpy** and visualized with **matplotlib**. Missing values were removed, and product features were extracted using **regular expressions (Regex)**.

---

## 📈 Data Processing and Modeling Steps
1. **Data Collection:** Products are obtained from Trendyol and stored as `.xlsx` and `.csv`.
2. **Data Cleaning:**
- Missing values are processed
- Unnecessary columns are deleted
- Regex is used to calculate the screen size
3. **Data Visualization:** Missing data distribution and feature distributions are plotted.
4. **Clustering:** Products are clustered using the **K-Means algorithm**. Clusters are tested using Silhouette score and Graph-based methods.
5. **Recommendation:** Users receive product recommendations based on the cluster closest to their filter selections.

---

## 🧠 Machine Learning Models
- ✅ **K-Means Clustering** (for grouping products)
- ✅ **Similarity-based recommendation** (assigns user input to the closest cluster)

---

## 💻 GUI Filtering System
The GUI allows users to:
- Filter products by attributes (brand, screen size, resolution, etc.)
- See recommended products in the most suitable cluster
- Easily interact with the recommendation system without coding knowledge

---
<img width="1236" height="1007" alt="image" src="https://github.com/user-attachments/assets/ee4bdf47-4c50-4084-b9c6-df765fea1e57" />


## ⚡ Quick Start
To quickly run the project:

```bash
# 1. Clone the repo
git clone https://github.com/user/project-name.git
cd project-name

# 2. Install the requirements

pip install pandas numpy matplotlib scikit-learn seaborn scipy openpyxl

# 3. Run the notebook
jupyter notebook main.ipynb
