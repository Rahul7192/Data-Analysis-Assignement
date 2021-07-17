# IMDB ASSIGNMENT

You have the data for the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. In this assignment, you will try to find some interesting insights into these movies and their voters, using Python.


### Profit Analysis

  * Created a new column called profit which contains the difference of the two columns: gross and budget.
  * Sort the dataframe using the profit column as reference.
  * Extract the top ten profiting movies in descending order and store them in a new dataframe - top10.
  * Plot a scatter or a joint plot between the columns budget and profit and write a few words on what we observed.

![IMDB1](https://user-images.githubusercontent.com/72228043/126030079-2c533a99-c1ff-4e74-94c5-de928501e6fa.png)



We observed from the Scatter Plot,

* That the average profits of all the movies are in the range of 0-200 Million$.

* Some of the movies that are in the negative profit zone doesn't mean that they are performing bad but they might be performing good outside USA. We can manually check their Gross profit worldwide and conclude.

### Run Time Analysis

![IMDB2](https://user-images.githubusercontent.com/72228043/126030136-6e5be50e-e30a-4967-b74e-4d7c2c23d3c2.png)


  * Most of the movies appear to be sharply 2 hour-long.

### Demographic Analysis

  #### Genre Counts
  
  ![IMDB3](https://user-images.githubusercontent.com/72228043/126030201-ceba4875-e8ab-4ec2-93c5-edb07c4cd18a.png)
  
  * We can clearly see that director are more inclined towards Drama more than others.

#### Gender and Genre

![IMDB4](https://user-images.githubusercontent.com/72228043/126030297-230a27da-fb62-42f6-877c-c3aab808a739.png)


Sci-Fi appears to be the highest rated genre in the age group of U18 for both males and females. Also, females in this age group have rated it a bit higher than the males in the same age group. What more can you infer from the two heatmaps that you have plotted? Write your three inferences/observations below:

* Inference 1: Age ranging 45 & Above have given lower votes irrespective of the gender.
* Inference 2: Animation genre is being loved pretty much by the Female group when compared with the counterpart.
* Inference 3: Male aged between 18-29 loved watching the movies compared to the Female counterpart.

#### Top Genre(Top 1000 Votes for Top 10 Genre)

![IMDB5](https://user-images.githubusercontent.com/72228043/126030352-e412559e-3762-442d-8839-af78bc3e6c14.png)


* The Thriller genre is being voted least by the top 1000 voters.
* Action genre is being loved by a max. chunk of people among the top 1000 voters.



  
