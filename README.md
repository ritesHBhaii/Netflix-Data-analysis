# Netflix Content Strategy Analysis

## Project Overview

Netflix is one of the world's largest streaming platforms, offering thousands of Movies and TV Shows across multiple countries and genres. This project performs an end-to-end Exploratory Data Analysis (EDA) on the Netflix dataset to uncover content trends and generate business recommendations that can support Netflix's content production and global expansion strategy.

The analysis focuses on answering:

* What type of content should Netflix produce more of?
* How has Netflix's content strategy evolved over time?
* Which genres dominate the platform?
* Which countries contribute the most content?
* How can Netflix expand its business globally?

---

## Business Problem

Netflix aims to understand content consumption trends and identify opportunities for future growth.

The objective of this analysis is to provide data-driven recommendations regarding:

* Content production strategy
* TV Show vs Movie investment
* Genre prioritization
* International expansion opportunities
* Audience targeting

---

## Dataset Information

The dataset contains information about Netflix Movies and TV Shows, including:

* Show ID
* Content Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

Dataset Size:

* 8,807 Records
* 12 Features

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Missing value analysis
* Datetime conversion
* Genre unnesting using explode()
* Country unnesting using explode()
* Director unnesting using explode()
* Cast unnesting using explode()
* Feature engineering:

  * Year Added
  * Month Added

---

## Exploratory Data Analysis

### Movies vs TV Shows

* Movies account for approximately 70% of Netflix's catalog.
* TV Shows account for approximately 30%.

### Release Trends

* Most content was released after 2010.
* Content production accelerated significantly after 2015.

### Genre Analysis

Top genres include:

* International Movies
* Dramas
* Comedies

### Country Analysis

Top contributing countries:

1. United States
2. India
3. United Kingdom

### Ratings Analysis

* TV-MA is the dominant rating category.
* Netflix primarily targets mature audiences.

### Content Growth

* Netflix experienced rapid catalog expansion between 2017 and 2020.
* TV Shows have grown faster than Movies over the last decade.

---

## Key Findings

* Movies dominate Netflix's catalog with nearly 70% share.
* TV Shows represent the fastest-growing content category.
* International content is a major growth driver.
* Drama, Comedy, and International Movies are the most represented genres.
* The United States and India are the most important content-producing countries.
* Most content additions occurred between 2017 and 2020.

---

## Business Recommendations

### 1. Increase Investment in TV Shows

TV Shows encourage binge-watching and improve subscriber retention.

### 2. Expand Localized Content

Increase content production in high-growth markets such as:

* India
* South Korea
* Japan

### 3. Focus on Proven Genres

Continue investing in:

* Drama
* Comedy
* International Content

### 4. Strengthen Creator Partnerships

Develop long-term relationships with high-performing directors and creators.

### 5. Expand Family-Oriented Content

Diversify the catalog to reach broader audience segments.

---

## Author

Ritesh Yadav

Data Scientist

