# King-County-House-Sales-Analysis
**Project Overview:** 
King County, situated in Washington, USA, is the most populous county in the state, located in the western part, encompassing the city of Seattle. Renowned for its diverse geography and extensive coastline along the Puget Sound, King County serves as a hub for technology, commerce, and tourism.
As part of the Seattle-Tacoma-Bellevue metropolitan statistical area, King County is one of three Washington counties included in this region. Approximately two-thirds of the population resides in the suburbs of Seattle. This statistical analysis aims to provide insights into the distribution of house prices in King County.

**The Data:**
This information is sourced from publicly available open-source data. 
The dataset utilized for this analysis comprises administrative data on more than 21,000 house sales occurring between May 2014 and May 2015. This data is derived from the official public records of property sales in the King County area, Washington state.

**Key Questions:**

1.How much are houses selling for in King County?

2.How do features of a house affect its price?

3.How does the location of a house affect its price?


**Independent Variables/Features: All are numerical Data**

1.id - unique identifier of a house

2.date - house sale date

3.bedrooms -  numbers of bedrooms

4.bathrooms -  numbers of bathrooms

5.sqft_living - square footage of house's living space

6.sqft_lot - square footage of lot

7.floors - number of floors (levels) in house

8.waterfront - has waterfront view

9.view - index 0-4, rating of the views from the house

10.condition - index 0-5, rating of the house’s condition

11.grade -  index 1-13, rating of the house’s construction/design

12.sqft_above -  square footage of house excluding basement

13.sqft_basement -  square footage of house basement

14.yr_built - house built year

15.yr_renovated - house renovated year

16.zipcode - zipcode of king county city

17.lat - lattitude coordinate

18.long - longitude coordinate

19.sqft_living15 - square footage of living space for the nearest 15 neighbors

20.sqft_lot15 - square footage of lot for the nearest 15 neighbors

21.price - price of the house

**Tools and Project Deliverables:**

In this project, I utilized Python along with several libraries:

**_Data Analysis_**:

**pandas and numpy:** These were employed for data analysis, manipulation, and numerical operations.

**_Data Visualizations:_**

**matplotlib and seaborn**: These libraries were used to create visualizations and graphs for better data understanding.

**folium:** It was utilized for geographic visualizations, adding a spatial aspect to the analysis.

**_Machine Learning:_**
sklearn: This library played a crucial role in implementing both supervised (regression) and unsupervised (clustering) machine learning tasks.
