# Phase 1 Project
![studio_picture](https://macksennettstudios.net/wp-content/uploads/2021/02/What-does-a-film-studio-do.jpg)
The above diagram is a film Studio
## Project Overview
The objective of this project is to analyze the film industry and provide actionable insights to the head of Microsoft's new movie studio on the types of films that are currently performing the best at the box office, as well as the current producers and writers who have experience in producing successful movies. Additionally, we will investigate the relationship between the budget, profits, and revenue of the film industry, and provide recommendations on the optimal budget and runtime for film productions.
To achieve this objective, we will analyze provided datasets on movie box office performance, including genres and revenue. We will also analyze data on successful producers and writers, including their track record and the number of successful movies they have produced or written.
We will also investigate the relationship between the budget, profits, and revenue of the film industry to provide insights into the optimal budget for a film production. We will analyze the data to determine the typical budget range for successful movies and identify the factors that contribute to a successful movie's profitability. We will also provide recommendations on the optimal runtime for film productions based on our analysis of the data.
Basically, at the end of the project the staff at Microsoft's new movie studio should comprehensively understand the current state of the film industry and have actionable insights to guide their decision-making when creating new movies.

## Business Understanding
Microsoft wants to enter the movie industry by creating a new movie studio, but they lack knowledge and expertise in the field. They recognize the trend of big companies creating original video content and want to capitalize on the opportunity. To achieve this, they need to understand the types of films that are currently successful at the box office and translate those findings into actionable insights that can guide the development of their own movies. The goal is to identify the most lucrative film genres and themes to maximize the success of their new movie studio. The actionable insights to add on to the currently successful films include a queries to the datasets that are set to find out the current producers who have experince in producing successful movies, same to the writers who have had a good number of their works turned into successful films, the relationship between the budget, profits and the revenue, the recommended budget and the recommended runtime.  
## Data Understanding and Analysis
### Source of data

They are movie datasets from:
   * [IMDB](https://www.imdb.com/)
   * [The Numbers](https://www.the-numbers.com/)
### Description of data
 The data sources for this analysis will be pulled from the following data files
`im.db.zip`
**Contents:**
   ![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)
**Format** - It is formatted in a database with the above tables.
        
`tn.movie_budgets.csv.gz`
**Contents:**
The dataset contains the following columns id, release_date, movie, production_budget, domestic_gross and the worldwide_gross.
            * **Format** - The values are comma separated thus a CSV file.     

### The visualizations
#### Query 1  
* ![Genre_vs_Average_Rating](https://github.com/Muramati/File-hosting/blob/main/Movie%20Vs%20Average%20Rating.png?raw=true)
* ![Director_Name_vs_Average_rating](https://github.com/Muramati/File-hosting/blob/main/Director_name%20vs%20Total%20Average%20rating.png?raw=true)
* ![Writers_name_vs_average_Rating](https://github.com/Muramati/File-hosting/blob/main/Writers_name%20vs%20Average_rating.png?raw=true)

#### Query 2
* ![Production_budget_vs_Total_Revenue_and_Profits](https://github.com/Muramati/File-hosting/blob/main/Production%20budget%20vs%20Totol%20Revenue%20and%20Profits.png?raw=true)
* ![production_budgets_vs_number_of_movies](https://github.com/Muramati/File-hosting/blob/main/production_budgets%20vs%20number%20of%20movies.png?raw=true)

#### Query 3
* ![runtime_minutes_vs_number_of_movies](https://github.com/Muramati/File-hosting/blob/main/runtime_minutes%20vs%20number%20of%20movies.png?raw=true)

## Conclusion
### Query 1
* From Query 1's first plot the company should consider genres and genre combinations on the X axis as a good place to start as they have a good average rating and are more likely to succeed.
* From Query 1's second plot the company should hire the directors on the X axis as they have more experience in creating high rating films.
* From Query 1's third plot the company should hire the writers on the X axis as they have more of their works made to high rating films.

### Query 2 
* From Query 2's first plot the scatter plot 2.4.1 shows that the more the production money the more the total gross revenues and gross profits the company will get.
* From Query 2's Second plot the histogram shows the mean production budget which indicates that most shows have a budget of $34M. The scatterplot tough in the latter point strongly stipulates that films with budgets going into hundreds of millions tend to be more successful in terms of profits.

### Query 3 
* From Query 3's plot the findings are that most shows ran approximately by measures of central tendency to a maximum of 90 minutes and the recomendation to the company would be to see to it that their runtimes are within that number where mos companies keep them so that they can allign themselves with already successful companies.