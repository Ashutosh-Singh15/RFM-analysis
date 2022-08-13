# Customer Segmentaton using RFM analysis
## Data Cleaning
* Checked for missing data.Filled the null CustomerID values with 10 frequent values and equally distributed them.
* Removed duplicate data records.
## Data Transformation
* Performed Cohort analysis. Analyzed active customers for each cohort.
* Analyzed Retention Rate of the customers.
## Data modelling(RFM analysis)
* Built an RFM (Recency Frequency Monetary) model(Period:1 year)
* Calculated RFM metrics. Added them(as strings) get an RFM segment. Also, added the individual scores in order to get an RFM score.
* Analyzed the RFM segments and commented on the findings.
## Data modelling(KMeans)
* Prepared the data for the algorithm. If the data was asymmetrically distributed, managed the skewness with log transformation. Scaled the data using StandardScaler.
* Found the optimal number of clusters(elbow method). Performed clustering using Kmeans.
* Analysed the clusters and commented on the findings.
## Data visualization([Dashboard link](https://public.tableau.com/app/profile/ashutoshsinghwastaken/viz/Project3RetailDashboard/Dashboard1))
* Country-wise analysis to demonstrate average spend. Used a bar chart to show the monthly figures.
* Made a Bar graph of top 15 products which were mostly ordered by the users to show the number of products sold
* Made a Bar graph to show the count of orders vs. hours throughout the day
* Plotted the distribution of RFM values using histogram
* Visualized to compare the RFM score of the clusters using heatmap
