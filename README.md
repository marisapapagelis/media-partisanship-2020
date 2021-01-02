# Predicting Media Partisanship in Relation to the 2020 U.S. Presidential Election
Facebook is becoming an increasingly popular distributor of political news, especially among younger generations. As the 2020 U.S. presidential election approaches, news outlets are reporting on a variety of political topics, and their readers are interacting with them on a widespread scale. This project uses these ideas to conduct an investigation into the most frequently discussed political topics across partisan and nonpartisan news sources on Facebook and builds a classification system to predict partisanship of news posts. To accomplish this, the code for the project uses Selenium with Chromedriver and BeautifulSoup to scrape, store, and parse publicly accessible posts on Facebook, and the NLTK package for Python to create a supervised classification system.

## Authors
* Marisa Papagelis [(marisapapagelis)](https://github.com/marisapapagelis)
* Natalie Reid

## About
* This code was written using Jupyter Notebook. 
* This project served as a cumulative project for our Data and Text Mining and Misinformation course at Wellesley College (Fall 2020).

## Navigation Instructions 
‘PM6_MarisaPapagelis_NatalieReid’ contains all of the data files collected/
generated and all of the notebooks created for this research project.

In order to replicate our process on a personal computer, the file path for all
JSON files may need to be altered. For easiest access, move the
'PM6_MarisaPapagelis_NatalieReid' folder, containing all of our work, to your
desktop, and the given file paths should work.

Below is a legend to help with navigation through the folder:

* Python Notebooks - this subfolder contains the two notebooks we created,
one to collect our data and one to explore/analyze our data.
- Final_Collecting_Data_CS315_Project_MarisaPapagelis_NatalieReid
.ipynb - in this notebook we collect our data by scraping the likes,
comments, and text of Facebook news pages and saving them to
JSON files for later use.
- Final_Exploring_Data_CS315_Project_MarisaPapagelis_NatalieReid.
ipynb - in this notebook we perform the load of our project with a
thorough thought process, test explorations, final explorations,
analysis, and supervised classification models. (Some of this analysis
ended up in our paper and some of it was exploratory and did not
make it.
* HTML pages - this folder contains 9 HTML files, each corresponding to one
of the news sources explored in the project. The HTML files were used
during data collection to save news page content to be parsed through later. 
**This folder is not included in GitHub version as it is very large**
* JSON files - this folder contains 9 JSON files, each corresponding to one of
the news sources explored in the project. The JSON files were created
during data collection to store data frames of scraped data, and they were
used in data exploration to import the data for exploration and analysis.
