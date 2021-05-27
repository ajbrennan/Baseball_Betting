# Baseball_Betting

This project was created in an attempt to gain an advantage in sports betting on MLB regular season games. I am keeping it relatively simple so that it is not overly time consuming to maintain. The whole project can currently be run through the MLB.rmd file. The model takes fivethirtyeight's MLB ratings (https://projects.fivethirtyeight.com/2021-mlb-predictions/) and combines it with doubleheader variable, games played the day before, and the distance traveled on travel days. I use Retrosheets data to to get inning by inning data. I currently keep track of odds in a google sheets data sheet, which is loaded directly into the rmd code. The odds are based on Draftkings Sportsbook. The 3 main bet types that I currently keep track of are moneyline, over/under total runs, and -1.5/1.5 run spreads.

Things I am working to add:
- Other types of machine learning models to see if I can get a more precise model
- Set up webscrapping code so that I don't have to manually imput odds data into a spreadsheet.
- Create 3 or 5 inning prediction models

I have been sitting at an ROI generally between 2-5% over the 2021 season. When factoring in that betting 50-50 will lead to an ROI of -4-5% after the sportsbook keep, I am sitting at an ROI of approximately 6-10% over the expected value.

The information used here was obtained free of
charge from and is copyrighted by Retrosheet.  Interested
parties may contact Retrosheet at "www.retrosheet.org".
