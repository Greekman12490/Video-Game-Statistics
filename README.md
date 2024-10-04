## Merit America Capstone Project - Video Game Statistics

This is my capstone project for Merit America. We had choices on what we wanted to do, and I decided to work on my own case study. Now I am a gamer and I wanted to do something that involved video games. So, I decided to look into the number of sales for individual video games sold throughout the years. When I mean years.... I mean decades. I gathered my information via Kaggle where I maniuplated the data using tools such as Google Sheets and Bigquery (SQL). I wanted to ask several question regarding the data I was looking at. One, I wanted to see which genre of video games did developers create the most and the least. Two, I wanted to see which region of the world sold the most and least games. And lastly, I wanted to see how the critics and consumers viewed said games based on score. 

## Analysis and Challenges

### Analysis 

#### Which genre of video games did developers create the most and the least?

When we maniuplate the data via any spreadsheet and SQL programs, we came to the conclusion that "Action" based games were created the most (3,370 out of 16,717). The least being "Puzzle" based games (580 out of 16,717). To my surprise, I thought first person shooters (FPS) or shooters as the data indiciates, would be the most. But, I was not correct on that assumption. Please check the figure below below for details.

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












