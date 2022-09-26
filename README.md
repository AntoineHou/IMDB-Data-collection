# IMDb dataset 

These scripts manage the download, parsing and handling of datasets collected from public IMDb resources. 

# Files

The files contained are a collection of script for downlading, handling and parsing data comming from the API Dojo's IMDB API. 
The collection conducted in our study concerned a sample of 496076 movies as well as the cast and crew (limited to a set of selected position) listed in the movie credit (composed of 3080140 individuals). 
All scripts are made available and data will be made available on the INDICIES repository. 

# Output description 

The scripts allow to download and parse data for the following endpoint : 

 -**Buisness** : Returning, for each movie, the budget and revenue of each movie (broken down by country where possible). 
 -**Metacritic** : Returns the metacritic score for both expert and standard users. 
 -**Rating** : Returns the vote repartition (between 1 and 10) for the categorie definied in enndpoint_rating file. 
 -**More like this** : Returns a list of recommended movie (15). 
 -**Credits** : Returns the list actors and crew members if they held a position a position listed in endpoint_credits. 
 -**Bio** : Returns for each Individual the following information : Name, Gender, Name, Age (and if the person is alive). 

# Complementary data 

The data can be complemented using the data dumps provided by IMDB and eventually using the following API (https://rapidapi.com/rapidapi/api/movie-database-alternative/) to gather (mostly) basic information for the different movies.   
