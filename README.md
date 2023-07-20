# Microsoft-venture-into-the-movie-industry
![image](https://github.com/EvangelineNgunjiri/dsc-phase-1-project/assets/133154189/b2ba97c1-089a-484b-8d38-07f040d4e759)

# <span style="color: blue; font-size: 24px;">Overview</span>

The project will primarily focus on the genres of movie films doing well in the industry at the Box Office. The goal is to provide the best recommendations to Microsoft for their new movie studio. As a result, this should guide Microsoft into making the most informed decisions through understanding of the films that are most popular in terms of performance in the industry. This will also bring in a competitive advantage into an already existing market.

# <span style="color: blue; font-size: 24px;">Business Problem</span>
![image](https://github.com/EvangelineNgunjiri/dsc-phase-1-project/assets/133154189/15bcfe78-79a0-4bea-9c80-ab57584cbc0f)



Microsoft is considering venturing into the entertainment industry, specifically movie creation. However, it does not have full information necessary to enter into the industry and be successful. Therefore, the aim is to provide relevant data that enables the company to acquire insights into the popularity of various films in order to venture the market successfully.

By the end of the analysis,one will be able to answer the following:
- Most profitable genres in the industry
- Most popular production studios
- Movies making most profits
- Preferred languages to enhance inclusivity

# <span style="color: blue; font-size: 24px;">Objectives</span>

The objectives of this project are:
- Research current film trends and analyze box office success of various movie genres.
- Identify the most profitable and popular movie genres in the market.
- Develop a list of recommendations for Microsoft's new movie studio based on the research findings.
- Present a comprehensive report of the research findings and recommendations to the head of the new movie studio.

# <span style="color: blue; font-size: 24px;">Data Understanding</span>


In this project, we will work with movie datasets which will provide the following information:
1. Movie titles
2. Movie genre
3. Year of production
4. Runtime for each movie
5. Domestic and foreign gross earnings

The data is contained in fie separate csv files
1. imdb.title.basics: each record contains the movie title, genre, start year and run time
2. bom.movie_gross: each record contains the movie title, start year, studio, gross and foreign earnings
3. tn.movie_budgets.csv: each record contains movie ID, release date, movie title, production budget, domestic and foreign gross earnings in USD
4. tmdb.movies.csv: each record contains genre IDs, original language and title, level of popularity, release date, movie title, vote averages and vote counts.
5. title_ratings: each record contains the movie title, average ratings and number of votes.

# <span style="color: blue; font-size: 24px;">Load the datasets</span>


Create a dataframes title_basics and movie_gross that represent the two CSV files. Use pandas methods to inspect the shape and other attributes of these dataframes.

# <span style="color: blue; font-size: 24px;">Data Cleaning</span>

For data cleaning, I examined the structure of my dataset and dropped unnecessary columns and rows to ensure there are no missing values. Also i merged various datasets into a single one to make it easier to do analysis and correlations.

# <span style="color: blue; font-size: 24px;">Merging of Data frames</span>

Creation of joins is necessary to ease analysis of data and investigate relationships.

# <span style="color: blue; font-size: 24px;">Analysis of the movie industry competitiveness</span>

In the cells below, i am going to analyse the competitiveness of the existing movie industry based on the cleaned and merged data above. I will look into the profitability of different genres, profitability per studio, and the ratings of genres.


# <span style="color: blue; font-size: 24px;">Budgeted domestic profit per movie</span>

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/5b355e0c-12ee-4657-a5f0-a486347f2e0b)

### <span style="color: blue; font-size: 24px;">Observation</span>

From the graph above, the bars represent the budgeted profitability while the line graph represents the production cost for the top 10 profit making movies. 
Beauty and the beast(an animation) is the number 1 profit making movie while shrek 2(also an animation) is number 10.

# <span style="color: blue; font-size: 24px;">Analysis of movies with the highest production budget against their domestic and global earnings</span>

In the cells below, i investigated the movies that cost the most to produce in order to check the correlation with their respective gross earnings.

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/9fae2dbf-a0d7-4642-9e05-17b927b2d275)

### <span style="color: blue; font-size: 24px;">Observation</span>
 From the graph above, Avatar has the highest worldwide gross earnings despite have a lower production budget.
 Dark Phoenix on the other hand, has the lowest worldwide gross earnings yet production budget is almost the same as that of the other movies. 

 # <span style="color: blue; font-size: 24px;">Analysis of genre against number of votes</span>

In the cells below, i shall analyse the popularity of genres against the number of votes.

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/77489cf9-b4c9-4073-85b9-3cc96661a678)

### <span style="color: blue; font-size: 24px;">Observation</span>

The top 3 most voted(most popular) genre of movies are (Action,Adventure, Sci-fi), (Action,Adventure, Fantasy) and (Adventure, Animation, Fantasy)

The least voted genre of movies are (Comedy, Drama),(Comedy) and (Drama,Romance)

# <span style="color: blue; font-size: 24px;">Analysis of earnings per production studio</span>

In the cells below, i shall look into the domestic gross earned per studios currently existing in the industry.

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/315ea010-e2a1-486b-a9c8-4bbfd3ffa23f)

### <span style="color: blue; font-size: 24px;">Observation</span>

From the graph above, the top 3 gross earning studios are BV, P/DW and WB(NL)
The bottom 3 gross earning studios are Par, MGM and Sum

# <span style="color: blue; font-size: 24px;">Analysis of popularity of movies per language</span>

In the cells below, i shall look at the popularity of movies in different languages.

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/e4de7a90-a325-4d3e-9a4a-6694ee4d9a4d)

### <span style="color: blue; font-size: 24px;">Observation</span>

It is necessary to diversify movie production to enhance inclusivity among people of different races and areas dominated by other languages apart from English. 
From the graph above,besides English, the top 3 most popular languages are fr, ja, and es.
The least 3 popular languages are sv,da and hi

# <span style="color: blue; font-size: 24px;">Conclusion</span>


**1. Diversify movie languages**- Apart from English dominated areas, there are other niche markets that are dominated by other langauges. It is important for the movie industries to prioritize inclusivity for all people and races.

**2. Encourage audience feedback**- Microsoft can do this by asking the audience to rate the movies based on their preference or create a survey to enhance decision making.

**3. Focus on popular genres**- Microsoft should emphasize production of popular genres, that is, those with high ratings or with the most vote counts.

**4. Collaboration with successful production studios**- Microsoft should consider joining forces with the top earning production studios to create content that is popular to the audience.

**5. Incorporate technology to their data analysis**- Microsoft should continue to implement and incorporate technology-based data anaysis to do current analysis and predictive modelling of data.
