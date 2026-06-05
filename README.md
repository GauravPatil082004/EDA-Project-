# Amazon Prime TV Shows and Movies - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on Amazon Prime Video's Movies and TV Shows dataset. The objective is to analyze the platform's content library, identify trends, understand audience preferences, and generate actionable business insights that can help improve content acquisition, marketing strategies, and platform growth.

## Project Type
- Exploratory Data Analysis (EDA)
- Individual Project

## Business Objective
The primary goal of this project is to provide data-driven insights into Amazon Prime Video's content catalog by analyzing:

- Content distribution (Movies vs TV Shows)
- Release year trends
- Genre popularity
- Content ratings and certifications
- Production countries
- IMDb and TMDB ratings
- Runtime distributions
- Popular actors and directors

These insights can help Amazon Prime optimize content strategy and enhance user engagement.

---

## Dataset Information

The project uses two datasets:

### 1. Titles Dataset (`titles.csv`)
Contains information about Amazon Prime Movies and TV Shows such as:

- Title
- Content Type
- Release Year
- Genres
- Runtime
- Age Certification
- IMDb Score
- IMDb Votes
- TMDB Score
- TMDB Popularity
- Production Countries

### 2. Credits Dataset (`credits.csv`)
Contains information related to cast and crew:

- Person Name
- Role (Actor/Director)
- Character
- Associated Title

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Understanding
- Dataset loading
- Initial exploration
- Data structure analysis
- Missing value identification
- Duplicate value detection

### 2. Data Cleaning & Wrangling
- Handling missing values
- Removing duplicates
- Data transformation
- Feature preparation

### 3. Exploratory Data Analysis
Various visualizations were created to uncover insights:

#### Univariate Analysis
- Content Type Distribution
- Release Year Distribution
- Age Certification Analysis
- Runtime Distribution
- IMDb Score Distribution
- TV Show Seasons Distribution
- Episode Runtime Distribution
- TMDB Popularity Distribution
- IMDb Votes Distribution

#### Bivariate Analysis
- IMDb Score vs TMDB Score
- Top Genres Analysis
- Top Production Countries
- Role Distribution (Actors vs Directors)
- IMDb Scores by Content Type
- Average IMDb Score by Genre
- Content Type vs Age Certification
- IMDb Score Distribution by Genre

#### Multivariate Analysis
- Correlation Heatmap
- Pair Plot Analysis

---

## Key Insights

### Content Library
- Movies significantly outnumber TV Shows on Amazon Prime.
- The platform has experienced substantial content growth in recent years.

### Genres
- Drama and Comedy are among the most common genres.
- Certain genres consistently achieve higher IMDb ratings.

### Ratings
- IMDb and TMDB scores show a positive correlation.
- Most content receives moderate-to-good audience ratings.

### Global Presence
- Content is produced across multiple countries, demonstrating Amazon Prime's international reach.

### Talent Analysis
- A small number of actors and directors appear frequently throughout the catalog.

---

## Business Recommendations

1. Increase investment in high-performing genres.
2. Expand production in regions showing strong audience engagement.
3. Focus marketing efforts on highly rated content.
4. Continue balancing Movies and TV Shows to satisfy diverse viewer preferences.
5. Collaborate with frequently successful actors and directors.

---

## Conclusion

This EDA provides valuable insights into Amazon Prime Video's content ecosystem. The findings can support strategic decisions regarding content acquisition, audience targeting, and platform expansion.

---

## Author

**Gaurav Arun Patil**

## License

This project is intended for educational and learning purposes.
