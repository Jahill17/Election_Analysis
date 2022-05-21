# Election_Analysis

## Project overview
A Colorado Board of Electiosn employee gave me the following tasks to complete the election audit of the most recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes that each candidate received.
4. Calculate the percent of votes that each candidate won.
5. Determine the winner of the election based on popular vote (most votes received).

## Resources
1. Data Source: [Election Results CSV File](Resources/election_results.csv)
2. Software: Python 3.10.4 64-bit, Visual Studio Code [PyPoll Challenge Python Script](PyPoll_Challenge.py)

## Election-Audit Results:
The analysis of the election shows the following information:
- Total votes: 369,711
- Candidates:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- Breakdown of votes by county:
    - Jefferson County: accounted for 10.5% of the votes for a total of 38,855 votes
    - Denver County: accounted for 82.8% of the votes for a total of 306,055 votes
    - Arapahoe County: accounted for 6.7% of the votes for a total of 24,801 votes
- County with largest voter turnout: Denver
- Breakdown of candidate results:
    - Charles Casper Stockham: received 23.0% of the vote for a total of 85,213 votes received
    - Diana DeGette: received 73.8% of the vote for a total of 272,892 votes received
    - Raymon Anthony Doane: received 3.1% of the vote for a total of 11,606 votes received
- Winner of election:
    - Diana DeGette won the election by receiving 73.8% of the votes for a total of 272,892 votes received

The text file summarizing the analysis can be found in the github directory. [Election Analysis Text File](Analysis/election_analysis.txt)

## Election-Audit Summary:
As a result of the election audit, it is my belief that the python script used as part of this audit can be used for any future election.  With a slight modification this could be used for state governor election and for primary election results.  The modifications needed for these election types would include the following: obtain a new data source csv file with governor election results for all parties and add additional script that includes breakdown by candidate party (Democrat, Republican, Independent).  Essentially all other script relating to the county and winner could remain the same.
