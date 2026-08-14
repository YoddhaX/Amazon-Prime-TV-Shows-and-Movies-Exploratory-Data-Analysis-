# 🎬 Amazon Prime Content Analysis — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge\&logo=python\&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-3776ab?style=for-the-badge)

> **An exploratory data analysis project focused on understanding Amazon Prime Video's content library through trends in titles, genres, ratings, countries, certifications, and cast & crew.**

---

## 📌 About the Project

Streaming platforms contain thousands of movies and TV shows across different countries, genres, ratings, and release periods.

This project uses **Exploratory Data Analysis (EDA)** to investigate Amazon Prime Video's content library and identify meaningful patterns in its catalog.

The analysis combines **title-level metadata** with **cast and crew information** to explore content distribution, audience ratings, geographical representation, and the people involved in producing the content.

---

## 🎯 Objectives

The main objectives of this project are to:

* Understand the distribution of **Movies vs. TV Shows**
* Analyze content growth across **release years**
* Identify the most common **genres**
* Explore **IMDb and TMDB ratings**
* Analyze content based on **certification / age ratings**
* Identify countries contributing the most content
* Explore **runtime patterns**
* Analyze the contribution of **actors, directors, and writers**
* Identify relationships between ratings, votes, and content characteristics

---

## 🔍 Key Analysis Areas

### 🎬 1. Movies vs. TV Shows

Analyze the composition of Amazon Prime's catalog:

* Number of Movies
* Number of TV Shows
* Distribution of content types
* Runtime differences
* Release trends over time

---

### 🎭 2. Genre Analysis

Explore the most frequently occurring genres and understand how content categories are distributed across the platform.

Key questions include:

* Which genres dominate the catalog?
* How are genres distributed across Movies and TV Shows?
* Which genres have grown over time?

---

### ⭐ 3. Ratings & Popularity

Analyze available IMDb and TMDB metrics to understand content performance.

The analysis explores:

* IMDb scores
* TMDB scores
* Vote counts
* Rating distributions
* Relationship between ratings and popularity

---

### 🛡️ 4. Certification Analysis

Study the maturity and audience classification of content using available certifications such as:

* G
* PG
* PG-13
* R
* TV ratings

This helps understand the type of audience the content is targeted toward.

---

### 🌍 5. Geographical Analysis

Explore the global distribution of Amazon Prime content.

Analysis includes:

* Top content-producing countries
* Country-wise title distribution
* International representation
* Comparison of major content-producing regions

---

### 🎬 6. Cast & Crew Analysis

Using the `credits.csv` dataset, analyze the people associated with the content.

This includes:

* Actors
* Directors
* Writers
* Number of titles associated with individuals
* Frequently appearing cast and crew members

---

## 📊 Dataset

This project uses two datasets:

| File          | Description                | Important Columns                                                                          |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------ |
| `titles.csv`  | Movie and TV show metadata | Title, Type, Release Year, Runtime, Genres, Country, Certification, IMDb Score, TMDB Score |
| `credits.csv` | Cast and crew information  | Person ID, Name, Role, Title ID                                                            |

### `titles.csv`

Contains information about individual movies and TV shows, including their:

* Title
* Type
* Release year
* Runtime
* Genres
* Country
* Certification
* IMDb score
* TMDB score
* Vote counts

### `credits.csv`

Contains information about people involved in producing the content:

* Person ID
* Name
* Role
* Title ID

Roles include:

* Actor
* Director
* Writer

---

## 🧹 Data Preparation

The analysis includes common data-preprocessing and cleaning operations such as:

* Loading datasets using Pandas
* Inspecting dataset structure
* Checking missing values
* Handling duplicate records
* Converting columns into appropriate data types
* Extracting useful information from categorical columns
* Preparing data for visualization and analysis

---

## 📈 Visualization

The project uses **Matplotlib** and **Seaborn** to create visualizations for:

* Content distribution
* Year-wise trends
* Genre distribution
* Rating analysis
* Certification distribution
* Country-wise content
* Runtime patterns
* Cast and crew analysis

---

## 🛠️ Tech Stack

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| 🐍 Python           | Programming & analysis    |
| 🐼 Pandas           | Data manipulation         |
| 🔢 NumPy            | Numerical operations      |
| 📊 Matplotlib       | Data visualization        |
| 📈 Seaborn          | Statistical visualization |
| 📓 Jupyter Notebook | Analysis environment      |

---

## 📂 Repository Structure

```text
Amazon-Prime-Content-Analysis/
│
├── data/
│   ├── titles.csv
│   └── credits.csv
│
├── amazon_prime_analysis.ipynb
│
├── README.md
│
└── assets/
    └── project-preview.png
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project

```bash
cd Amazon-Prime-Content-Analysis
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
amazon_prime_analysis.ipynb
```

and run the notebook cells sequentially.

---

## 💡 Key Insights

The analysis aims to answer questions such as:

* What type of content dominates the library?
* Which genres are most common?
* How has content production changed over time?
* Which countries contribute the most titles?
* What certifications are most common?
* How are IMDb and TMDB ratings distributed?
* Which actors, directors, and writers appear most frequently?
* Is there a relationship between ratings and vote counts?

---

## 📌 Project Highlights

* ✅ Real-world streaming content dataset
* ✅ Exploratory Data Analysis
* ✅ Data cleaning and preprocessing
* ✅ Statistical analysis
* ✅ Multiple data visualizations
* ✅ Categorical and numerical analysis
* ✅ Geographic content analysis
* ✅ Cast & crew analysis
* ✅ IMDb & TMDB rating analysis

---

## 🎓 Learning Outcomes

Through this project, I practiced:

* Data cleaning with **Pandas**
* Data exploration and aggregation
* Handling categorical data
* GroupBy operations
* Statistical analysis
* Data visualization with **Matplotlib & Seaborn**
* Extracting meaningful insights from real-world datasets
* Presenting analytical findings in a structured manner

---

## 👨‍💻 Author

**Mayank Sahu**

📌 Data Analysis | Python | Pandas | SQL | Machine Learning

---

⭐ **If you found this project useful, consider giving the repository a star!**
