
![FHFA](https://github.com/user-attachments/assets/58b4a95a-9635-4253-8015-3c7ed7d86b4d)


# House Price Index Change 1991-2025

At it's core the House Price Index Change 1991-2025 project tracks the change in the Housing Price Index (HPI) provided by the Federal Housing Finance Agency (FHFA) from 1991-2025. Although I am mainly focused on the metropolitan area of Louisville, KY, this can be used to review other metropolitan areas as well. In the plainest terms HPI data for this set started with 1991. 100 = 0 and any icrease from 100 is a percent uptick. For example, Louisville started at 100 in 1991 by 1994 Louisville was at about 140 which represents a 40% increase in the HPI index which, in turn, correlates to traditional homes in Louisville costing 40% more. 

## Questions I Would Like to Answer
1. What is the increase in HPI for Louisville, KY from 1991-2025?
2. How does Louisville's HPI relate to the rest of the state?
3. How does Louisville's HPI relate to other metropolitan areas of the same size?
4. How does Louisville's HPI relate to it Census geographical regoin?
5. Is Louisville above or below the nation HPI in 2025?

## Visualization Example
<img width="853" height="701" alt="louisville_compared_to_similar_cities" src="https://github.com/user-attachments/assets/b0f8a991-7b03-42c0-afc6-6876bc6082c5" />


The visual above displays the HPI data for with cities with a population similar to Louisville(+- 100,000).
All cities have seen an exponential increase in HPI starting in 2020 with the almost verticle trend
continuing up to the last year of data, 2025


## How to Use
1. Clone this repository.
2. Install the required Python packages:  
   pip install -r requirements.txt
3. Open `housing_price_data.ipynb` in Jupyter Notebook

## Data Sources
1. HPI Master CSV from https://www.fhfa.gov/data/hpi/datasets?tab=master-hpi-data(historical (provided in 'data/')
2. Population Est Totals CSV from https://www.census.gov/data/tables/time-series/demo/popest/2020s-total-metro-and-micro-statistical-areas.html (provided in 'data/')

## Next Steps
1. Locate a dataset which coontains historical Median Household Income ideally going back to 1991 for the metropolitan areas contained in the HPI dataset.
2. Compare the rise over time in Median Household Income to the rise over time in HPI.
3. Is Median Houshold Income keeping up the increase in HPI?

 ## Author
 Ryan Hyman
