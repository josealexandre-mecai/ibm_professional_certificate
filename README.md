# ibm_professional_certificate
Material related to the IBM Data Science Professsional Certificate

For this project, we will use the following data:

- Data from restaurants situated at the main regions of São Paulo, including Locality, Cuisines, Restaurant Names, Rating, Latitude, Longitude, etc.:
    - Data source: Zomato kaggle dataset. This dataset contains the required information to explore various localities of São Paulo.

- Data from nearby places in each locality of the main regions of São Paulo:
    - Data source: Foursquare API. By using this API we will get all the venues in each neighborhood.

The following methodology will be applied:

- Collect restaurants data from Zomato Kaggle dataset.
- Clean up data.
- Visualize data using Folium Python library.
- Generate plots to compare each locality with regards to restaurants.
- Group data based on locality.
- Use Foursquare API to find all venues for each neighborhood.
- Filter out all nearby venues by locality.
- Use aggregate rating from each restaurant to find the best places.
- Run k-means to cluster the localities into 5 clusters.
