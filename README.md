# Election_Analysis
Module 3: PyPoll with Python Challenge

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following task to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Calculate the total number of votes that each candidate received.
3. Determine the winner of the election based on popular vote.
4. Calculate the total number of turnout by county.
5. Determine the county with the higher turnout.

## Resources
- Data Source: election_results.csv
- Sofware: Python 3.10, Visual Studio Code 1.72.2

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast on the election.
- The counties turnout were:
    - Jefferson turnout was 10.5% of the vote and 38,855 number of votes
    - Denver turnout was 82.8% of the vote and 306,055 number of votes
    - Arapahoe turnout was 6.7% of the vote and 24,801 number of votes
- The county with the higher turnout was:
    - Denver with 82.8% of the vote and 306,055 number of votes.
- The candidates results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
    - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

### Command Line Screen Shot
![Command Line Screen Shot](https://github.com/ggalguera/Election_Analysis/blob/main/Election_Results_picture.png)

## Election-Audit Summary
This script can be used to analyze any set of data from any election as long as we keep the same column structure, we can add an input on the script where we can define the name of the file with the raw data that we want to use and another input to define the election results file name, in this way the scrip can be used for multiple elections without affecting previous results. We also can add the state in a column 4 of the data, by doing this we have the option to create an external for loop to get reports by state or just and if condition to filter the desired state for the analysis.
