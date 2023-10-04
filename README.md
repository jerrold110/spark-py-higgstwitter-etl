## Introduction
The goal of this project is to do some ETL to create a feature store on higgs twitter dataset with Spark's Python API. 

The [Higgs Twitter Dataset](https://snap.stanford.edu/data/higgs-twitter.html) contains a few directed graphs. For each user I want to find out how many followers they have, and how many times their tweete were retweeted. I create this data pipeline with two approaches:
- ETL with Pyspark Dataframe API
- ETL with SQL 
- Comparison of API and SQL operation runtime on uncached DF and cached DF