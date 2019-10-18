# NFL-Prediction-model
To predict the match-winners of a gameweek of the National Football League based on game stats parsed from NFL.com's live GameCenter using the [nflgame API](https://github.com/derek-adair/nflgame) - API used in order to get the in-game stats.

### Things done 
* Built a model using RandomForest Classifier and utilized statistics like Rushing Yards per game, Passing Yards per game, etc. after applying Feature Selection.
* Wrote ETL(Extract,Transform,Load) job to collect stats for the home and away teams for the last 10 years using python nflgameapi.

#### This project works on python 2.7 as the API first worked only for python 2.7 but this would be updated to python 3 in some time.

The outcome and the predictions for the gameweeks are all posted on my [Blog](https://medium.com/@siddhantthakur08) on Medium. Do check it out.

### If the notebook is not rendering then use the link given below in order to view the ipynb file.
* [nbviewer](https://nbviewer.jupyter.org/)
