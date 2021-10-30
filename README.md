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
