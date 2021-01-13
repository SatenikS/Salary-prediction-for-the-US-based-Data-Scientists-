# Salary-prediction-for-the-US-based-Data-Scientists-

Objective
In this project I am going to scrape job postings from Indeed and build a model to predict Salary Estimates for full-time Data Scientist, Data Analyst and Data Engineer roles in major cities across the US. During this project I am going to conduct an exploratory data analysis of the scraped data and understand what factors affect the salary estimates of the Data Scientist job postings. 
 
Ideally, I would predict the actual salaries advertised in the postings instead of the salary estimates, but very few of them have salary information. Indeed does not explicitly provide salary estimates for each posting, but has a filter that allows setting a desired minimum salary. By incrementally varying filtering criteria and recording the search results, we can infer the salary bracket of the job posting.
 
Features and target variables
Features:
1) City, State
2) Experience level
3) Position
4) Presence of specific keywords  in the job description (e.g. python, SQL, Spark, etc.)
Target:
Salary estimate (by Indeed)
 
Data Sources
1) [Wikipedia](https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population)

2) [Indeed](https://www.indeed.com/)
 
Used tools
1) BeautifulSoup
2) Seaborn
3) scikit-learn

Possible impacts on the project
The results from this project will help identify how different factors impact the salaries of data professionals. Identifying which keywords correlate with higher salaries can potentially help prepare a better resume when applying for roles.
