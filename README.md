# InfoViz
Top Trending Google Search Queries

Significance:
One of the main figures in the project is a word map visualization of the most trending ‘Google’ queries. Word map is a ranking visualization in which each word’s font size is based on its weight. Google is the number 1 search engine of the world and hence analyzing the search trend helps in optimizing SEO strategy. It tells a keyword, search category popularity country wise. This data can be very helpful in refining a marketing strategy and campaigning.

Findings: 
•	Queries like ‘Whitney Houston’, ‘Gangnam Style’, ‘Amy Winehouse’, ‘Paul Walker’ and “black Panther’ are among the most popular search queries on Google.
•	Among the categories ‘People’ is one the most favorite category that are often searched
•	Under ‘Search’ category ‘Gangnam Style’ is the most frequently searched song and the next frequently searched query’s frequency in this category is quite low as we cannot even see it in the graph. Same goes for ‘Game of Thrones’ in ‘TV Shows’ category.
•	Word graphs are quite resourceful when it comes to determining the top items

Limitations: 
•	Same query can fall under multiple categories and hence while plotting a word in a word cloud highest frequency category among top 7 categories is selected. 
•	Since word cloud use relative sizing, therefore there is a limit on how many words can be effectively displayed in it and that’s why we can see only 7 categories legend. 
•	There are some popular queries which are not a part of final figure as they do not belong to top 7 categories.

Data:
The dataset used for this project has been taken from ‘Kaggle’. It’s a dataset of Google search trends over the years 2001 to 2020. Every year, Google releases the trending search queries all over the world in various categories. The data has been consolidated from these reports.

Method:
•	Top 1000 searched queries in the top 7 categories word map:
I’ve used search query frequency as its weight to adjust font size of queries and hence, the bigger the font the more frequently searched it is. Words are color coded as per their category. For plotting a clear graph top 7 categories were selected and then queries under them is used for the word cloud. The dataset used here, contains 2450 categories, and has data from the year 2000 to 2020. The color in the graph indicates the category of the query. Each category is symbolized with a unique color.
•	Top 1000 searched queries in the top 7 categories frequency graph: 
In this graph each query is categorized and visualized w.r.t average search frequency of the category and hence, an aggregated dataset is required for this visualization. Data is aggregated based on the top 7 categories. 


