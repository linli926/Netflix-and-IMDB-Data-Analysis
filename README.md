*This project analyzes movie and TV show data from Netflix and IMDB to explore content trends and characteristics.* \
*Due to file size limitations, the raw data files are not included in this repository.*


## Netflix Dataset
https://www.kaggle.com/datasets/shivamb/netflix-shows/data
## IMDB Dataset
https://developer.imdb.com/non-commercial-datasets/

- `title.basics.tsv.gz`: Basic movie information\
tconst (string) - alphanumeric unique identifier of the title\
titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)\
primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release\
originalTitle (string) - original title, in the original language\
isAdult (boolean) - 0: non-adult title; 1: adult title\
startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year\
endYear (YYYY) – TV Series end year. '\N' for all other title types\
runtimeMinutes – primary runtime of the title, in minutes\
genres (string array) – includes up to three genres associated with the title

- `title.ratings.tsv.gz`: Rating data \
tconst (string) - alphanumeric unique identifier of the title \
averageRating – weighted average of all the individual user ratings \
numVotes - number of votes the title has received


