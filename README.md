Explore, segment, and cluster the neighborhoods in the city of Toronto.
Scraping the Wikipedia page and wrangling the data, and then reading it into a pandas dataframe so that it is in a structured format.
The dataframe consist of three columns: PostalCode, Borough, and Neighborhood.
Cells with no Borough have been ignored.
More than one neighborhood can exist in one postal code area. These rows are be combined into one row with the neighborhoods separated with a comma.
If a cell has a borough but a Not assigned neighborhood, then the neighborhood is the same as the borough.
-----------------------------------------------------------------------------------------------------------------------
In order to utilize the Foursquare location data, we get the latitude and the longitude coordinates of each neighborhood.
Explore and cluster the neighborhoods in Toronto. Only boroughs that contain the word 'Toronto' have been worked on. 
------------------------------------------------------------------------------------------------------------------------
