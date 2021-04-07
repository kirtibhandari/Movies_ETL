# Movies_ETL
## **Project overview:**
Amazing Prime is an online streaming platform for movies and TV shows to its subscribers. This company intends to buy streaming rights of low budget movies which could become popular and hence increase their revenue. Through this analysis, company wants to know those movies. To perform this analysis, a robust and clean data set is required. This dataset will then be provided to seek a solution through participants of a Hackathon, which has been sponsored by Amazing Prime company. 
The purpose of this project is to extract, transform and store the cleaned dataset in an SQL database.
### **Resources:**
We have three files -- Wikipedia data, Kaggle metadata and the MovieLens rating data, which we need to use to prepare a cleaned dataset using a Data pipeline process - known as Extract, Transform and Load (ETL). This data is data of movies released since 1990 and their ratings.

#### **Brief about ETL process**
ETL is the core concept in Data Engineering which ensures that the data remains consistent and maintains its integrity. For any analysis to be possible, we need consistent and robust form of data. A well designed ETL pipeline strives to automate as much data wrangling as it can.

In this project, we have used Python and Pandas to perform our data wrangling of the available dataset and PostgreSQL to store our finished data.

## **Results:**
As a result of performing ETL process on the available data, a cleaned, consistent, robust data is stored in PostgreSQL as shown .

![](https://github.com/kirtibhandari/Movies_ETL/blob/main/Resources/movies_query.png)

![](https://github.com/kirtibhandari/Movies_ETL/blob/main/Resources/ratings_query.png)


