Session 2: Hadoop Framework Description
Assignment 5
1.	Difference between cluster and Hadoop cluster:
•	In a computer system, a cluster is a group of servers and other resources that act like a single system and enable high availability and, in some cases, load balancing and parallel processing.
•	In general, cluster is group of similar things or people placed closely together.
•	On the other hand, Hadoop cluster is a special type of computational cluster designed specifically for storing and analyzing huge amounts of unstructured data in a distributed computing environment.
2.	Rack and Rack Awareness in Hadoop Cluster:
•	Hadoop Rack is a set of 30 to 40 nodes physically stored close together.
•	These nodes are connected to the same network using a switch. Similarly Hadoop cluster is a collection of Hadoop racks.
•	Rack awareness (Rack arrangement) in Hadoop is the concept of choosing closer data nodes based on racks information.
•	Hadoop rack awareness helps the user to define manually the rack number of each slave DataNodes in the cluster.
•	A default Hadoop installation assumes all nodes belong to same rack.
•	When Hadoop cluster has more than 40 nodes are configured in multiple racks.
