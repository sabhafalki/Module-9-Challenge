# Module-9-Challenge  Surfs_up
Advanced Data Storage and Retrieval with Jupyter Notebook, SQLite and SQLAlchemy

# Overview of Project #
The purpose of this Project is to analyze the weather trends in Oahu,Hawaii to open a Surf and Shake shop that severes surf boards and ice cream to tourist and if the shop on Oahu does well, they could expand to other islands. Specifically, summary statistics of temperature trends data has been requested for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round.

The analysis consisted of the following:
1. The Summary Statistics for June
2. The Summary Statistics for December

# Resources #

- Data Source: hawaii.sqlite
- Programming Files: SurfsUp_Challenge.ipynb, climate_analysis.ipynb
-	Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, pandas, numpy
- Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

# Results #
## The Summary Statistics for June ##
To Extract the three data files (wiki, kaggle, movielens). MovieLens is a website run by the GroupLens research group at the University of Minnesota. The Kaggle dataset pulls from the MovieLens dataset of over 20 million reviews and contains a metadata file with details about the movies from The Movie Database.<br>

The following depicts the wiki_movies_df DataFrame:<br>
![Movie_DataFrame](/Image/Wiki_Movies.png) <br>

The following depicts the kaggle_metadata DataFrame: <br>
![MataData](/Image/kaggle_metadata.png) <br>

The following depicts the ratings DataFrame: <br>
![Ratings](/Image/Rating.png) <br>

##  Extract and Transform the Wikipedia Data ##
Filtering out bad data is important, in order to get good clean data and a cleaned Wikipedia data is converted to a Pandas DataFrame for clear view.<br>
The following depicts the columns from wiki_movies_df DataFrame to a list:<br>
![wiki_movie](/Image/to_list.png) <br>
<br><br>

## Extract and Transform the Kaggle data ##
The extraction and transformation of the Kaggle metadata using the ETL function and performe the merging of Wikipedia and Kaggle DataFrames. <br>
![wiki_movie](/Image/Wiki_Movies.png)<br>
<br><br>

## The Movie Database ##
The Movie DataFrame consist of the movies table and ratings table in the SQL database, by adding elapsed time to the database.
The following depicts the movies table in SQL database.<br>
![movies_query](/resources/movies_query.png)<br>
The following depicts the ratings table in SQL database.<br>
![ratings_query](/resources/ratings_query.png)<br>
<br><br>
