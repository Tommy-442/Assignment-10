# Assignment-10
## Project Overview: Netflix Data Pipeline with MongoDB & PyMongo
This project demonstrates how to design a simple data engineering pipeline using only Python, MongoDB, and PyMongo. 
The goal is to support the Data Science and Product teams of a global streaming platform by answering key business questions about content performance and user behavior.

The data originates from a cleaned Netflix dataset (netflix_cleaned.csv), which is first loaded into MongoDB (netflixDB.titles collection). 
From there, a series of aggregation pipelines is applied to extract insights such as popular genres, country-level trends, monthly content uploads, ratings distribution, and duplicate titles. Finally, results are automated and exported for further use in analysis or dashboards.
