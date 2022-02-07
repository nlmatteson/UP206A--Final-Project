#### **Project Proposal**

# Impact of BART's TOD Projects on Housing Accessibility and Affordability

## Introduction and Research Question
	
Research Question: How has BART TOD projects changed nearby communities in regards to rent burden and ethnicity demographics?

For our project, we hope to analyze how Bay Area Rapid Transit’s (BART) completed Transit-Oriented Development (TOD) projects have impacted the nearby communities, specifically considering the equity implications. We have researched changes in rent burden and ethnicity for census tracts in Alameda County between 2011 and 2019.

## Why it is important
	
Transit Oriented Development has been appraised by government officials and planners as a means to accommodate increasing populations without sprawl. Seen as a sustainable development strategy, TOD projects have numerous benefits including; increase public transit ridership, revitalize neighborhoods, reduce traffic congestion and associated impacts of single occupancy vehicle dominated travel, increase housing supply, and encourage physical activity. Despite these benefits, TOD projects have also shown to induce gentrification which has significant equity implications. Those who are priced out of their neighborhoods are forced to leave while others who can afford to live in the newly renovated area reap the benefits. TOD projects can therefore be a vehicle for continued social stratification, or it can be a solution.
	
It is crucial for TOD projects to ensure the benefits of the project are equitable and improve the livelihoods of the entire community. This topic is important to our group because we, as planners in the making, want to make sure we are contributing to the communities we serve in a way which promotes equity. The planning profession has had a history of inequities. We do not want to be another generation who ignores disempowered communities. Equity is a main pillar of sustainability and is essential for climate change adaptation. The State of California has encouraged cities to build TOD projects, but they must be done carefully to ensure the outcomes are equitable.  

## Spatial and Temporal Scope
	
Our project area of focus takes place in Alameda County. We have chosen 5 completed BART TOD projects: 
​​Fruitvale Transit Village (Fruitvale BART- Oakland)
Hayward Bart Station (Hayward)
MacArthur BART station (Oakland)
South Hayward BART station (Hayward)
Ashby BART station (Berkeley)
Since the project effects project hopes to look at are within the counties, lower level data specifications, like that at a zip-code level, will be required.

Since the project aims to map the change, temporal specification is important for the project. We are comparing equity implications from 2011 (before many TOD projects were built and enough time after the 2008 recession) and 2019 (when many of the projects have been completed). We need to compare between these two time periods because we need to see what and how things changed. We will also compared these changes to the County average, to see if the areas around these completed TOD projects have improved or worsened rent burden and if gentrification has taken place. 

## Data

The following data sources are used for the project

### TOD project locations in the BART System

The BART website has a summary and list of all of their completed TOD projects. From this list, we picked five we wished to focus on.

Source:
https://www.bart.gov/about/business/tod/completed 

### 5 TOD BART Stations

We were able to download a geoJSON file of all of California’s rail transit stops. After an arduous process of cleaning the data, we were able to isolate the key BART stations for our analysis.

Source: https://gis.data.ca.gov/datasets/63697b01616b4df68e2b316e73d7a4d6/explore?filters=eyJDT01NX05FVFdPIjpbIkJBUlQiXX0%3D&location=37.828312%2C-122.221573%2C12.57&showTable=true

### Housing Data: 

Rent Burden data was obtained from data.census.org. Rent burden is based on gross rent as a percentage of household income. 

2011: https://data.census.gov/cedsci/table?q=Alameda%20County,%20California&t=Renter%20Costs&g=0500000US06001%241400000&y=2011&tid=ACSDT5Y2011.B25070 

2019: https://data.census.gov/cedsci/table?q=Alameda%20County,%20California&t=Renter%20Costs&g=0500000US06001%241400000&y=2019&tid=ACSDT5Y2019.B25070

## 2019 Census Tract Ethnicity Data from Census Reporter

Data on demographics and employment/income will be used along with housing data to assess housing accessibility. 

2019: https://censusreporter.org/data/table/?table=B03002&geo_ids=05000US06001,140|05000US06001&primary_geo_id=05000US06001 

## 2011 Census Tract Ethicity Data from Data.census.org

2011: 


## Intended analysis and Visualizations

The project will establish housing affordability and accessibility indexes for periods before and after the TOD project(s) is completed. Affordability will be derived from information on housing costs, and rents. Accessibility will be calculated based on population characteristics including demographics, and income.

Primary product of the project is a visualization of changes to the affordability and accessibility indexes in the pre and post-project periods. Inclusion of neighboring regions in the project should enable us to track any patterns of gentrification due to the BART TOP Projects. 

## Conclusion

California’s deep housing crisis clears the way for TOD projects along key corridors. However these projects often increase land values in neighborhoods, forcing older residents out of their homes, only to exacerbate the issue of commute and access to transit. In this project, we hope to find some evidence for TOD-related gentrification in the form of changes to affordability and accessibility of housing around the project areas. 
 
## Midterm Notebooks
**Nicole’s:**

1. This first notebook is her first notebook of two where she analyzes rent burden data. In this notebook, she imports 2011 and 2019 rent burden data, provides links to the data sources, cleans them individually, explores their content, then merges them into one file. She then downloads a census tract shapefile to merge with the rent burden data, as they were CSVs. She then creates two different variables. One variable is the combined 2019 and 2011 datasets that turned into a shapefile. The second is a cleaned dataset that calculates the percent change between the two years. She attempted to create maps, but ran out of memory.

 https://github.com/nlmatteson/UP206A--Final_Project/blob/aa3cba5e3833c633717a1c0040c6ef30dcb9fca5/Midterm/Nicole's%20Portion/Rent_Burden.ipynb 

2. This second notebook is a continuation of the first, but with more memory. In this notebook, it provides the research question, conducts exploration on the variables, creates maps, conducts some basic statistics (mean, distribution), and creates two charts (one being an improvement of the other). The final cell details the division of work. 

https://github.com/nlmatteson/UP206A--Final_Project/blob/aa3cba5e3833c633717a1c0040c6ef30dcb9fca5/Midterm/Nicole's%20Portion/RentBurden_pt2.ipynb 




**Chaithra’s:**
 
