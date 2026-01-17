# House Price Index Change 1991-2025

At it's core the House Price Index Change 1991-2025 project tracks the change in the Housing Price Index (HPI) provided by the Federal Housing Finance Agency (FHFA) from 1991-2025. Although I am mainly focused on the metropolitan area of Louisville, KY, this can be used to review other metropolitan areas as well. Among the questions I would like to answer are:

*What is the increase in HPI for Louisville, KY from 1991-2025?

*How does Louisville's HPI relate to the rest of the state?

*How does Louisville's HPI relate to other metropolitan areas of the same size?

*How does Louisville's HPI relate to it Census geographical regoin?

*Is Louisville above or below the nation HPI in 2025?

## Visualization Example
<img width="853" height="701" alt="output" src="https://github.com/user-attachments/assets/752d4146-4e38-487e-b6b7-a005ae7b5c57" />

This visual displays the rise in HPI over Louisville and six other cities of a similar size. Salt Lake City Utah is a significant 
outlier in this dataset having the highest HPI in the Unites States amongst the 100 largest metropolitan areas.


## How to Use
1. Clone this repository.
2. Install the required Python packages:  
   pip install -r requirements.txt
3. Open `housing_price_data.ipynb` in Jupyter Notebook

## Data Sources
1. HPI Master CSV from https://www.fhfa.gov/data/hpi/datasets?tab=master-hpi-data(historical (provided in 'data/')
2. Population Est Totals from https://www.census.gov/data/tables/time-series/demo/popest/2020s-total-metro-and-micro-statistical-areas.html (provided in 'data/')

 ## Author
 Ryan Hyman
