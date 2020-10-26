# Data Analysis on Film Industry
Student Names: Adina Steinman, Chinh Ho, Andrew Banner

Instructor Name: Yish Lim

# Applications Used:

Data Science Tools Used:

* Jupyter Notebook
* Pandas 
* Plotly Express
* Matplotlib
* Seaborn
* APIs

Websites used:

* https://www.themoviedb.org/
* TMDBSimple

# Our Data 

The Movie Database (TMDb) 

* Used API call to retrieve movie data in JSON format

Utilized two groups of data from the API:

* Top 100 movies from 2019 with the highest revenues
* Dataset of 10,000 movies, across all years, sorted by popularity 


# Insight #1: Voter averages and Revenue

![Screen Shot 2020-10-25 at 7 06 53 PM](https://user-images.githubusercontent.com/72099238/97122672-90f97c00-16f5-11eb-92e6-71c62a08f191.png)

* Films with higher revenues tend to have higher voter averages
* Popular films generally have voter averages that are higher than 5.0 on a 1-10 scale

# Insight #2 : Revenue Conclusions

![Screen Shot 2020-10-25 at 7 11 07 PM](https://user-images.githubusercontent.com/72099238/97122727-12510e80-16f6-11eb-8361-3e16ebd284ff.png)

* Analyzing films with the highest revenue for 2019
* Relationship between budget and revenue is positive
* The highest revenue films typically have the largest budgets.
* Revenue is not typically correlated to Return on Investment

** Return on Investment 

![Screen Shot 2020-10-25 at 7 15 49 PM](https://user-images.githubusercontent.com/72099238/97122815-9c997280-16f6-11eb-9af4-f44943f4f785.png)

* Films with highest budgets do typically have largest revenues.
- Although films with  the highest budget typically do have the highest revenue they do NOT have the highest return on investment. 

# Insight #3 : Return on Investment continued

![Screen Shot 2020-10-25 at 7 18 56 PM](https://user-images.githubusercontent.com/72099238/97122892-f306b100-16f6-11eb-9e0f-c164610de17f.png)

- Parasite was movies with highest ROI for 2019. 
- Budget of just over 11 million
-ROI factor of over 22.
Avengers: End Game was highest in both revenue and budget only had a ROI of 7.85.
-Revenue and ROI are much different measurements in terms of financial investments

** Release month:

![Screen Shot 2020-10-25 at 7 19 25 PM](https://user-images.githubusercontent.com/72099238/97122912-1af61480-16f7-11eb-8df2-6c23a43fcbc9.png)

* Histogram detailing the average revenue per movie for each month in 2019
* April is the highest followed by July.
* The summer and holiday seasons are prefered release dates in terms of revenue.
* Summer and holidays are typically when the highest budget movies are released.

# Insight #4:  Correlation between Genres & Popularity

![Screen Shot 2020-10-25 at 7 32 52 PM](https://user-images.githubusercontent.com/72099238/97123306-424de100-16f9-11eb-8abc-9bef778efecd.png)

* Drama is the most popular and appeared over 2200 times.
* TV_Movie is the least popular and only appeared 5 times.
* Top 4 popular genres of movie are : Drama, Comedy, Action,  Thriller.

# Conclusions: 

* Popular films with higher revenue have higher vote averages
* While budget and revenue are positively correlated, high budgets does not necessarily mean a high return on investment.
* Microsoft should look at the impact of budget on both revenue and ROI when making budget and investment decisions  
* Microsoft should consider creating movies with popular genres; Drama, Comedy, Action and Thriller





