Complete this Project using you understanding of Hadoop, HDFS, Hive and Apache Spark to perform data management, storage, retrieval, and analysis. Do not answer questions using any other software or method. 
Dataset
**Download movielens.rar file.**
This file contains three data files.
1.	**u.data:**  A tab separated list of 100000 ratings by 943 users on 1682 items (movies).   Users and items are numbered consecutively from 1.  Column names are as following.
  user id  item id  rating  timestamp.
2.	**u.user:** A list of 943 user. Values in each row are separated by pipe sign |. Each row contains demographic information about the users under the following column names. user id | age | gender | occupation | zip code
3.	**u.item:** Information about the items (movies); this is a pipe sign separated list of: 
movie id | movie title | release date | video release date | IMDb URL | unknown | Action | Adventure | Animation | Children's | Comedy | Crime | Documentary | Drama | Fantasy | Film-Noir | Horror | Musical | Mystery | Romance | Sci-Fi | Thriller | War | Western | 
The last 19 fields are the genres, a 1 indicates the movie is of that genre, a 0 indicates it is not; movies can be in several genres at once. 
**Questions**
1.	Store the data in a Hive database ml as table userratings (u.data), users (u.user) 
2.	Write HiveQL queries to confirm the number of records in both tables. 
3.	Extract the list of top 10 items (movies) that received the most ratings (not necessarily highest rating) from female educators. 
4.	Find the highest rated Fantasy movie. 
5.	Load the u.data, and u.user files into Apache Spark as DataFrames named df_udata and df_uuser. Apply following queries. 
a.	How many unique occupations are in the data and what is the frequency of each occupation? 
b.	Find the number of recommendations corresponding to each occupation. 
**Instructions**
For each question, provide the steps, code in both text and image form. Take clear and readable screenshots of the shell commands along with the outputs. Attach or add results after each question.________________________________________


