# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the toatal number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Sourse: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were "x" votes cast in the election.
- The candidates were:
  - Candidate 1
  - Candidate 2
  - Candidate 3
- The candidate results were:
  - Candidate 1 received "x%" of te vote and "y" number of votes.
  - Candidate 2 received "x%" of te vote and "y" number of votes.
  - Candidate 3 received "x%" of te vote and "y" number of votes.
- The winner of the election was:
  - Candidate (1, 2, or 3), who received "x%" of te vote and "y" number of votes.
  
## Overview of Election Audit: 

Step 1:
- Determine a county list with the names of the counties.
- Determine a dictonary with the key and the votes cast for each county as the valuse.

Step 2:
- Determine an empty string with the county name for the county with the largest turnout.
- Determine a variable with numbers of votes of the county that had the largest turnout.

Step 3:
- Create the for loop script that finds the name from each row while reading the election results.

Step 4a:
- Write an if statement that checks that the county does not match any existing county in the county list.

Step 4b:
- Add the existing county to the list of counties.

Step 4c:
- Begin tracking the county's vote count.

Step 5:



## Election-Audit Results: 
- How many votes were cast in this congressional election?
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- Which county had the largest number of votes?
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Election Results

Total Votes: 369,711
-------------------------
Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)

-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------

## Election-Audit Summary: 
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.