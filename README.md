# Project-1       
Data analysis and manipulation with Pandas, Matplotlib, and OMDB API.
<br />
## Overview
My team and I were tasked with answering the folowing questions:
1. Does the number of awards impact box office success?
2. Does movie rating (G,PG, PG-13, ETC) impact box office earnings?
3. Have movies gotten longer over the years?
4. What actor has the most movies in the top 1000?
5. What actor has the highest average movie rating?
6. What is the most popular genre in the top 1000 movies dataset?
 
## Methodogolgy 
To accomplish this my team and I pulled the data into a pandas dataframe and cleaned it for analysis.
We then standardized the movie ratings by placing them all into US standardard ratings. 
We then used the OMDB API (http://www.omdbapi.com) to find all the awards wins & nominations per movie.
<br />
### Does the number of awards impact box office success?
![Fig_Awards Wins   Nominations VS Box Office](https://github.com/dclaxto1/Project-1/assets/128431134/2a6aa064-9363-4060-816a-49541c62704e)
<br />
We found the correlation between the number of wins & nomininations and box officer earnings is .271396  
indicating there is not a strong relationship between the award wins and box office earnings.

### What is the most popular genre in the top 1000 movies dataset?
![image](https://github.com/dclaxto1/Project-1/assets/128431134/b39c3c57-d2c0-449d-b544-8d7ac273c4ce)
<br />
We found drama to be the most popular.
<br />
### Does movie rating (G,PG, PG-13, ETC) impact box office earnings?
![image](https://github.com/dclaxto1/Project-1/assets/128431134/71a52a6e-240f-41d4-b37a-f59a959418c4)
<br />
Yes, we found the movie rating do impact earnings. 
<br />
### Have movies gotten longer over the years?
![image](https://github.com/dclaxto1/Project-1/assets/128431134/339ab2a5-8666-45ab-8f8a-682fd042b916)
<br />
There are been an increase in movie runtime since the 80's, but the average length difference is negligible.
<br />
### What actor has the most movies in the top 1000?
![image](https://github.com/dclaxto1/Project-1/assets/128431134/acf5e130-aa7a-4173-961c-12ff071ae99f)
<br />
Tom Hanks has the most movies in the top 1000.
<br />
### What actor has the highest average movie rating?
![image](https://github.com/dclaxto1/Project-1/assets/128431134/c1cdea06-d526-4a14-8cca-0f02b726cc57)
<br />
Tim Robbins has the highest average movie score
<br />

