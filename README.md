# Trainity_IMDB-Movie-Analysis

## DESCRIPTION
The Project is based on IMDb data records to gain meaningful insights from raw data of movies which can be useful  for movie recommendation process and to study nature of audience  and their preference. Furthermore, it answer the critical questions  which help in finding of user & critics favorite genres, actor, top  directors etc.

## APPROACH
1. To perform Analysis on data records I begin with choosing right column and extracting it for further cleaning process
2. After cleaning, filtering and sorting the dataset, it time to process  the data,
3. Here I use excel function such as advance filter, Text to column, mathematical function, Pivot Table etc. and apply different combinations and visualize it to understand it better.
4. Expect cleaning process all analysis is done by using Pivot table and basic excel function

## CLEANING THE DATA
1. Extracted & arranged required column by using cut , copy & paste function
2. Removed extra 'Â' character from movie title column
3. By using 'Remove Duplicates' function drop 112 duplicate rows   (to check duplicate I use movie title, director name, imdb score, actor_1, Actor_2, actor_3, budget column)
4. Checked Missing values and took appropriate action to each column
5. Calculated absolute number of missing values with ‘Countblank' function for each column and calculate percentage of null values per column

NOTE : Misleading values present in gross & budget column (difference in  currency such as….. budgets col recorded in Yuro, INR, won, etc. and gross col  recorded in US dollars)

## FINDINGS
1. PROFITABLE MOVIE
2. IMDb TOP 250
3. BEST DIRECTOR
4. POPULAR GENRE
5. USER VOTE OVER DECADE

## INSIGHTS
1. There are some tv shows’ records and web series' records present in dataset
2. Content type which related to TV shows and OTT based web series and shows are missing  Gross and Budget Amount also Directors’ name , may be because of it changes with per episode
3. All Top 10 highest grossing movies are high budgets movies
4. Most of Top 10 most profitable movies are documentaries or individual movies
5. Avatar is highest Grossing movie with 760+ million USD and Paranormal Activity is most profitable movie ever with 719348.55 % profit.
6. Top 250 movies in English and other language movies have content type ‘R or PG-13’


