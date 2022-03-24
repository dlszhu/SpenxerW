# Executive Summary
## Undervalued Rental Housing Markets Identification

The DSO 597 Consulting Project Team 2 has collected and leveraged the Yardi Matrix’s rental property information, US Census data and geographical location information 
of hospitals, grocery stores, etc. to develop 4 different supervised machine learning models and found the Top 5 undervalued rental housing “markets” defined by Yardi 
Matrix across 19 states and 22,452 rental properties: Northern Arizona University (Flagstaff, AZ), New Orleans (LA), Boise (ID), Miami (FL) and Albuquerque (NM). 

The goal of our analysis is to understand what factors drive the growth of rent with the exploration of our datasets, and to create a predictive model to identify the 
geographical areas as well as specific properties that could yield high rent growth. The team collected, cleaned and manipulated various datasets for exploratory data 
analysis and building the machine learning models. The property data was normalized and cleaned to create our dependent variables “Rent Per SQFT” and other building 
features like age. The demographic characteristics data like employment and population of the census tract the properties locating in was compiled from ACS 2016 and US 
Census 2010. Additional features of neighborhood amenities like number of hospital, grocery stores and Starbucks within certain radius of the properties were generated 
as independent variables in our model. 

Through our exploratory data analysis we found positive association between the rent per square feet and the quality of the building (age, improvement and location rating
by Yardi), the local growth  of population and employment opportunities, income and education level of local population. Based on the findings, we created our predictive 
model to identify rental housing markets with highly desirable conditions but abnormally low rent, as those would be considered “undervalued markets”. 4 supervised 
machine learning models of Decision Tree, Random Forest, Extremet Gradient Boost and Elastic net were implemented. Each property and “market” record was assigned 4 
anomaly scores from each model. We ranked them by the average anomaly score from high to low, hence finding our top 5 markets.

We found major job hubs with a recent-year high growth of employment opportunities in our top markets like Miami, Boise and Albuquerque. According to Census, during the 
pandemic era these regions also absorbed many remote-work population inflow from states like California and New York. Within currently hot and tight inventory markets 
with close-to-100% occupancy rate; on average decent building age (<40) with good improvement rating (B or above). Neighborhood amenities abundant indicated by Locating 
Rating and our features of number of Starbucks and Grocery.

Miami, FL, Albuquerque, NM and Boise, ID are the major metropolitan areas and local economy powerhouses. Both cities have had large population and job growth in the past 
few years. Overall “Sun Belt” tech and manufacturing hubs maintains the leading ranks of rental market with business and worker moving in. The growth in 2021 was largely 
fueled by accelerated domestic migration and job growth. Miami has a rent growth rate of 22.6 percent for the past year. Markets with the highest percentage of jobs in 
“at-risk employment sectors” during the pandemic like Miami withstood the impacts, as they were supported by robust in-migration from higher-cost states like California 
and New York. We also found substantial amount of high-quality housing properties with potential of rent growth: characterized by high location and improvement rating 
(B or above), and on average high occupancy rate of over 95% (as benchmark, we could push for more revenue on building with over 96% occupancy rate).

Northern Arizona University (defined by Yardi) or Flagstaff, Arizona was a unique small city our model discovered with rent growth potential. It is a mid-size college 
town with travel destinations (national monuments, ski resorts) and proximity to Phoenix, AZ (1.5-hour drive). Local population has grown steadily for the past years. 
The domestic migration influx has put a squeeze on the housing market while the current inventory is relatively limited. A similar case we see from Reno, NV and 
Colorado Spring, CO, which is also on our top records. 

New Orleans has substantial population and employment growth ever since the post-Katrina era. The number of high-rated properties of New Orleans is highest among all 
top 5 regions, similarly due to the city-wide rebuild. Over the past 10-year period New Orleans’ population has grown over 11%. Manufacturing and Leisure employment 
remain growing, benefited by the reopening from COVID-19. 
