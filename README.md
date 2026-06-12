# 🎬 Netflix Movies & TV Shows Analytics Dashboard

## 📌 Project Overview

The **Netflix Movies & TV Shows Analytics Dashboard** is a Big Data Analytics project developed using Python. The project analyzes Netflix's content library to uncover insights related to content types, genres, countries, ratings, directors, and content growth over time.

Using data visualization and exploratory data analysis (EDA), the dashboard transforms raw Netflix data into meaningful business insights through interactive and static visualizations.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing on real-world Netflix data.
* Conduct Exploratory Data Analysis (EDA).
* Visualize trends and patterns in Netflix content.
* Build interactive dashboards using Plotly.
* Generate a recommendation system using Natural Language Processing (NLP).
* Demonstrate key Big Data concepts such as Volume, Variety, Veracity, Velocity, and Value.

---

## 📂 Dataset

Dataset: **Netflix Movies and TV Shows**

Source: Kaggle

File: `netflix_titles.csv`

The dataset contains information about:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Release Year
* Rating
* Genre
* Description

---

## 🛠️ Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* WordCloud
* Scikit-Learn

---

## 📊 Dashboard Features

### 1. Movies vs TV Shows Analysis

* Pie chart visualization.
* Displays the percentage distribution of Movies and TV Shows.

### 2. Content Growth Over Time

* Line chart showing content growth by release year.
* Helps identify Netflix expansion trends.

### 3. Top Content-Producing Countries

* Horizontal bar chart of top countries contributing content.

### 4. Ratings Distribution

* Visualizes the distribution of content ratings.
* Identifies audience targeting patterns.

### 5. Genre Analysis

* Displays the most common genres on Netflix.
* Helps understand content strategy.

### 6. Interactive Plotly Dashboard

* Interactive histogram with filtering and zooming capabilities.
* Compares Movies and TV Shows by release year.

### 7. Netflix Word Cloud

* Text mining visualization generated from content descriptions.
* Highlights frequently occurring terms.

---

## 🚀 Advanced Features

### Content Recommendation System

A simple recommendation engine built using:

* TF-IDF Vectorization
* Cosine Similarity

The system recommends similar titles based on content descriptions.

### Most Prolific Directors Analysis

Identifies directors with the highest number of Netflix titles.

### Country-Wise Heatmap

Visualizes content production patterns across countries and categories.

---

## 📈 Key Insights

* Movies dominate Netflix's content library.
* Content production increased significantly after 2015.
* The United States contributes the largest amount of content.
* TV-MA and TV-14 are the most common content ratings.
* Drama and Comedy are among the most popular genres.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/netflix-analytics-dashboard.git
```

2. Navigate to the project directory:

```bash
cd netflix-analytics-dashboard
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly wordcloud scikit-learn
```

4. Place the dataset file:

```text
netflix_titles.csv
```

inside the project directory.

5. Run the notebook:

```bash
jupyter notebook
```

or open the project in Google Colab.

---

## 📁 Project Structure

```text
Netflix-Analytics-Dashboard/
│
├── netflix_titles.csv
├── Netflix_Analytics_Dashboard.ipynb
├── README.md
│
└── assets/
    ├── movies_vs_tvshows.png
    ├── content_growth.png
    ├── genre_analysis.png
    └── wordcloud.png
```

---

## 🔮 Future Enhancements

* Streamlit Web Application
* Real-Time Dashboard
* Advanced Recommendation System
* Sentiment Analysis of Content Descriptions
* Genre Prediction using Machine Learning

---

## 👨‍💻 Author

**Afnan KC**

Data Science & Analytics Enthusiast

---

## 📜 License

This project is created for educational and academic purposes.
