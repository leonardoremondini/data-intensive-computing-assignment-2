# Data Intensive Computing - Assignment 2
In this lab assignment done togheter with [Haris Poljo](https://github.com/harispoljo), we practiced stream processing and graph processing using Apache Spark, Apache Kafka, and Apache Cassandra. Moreover, we practiced Apache Spark GraphX within two jupyter notebook.

# Assignment 2 - Part 1
We implemented a Spark Streaming application which calculate the average value of (key, value) pairs and continously update it, while new pairs arrive. We read data from Apache Kafka and store the results in Cassandra continuosuly. The results are in the form of (key, average value) pairs.

* **Requirements**: Kafka 2.6.0, Cassandra 3.11.2, Python 2.7, Spark 2.4.3.

* **Run the code & implementation explanation**: Information can be found in LAB 2, PART 1.pdf

# Assignment 2 - Part 2
* **graphx_songs.ipynb**: Use GraphX to cluster music songs according to the tags attached to each songs.
* **graphx_social_network.ipynb**: Use a GraphX to analyse a property graph.

# Collaborators
- [Haris Poljo](https://github.com/harispoljo).

