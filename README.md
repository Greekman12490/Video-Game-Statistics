## Merit America Capstone Project - Video Game Statistics

This is my capstone project for Merit America. We had choices on what we wanted to do, and I decided to work on my own case study. Now I am a gamer and I wanted to do something that involved video games. So, I decided to look into the number of sales for individual video games sold throughout the years. When I mean years.... I mean decades. I gathered my information via Kaggle where I maniuplated the data using tools such as Google Sheets and Bigquery (SQL). I wanted to ask several question regarding the data I was looking at. One, I wanted to see which genre of video games did developers create the most and the least. Two, I wanted to see which region of the world sold the most and least games. And lastly, I wanted to see how the critics and consumers viewed said games based on score. 

## Analysis and Challenges

### Analysis 

#### Which genre of video games did developers create the most and the least?

When we maniuplate the data via any spreadsheet and SQL programs, we came to the conclusion that "Action" based games were created the most (3,370 out of 16,717). The least being "Puzzle" based games (580 out of 16,717). Please check the figures below for details

####  Which region of the world sold the most and least games? 

> **Please note, the numbers describe in this analysis are in millions**

Like before, when we maniuplate the data, North America sold the most copies of all genres combined (4400.84 out of 8913.64) and regions classifed as "Other" such as South America, Oceania, etc., sold the least amount of copies (791.26 out of 8913.64). Please check the figures below for details.

![Chart 1](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Video%20Game%20Total%20Sales%20Globally%20and%20Regionally.PNG)

#### How the critics and consumers viewed said games based on score?

> **Please note, critic scores are based on a scale of 0 (lowest) - 100 (highest) and consumer (user) scores are based on a scale of 0 (lowest) - 100 (highest)**

As we continue to maniuplate data, we wanted to see how critics and consumers rated games. Based on critics, the highest rated video game score in a select genre was a three way tie. "Action", "Fighting" and "Sports" all scored a 98. The lowest rated game in a select genre was "Racing" being at 13. When we average out all the scores of video games per selected genre for critics, the highest average genre would be "Role Playing" (RPG) at 72.653. The lowest average genre would be "Adventure" at 65.331. Based on the consumers, the highest rated video game score in a select genre is "Role-Playing" at 9.7. The lowest rated score in a select genre was "Adventure" with a measly 0. When we average out all the scores of video games per selected genre for consumers, the highest average genre would be "Role-Playing" at 7.620. The lowest average genre would be "Misc" at 6.819. Please check the figure below for details.

![Chart 2](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Video%20Game%20Genre%20Critic%20and%20User%20Ratings.PNG)

### Challenges

When I tried using Microsoft Excel, I made multiple sheets pertaining the maniuplation of data via formulas. When I saved an closed out the window. I decided to reopen the file to see if the work was saved adequately, to my demise, it wasn't. I made the decision to use Google Sheets instead. When I used BigQuery (Google SQL platform), I upload my file using the Google Drive. With this, I was unable to change any columns names. So, with the original excel file I had for the project, I upload it to BigQuery. From there, I was able to make changes to tables as needed.

## Visuals

### Video Games per Genre Visual

Here is a visual of the total amount video games per selected genres

![Chart 3](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Video%20Games%20per%20Genre.png)

### Video Game Genre Sales per Global Region Visual

Here is a visual of sales per selected genre in each global region

![Chart 4](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Video%20Game%20Genre%20Sales%20per%20Global%20Region.png)

### Percentage of Video Games sold per Global Region Visual

Here is a visual that shows the percentage of video games sold in each global region

![Chart 5](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Percentage%20of%20Video%20Games%20sold%20per%20Global%20Region%20(in%20millions).png)

### Critic Scores per Video Game Genre Visual

Here is a visual that shows critic scores per selected genre

![Chart 6](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Critic%20Scores%20per%20Video%20Game%20Genre.png)

### Consumer Scores per Video Game Genre Visual

Here is a visual that shows consumer score per selected genre

![Chart 7](https://github.com/Greekman12490/Video-Game-Statistics/blob/main/Images/Consumer%20Scores%20per%20Video%20Game%20Genre.png)

### Data and Visual Links

Below are links showing the data manipulation and interactive visuals 

> **Please note, the Google Sheet link will allow you to interactive with visuals shown above, a bar should be at the bottom with the name of the sheets**

Google Sheets Data Manipulation - [Video Game Statistics](https://docs.google.com/spreadsheets/d/17xVlI8Svoc3IZFuhalik6YDsVKH1gJD2HLKXhKOauIg/edit?usp=sharing)

Tableau Public Data Visualization Link 1 - [Video Game Stats Visuals (Sales and Total Games)](https://public.tableau.com/app/profile/panagioti.pete.tsivis/viz/VideoGameStatsVisualsSalesandTotalGames/Dashboard1)

Tableau Public Data Visualization Link 2 - [Video Game Stats Visuals (Critic and Consumer Scores)](https://public.tableau.com/app/profile/panagioti.pete.tsivis/viz/VideoGameStatsVisualsCriticandConsumerScores/Dashboard2)

## Results

When going over the dat I was surprised with certain outcomes. I honestly thought "First Person Shooters" (FPS) would've sold the most. However, it came at around third. "Action" was first, which makes sense. I can make the assumption based on the average of scores on both critics and consumers that "Role-Playing" (RPG) games is what most people are fond to. It makes sense since it provides a bit of imagination for those who play those type of games.

## Additional Links

I am providing additional links such as where I downloaded the original file for this project and the results of my SQL data manipulation results to Google Sheets

SQL Data Manipulation Link 1 [Video Game Total Sales Globally and Regionally](https://docs.google.com/spreadsheets/d/1149qkp4-qoIIFgp9jPxIjlSLrTP_qiFVhajZaFgsDuQ/edit?usp=sharing)

SQL Data Manipulation Link 2 [Video Game Genre Critic and User Ratings](https://docs.google.com/spreadsheets/d/1wu2TithWcvf_30KX8Qj-PVqmyr6ORmq5giAxqlSLPic/edit?gid=676272531#gid=676272531)

Kaggle Dataset Link [Video Games Data](https://www.kaggle.com/datasets/ghassenkhaled/video-games-data)

## Additional Notes

On the top of this page, I am providing the schemas and queries I used in BigQuery


















