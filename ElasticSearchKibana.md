Elastic Search and Kibana

### Node: 
	- instance of elasticsearch
	- belongs to a single cluster
	- unique id and a name
	- members of a luster sharing common goal
	- assigned to one or mutiple goals
	- one is to hold data

### Cluster:
	- collection of nodes
	- nodes distributed among separate machines
	- 


### Data
	- stored in elastic search as document(json object)
	- Documents are grouped as Index
	- Index share some logical related to each other or share similar trait


### Cluster 
	- Node1 : produce index, wine index
	- Node2 : produce index, wine index
	- Node3 : produce index, wine index

	- here the index is not storing documents
	- its virtual thing that tracks where document is sotred.
	- you cant find index in a disk
	- it is actually Shard that actually stores documents/data. this is where yo wanna search
	- when you create an index one shard comes by default and shard is assigned to a node
	 indices can contain mutiple shards across nodes
![image info](shards1.png) 
![image info](shards2.png)

#learn elasticsearch and kibana communicattion
- keystore and ssl certificates