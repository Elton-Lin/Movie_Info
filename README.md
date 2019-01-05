# Movie_Info
Utilizing google custom search engine to create a narrower movie search results and its api client to scrape the results for essential information for a movie search - poster, rating, reviews, wikipedia page, and trailer, and display them with a table.

To be improved upon: 1. Search an array of movies and display rows of results. 2. Display part of the content instead of only the links.
## Setup
1. Install Jupyter Notebook (with Anaconda) or use the online version: https://jupyter.org/index.html
2. register a Google JSON API Key: https://developers.google.com/custom-search/v1/overview (including pricing for over 100 search/day)
3. Clone or copy the lines in [movie_info.ipynb](/movie_info.ipynb) and run the main program, sample code is provided on the bottom.
**Note: In the code, replace 1. local path in convert_image() 2. api_key 3. Movie title, accordingly**

## Libraries 
Make sure to install the necessary libraries, e.g. 
```bash
$ pip install --upgrade google-api-python-client
```
Apply the same command for other libraries that are used in [movie_info.ipynb](/movie_info.ipynb)
## References 

Google Custom Search Engine(CSE):
- Website: https://developers.google.com/custom-search/
- Useful docs for parsing search result: https://developers.google.com/custom-search/v1/cse/list

Google API Python Client:
- Official github: https://github.com/googleapis/google-api-python-client
- Implementation: https://www.youtube.com/watch?v=ScdA3q9y2Y8&t=321s

Embed Image Into Table:
- https://stackoverflow.com/questions/47113934/how-to-display-table-with-text-and-images-in-jupyter-notebook

Pandas Library (For The Table): 
- https://pandas.pydata.org/pandas-docs/stable/api.html#style
- DataFrame: https://www.tutorialspoint.com/python_pandas/python_pandas_dataframe.htm

