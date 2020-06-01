# Description
This project formulates and analyzes the ratings for defenders from the Premier League(18/19) season.
The data is extracted from [here](https://github.com/vaastav/Fantasy-Premier-League).

### Methods 
Ratings are calculated by extracting and modifying game metrics like key-passes, recoveries, goals etc.. These metrics are given equal weight and summed up to output a player rating. 
The ratings are standardized to give a final rating within a range of 0-10. 

### Evaluation
The ratings are evaluated with the [Who Scored Ratings](https://www.whoscored.com/Explanations) .
To check how valid my calculated player ratings are, the correlation is calculated between the calculated ratings and the whoscored ratings. 

### Results
The correlation between whoscored player ratings and my player rating method is 0.68 which means that the two rating methods are closely related. More information can be found in my final year paper [here](https://docs.google.com/document/d/1uximB8PYCJrTc2FQK19VJEl_H4emV4H15qRyUUM3LS8/edit?usp=sharing).



