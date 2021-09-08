# CIA-Country-Analysis-and-Clustering
CIA Country Analysis and Clustering with KMeans

[Source: All these data sets are made up of data from the US government](https://www.cia.gov/library/publications/the-world-factbook/docs/faqs.html)


[Click here to see the whole codes!](A-Country-Analysis-and-Clustering/blob/main/CIA_Country_Analysis_and_Clustering_w_Kmeans.ipynb)
# Goal :
Gain insights into similarity between countries and regions of the world by experimenting with different cluster amounts. What do these clusters represent?

## Exploratory Data Analysis
## Visualisasi
![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/gdp%20vs%20phone.png)


***Features Correlation***

![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/corr().png)
![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/clustermap.png)

## Data Preparation
### Missing Values

## Data Feature Preparation

## Creating and Fitting Kmeans Model
Use a for loop to create and fit multiple KMeans models, testing from K=2-30 clusters. Keep track of the Sum of Squared Distances for each K value, then plot this out to create an "elbow" plot of K versus SSD. Optional: You may also want to create a bar plot showing the SSD difference from the previous cluster.

![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/elbow.png)


![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/elbow%20diff.png)

## Model Interpretation
What K value do you think is a good choice? Are there multiple reasonable choices? What features are helping define these cluster choices. As this is unsupervised learning, there is no 100% correct answer here. Please feel free to jump to the solutions for a full discussion on this! 

Example Interpretation: Choosing K=3
One could say that there is a significant drop off in SSD difference at K=3 (although we can see it continues to drop off past this).

## Geographical Model Interpretation
The best way to interpret this model is through visualizing the clusters of countries on a map!

![alt text](https://github.com/docum5/CIA-Country-Analysis-and-Clustering/blob/main/kmeans%20clustering.png)
