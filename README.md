# Network-Intrusion-Detection
We use PySpark to implement the algorithms for detecting intrusive behaviors inside a network log. The data set is a 4 GB compressed TCP data dump provided by the International Knowledge Discovery and Data Mining Tools Competition (KDD cup 99). Data dictionary and important notes on the data set can be found on http://kdd.ics.uci.edu/databases/kddcup99/task.html

The KDD cup 99 page describes the motivation of the competition as follows:

Software to detect network intrusions protects a computer network from unauthorized users, including perhaps insiders. The intrusion detector learning task is to build a predictive model (i.e. a classifier) capable of distinguishing between "bad" connections, called intrusions or attacks, and "good" normal connections.

The classification of the KDD cup 99 mainly targets four types of attacks:

DOS: denial-of-service, e.g. syn flood;
R2L: unauthorized access from a remote machine, e.g. guessing password;
U2R: unauthorized access to local superuser (root) privileges, e.g., various "buffer overflow" attacks;
probing: surveillance and other probing, e.g., port scanning.
In this project we use pyspark to explore some well-known rules to extract some useful information from the KDD 99 data set. By implementing the Spark interfaces in python (PySpark) to perform big-data analysis on statistical data using Jupyter notebook, we were able to evaluate the difficulty of brute force login attack & distribution of DDOS attack by correlating SYN flooding in 0.6s
