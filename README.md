# 🎬 Netflix Titles Exploratory Data Analysis (EDA)

This project presents an in-depth **Exploratory Data Analysis (EDA)** on the **Netflix Titles Dataset**, using **Python and Jupyter Notebook**. The goal is to analyze Netflix’s content in terms of type, duration, country of origin, rating, and release trends — and to visualize all findings with clean, interpretable charts.

This project was completed as part of an internship data analysis task.

---

## 📁 Project Structure

CodeALpha_EDA/
│
├── notebooks/
│ ├── task2.ipynb # Main Jupyter Notebook (EDA)
│ └── netflix_titles.csv # Netflix dataset used in the project
│
├── images/ # Folder containing all saved plots
│
├── requirements.txt # Python libraries used
└── README.md # Project description and instructions


---

## 📌 Dataset

- **Source**: [Netflix Shows Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Format**: CSV
- **Details**: Metadata of movies and TV shows available on Netflix, including:
  - Title, type, cast, director, country, rating
  - Release year, date added to platform, duration, genres

---

## 🎯 Objectives

- Explore and understand the structure of the dataset
- Clean missing and inconsistent data
- Extract useful features such as `duration_mins` and `year_added`
- Identify key patterns in content types, duration, country distribution, ratings, and time trends
- Visualize findings using Seaborn and Matplotlib
- Save graphs as `.png` images for reporting or presentations

---

## 📊 Visualizations

All charts are saved in the `images/` folder:

| Chart Title                      | File Name                              |
|----------------------------------|----------------------------------------|
| Count of Movies vs TV Shows     | `graph_movies_vs_tvshows.png`          |
| Movie Duration Distribution      | `graph_movie_duration_distribution.png`|
| Top 5 Content Ratings            | `graph_top_5_ratings.png`              |
| Boxplot of Movie Durations       | `graph_boxplot_movie_duration.png`     |
| Top 5 Countries by Content       | `graph_top_5_countries.png`            |
| Titles Added Over the Years      | `graph_titles_added_over_years.png`    |
| Correlation Heatmap              | `graph_correlation_heatmap.png`        |

---

## 🧪 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data handling
- **NumPy** – Numerical operations
- **Seaborn & Matplotlib** – Visualizations

---

## 🚀 How to Run the Project

1. **Clone the repository** or download the ZIP:
   ```bash
   git clone https://github.com/your-username/netflix-eda-project.git
   cd netflix-eda-project
