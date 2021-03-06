# Election Audit Report

## Overview of Election Audit
### Purpose
I assisted Seth and Tom with submiting the election audit results to the election commission. However, the election commission has requested some additional data to complete the audit. The commission has requested the following data:
- The voter turnout for each county.
- The percentage of votes from each county out of the total count.
- The county with the highest turnout.

The purpoose of this audit analysis is to pull the additional data requested by the commission.

## Election-Audit Results
- Votes cast in this congressional election: 369,711 
- Breakdown of the number of votes and the percentage of total votes for each county in the precinct:
Jefferson: 10.5% (38,855), Denver: 82.8% (306,055), Arapahoe: 6.7% (24,801)
- County with the largest number of votes: Denver with 82.8% (306,055)
- Breakdown of the number of votes and the percentage of the total votes each candidate received: Charles Casper Stockham: 23.0% (85,213), Diana DeGette: 73.8% (272,892), Raymond Anthony Doane: 3.1% (11,606)
- Candidate who won the election: Diana DeGette
- Winning Candidate's Vote Count: 272,892
- Winning Candidate's Percentage of the Total Votes: 73.8%

<img width="284" alt="Election Results" src="https://user-images.githubusercontent.com/85654649/126088541-08339820-3476-44ee-a802-191c757fa438.png">


## Results
This script can be used to automate future election results by making some minor changes. Below, please find two examples of how the script can be modified to be used for other elections: 

1) Depending on the type of election, instead of referencing counties, we could pull in data for cities or even states for that matter.
2) Another example would be to change the script and where it's pulling the data from, as different elections will store the data in different files. 

In conclusion, utilizing Python to process the election data is more efficient and can be used to automate future elections.
