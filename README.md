# PHASE_1 PROJECT
![pexels-donald-tong-66134](https://user-images.githubusercontent.com/125992952/224551945-3b281375-25aa-48a1-adea-da571499cc3b.jpg)

## Project Information
Susan Warigia
Data Science Fulltime
6/03/2023 - 12/03/2023

William, Nikita & Lucille

## Business Problem
Microsoft wants to get into Film making and they've decided to create a new movie studio.They don’t know anything about creating movies. Given the data, explore what types of films are currently doing the best at the box office.Translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Data Used was from
Box Office Mojo
IMDB Data
The Movie Database
Problem Solving Plan
#### Data Cleaning
Data Analysis and Data Visualisation
Summary
Importing of Libraries
## import the libraries

## DATA CLEANING
- checking for missing values
- replacing the missing values with the median
- checking for duplicates
- checking for extraneous characters and values
- changing Datatypes to make for easy merging
- getting the central measures of tendancies
- checking for outliers using Interquartile Range

### Merging the clean DataFrames into one clean Dataframe
- Merged df1 and Df2 to make bom_tmdb
- Merged bom_tmdb with movie_budgets_df3 to make three_combo DataFrame

## Sqlite3
- Import sqlite database to Pandas
- Data cleaning process

## DATA ANALYSIS AND VISUALISATION
#### GROSS PROFIT AND GROSS PROFIT MARGIN

- Used the gross profit to determine the company's gain from the movie production
- The profit margin was to show the efficiency of the profits to the company
- Calculating Worldwide Gross Profit and Gross Profit Margin
### profit gross analysis
![Gross profit and earnings](https://user-images.githubusercontent.com/125992952/224552071-65486276-ba11-42f4-b1e7-057b311607cd.png)

- The worldwide gross is significantly much more than the domestic gross and is it can be seen even for the profit generated after selling worldwide is much greater.
The cost of production doesn't change regardless of where the movie will sell.

#####  profit gross analysis recommendation
- The movie made should target the global market to maximize on the profit since even when the market was domestic the cost of production remained the same.

### Return On Investment
- Return On Investments will help compare the potential profitability of different investment in this case being Movies production.
![ROI Analysis](https://user-images.githubusercontent.com/125992952/224552096-fc154521-a5a0-4065-bd03-59c54965fb7d.png)

###### ROI Analysis

- The Return On Investment was not high.
This is by comparing the cost of production of a movie and the gross profit made after selling both domestic and globally.

##### ROI Recommendation

- The studio should maximise on marketing so as to increase the worldwide gross sales; no matter how high the cost of production, the studio will make more Return on Investment.

#### Genre Rating
- This will help get the best rated genre to compare with their production budget

![Genre Ratings](https://user-images.githubusercontent.com/125992952/224552011-0efc283a-43d1-4800-8130-4978952fa9a9.png)

###### Genre rating analysis
- The highest rated genre is pure drama and this would only mean it the most prefered genre by the views.

###### Recommendation

- The studio should consider producing a genre that is highly prefered as that will sell easily and will sell more.

#### The Best 50 Movies

- This helps the firm get a preview of how much a movie made and what they did unique

![Best 50 movies](https://user-images.githubusercontent.com/125992952/224552157-282661af-69e4-4462-b6ea-bd2dd2a75990.png)

##### Best movies Analysis

- Avengers: Infinity war was the most profitable movie. Its cost of production was equally high and after the sales the profit matgin was high as well. The cost of production being high couold have been led by producers trying to produce the best quality they could which ended up making high profits.

##### Recomendations

- The Micrsoft studio can capitalize on making a good quality movie as it may lead to increased sales and hence better profit margins.

# SUMMARY

- With the data provided it is possible to know the viewers preferences by analysing the viewers ratings. The data also helps analyse the profits and losses made by the movie thereby we are able to tell whether it worth venturing into the movie production. By the end of the analysis we have been able to tell which is the best movie genre to start with and what was the profits made by the best selling movie. It is a field worth the trial.
