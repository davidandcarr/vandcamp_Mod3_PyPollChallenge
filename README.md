# vandcamp_Mod3_PyPollChallenge

# Election Analysis Summary

In this challenge the client has asked for a program to crunch the numbers of a congressional election and yield a concise and accurate read of the results. Since there are separate counties involved, each must have its own vote count alongside the tally of votes for each candidate. 

## Broad Strokes in Numbers
* Total Votes Cast: 369,711
* Votes by County:
    * Jefferson: 38,855 votes (10.5% of turnout)
    * Denver: 306,055 votes (82.8% of turnout)
    * Arapahoe: 24,801 votes (6.7% of turnout)
        * Denver county had the highest voter participation with almost 10 times the amount of votes of Jefferson county. (306,055 votes cast.)
* Votes by Candidate (% of total votes)    
    * Charles Casper Stockham: 85,213 votes (23%)
    * Diana DeGette: 272,892 votes (73%)
    * Raymon Anthony Doane: 11,606 votes (3%)
        * Diana DeGette wins the election with 272,892 votes. A landslide victory with 73% of votes in their favor.

## Future Elections
I would recommend this simple and effective tool to the election commission for nearly all future elections, with a few additional features added for the commission and counties' better service of their communities.

First, it would perhaps be beneficial to include a parsing of votes by city. While some counties may have lots of cities and townships, it would be a helpful aid to cross reference with census data, and understand which communities led to a candidate's victory.

Other parsing features I would like to include are each candidate's votes by county. This is doable with the data present, but as it was not part of the initial ask from the client that presentation of data may be over-engineering the thing.

Depending on the scale of the voter and cadidate pools in future elections, this tool may need to only show results that yielded a significant amount of votes. As it stands, the analysis would conceivably tally and list _all_ votes cast, so it would even tally all the write-ins for Mickey Mouse or what have you. While it is true that those votes must be tallied in general (as part of the rule of law) I find it unneccessary to list them to the election commission's report, so perhaps a threshhold should be established that would bar the program from displaying vote tallies for candidates that did not perform well.
Of course, this creates a hole in the election report in a scenario where there are so many candidates that not one receives above the threshold, but that would certainly lead to more legal proceedings than this tool is prepared for.

### Last Thought
Overall, this simple report generator is helpful for tallying large, yet simple sums of data, but will ultimately need to be refactored for UX features if it should get widespread use. 