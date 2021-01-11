# Election_Analysis
The following code was used to bring meaning to bulk election data that contained candidates, votes for that candidate, and the county the vote was cast in.
We were able to return the following
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

## Results


### Full Code

[PyPoll_Challenge_starter_code.py](https://github.com/JasonWilliams88/Election_Analysis/blob/main/PyPoll_Challenge_starter_code.py)


### PNG of terminal readout for Deliverable 1

![Election_Analysis/blob/main/Deliverable1.png](https://github.com/JasonWilliams88/Election_Analysis/blob/main/Deliverable1.png)



### txt. document for Deliverable 2

https://github.com/JasonWilliams88/Election_Analysis/blob/main/election_analysis.txt



__Answers to the questions above__

* Total votes 

    - 369,711
    
    
* Number of votes and % of total votes for each county

  - County Votes:
    Jefferson: 10.5% (38,855)
    
    Denver: 82.8% (306,055)
    
    Arapahoe: 6.7% (24,801)

* County with largest number of votes

    - Largest County Turnout: Denver
    
* Breakdown of candidate votes received
    
    Charles Casper Stockham: 23.0% (85,213) \
    Diana DeGette: 73.8% (272,892) \
    Raymon Anthony Doane: 3.1% (11,606) 
    
 * Breakdown of winner
 
    Winner: Diana DeGette \
    Winning Vote Count: 272,892 \
    Winning Percentage: 73.8%



## Summary

The code we created is dynamic. changing a few lines allows us to apply this for other and  even larger elections

'file_to_load = os.path.join("./", "election_results.csv")' \
by changeing the csv the code is pointing towards we can use this code for a new election as long as the csv follows the same format 

instead of printing to a txt document the code can be changed to email directly. This allows minimal effort on everyone elses part.

Dictionaries allow us to add even more variables to them which allows us to analysis even more complex relationahips within the election.


