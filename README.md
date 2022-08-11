# ETL with Wiki and Kaggle Movie Data

## Overview of Project
Data is awesome! And there is so much of it out there to analyze. There is a great amount of exploration into truth that can be accomplished through data science. But in order to get to that truth, the raw data first has to be organized so that it can actually be read. Data comes from a plethora of sources. Depending on the industry and the project, data harvested for research can be either relatively clean or pretty dirty. Extract, transform, and load (ETL) is the process by which data scientists harvest data, clean it up to be presentable, and then load it into databases for wide-spread use. ETL is the goal of module 8 of the DU Data Analytics bootcamp.

### Purpose of Project
The specific purpose of this week's module is to harvest data associated with movies in an effort to determine if through data science, an accurate understanding can be obtained about what really makes movies widely popular. If we can understand what makes movies popular, we can also build an algorithm that might give a hint as to what movies might grow in popularity in the future. In this module a psuedo-company is seeking to purchase low-cost streaming rights for movies that will eventually become household favorites. Nothing like a little financial margin to motivate the data scientists!

## Analysis and Challenges

### Analysis of Outcomes Based on Project
What an amazing library of movies! And all of this data to go with it! Over six thousand movie titles and associated information was loaded into a local database. The data was extracted from multiple sources. Each dataset was transformed in Python (Pandas), resulting in easy to read tables that could be merged together to create a single dataset of movie ratings. This allows for incredible amounts of analysis on the correlations to genre, release date, movie budget, overall view ratings, and more.

### Analysis of Outcomes Based on Challenges and Goals


### Challenges and Difficulties Encountered
This module had a lot of information in it: learning the ETL process, overcoming large data storage hurdles, gaining an understanding of regular expressions (regex), and then finally migrating data into Python (Pandas) and then out into a SQL database.

Realistically, I've been doing ETL for a long time without actually having the correct nomenclature for it. Anyone who routinely works with datasets has to perform ETL on some basic level. The exciting challenge of this week's module was to continue learning to transform data in Pandas, which is <i>so much better</i> than using another more basic tool like Microsoft Excel; and then the additional challenge of loading that transformed data into a real database (SQL table). This is INCREDIBLY useful so that not only do I have a reliable clean data source that I can reuse, but I can also share that data source.

This week featured some larger datasets, which provided an initial hurdle of storage solutioning in GitHub. The site rules only allow for files of a certain size, and to overcome that, they have an upgrade solution for Git-LFS (large-file-storage). I had a few hiccups with the initial setup overwriting some of my files, but once I nailed down which files to load into the lfs and others to ignore, it was an easy solution.

Then came the challenge of using regular expressions (regex). We have definitely reached the point where just "glancing" at the code could make most people's eyes widen and come to some conclusion about the impossibilities of reading coding languages. <i>But</i> the documentation is extremely helpful, and once you begin to understand the rules things become manageable. The key is to build small bits of regex code to perform the task that you desire, and then to fine-tune it by expanding out some options.

Learning how to convert dates and times into something that can be used in calculations was especially valuable to me as that is something that I use in financial modeling and reporting pretty consistently. The explanations of which formatting to use were logical, but I can definitely see how there are varieties of solutions here that could be explored based on the datasets and eventual users.

## Results
I am beyond thrilled to have gotten deep into the learning curve on the ETL process. This is something that I have been looking forward to from the beginning and I can't wait to implement what I've learned in this module to the data structures I deal with at work. This will make my current role of financial reporting and analysis much more in-depth and give me a grander opportunity to contribute to my company's future growth.