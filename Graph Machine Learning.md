## Graph Machine Learning
Graph Neural Networks (GNNs) are gaining attention in data science and machine learning but still remain poorly understood outside expert circles. 
There is another thing called Graph Machine learning (GML) but not to confuse with GNNs :GML’s primary purposes is to **compress** large sparse graph 
data structures to enable feasible prediction and inference

### Graphs
َHas 3 main componeents : Nodes, Relationships, Properties
<img src="images/GraphML/graph_example.png">

### What is Graph ML
application of machine learning on the graphs specifiacally for predictive and prescriptive tasks. GMLs has a variety of usecases across supply chain,fraud detection, recommendations, customer 360,drug discovery and more...

### Supervised GML Tasks be like :
- **Node property prediction** (predict a discret or continuous node property called Node classification & node regression) : predecting an adjective about something : account on financial service
- **Link prediction** (Predict if a relationship could exist between two node -- often a binary classificaiton task but could include more link types ): predecting if a relationship should exist between two nodes. Link prediction is helpful for applications like entity 
- **Graph property prediction** : Graph property prediction is useful in domains where you **want to model each entity as an individual graph** for prediction rather than modeling entities as nodes within a larger graph representing a complete dataset.

### Unsupervised GML Tasks
- **Representation Learning** : Automatically generate features based on graph structure for downstream ML & EDA (exploratory data analysis)
-<a href="https://neo4j.com/docs/graph-data-science/current/algorithms/community/"> **Clustering/Community detection** </a>: Community detection algorithms are used to evaluate how groups of nodes are clustered or partitioned, as well as their tendency to strengthen or break apart.
- **Similarity** :
- **Centrality & Pathfinding** : 
