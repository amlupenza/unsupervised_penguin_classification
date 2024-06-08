# Penguin Clustering with K-Means
This project explores unsupervised machine learning techniques, specifically K-means clustering, to analyze a penguin dataset and discover hidden patterns within the data. This project is also one of the activities
in google advanced data anlytics professional certificate.

## Data:

The dataset consists of 345 penguin observations. Each datapoint includes features like:
* Species (e.g., Adelie, Chinstrap, Gentoo)
* Island (location where observed)
* Sex (male or female)

## Goal

Utilize K-means clustering to group penguins based on similarities in their characteristics.
Identify meaningful patterns within the clusters to gain insights about penguin behavior and habitat preferences.

## Methodology

**Data Preprocessing**: We explored the data to understand its structure and potentially cleaned it (handling missing values).

**Feature Engineering**: Features were standardized using StandardScaler.

**K-Means Clustering**: We implemented the K-means algorithm to group penguins into a predefined number of clusters.
Through analysis techniques like silhouette analysis and inertia, we determined that an optimal number of **6 clusters** best represents the data.

**Cluster Analysis**: We meticulously analyzed the resulting 6 clusters and their characteristics:
* The clusters effectively separated penguins by both sex and species.
* We observed clusters containing primarily male or female penguins of specific species (e.g., Adelie penguins in separate clusters for males and females).
  
## Expected Outcome

1. Identify meaningful patterns within the penguin data based on the formed 6 clusters.
2. Gain valuable insights about the relationship between sex and species within the clusters.
   
## Project Files

The project includes code for data loading, preprocessing, clustering, and visualization (exploratory data analysis and cluster visualizations).

## Future Exploration

This initial analysis can be extended to explore additional features or investigate specific penguin species in more detail.
Different unsupervised learning algorithms could be compared to K-means for potential improvements.
Feel free to explore the code and experiment with different parameters!

