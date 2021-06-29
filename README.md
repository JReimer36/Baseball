## Analysis of baseball stats and run generation vs salary <br>
## <i>(Update of class project done in R on 2019 MLB stats)</i> <br>
Currently just analysis of player performance and salaries using machine learning.  A metric for run creation is derived by fitting a random forest model to team runs with team stats as indicators, then predicting the run generation for each individual player.  This is then normalized and compared to player salaries.  Also important to note is that many MLB players are on rookie contracts, where their contract is not a result of past/current performance.  Because of this, we predict the salaries of these players using KNN clustering.  Clusters of various sizes are created using the veteran players, and the clusters of the rookie players are then predicted using these models.  The salaries of these models are then averaged and used as prediction salaries of players currently under rookie contracts. <br> <br>
Plotly graphic stored as html due to file size limits of github and display of pandas styler object only shows every other row on github<br> 
<i>Final version and project focused on statistical analysis if player size influences offensive performance/pay
