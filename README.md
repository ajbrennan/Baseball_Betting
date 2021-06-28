# Baseball_Betting

This project was created in an attempt to gain an advantage in sports betting on MLB regular season games. I am keeping it relatively simple so that it is not overly time consuming to maintain. The whole project can currently be run through the MLB.rmd file. The model takes fivethirtyeight's MLB ratings (https://projects.fivethirtyeight.com/2021-mlb-predictions/) and combines it with doubleheader variable, games played the day before, and the distance traveled on travel days. I use Retrosheets data to to get inning by inning data. I currently keep track of odds in a google sheets data sheet, which is loaded directly into the rmd code. The odds are based on Draftkings Sportsbook. The 3 main bet types that I currently keep track of are moneyline, over/under total runs, and -1.5/1.5 run spreads.

Things I am working to add:
- Tracking teams my model routinely over predicts and under predicts
- Other types of machine learning models to see if I can get a more precise model
- Set up webscrapping code so that I don't have to manually imput odds data into a spreadsheet
- Create 3 or 5 inning prediction models

Model ROI's for the 2021 season based on most recent model adjustments (as of June 27th)
ML: 2.71%
o/u: 6.63%

Keep in mind that if you are a perfectly average bettor, you expect a baseline ROI of -3-5% after the sportsbook keep.

The information used here was obtained free of
charge from and is copyrighted by Retrosheet.  Interested
parties may contact Retrosheet at "www.retrosheet.org".
