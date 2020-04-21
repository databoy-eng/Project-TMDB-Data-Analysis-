# Investigate_Dataset_TMDB_Movies

### Project: TMDB Data Analysis

TMDB is the dataset originated from Kaggle to be used for this investigated research. That dataset contains over 10,00 movies gathered from The Movie Database(TMDB). Consisting of of 21 columns addressing areas as revenue, budget, and popularity.

The following segment provides the research questions that guided this exploratory analysis.

1) Which movie has the highest and lowest profit?
2) Is there a relationship between higher budgeted movies and more revenue?
3) What impact do user ratings have on proft?
4) Which genres demonstrates the highest profit?

### Datasets
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of dollars, accounting for inflation over time.


Data
Files
This project contains 2 files and 2 folder:

data.csv : The dataset file containing 10k+ entries of movies that I have worked on.
report.ipynb : The investigation of the dataset has been done in this jupyter notebook file.
export/ : Folder containing HTML and PDF file of notebook.
plots/ : Contains images of all the plots that are displayed in report.ipynb file.
Dataset file
This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as title, cast, director, runtime, budget, revenue, release year etc.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Nothing to care much of, I leave them as is.
The final two columns ending with “_adj" show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.
Loading Project
Requirements
This project requires Python 3 and the following Python libraries installed:

Python 3.6.5
NumPy
Pandas
matplotlib
seaborn
You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
