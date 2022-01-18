# Election_Analysis #

## Project Overview
Analysis of the results for a local congressional election in the state of Colorado over three different counties, involving three different candidates.

## Breakdown of questions answered by analysis include:
1. Calculating the total number of votes cast.
2. Compiling a complete list of candidates who recived votes.
3. Calculating the total number of votes each candidate recieved.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on popular vote.
6. Calcuating the number of votes cast by county and their percentage in respect to total votes.
7. Determining which county had the greatest voter turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code. 1.38.1

## Summary
The analysis of the election results were as follows:

* Total Votes: 369,711
* Candidates, Vote Percentage and total votes recieved:
  *  Charles Casper Stockham: 23.0% (85,213)
  *  Diana DeGette: 73.8% (272,892
  *  Raymon Anthony Doane: 3.1% (11,606)
* Largest County Turnout: Denver
* Winner: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8% 

## Future Application

The code used to determine the election results in this analysis can be applied to future elections with data stored on csv files by changing the path where the "file_to_load" variable is initialized.
* Example: ![File_to_load](https://user-images.githubusercontent.com/96406929/150031150-1d9a9546-73ee-43dc-9e81-11653134210c.png)

Row indexes may have to be changed to fit the format of future csv files. For example the csv used to compile the results above had the format: Ballot ID, County, Candidate so indexes were as follows:
* ![File_to_load](https://user-images.githubusercontent.com/96406929/150036160-93d5a3ea-68c0-4faf-a27f-bc3b08af490b.png)


