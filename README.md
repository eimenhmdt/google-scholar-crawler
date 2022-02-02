# Google Scholar Publications Crawler

This crawler allows you to define a list of scholars for which it then creates a CSV file of all the scholars' publications listed on Google Scholar.

Currently, the following information per publication will be crawled automatically:

1. Author
2. Title of Paper
3. Publication Year
4. Number of Citations
5. Number of co-authors
6. Citations per year -> Creates a column for each year during a specific time span. The span can be defined as needed.

## How it works

I would suggest running the crawler in Google Colab (https://colab.research.google.com/)

1. Create a list of scholars for which you want to crawl their publications.
2. Make sure they have a Google Scholar profile and that the names in the list match the names in the Google Scholar profiles.
3. Paste the names into the 'author_names' list in the code file.
4. Optional: Edit the crawler as you see fit.
5. Install the "scholarly" module.
6. Run the crawler!

You can interrupt the crawler's runtime. As long as the CSV file is still in the directory, it will continue where it left off when you restart it.


## License
[MIT](https://choosealicense.com/licenses/mit/)
