# ElasticsearchSQL

Just a simple example of using Apache Spark SQL against Elasticsearch 5

Using Apache Spark SQL 'pushes-down' as much of the query functionality as it can to the Elasticsearch
cluster by translating it to Elasticsearch query DSL. The results are collected by the Spark
nodes and the remaining crunching is performed in batches distributed across the Spark
cluster.
