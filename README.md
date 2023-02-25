# Predicting Total Revenue of US Movies for Private Investors

Objective: 

The clients of interest are movie investors who seek to work on new movie projects and would be interested in the analysis of predicting a movie’s success based on multiple features that range from: budget, genre, mpaa rating, actors/actresses etc. This analysis will help lower risks in investing in a multi million industry and overall help distinguish the profitability of movies as a whole. 

Data Description: 

Two sources will be taken into account: www.boxofficemojo.com and www.imdb.com in order to scrape data based on features of interest that will help analyze a movie’s success. I will gather most of the features data from boxofficemojo.com. On the other hand, imdb.com will be used to gain information on which actors and actresses have gotten nominations and/or awards in Oscars. These actors and actresses listed will have a star value which will be based on the sum of nominations and wins they have received. 

For the model, the target will be total revenue which is based on the sum of grosses domestically and internationally. The individual sample/ one row represents the impact certain features have in association to total revenue. The features I will work with will be: movie title, gross domestic, gross international, gross worldwide,  director, distributor, genre, mpaa rating , actor 1, actor 2, actor 3, actor 4, and star value.

Tools:
In order to obtain data from the two websites of interest, it will be web scraped using the python library, Beautiful Soup. For further analysis, python, matplotlib and seaborn will be utilized. Selenium will be used for certain pages that require web browser interaction. 

MVP Goal:
The MVP goal is to investigate whether a certain feature like budget is significant in considering it as a factor of interest to predict a movie’s success based on total revenue using linear regression and comparing r squared values. Following this analysis I hope to utilize other features like how actors and actresses may impact or signify association to total revenue. 
