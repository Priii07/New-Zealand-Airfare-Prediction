# New-Zealand-Airfare-Prediction Using PySpark

### Objective: 
Analysis is being done on airline pricing practices and competition for airline carriers in New Zealand. The data set displays domestic airfares for New Zealand airlines on various domestic routes, especially for Air New Zealand, Jetstar, and SoundAir. Based on the above characteristics, the airlines compete with one another to predict domestic fares for various New Zealand carriers.
 
## Data Set Description: 

- Overview: By analyzing all the independent features with our dependent variable(fare) we will be predicting the price of the fare.
- Number of rows and cols- We have 162833 rows and 11 columns.
- Sample predictors:  Below is the list of Sample predictors:
- Travel Date- Day the person is boarding the flight
- Departure Airport: Flight departure airport
- Arr. Airport- Arrival airport 
- Duration: Total duration of the flight i.e., time
- Direct- Flight has in between stops or not.
- Transit- Stopover at a particular airport
- Baggage- Is the check-in bag allowed with the fare.
- Airline- Airline chosen by the traveler.
- Airfare-Price of the ticket (Target Variable)
- Data Set link- NZ_Airfares
- Interesting Facts
    - The data was collected by Expedia group, one of the biggest online travel company and it is from Year 2019.
    - Major airlines in NZ are ‘Air New Zealand’ and ‘Jetsar’.
	  - The data set ranges from 19th September 2019 to 18th  December 2019,  a total of 90 days.
	  - There are 26 airport pairs.
    
## Preliminary Data Exploration:

	- To begin with the shape of the data set is 162833 rows and 11 columns.
	- After removing all the Null Values the shape is 162804 rows and 11 columns.
	- Data type of all the columns is ‘str’ which is changed to their respective data types for e.g., all the data columns were encoded as ‘str’ so we 	     changed it to datetime.
	- Maximum Fare Price is $1364 , Minimum Fare Price is $32 and Average Fare Price is $411.
	- The primary airports are: Auckland (AKL), Christchurch(CHC), Wellington(WLG) and Queenstown(ZQN). 
	- Secondary airport are: Dunedin (DUD), Napier/Hastings(NPE), New Plymouth(NPL), Nelson(NSN) and Palmerston North(PMR).
	- There are 52 one way routes, out of which 12 are trunk routes i.e., between primary airports and 40 secondary routes.
	

