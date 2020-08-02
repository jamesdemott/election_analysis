# Overview of Audit 
    Our purpose was to help Seth and Tom submit an election audit to the Colorado Election Board. The election commission requested an audit to determine the qinning candidate and some other data around county participation, total votes both statewide and by county, as well as voter turnout. 

# Election Audit Results 
    Our analysis found the following: 
    #Total Statewide Votes were: 369,711
    #Total county voter participation as a percentage of the whole and total votes were: 
        Jefferson: 10.5% (38,855)
        Denver: 82.8% (306,055)
        Arapahoe: 6.7% (24,801)
    # Our largest county by vote count was Denver, with 306,055 Votes
    #Diana DeGette won the election with 73.8% of the vote, or exactly 272,892 votes. 

# Election-Audit Summary
    In summary, we have constructed a script which can easily be adapted for any election. One example of how this file could be modified would be by incorporating data about how many registered voters there are in a given county. As a separate csv file, this data could be read and iterated upon and then used as a denominator to determine the voter participation, as a percentage of total registered voters to understand turnout. Another way this script could be modified would be to analyze which candidate won each individual county. This could be easily accomplished by setting variables for county_winner and tabulating the variables slightly differently. 