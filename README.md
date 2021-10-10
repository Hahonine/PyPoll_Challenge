# PyPoll Challenge Analysis

## Overview of Election Audit

### Purpose

- The purpose of the election analysis was to determine the winner of the most recent election, as well as the distribution of votes by county and by candidate

## Election Audit Results

### Overall Results

- In this election, 369,711 votes were cast from three counties to select from three candidates. The election produced a clear result with a supermajority of voters selecting one candidate.

### Results by Candidate

- The winner of the election was Diana DeGette with 272,892 votes, which amounts to approximately 73.8% of all votes cast.

### Results by County

- The county with the highest turnout was Denver County, with 306,055 votes cast, which amounts to approximately 82.8% of all votes cast. 

##Election Audit Summary

- The software used to audit this election can be used in elections of any size and scope with minimal adjustment to the code. The counties and candidate names are sleected from the data, so an arbitrarily large (or small) number of candidates and counties can be audited without any changes.

- To audit an election of a larger(or smaller) scope, the only adjustents that need to be made to the code behind the audit sfotware would be the output naming. For example, if we audited by states, the code would have to be adjusted to call out states instead of counties.

- This software can also be adjusted to audit to a finer granularity. To expand upon the previous example, we could repeat the analysis logical pattern to audit both by state and by county, instead of choosing one over the other, allowing for a more detailed breakdown of how and where voters cast their votes.

- Finally, a filter option can be added to the code to deliver results for an individual state and all counties in that state, without having to parse that data from the raw dataset ahead of time. 
