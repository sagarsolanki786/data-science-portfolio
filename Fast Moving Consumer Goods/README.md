New DG Food Agro is a multinational exporter of various grains from India for nearly 130 years but their main product of exporting since the early 1980s has been Wheat. They export wheat to 207 countries. They started seeing varying exports of sales year on year for various countries. The reason that was theorized by them had a lot of natural causes like floods, country growth, population explosion etc.

Now they need to decide which countries fall in the same range of export and which don’t. They also need to know which countries export is low and can be improved and which countries are performing very well across the years. What they need is a repeatable solution which won’t get affected no matter how much data is added across time and that they should be able to explain the data across years in less number of variables.

Please click this link https://bit.ly/2nlT9WS to view the notebook with complete rendering of plotly world map plots.

The solution was applied as follows:
1. Data cleaning
2. Data preprocessing and principal component analysis.
3. KMeans Clustering algorithm was applied to find out how many clusters the data can be separated into  using Elbow Curve method.
4. Hyperparameter tuning using 10 fold cross-validation was done to find out the best possible combination of hyperparameters.
5. Finally, countries were clustered on a world map to showcase which of them belong to the same cluster. Higher the cluster number, greater the sales for a country. This helps the company to redesign the sales strategy and target countries with low sales.
