# Project1
Data Analyst
Benson Kinyua
## a) Business Understanding.
A film production company creates, produces and markets long- or short-form film or video content. As the owner of a film or video production company, you’ll create, produce, market and find distribution for digital or analog film or video content. This might take the form of movies, television programming, documentaries, industrial films, commercials or other related work. The film industry is a complex and multifaceted ecosystem that includes various stakeholders such as producers, directors, actors, and distributors, among others. Despite its massive contributions to the entertainment sector, it faces numerous challenges that pose significant threats to its sustainability.
This project seeks to explore what types of films are currently doing the best at the box office, then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create. Pre-production is when you should be working with your team to solidify the structure of your story. Pre-production is the time to research and understand exactly how much money you need to finance each stage of the filmmaking process. You want to think about actors, crew, costumes, catering, equipment, location rental, and any special permissions you’ll need for filming.
 The production stage, also known as principal photography, is when all the actual shooting and recording happens — with cameras, actors, and location licenses. For many, it’s the most exciting part of the filmmaking process.
Post-production is where all of the pieces of your film come together. It involves various post-production techniques including editing, color grading, and visual effects to turn your raw footage into a finished film.

In the post-production stage, you can do things like add lens flare to sci-fi shorts, flying digital doubles in fight scenes. You’ll also be streamlining all your jump cuts and high-speed chases into the perfect action sequence.

### b) Problem Statement
One of the most significant creative challenges facing the film industry today is the lack of originality. Many movies released by studios are either sequels or remakes, rather than original content. While sequels and remakes can be profitable, the overreliance on them has led to a lack of diversity in the industry’s output. This is because studios often prioritize established franchises over new and innovative ideas, which can limit the range of content available to audiences. The project seeks to investigate the current genres of movies that are doing well at the box office, so that the movies produced can be profitable to the movie studio.
### c) Main Objective
This project seeks to explore what types of films are currently doing the best at the box office, then translate those findings into actionable insights that can be used to decide what type of films to create.
### d) Specific Objectives
i)	To analyze the data set so as to come up with recommendations about the movies to produce.
ii)	To investigate whether starting and operating a movie studio is a profitable venture to pursue.
iii) To show whether the number of movies produced affect the total gross of the studio or it is the genre.

### e) Experimental Design
1. Data Collection
2. Read and check the data
3. Cleaning the data
4. Exploratory Data Analysis
5. Conclusions and Recommendations

### f) Data Understanding 
The data is from BOM which is one of the most popular movies site.
The dataset contains 3387 rows and 5 columns
|NO.| Column    |  Description|
|---| ---       |  ---          |
|1|Title|Movie Name|
|2|Studio|Production Studio|
|3|domestic_gross|How many local sales|
|4|Foreign_gross|How many international sales|
|5|Year|Production year|

The TN data has 5782 rows and 6 columns.
|NO.| Column    |  Description|
|---| ---       |  ---          |
|1|ID|ID|
|2|Release date|Date the movie was released|
|3|Movie|Title of the movie|
|4|Production Budget|How much the movie cost to produce|
|5|Domestic Gross|How many copies sold locally|
|6|Worldwide_gross|How many international sales|


The database from IMDB shows how the Movie Data is connected using primary keys and foreign keys. This project will use Movie_basics, movie_akas and Movie_ratings tables. The three tables have 73856 rows and 7 columns.
|NO.| Column      |  Description|

|1|Movie_id| ID|
|2|Primary_title|Title of the movie|
|3|Original_title|Original title of the movie|
|4|Start_year|Year the movie started|
|5|Genres|Category of the movie|
|6|Averagerating|rating|
|7|Numvotes|Votes the movie got|

## 2) Importing libraries

## 3) Reading the data

## 4) Connecting to the database

## 5) Tidying the Dataset
checking for duplicates.
searching for missing values.

## 6) Exploratory Data Analysis.
I took a sample of 15 genres from the data to establish which genres have the highest ratings.

Calculated the mean of every genre to find out which genres had the highest average ratings. This analysis shows that Documentary has the highest average rating of 7.3, Drama with 6.5, Adventure 6.3, Action 5,8 and comedy 5.8.

Calculating the total gross for the top 100 movies. These two visualizations show the number of movies produced by each studio and their total gross per studio. We see that universal produces the most number of movies but in terms of total gross Beuna vista leads.
# Recommendation
To answer Microsofts question about what is required to create and a own movie studio:
1) The movie studio industry is very lucrative if you look at the total gross per studio from 2010 - 2018 as we can see from the two visualizations. I would recommend that they start producing movies.
2) Looking at the genres, documentaries have high average ratings, followed by Drama genre with average rating of 6.5 and adventure genre with average rating of 6.3. I would recommend that Microsoft focuses on the production of these three genres. 
3) Total gross is not affected by the number of movies that you produce as a studio rather it is proportional to the ratings and the genres that you are producing. Therefore, I would recommend that Microsoft focuses on producing the movies with the highest ratings.

# Conclusion
The movie industry is a good venture to venture in, if done well in terms of the genre being produced. Microsoft should go ahead and develop the studio based on the recommendations that I have given them.
Movies with the highest rating do well since they are most watched and thus bringing more income to the studio.


The link to the Non-Technical presentation. https://www.canva.com/design/DAFkAOlf7T4/i8dQ3uLg-1OmhFzfdV8FwQ/edit





