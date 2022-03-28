# Election data analysis

## Project Overview

The purpose of this analysis is to complete an election audit of a recent local 
congressional election in Colorado. We need to accomplish the following tasks:

1. Report the total number of votes cast
2. Get a complete list of candidates who received votes
3. Report the total number of votes for each candidate 
4. Report the percentage of votes for each candidate 
5. Determine the winner of the election based on the popular votes. 

To get those results, we will automate the process using Python.

## Resources

. Data source : [election_results.csv](https://github.com/valerielnd/Election-Analysis/blob/main/Resources/election_results.csv)
. Software : Python 3.10.2, Visual Studio Code 1.65.2

## Results for the candidates votes

The analysis of the election shows that:
- There were 369,771 votes cast in the election
- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
- The candidates' results were:
	- Charles Casper Stockham received 23.0% of votes and 85,213 number of votes
	- Diana DeGette received 73.8% percent of votes and 272,892 number of votes
	- Raymon Anthony Doane received 3.1% of votes and 11,606 number of votes
- The winner of the election was:
	- Diana DeGette received 73.8% percent of votes and 272,892 number of votes
	
## Additional analysis

The election has requested that we compute some additional data to complete the audit:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Results for the counties' votes

The analysis for the counties show that:
- The counties were:
	- Jefferson
	- Denver
	- Arapahoe
- The counties results were:
	- 10.5% of the votes came from Jefferson, with a number of 38,855 votes
	- 82.2% of the votes came from Denver with a number of 306,055 votes
	- 6.7% of the votes came from Arapahoe with a number of 24,801 votes
- The largest county turnout was Denver with Arapahoe

The election results can be viewed in the output file [election_results.txt](https://github.com/valerielnd/Election-Analysis/blob/main/analysis/election_analysis.txt)

![elections_results](https://github.com/valerielnd/Election-Analysis/blob/main/election_results.png)
# Summary
As the audit of the congressional election in Colorado was successful, the code
we wrote can be used to audit senatorial districts and local elections. 
In the case of senatorial elections, once we get the votes cast for each district, 
to determine the results of the election, we will analyze the data set received for each district. 
To proceed, after uploading the file for a specific district, as we did in the current audit, 
we will create a county list and a candidate list to hold the name of each county and each candidate.
We will also create a county and a candidate dictionaries to hold the vote
for each county and candidate. We will scan the file and populate the
lists of candidates and counties and the dictionaries of candidates and counties.
Then to get the winner for each district, we will compute the number of votes and
the percentage of votes for each candidate. To get the largest county turnout,
we will compute the number of votes and percentage of votes for each county.
That way, we will get the winning senator for each district. 

This audit can also be used for local elections such as mayor elections.
We can create a list of counties part of the city where the elections are
conducted and a list of candidates as well as county and candidate dictionaries. 
As we did in the current audit, we will scan the file with the results for the city
and populate each list and dictionary. To get the candidate that will become the
mayor, we will compute the number of votes and the percentage of votes for each 
candidate.
