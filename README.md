# Election-Analysis
Using Python to Analyze Colorado Election Data
## Overview of Election Audit
The purpose of this challenge is to perform an election audit for the Colorado Board of Elections concerning a recent local congressional election. Some of the data points included in this audit include the total number of votes cast, a list of candidates receiving votes, and a percentage of votes each candidate won. The Python script for this project is implemented to show the winner of the election based on the popular vote. 

## Election Audit Results
- The total votes cast in this election totaled 369,711.
### County Vote Breakdown:
- Jefferson county had 38,855 votes or 10.5% of total votes.
- Denver county had 306,055 votes or 82.8% of the toal votes.
- Arapahoe county had 24,801 votes or 6.7% of the total vote.
- Thus, Denver county (largest county turnout) had the largest number of total votes receiving  242,399 more votes total compared to Jefferson and Arapahoe counties.

### Candidate Vote Breakdown:
- Charles C. Stockham received 85,213 total votes or 23.0% of the total vote.
- Diana DeGette received 272,892 total votes or 73.8% of the total vote.
- Raymon A. Doane received 11,606 total votes or 3.1% of the total vote.
- Thus, Diana DeGette won the election as a result of winning the popular vote.


Below are some code snippets demonstrating how the votes were computed given the parameters discussed above. Additionally, there is an image of the txt file produced, which illustrates to the non technical user the output of the code.

<img width="344" alt="Screen Shot 2021-07-18 at 4 42 27 PM" src="https://user-images.githubusercontent.com/85506567/126081572-84012c1f-e216-4393-86d8-168aa8deea4e.png">

<img width="553" alt="Screen Shot 2021-07-18 at 4 40 22 PM" src="https://user-images.githubusercontent.com/85506567/126081512-af791359-8f55-4e3d-bcf6-a1c4c61d896a.png">

## Summary:
This can be modified for the use of an audit to other elections simply by changing the "with open" statement to recognize a different file. This is useful as an important measure of election integrity. One way is to change the open statements to reflect a different set of election data and to rearrange .txt file that displays the output. Secondly, the parameters can be altered to reflect the desired statistics the auditor wants to capture. 



