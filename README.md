# **Airbnb Berlin — Exploratory Data Analysis 2024**
![68747470733a2f2f7777772e62722e64652f756e7465726e65686d656e2f696e68616c742f6f7267616e69736174696f6e2f6b6f72726573706f6e64656e74656e2f6265726c696e2d646575747363686c616e642d73747564696f2d3130307e5f762d696d675f5f31365f5f3](https://github.com/user-attachments/assets/399350a3-5647-4d31-aee6-0a010330ff9e)
## Summary
### Airbnb is an online platform that allows property owners, or hosts, to rent accommodations to travelers. The company takes a percentage of a host's booking through a split fee paid by the host and guest or a host-only fee.
#### In recent years, Berlin has encountered a number of challenges due to the rise of Airbnb and other short-term rental platforms. To address these issues, the city has introduced strict regulations, restricting short-term rentals in certain neighborhoods. These measures have sparked concerns about the availability of affordable housing for long-term residents and the overall impact on the housing market. Additionally, the growing demand for short-term stays has increased pressure on urban infrastructure, including public transportation, raising questions about the long-term sustainability of this trend. The situation remains complex and continues to be the focus of public debate and policy discussions.

## Dataset
### For this project we are analyzing Berlin’s Airbnb data from 2009 to 2024.
### The dataset is publicly available at [site](http://insideairbnb.com/get-the-data.html)

| Field | Description |
|-------|-------------|
| id                          | A unique identifier for each listing in the dataset.|
| date                        | The specific date associated with the listing or the review (often corresponds to when the data was recorded).                               |
| name                        | The name or title of the Airbnb listing, often provided by the host.|
| host_id                     | The neighbourhood group as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles A unique identifier for the host who owns the listing. |
| host_name                   | The name of the host                                                                 |
| neighbourhood_group         | The general region or area the listing is located in. It might refer to a large geographical area like a district or a collection of neighborhoods.                                     |
| neighbourhood                    | The general region or area the listing is located in. It might refer to a large geographical area like a district or a collection of neighborhoods. |
| latitude                   | The geographic latitude of the listing (helps locate the property on a map). |
| longitude                          | The geographic longitude of the listing (helps locate the property on a map).|
| room_type                        | The type of room being rented (e.g., Entire home/apt, Private room, Shared room).                               |
| price                        | The price per night for booking the listing.|
| number_of_reviews                     | The total number of reviews received by the listing. |
| reviews_per_month                   | The average number of reviews the listing receives per month.                                                                |
| calculated_host_listings_count                | The total number of listings owned by the host.                                        |
| availability_365                    | The number of days in a year (365) that the listing is available for booking. |
| name_lang                   | The language of the listing’s name (e.g., English, German, etc.). |
| year                    | The year the data was recorded or the review was posted. |
| month                   | The month the data was recorded or the review was posted. |

## Tools
### 1. [Python](https://www.python.org/)
### 2. [Jupyter Notebook](https://jupyter.org/)
### 3. [Pandas](https://pandas.pydata.org/)
### 4. [GeoPandas](https://geopandas.org/en/stable/)
### 5. [Matplotlib](https://matplotlib.org/)
### 6. [Seaborn](https://seaborn.pydata.org/)

## Analysis
### We will uncover insights on:

##### 1. Listings types: Company 'Airbnb' offers a room or a shared room within one's home. Is it so?
##### 2. Neighborhoods: Are listings evenly spread across neighborhoods or are there hotspots?
##### 3. Ownership: are properties owned by individual users or are there users with multiple rental properties (i.e. potentially for speculation)?
##### 4. Prices: What does mostly the price depend on?
##### 5. Trends and Seasonality: Is the flow of tourists seasonal, that is does it follow a seasonal trend? Can we explain the pattern?
