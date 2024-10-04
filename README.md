# Analysis Effects of Gas Extraxtion on Dutch Real Estate

This project analyses the effects of gas extraction on Dutch real estate in the province of Groningen, The Netherlands. 


Since 1997, Groningen has been plagued with earthquakes caused by the extraction of natural gas. Over 1120 induced earthquakes have occurred that caused damage on over 85,000 properties. This research will analyse whether there is a relation between earthquake damages and affected real estate value and demand.

## Requirements
Please see the requirements text file to see what libraries are necessary to use this repository.

## Hypotheses formed
	1. Gas extraction has a negative impact on local real estate value
	2. Areas impacted by gas extraction are less occupied than areas that are not impacted

## Dataset
Data was obtained by the CBS in the form of CSV files. Additonally there was looked into API sources provided by the Dutch KNMI, but these turned out to become redundant.

## Data cleaning and combining
Some general cleaning tasks have been performed on the raw datasets, and these have later been joined to achieve a long time range. Cleaning tasks included:
- Remove redundant columns;
- Formatting column titles;
- Converting date columns to date formats;

Important:
NaN values have been kept to keep datasets as informative as possible: cutting NaN would reduce the dataset to a size that could not be worked with.

> Cleaning notebooks can be accessed by files in /notebooks/cleaning_***.ipynb or /combining_***.ipynb or /joining_***.ipynb.

## Analysis
The analysis was partly visual and party through statistical t-testing in Tableau and Python.

## Findings
1. **Gas extraction has a negative impact on local real estate value**: there was sufficient information gathered that supports this hypothesis.
2. **Areas impacted by gas extraction are less occupied than areas that are not impacted**: There was no evidence found that supports this hypothesis.

## Challenges
- Complete historical real estate data was only available for just a few impacted cities/villages;
- From the real estate data that was obtained, a lot of timeframe periods made them unsuitable;
- Inventory and occupation figures were only available from 2012 to 2024.

## limitations
Due to the many factor influencing real estate values and pricing, it is still very hard to conclude whether earthquakes are to blame for a lower real estate price. There is a possibility that the price is lower due to countless possible alternative factors that have not been researched.

## Recommendations
Additional in-dept research needs to be done to include more independent variables. However, due to the uniqueness of each region, finding appropriate benchmarks will remain to be difficult due to the variety of independent factors influencing price and availability. A suggestion is that a combination of qualitative and quantitative studies needs to be done in order to get a full picture on the effects of gas extraction and its effects on real estate values.



