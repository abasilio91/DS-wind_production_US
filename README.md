updated at: 2023-05-14 (commit: cleaning data and setting the goals)
# A Statitstical study over the wind power prodution in US from 2001-2023

This notebook aims to perform some basic analysis over the data provided in [this Kaggle dataset](https://www.kaggle.com/datasets/henriupton/wind-power-production-us-2001-2023). Information about it says the information comes from official entities of the administration.

Disclaimer: please, bear in mind that I am not american, nor I live in the US. So the analysis here is based solely on the information from the dataset itself. 

## First step: Exploring, understanding and cleaning the data

Exploring the data revealed some inconsistences such as numeric values as strings, missing values and features mixing strings and numbers. Regular expressions were used to identify the odd values and treat them appropriately. (with a little help from https://regexr.com/ and chatGPT)
 
## Second step - Statistical analysis

Now, with a more workable dataframe, let's search for some answers:

- [ ] What's the average wind-power production over US?
- [ ] What's the average wind-power production over US per state?
- [ ] Which state produces the most?
- [ ] Which state produces the least (considering that it produces at all)?
- [ ] How much wind-power is produced compared to other sources?
- [ ] What was the first state to start producing?
- [ ] What was the last state to start producing?
- [ ] Which time of the year has the pick production overall? and by state?
- [ ] Which time of the year has the lowest production overall? and by state?
