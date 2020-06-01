## Description
This project formulates and analyzes the ratings for defenders from the Premier League(18/19) season.
The data is extracted from [here](https://github.com/vaastav/Fantasy-Premier-League) by @vaastav .

## Methods 
Ratings are calculated by extracting and modifying game metrics like key-passes, recoveries, goals etc..The variables are given equal weight and summed up to output a player rating. 
The ratings are standardized to give a final rating out of 0-10. 

## Evaluation
The ratings are evaluated with the [Who Scored Ratings](https://www.whoscored.com/Explanations) .
To check how valid the calculated ratings are, we check the correlation between the calculated ratings and the whoscored ratings. 

## Results
The correlation between whoscored player ratings and the calculated player ratings is 0.68 which means that the two rating methods are closely related. More information can be found in my final year project [here](link).

