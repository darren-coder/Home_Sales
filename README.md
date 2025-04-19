# Home_Sales

This assignment was to use use PySpark in Google Colab to write some SQL queries. A dataframe was read in from the provided URL. SparkSQL was used to create temporary views and cache and uncache a temporary table. One of the queries was timed to note the difference in run time between uncached, cached, and parquet data. The run times are below.

##### Uncached
--- 1.3788704872131348 seconds ---

#### Cached
--- 0.6164233684539795 seconds ---

#### Parquet
--- 1.119100570678711 seconds ---