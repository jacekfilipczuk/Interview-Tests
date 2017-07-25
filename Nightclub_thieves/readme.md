# Stolen phones in a nightclub

## Scenario
Your friend owns a nightclub, and the nightclub is suffering an epidemic of stolen phones. At least one thief has been frequenting her club and stealing her visitors' phones. Her club has a licence scanner at its entrance, that records the name and date-of-birth of everyone who enters the club - so she should have the personal details of the thief or thieves; it's just mixed in with the details of her honest customers. She heard you call yourself a "data scientist", so has asked you to come up with a ranked list of up to 20 suspects to give to the police.

She's given you:
`visitor_log.csv` - details of who visited the club and on what day (those visiting 2AM Tuesday are counted as visiting on Monday).
`theft_log.csv' - a list of days on which thefts were reported to occur (again, thefts after midnight are counted as the previous day - we're being nice to you)

She wants from you:
- A list of ID details for the 20 most suspicious patrons, ranked from most-suspicious to least-suspicious.
- If you think there are fewer than 20 thieves, a list of ID details for everyone that you think is a thief.
