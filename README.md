# Kickstarting with Excel

## Overview of Project
Project is to assist organizer in anticipation of new kick starter campaign. By analyzing data dump of past Kickstarters of similar categories we can position the organizer with the right information to launch a successful campaign. 


### Purpose
Analysis seeks to gain information on selected variables and how they track with campaign outcome.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Data was filtered and summarized in a pivot table where 'launch date' was analyzed as months. For this analysis, only records with category type 'theater' whose campaign had concluded were considered. 
This simplified the analysis to three categores in which the outcome values were tabulated on occurence, providing new information that was used as inputs for a line chart. 
 

### Analysis of Outcomes Based on Goals
A summary table was setup which consolidated the campaigns based on ranges in the set dollar goals. Counting functions were then used to tabulate the outcomes into different columns from which a total and percentages were calculated. The percentage column formed the basis for a line chart which tracked the percentage outcomes categories against the goal ranges.

### Challenges and Difficulties Encountered
Challenges and difficulties could be encountered on setting up and modifying elements, organization of a pivot table and\or the various graphs. For instance, I had to search a bit to figure out how to filter column labels and to organize the remaining ones in a descending order. It's not always clear what functions are to be controlled on the various panes or on the toggles embedded in the worksheet. Just a matter of gaining muscle memory. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. There seems to be an advantage to launching a kickstarter at certain times of the year. The volume of launches changes throughout the year with the largest counts found in the spring and early summer months. Two additional spikes are seen in February and October. For the entirety of the year the data show that there are more 'successful' outcomes than 'failed'. 
2. The largest separation between the 'successful' and 'failed' outcomes occurs between April and July. The data points for May and June show that for every failed kickstarter there are just over 2 that are successful during the same timeframe. This gap narrows toward the end of the year when the 'successful' and 'failed' outcomes converge in count. 


- What can you conclude about the Outcomes based on Goals?
Although some irregularities exist, the data point to the conclusion that the lower the funding the goal, the better chance the campaign succeeds. 

- What are some limitations of this dataset?
For the analyses asked of us, i didn't find the dataset to be lacking or limited. It includes what i think are the important data points. What could be useful to narrow down is possibly some information about the overall budget of the project. We have the goal but how much of the budget does the goal cover? we could use a filter on the budget to better create a sub-set that tracks with the budget contraints of Louise's situation.

- What are some other possible tables and/or graphs that we could create?
