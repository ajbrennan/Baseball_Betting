# Baseball_Betting

This project was created in an attempt to gain an advantage in sports betting on MLB regular season games. I am keeping it relatively simple to make it not too time consuming to maintain. The whole project can currently be run through the MLB.rmd file. The model takes fivethirtyeight's MLB ratings (https://projects.fivethirtyeight.com/2021-mlb-predictions/) and combines it with doubleheader variable, games played the day before, and the distance traveled on travel days. I currently keep track of odds in a google sheets data sheet, which is loaded directly into the rmd code. The odds are based on draftkings sportsbook.

Things I am working to add:
- Total runs prediction, models I've made are very weak right now so I don't know how feasible it is right now using the current data
- Other types of machine learning models (possibly try and incorporate something similar the poisson model in my soccer project, which could help with my total runs dilema)
- Set up a webscrapping code so that I don't have to manually imput odds data into a spreadsheet.
