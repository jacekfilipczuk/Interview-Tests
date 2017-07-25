# Call Centre
## Setup

This is a test on basic data processing. The test is tool-agnostic; you may use any data processing tool you like. Typical examples would include, Excel, python / pandas, matlab, SQL etc. The test is timed to last approximately 2 hours. Points available for each question are marked in [brackets].
 
You have been given 3 csv files:

- leads.csv. This is a list of fictitious company directors, with some basic data about them and their company.

- calls.csv. This is a list of fictitious calls made by an outbound call centre. The call centre consists of several agents, who make calls one after the other. They don’t get to choose who to call, the system does. The objective of the call is to get the lead to signup on the website. When they finish a call, they mark down the outcome, from a fixed list of possible outcomes. Note that a single lead may be called multiple times.

- signups.csv. This is a list of leads who signed up after being called by someone from the call centre. Each signup was risk assessed and either approved or rejected for a loan.


## Questions

- Which agent made the most calls? [1]  

**Orange**
- For the leads that received one or more calls, how many calls were received on average? [2] 

** avg: 1.8 **
- For the leads that signed up, how many calls were received, on average? [2] 

** avg: 2.1 **
- Which agent had the most signups? Which assumptions did you make? (note that there is a many-to-one relationship between calls and leads) [4]

** The agent RED had the most signups. I assumed that a good indication of signups is the number of INTERESTED Leads that each agent had and the difference between CALL BACK LATER and INTERESTED outcome. Agent RED had the biggest difference between these two outcomes. **
- Which agent had the most signups per call? [2]

** Agent BLUE had the most signups per call with 0.26 ratio. But I would say that this ratio is not accurate (and is just a lucky strike) because the total number of calls made by agent BLUE is so much lower compared to other agents. I would say that agent RED is the one with the highest signups per call average among the agents. **
- Was the variation between the agents’ signups-per-call statistically significant?

** Was not for all the agents. **
- Why? [5]

** The difference was not always statistically significant because the sample size of certain agents was too small. **
- A lead from which region is most likely to be “interested” in the product? [3]

** north-west. **
- A lead from which sector is most likely to be “interested” in the product? [1]

** consultancy. **
- Given a lead has already expressed interest and signed up, 
 - signups from which region are most likely to be approved? [2]
 
 ** north-west. **
 - Is this statistically significant? Why? [5]
 
 ** Like before, the sample for some regions are too small to be statistically significant.**
- Suppose you wanted to pick the 1000 leads most likely to sign up (who have not been called so far), based only on age, sector and region.
 - What criteria would you use to pick those leads? [10]
 
 ** Age 18-20 -- Region nort-west, south-west -- Sector food, retail, consultancy, wholesale.***
 - In what sense are those an optimal criteria set? [3]
 
 ** These are the top criteria for leads who signed up for the product. **
 - How many signups would you expect to get based on those called leads, assuming they were being called by random agents? [3]
 
 ** Around 10% of the sample, so 100 leads.**
 - If you could choose the agents to make those calls, who would you choose? Why? [3]
 
 ** I would chose agent RED because he has the highest, statistically significant, signup per call average.**
 

