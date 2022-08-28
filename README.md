# Election-Analysis

## Project Overview

A Colorado Board of Elections employee asked you to complete an audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of the candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary

Summary of Candidate Votes:
- There were 369,711 votes cast in the election.
	- Candidate 1: Charles Stockham
	- Candidate 2: Diana DeGette
	- Candidate 3: Raymon Anthony Doane
- The candidate results were:
	- Charles Stockham: received 23.0% of the votes with 85,213 total votes.
	- Diana DeGette: received 73.8% of the votes with 272,892 total votes.
	- Raymon Anthony Doane: received 3.1% of the votes with 11,606 total votes.
- The winner of the election was:
	- Diana DeGette: received 73.8% of the votes with 272,892 total votes.

## Challenge Overview
The election comission would like to know voter turn out for each county including percentage of each county and total count along with which county had the highest turn out. 

## Challenge Summary

Summary of County Votes:
- There were 369,711 votes cast in the election.
    - County 1: Jefferson
    - County 2: Denver
    - County 3: Arapahoe
- The county results were:
    - Jefferson: received 10.5% of the votes with 38,855 total votes.
    - Denver: received 82.8% of the votes with 306,055 total votes.
    - Arapahoe: received 6.7% of the votes with 24,801 total votes.
- County with largest number of votes:
    - Denver

## Election Audit Summary
This script can be used to analyize other elcections by replacing the .csv data file in the code with another .csv data file. This will work as long as the csv file is in the .Resources Folder:
![election_results.png](/Resources/election_results.png)
 By including more 'for loops' we could modify the code to see each candidates ranking in each county.
