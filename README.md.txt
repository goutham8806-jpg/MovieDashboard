# 🎬 Movie Data Analysis Project

## Project Overview
This project is a mini Data Analyst portfolio project built in Jupyter Notebook.  
It involves scraping movie data from online sources, cleaning it, performing exploratory data analysis (EDA), and visualizing insights such as top movies, distributors, and trends.  

The project demonstrates skills in **web scraping, data cleaning, analysis, and visualization** — perfect for showcasing in a GitHub portfolio.

---

## 🛠 Tools Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- BeautifulSoup
- Requests
- WordCloud (Optional)

---

## 📋 Steps Followed
1. **Web Scraping**
   - Fetched movie tables from online sources using `requests` and `BeautifulSoup`.
   - Parsed HTML tables and extracted movie details like title, distributor, domestic gross, production company, cast & crew.

2. **Data Cleaning**
   - Removed duplicates and missing values.
   - Formatted columns like `Domestic gross` to numeric for analysis.

3. **Exploratory Data Analysis (EDA)**
   - Top 10 movies by domestic gross.
   - Top distributors and production companies.
   - Trends over months/quarters.

4. **Visualizations**
   - Bar charts for top movies & distributors.
   - Pie charts for distribution of production companies.
   - Optional: Word Cloud of movie titles.

5. **Insights & Conclusions**
   - Key patterns in movie revenue, distributor performance, and popular genres.

---

## 📊 Sample Visualizations

### 1. Top 10 Movies by Domestic Gross
![Top 10 Movies](visuals/top10_movies.png)

### 2. Revenue Distribution by Distributor
![Distributor Revenue](visuals/distributor_revenue.png)

### 3. Production Company Contributions
![Production Companies](visuals/production_companies.png)

### 4. Word Cloud of Movie Titles (Optional)
![Movie Word Cloud](visuals/movie_wordcloud.png)

> *You can add your own screenshots or exported images from Matplotlib/Seaborn/WordCloud to the `visuals/` folder.*

---

## 📝 Additional Documentation

### Data Dictionary
| Column Name         | Description |
|--------------------|-------------|
| Rank               | Rank of the movie based on domestic gross |
| Title              | Name of the movie |
| Distributor        | Company distributing the movie |
| Domestic gross     | Domestic box office revenue (USD) |
| Opening            | Opening date |
| Production company | Movie production companies |
| Cast and crew      | Key cast and crew members |
| Ref                | Reference link or note |

### Key Insights
- The top distributors dominate box office revenue.
- Certain production companies consistently release high-grossing movies.
- Trends over months show peak releases during holiday seasons.

---

## 🚀 How to Run the Notebook
1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/movie-data-analysis.git
