# Election_Analysis_3

## Project Overview
A Colorado Board of Elections employee has asked us to undertake an analysis of the results of a recent congressional election.  They have requested the following steps be taken:  

1) Calculate the total number of votes cast
2) Get a complete list of candidates who received votes.
3) Calculate the total number of votes each candidate received.
4) Calculate the percentage of votes each candidate won.
5) Determine the winner of the election based on the popular vote.

## Resources
- Data Source:  election_results.csv
- Software:  Python 3.8.2, Visual Studio Code 1.43.2

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates who received votes were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- Results:
  - Charles Casper Stockham received 23% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was Diane DeGette with 73.8% of the vote and 272,892 votes

## Challenge Overview
As an additional ask, the employee (our client) tasked us with writing code to include the following in our analysis:

- Determine the voter turnout for each county.
- Determine the percentage of votes from each county out of the total count
- Determine the county with the highest turnout

The elections employee requeseted that we take the following steps:

1) How many votes were cast in this congressional election?
2) Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3) Which county had the largest number of votes?
4) Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
5) Which candidate won the election, what was their vote count, and what was their percentage of the total votes

The analysis of the election shows that:
- There were 369,711 votes cast in the election
- Denver had the largest number of votes
- Votes & Percentages by Candidate:  
  - Charles Casper Stockham received 23% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was Diane DeGette with 73.8% of the vote and 272,892 votes

We were asked to ensure the code printed the desired results in Terminal and also printed and saved to a text file "election_analysis".

When the coding was finalized the results printed as expected in Terminal (though we edited the code to add some cleaner labels and spacing):

![Election_Analysis_Terminal_Output](https://github.com/PatriciaCB1/Election_Analysis_3/blob/main/Election_Analysis_Terminal.png)

In addition - the text file populated as request and results were able to be saved in this format:

![Election_Analysis_Text File_Output](https://github.com/PatriciaCB1/Election_Analysis_3/blob/main/Election_Analysis_text_file.png)

The ultimate code we created to perform this analysis was as follows:

![Election_Analysis_Code_1](https://github.com/PatriciaCB1/Election_Analysis_3/blob/main/Election_Analysis_Code_1.png)
![Election_Analysis_Code_2](https://github.com/PatriciaCB1/Election_Analysis_3/blob/main/Election_Analysis_Code_2.png)
![Election_Analysis_Code_3](https://github.com/PatriciaCB1/Election_Analysis_3/blob/main/Election_Analysis_Code_3.png)

## Challenge Summary

Provide the format of the input file (i.e. any future CSV file of results) remains in the same for future elections, the code we have written can be utilized again and again for analyzing the results of future elections.  This is because we are utilizing dynamic code and did not hard code any of the candidates or counties.  In future we could update the code to analyze and report on the following (in addition to the current output):

  1) Break out the number number of votes per candidate per county using for conditionals/ for loops - we could also calculate the % of the vote each candidate won in each county to determine if popularity of a candidate varies by county.
  2) If the data file we receive has demographic details in future we could update the code to analyze and report on the demographic distributions of voters by candidates and also by county (i.e. age, gender, income, race/ ethnicity).  I'm sure it would be informative for the election officials, candidates and campaign strategists.
