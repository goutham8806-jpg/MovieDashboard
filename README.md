🎬 Movie Data Analysis Project

A complete data analysis workflow built in Python & Jupyter Notebook — featuring web scraping, data cleaning, exploratory data analysis (EDA), and visual reporting.

This project demonstrates real-world data analyst skills including web scraping, data wrangling, visualization, and trend analysis.

🛠 Tools & Technologies

Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

BeautifulSoup, Requests

WordCloud (optional)

📋 Project Workflow
1. Web Scraping

Using requests and BeautifulSoup, extracted movie data such as:

Title

Distributor

Domestic Gross

Opening

Production Company

Cast & Crew

2. Data Cleaning

Removed missing values & duplicates

Standardized column names

Converted Domestic gross from string → numeric

Cleaned production company and distributor fields

3. Exploratory Data Analysis (EDA)

Analyzed patterns and trends:

Top 10 movies by domestic gross

Revenue share of distributors

Most frequent production companies

Seasonal/quarterly revenue variations

4. Visualizations

Bar chart: Top movies

Pie chart: Production company share

Distribution charts for distributors

Word Cloud of movie titles (optional)

📊 Sample Visuals

Top 10 Movies by Domestic Gross
visuals/top10_movies.png

Distributor Revenue Share
visuals/distributor_revenue.png

Production Company Breakdown
visuals/production_companies.png

Movie Title Word Cloud
visuals/movie_wordcloud.png

Add your exported images inside the visuals/ folder.

📝 Data Dictionary
Column	Description
Rank	Rank based on domestic gross
Title	Movie title
Distributor	Release distribution company
Domestic gross	Total domestic revenue (USD)
Opening	Opening date or weekend
Production company	Company producing the film
Cast and crew	List of actors/directors
Ref	Reference source
🚀 How to Run This Notebook

Clone the repository:

git clone https://github.com/YOUR_USERNAME/movie-data-analysis.git


Install required libraries:

pip install pandas numpy matplotlib seaborn requests beautifulsoup4 wordcloud


Open Jupyter Notebook:

jupyter notebook


Run the notebook step-by-step.

🎯 Key Insights

Top distributors account for most of the box office revenue.

Major production companies consistently release high-grossing movies.

Revenue spikes during holiday months and festival seasons.
