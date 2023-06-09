- updated at: 2023-05-24 (commit: annual production analysis)

Peformed a simple analysis on the production over the years in the US as a whole. The analysis can be easily extended to be statewise.

- updated at: 2023-05-23 (commit: answering all the historical questions)

New historical questions added and answered. Geographical information added to map the wind power production statewise.

- updated at: 2023-05-14 (commit: cleaning data and setting the goals)

# A Statistical study over the wind power prodution in US from 2001-2023

This notebook aims to perform some basic analysis over the data provided in [this Kaggle dataset](https://www.kaggle.com/datasets/henriupton/wind-power-production-us-2001-2023). Information about it says the information comes from official entities of the administration. Unfortunately, the dataset is also not clear about the unit of the quantities, so I'll assume kWh for good measure.

Disclaimer: please, bear in mind that I am not american, nor I live in the US. So the analysis here is based solely on the information from the dataset itself. 

## First step: Exploring, understanding and cleaning the data

Exploring the data revealed some inconsistences such as numeric values as strings, missing values and features mixing strings and numbers. Regular expressions were used to identify the odd values and treat them appropriately. (with a little help from https://regexr.com/ and chatGPT)
 
## Second step: Statistical analysis

Great. Now that we have a more workable dataframe, let's search for some answers. The follwing questions popped up in my mind while writing this code. Hopefully, you can make different ones.

### Historical questions:
- [X] How many states produce wind power today?
- [X] How many states produce wind power in a specific moment in history?
- [X] What was the first state to start producing?
- [X] What was the last state to start producing?
- [X] Who has been producing the longest?

### Overall production:
- [ ] The ratio of producers/total
- [ ] The ratio of producers/non-producers
- [ ] What's the average wind-power production over US?
- [ ] What's the average wind-power production over US per state?
- [X] Which state produces the most?
- [ ] Which state produces the least (considering that it produces at all)?
- [ ] How much wind-power is produced compared to other sources?

### Annual production:
- [X] Which time of the year has the pick production overall?
- [X] Which time of the year has the lowest production overall?
