# Baseball_Betting

This project was created in an attempt to gain an advantage in sports betting on MLB regular season games. I am keeping it relatively simple to make it not too time consuming to maintain. The whole project can currently be run through the MLB.rmd file. The model takes fivethirtyeight's MLB ratings (https://projects.fivethirtyeight.com/2021-mlb-predictions/) and combines it with doubleheader variable, games played the day before, and the distance traveled on travel days. I use Retrosheets data to to get inning by inning data. I currently keep track of odds in a google sheets data sheet, which is loaded directly into the rmd code. The odds are based on Draftkings Sportsbook.

Things I am working to add:
- Total runs prediction, I am still trying to fine tune the model as it is not a normal bell shaped distribution, additionally the model I have made generally predicts the over so I'm trying to analyze how effective it is
- Other types of machine learning models (possibly try and incorporate something similar the poisson model in my soccer project, which could help with my total runs dilema)
- Set up a webscrapping code so that I don't have to manually imput odds data into a spreadsheet.
- I was previously working on 5 inning predictions, but am putting it on pause for the moment

The information used here was obtained free of
charge from and is copyrighted by Retrosheet.  Interested
parties may contact Retrosheet at "www.retrosheet.org".
