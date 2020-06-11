# Coursera Capstone Final Deliverable

## Introduction
The buisness problem I chose to solve was finding prime real estate within Toronto for opening a new restaurant in a housing community where there is a lack of available food choices. This is a prevelant problem as location has a large effect on the earnings of restaurants (if they are too far from large communities, if they have strong competition from other local stores, etc.).

## Data
The data I used came from two sources: four square, and the City of Toronto. The four square data is similar to what was collected during earlier labs, but with a wider focus of any store which sells food (i.e. a restaurant, grocery store, or fast food). The City of Toronto data gave me a selection of homes which I used in the selection of four square locations. This data can be found here: https://open.toronto.ca/dataset/toronto-community-housing-data/

## Methodology

I started this project by collecting the home data from the City of Toronto. This is the best source I could find regarding housing data (albeit was lacking in data points). The data provided me developmental data, community names, and most importantly geographical locations of homes. I removed certain columns which were not prevelant to the investigation, split the location column into two seperate columns (latitude and longitude). I also clustered the houses using the DBSCAN model to get a good idea of what communities were available. I then used the locations from the previous step to generate a list of food related stores using four square, and processed the data using pandas until it was what I needed. I then generated a map using folium of the gathered locations. With this map I could easily spot areas where there are housing communities but a lack of available food options, meaning good locations for new restaurants to open without competition and a large consumer base.

## Results
What I found by using the generated map was there are good locations available around these communities: Sheppard Yatescastle, Jane St., Midland Ave., and Mornelle Ellesmere. These properities show large communities with wide areas of empty food real estate. Some have to travel long distances to reach clusters of restaurants.

## Discussion
I would recommend opening a restaurant south of the Sheppard Yatescastle community as they are large than the others noted above and still have similar difficulties reaching food spots.

## Conclussion
After analyzing the data of Toronto housing communities and food located around them, I have found that the Sheppard Yatescastle community has prime real estate for opening a successful restaurant based on the lack of competition, available space, and large population in the area.
