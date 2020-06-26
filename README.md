# Community Detection and Link Prediction Algorithms

Thi project performs a community detection and link prediction algorithms using Facebook "like" data. We will be working in this project with unsupervised learning methods.

The file `edges.txt.gz` indicates like relationships between facebook users. This was collected using snowball sampling: beginning with the user "Bill Gates", I crawled all the people he "likes", then, for each newly discovered user, I crawled all the people they liked.

The resulting graph is clustered into communities. This project also implements a recommendation system for recommending friends for Bill Gates.

Several community analysis algorithms are used and implemented from scratch through the project. The implementations are:

- __Breadth First Search__: A bfs algorithm is implemented from scratch.
- __Girvan Newman Algorithm__: Implementation of the Girvan Newman Algorithm for creating partitions in graphs.
- Several distance node functions for obtaining a distance score between a pair of nodes ccording to their neighbours.

For running the script just run:
`python a1.py`

Bear in mind that you can use another source of  graph if you want to perform the analysis on a different data. You will just need to chnge the download_data url.

Also several doctests are provided to test each function.
