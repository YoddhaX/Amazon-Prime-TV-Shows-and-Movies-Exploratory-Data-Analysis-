# 🎬 Amazon Prime Content Analysis — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-3776ab?style=for-the-badge)

An in-depth Exploratory Data Analysis (EDA) decoding content strategies, viewer trends, ratings dynamics, and global diversity across Amazon Prime Video's extensive library.

---

## 📌 Executive Summary

With the massive growth in digital streaming, understanding library trends is essential for platforms and content creators alike. This project analyzes two rich datasets—capturing title specifications and crew details—to explore how Amazon Prime has evolved over decades, catered to global audiences, and balanced quality vs. popularity.

---

## 🎯 Key Analysis Focus Areas

* 📊 **Movies vs. TV Shows:** Analysis of content portfolio distribution, runtime patterns, and release acceleration over time (including post-COVID shifts).
* 🎭 **Genre Dynamics:** Identifying dominant genres (Drama, Comedy) vs. rapidly growing genres (Documentary, Thrillers) across decades.
* ⭐ **Ratings & Popularity:** Cross-evaluating IMDb and TMDB scores against vote counts to assess critical acclaim vs. mass popularity.
* 🛡️ **Age & Maturity Distribution:** Decoding platform demographics across certifications ($G$, $PG$, $PG-13$, $R$, etc.).
* 🌍 **Geographical Insights:** Mapping top content-producing nations, US vs. Non-US library ratios, and international ratings on a global scale.
* 🎬 **Cast & Crew Influence:** Profiling the top directors, writers, and actors driving viewer satisfaction and high ratings.

---

## 📊 Dataset Overview

| File | Description | Key Attributes |
| :--- | :--- | :--- |
| **`titles.csv`** | Metadata of movies & shows | Title, Type, Release Year, Runtime, Genres, Country, Certification, IMDb/TMDB Scores |
| **`credits.csv`** | Cast & Crew mapping | Person ID, Name, Role (Actor/Director/Writer), Title ID |

---

## 📂 Repository Structure

```text
├── titles.csv                  # Detailed title metadata
├── credits.csv                 # Cast and crew information
├── amazon_prime_analysis.ipynb # End-to-end Python EDA Notebook
└── README.md                   # Documentation
