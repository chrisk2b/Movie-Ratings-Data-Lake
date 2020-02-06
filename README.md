# Purpose of the Repository
This repository contains the results of the Data Engineering Nanodegree Capstone Project. Its’s purpose is to give the reviewers access to the code. For more information click [here](https://www.udacity.com/course/data-engineer-nanodegree--nd027).
# Summary of the Project

In this project we build a Data Lake on Amazon S3. We will use movie ratings data to illustrate the core concepts. The raw data will be stored in S3. Afterwards, we use Spark as an ETL tool to transform the raw data into a dimensional schema. AWS services like Glue are used to build a metadata repository. Based on the dimensional schema, one could use tools like AWS Athena to submit analytical SQL queries to answer questions like ‘how many users have watched a given movie’.

The project follows the follow steps:

-   Step 1: Scope the Project and Gather Data
-   Step 2: Build Different Layers of the Data Lake and Ingest Data
-   Step 3: Design the ETL Process to Transform and Load Data to Cleanse
-   Step 4: Define the Data Model for Analytical Queries and the Access Layer
-   Step 5: Assess Data Quality
-   Step 6: Build Metadata Repository
-   Step 7: Complete Project Write Up
# How to Use the Repository
All relevant information and the project steps outlined above are described and executed in the Notebook [Capstone Project](https://github.com/chrisk2b/Movie-Ratings-Data-Lake/blob/master/notebooks/Capstone%20Project%20.ipynb). The data dictionary can be found [here](https://github.com/chrisk2b/Movie-Ratings-Data-Lake/tree/master/data-dictionary).

**Important:** The ratings data in the [data](https://github.com/chrisk2b/Movie-Ratings-Data-Lake/tree/master/data) contains just a sample of the original dataset since the original can not be uploaded to GitHub due to its size (100M recodrs). In order to fully reconstruct the results, the original dataset needs to be downloaded from [here](https://grouplens.org/datasets/movielens/), cf. also the Notebook for details.

