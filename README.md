# Surfs Up Analysis
Follow the link to reach Data Sources:[Surfs Up Analysis](https://github.com/JohnCselcuk/surfs_up)

We used several tools to complete this Analysis:
- Jupyter Notebook
- VS Code 
- Python 3
- Flask application
- Matplotlib
- SQLite and SQLAlchemy
- Pandas and Numpy

## Overview of Analysis
The goal of this analysis is, Fictional company Waves and Ice Cream wants to determine if opening a surf shop in Oahu, Hawaii has good business value. Temperature data for the months of June and December were analyzed to assist in determining if a surf and ice cream shop business is sustainable year-round.

## Results

### June and December Temperature Analysis
Based on the analysis, using Python, Pandas , and SQLAlchemy, the date column of the Measurements table was filtered in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. Those temperatures were converted to a list, a DataFrame was created from those lists, and then summary statistics were generated for each dataset.

#### June temperature statistics;
![June Temps](https://user-images.githubusercontent.com/85411967/139533230-894297f8-bb73-4f8b-bb0c-6dac051d30ed.png)

#### December temperature statistics;
![December Temps](https://user-images.githubusercontent.com/85411967/139533273-9ca493d7-4c3b-4d1e-821a-b075be3d1ab2.png)

#### Comparing the temperatures for the two month;

- There were 12% more temperature points for June than there were for December.
- The average temperature for December was 71 degrees, which is nearly four degrees cooler than June's average temperature of 74.9 degrees.
- The maximum temperature for June was 85 degrees, which is only two degrees warmer than December's maximum temperature of 83 degrees

## Summary
From our data we can tell what our temperatures are but since there are other attributes to the weather such as precipitation it shows that we can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries! From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.

Thank you for your time,

John
