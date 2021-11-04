# Shark_attack
## Objectives:
 To determine if most of the shark attack occurences are fatal or not, and if those occurences are related to any specific species or migration patterns.

## Status:
 Complete

## Tools used:
 *Pandas library
 
 *Regular expressions
 
 *Filters

 *Grouping

## Step-by-step:
 First, as I needed an analysis regarding species x location x period, I needed to clean the *species* column. The main issue I faced was that there is no clear pattern of how shark species were inserted. On most of lines there was a correct name as "White Shark", however there were other names such as "Hammerhead" instead of "Hammerhead sharks", or just 6' shark or small shark, making the cleaning process hard. I was able to clean half of the items, but it already showed some results. 
 
 Most of the columns that were not clean didn't have a great amount of extra information, or didn't contain information about sharks as well. 
 
 Most of the ocurrences were related to Unkown sharks (1394 occurrenced) (the ones with only the size as description), white sharks, bull sharks, and invalid which was the hardest to get the data. 
 
 Invalid meant that the occurence was not related to sharks or that shark involvement did not happen prior to the person's death, or that the shark involvement was not confirmed.
 
 After cleaning the *species* column, I cleaned the *fatal* column, to get the number of fatalities in occurrences. 
 
 Then, I changed the date to a *datetime* format to get the months of each occurence. 
 
 With all these data at hand, I could create masks and filters to group, by species, periods of the year and the fatalities of the 4 most fatal species. 
 
## Conclusion:
### White Sharks

<img align="right" src="https://pbs.twimg.com/media/E5tyqoBXwAwBzym.jpg" alt="" width="201" height="201" />
White sharks are by far the most famous shark thanks to Hollywood. It is, indeed, the species with the greatest number of fatal occurences, with a count of 143. However, It is also the species with the second greatest number of not-fatal attacks, with a count of 477 occurrences. losing only for unknown species. Therefore, White Sharks 
hold the position of the greatest number of occurrences, for both fatal and not fatal.
Most of the attacks happen in California between August and November. From November to March, according to https://www.fws.gov/uploadedfiles/whitesharkwengetal.pdf, White sharks leave California to hawaii to migrate, explaining why the numbers of occurrences drop significantlyafter November. I coudn't find any information relate to their return to California, to explain why attacks rise just in August.


### Bull Sharks
Bull sharks don't go too far when they migrate, according to https://www.floridamuseum.ufl.edu/discover-fish/species-profiles/carcharhinus-leucas/, they spend most of the time in Florida, but during summer they go north looking for cooler waters and they come back when fall starts, and water has cooled again.
This probably explains the occurrences in North Carolina happening only between June and September.

# Questions that still need answer.

During my research I discovered that there are plenty of Whitesharks living on the USA's East coast as well, but there aren't any significant data regarding occurrences just like it happens on the West coast.

When do White sharks return from migration so that attacks increase significantly in August, which is the month with the greatest number of occurrences. 

Migration patterns in South Africa and Australia, which hold a large number of occurrences as well.


	

	
	
	
	
	
	
