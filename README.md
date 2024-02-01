## AirBnB_Listings_Analysis_Python

#### Airbnb data for 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews.
the dataset was downloaded from the free Data Playground of MavenAnalytics. [https://mavenanalytics.io/data-playground?search=ai]

### Objective 1 : Profile and explore the data
#### Import/open the listing.csv
#### Cast any date columns as datetime format
#### Filtering the data down to rows where the city is Paris, and keep only the columns 'host_since', 'neighbourhood','city','accommodates', and 'price' in the table
#### checking for missing values, and calculate the minimum,maximum, and average for each numeric field.


### Objective 2 : Prepare for visualization
#### Creating a table named paris_listings_neighbourhood,that groups Paris listing by 'neighbourhood' and calculates the mean price for each neighborhood sorted from lowest to highest average price.

#### Then, creating a table named paris_listings_accomodations, neighborhood in Paris, grouped by the 'accommodations' column, and contain the mean price for each value of 'accommodates' sorted from lowest to highest average price.

#### Finally, creating a table called paris_listings_over_time, which is grouped by the year of the 'host_since' column. Calculate a count of rows, representing total number of new hosts, and the average price for each year.

### Objective 3:Data Visualization
#### Create a horizontal bar chart of the average price by neighborhood in Paris.

#### Create a horizontal bar chart of the average price by 'accommodates' in Paris most expensive neighborhood.

#### Create two line charts : one of the count of new hosts over time, and one for average price.

#### Based on your findings, what insights do you have about the impact of the 2015 regulations on new hosts and prices?
