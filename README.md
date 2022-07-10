# Election-Analysis

## Overview of Election Audit
A Colorado Board of Elections employee assigned me to complete an audit of a recent local congressional election. This report contains the following information:
1. The total number of votes cast. 
2. A complete list of candidates who received votes.
3. The total number of votes each candidate received.
4. The percentage of votes each candidate won.
5. The winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.1, Visual Studio Code, 1.38.1

## Election Audit Results - Candidate Vote Results & Winning Candidate
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  -  Candiate 1 Charles Casper Stockham
  -  Candiddate 2 Diana DeGette
  -  Candidate 3 Raymon Anthony Doane
The candidate results were:
  - Candidate 1 received 23.0% of the vote and 85,213 votes
  - Candidate 2 received 73.8% of the vote and 272,892 votes
  - Candidate 3 received 3.1% of the vote and 11,606 votes
The winner of the election was:
  - Candidate 2 Diana DeGette who received 73.8% of the vote and 272,892 votes

## Challenge Overview
In addition to the information supplied above, an additional purpose of the challenge was to ascertain the number of votes cast in each county and the percentage of the overall vote per county, in addition to the candidate information supplied above.

## Challenge Results - County Vote Results & Largest County Turnout
My analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The counties were:
  - Jefferson
  - Denver
  - Arapahoe
The county results were:
  - Jefferson had 10.5% of the vote, 38,855 total votes cast.
  - Denver had 82.8% of the vote, 306,055 total votes cast.
  - Arapahoe had 6.7% of the vote, 24,801 total votes cast.
The county with the highest turnout was:
  - Denver County, with 306,055 total votes cast (82.8%)

### Summary Screenshot 
![Election Results](https://user-images.githubusercontent.com/106618404/178159152-206da38c-977b-472c-b74e-7529011c7860.PNG)

## Election-Audit Summary
### Provide a business proposal to the election commission on how this script can be used for any election. Provide 2 examples of how this script can be modified for other elections.
Future election data that is stored in a .csv file can be read and analyzed with the script used for this analysis. This script can be used in the following 2 ways:
1. A tally of votes cast in other counties can be analyzed with this script providing that the county names are adjusted in the script and that the number of counties is modified if there are more than 3 counties like there was in this dataset. Additional counties can be added to the dictionary using the .append function. Furthermore, the .csv file will need to be assessed to determine which row contains the county name. In this .csv file the county name was in row [2], but other datasets may have it in a different location and the script will need to be changed to account for that difference. 
2. A tally of votes cast for multiple candidates can also be assessed with this script. Similar to the county information, the script may need to be adjusted to account for more than or less than the 3 candidates that were running in this election, but it should work.
