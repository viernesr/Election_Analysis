# Election Analysis

## Overview

The Colorado Board of Elections requires assistance on data based on an election audit. Initially they requested for the total number of votes casted, a complete list of candidates who received votes, the total number of votes each candidate has received, the percentage of votes each candidate won, and the reported winning candidate based on popular vote. The Board then additionally requests to have voting information based on county. One method for this problem is to write a Python script, reading the [given data,](./Resources/election_results.csv) and providing the details in a readable format.

## Results

Once the [Python script was run,](./PyPoll_Challenge.py) created a [new file](./analysis/election_analysis.txt) having the relevant information the Board requested.
* 369,711 votes were casted in this congressional election
* The numbers for each county were the following:
  * Jefferson had 38,555 votes, containing 10.5% of the total votes.
  * Denver had 306,055 votes, containing 82.8% of the total votes.
  * Arapahoe 24,801 votes, containing 6.7% of the total votes.
* Denver had the largest number of votes.
* The numbers for each candidate were the following:
  * Charles Casper Stockham received 85,213 votes, containing 23.0% of the total votes.
  * Diana DeGette received 272,892 votes, containing 73.8% of the total votes.
  * Raymon Anthony Doane received 11,606 votes, containing 3.1% of the total votes.
*  Diana DeGette won the congressional election by popular vote, having 272,892 votes, 73.8% of the total votes.

## Summary

Assuming the winner is based on popular vote (i.e., whoever has the majority), the Python script can be used for elections on any scale mainly by modifying the script. One way would be to use nested dictionaries, where the top dictionary's keys can represent the riding. Another method would be having each candidate be placed in another dictionary, where each key's value would be their respective representing party.
