---
layout: post
title:      "Profitable Microsoft Studios Analysis"
date:       2020-08-04 14:37:07 +0000
permalink:  profitable_microsoft_studios_analysis
---


The complete blog can be found in the url below:

https://medium.com/@khuloodnasher72/profitable-microsoft-studios-analysis-by-khulood-nasher-d15a310098e2


In an effort by Microsoft to diversify its investments, they decided to invest in the film industry, and since Microsoft is keen on implementing its plans professionally, they have decided to employ a data scientist whose job is to explore the data of the movie industry, analyze it and set recommendations based on the outcomes of the analysis. The data scientist conducted a comprehensive analysis of the movie’s data and set a couple of recommendations to what types of movies could be profitable at the box office. The data scientists set the findings based on many factors such as the genre, the season, the production budget, and the length of the movie. The data scientist ended up with informative visualized recommendations for the executive director of Microsoft.
The following Questions were addressed:
1- How has the movie industry changed in the last decade from 2008–2018?
2- What production budget range is more profitable for movies?
3- Which season is the most profitable?
4- What are the most successful genres?
5- Which genre is the most profitable for each season?
6- Does the runtime have any effect on the popularity of the genre?
Data Sources:
The data was collected from the following GitHub repository:
https://github.com/khuloodnasher/dsc-mod-1-project-v2-1-onl01-dtsc-ft-030220/tree/master/zippedData
Data Processing
Pandas library was used to read the data as data frames that are stored in the files:
‘tn.movie_budgets.csv.gz’
‘Imdb.title.basics.csv’
‘tmdb.movies.csv.gz’
Tables of movie data were merged and the most correlated features were extracted and processed.
Features that were analyzed go as follows:
Movie name, genre, release date, runtime, production budget, worldwide gross, and domestic gross.
