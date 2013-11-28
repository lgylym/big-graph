---
layout: default
title: Big Graph Data Sets
---

## Big Graph Data Sets ##
There are quite a few big graphs that are publicly available. Usually they are web graphs and social networks. Also thanks to the researchers for their hard work to collect and prepare these data sets.

### Real-world Data Sets ###
#### General Graph Data Sets ####


- Stanford Large Network Dataset Collection (SNAP)
  - A collection of medium to large graph data sets.
  - [link](http://snap.stanford.edu/data/)
- KONECT
  - A collection of various sizes of graph data sets. Some of them are really big (E.g., twitter).
  - [link](http://konect.uni-koblenz.de/networks/)
- LAW
  - Also a collection of big graphs.
  - [link](http://law.di.unimi.it/datasets.php)
- ClueWeb09
  - More than 4 billion nodes, web graph.
  - [link](http://boston.lti.cs.cmu.edu/clueweb09/wiki/tiki-index.php?page=Web+Graph)
- Friendster Social Network
  - 2 billion connections (edges).
  - [link](https://archive.org/details/friendster-dataset-201107)
- Hyperlink Graph
  - 3.5 billion nodes, 128 billion links, web graph, from common crawl.
  - [link](http://webdatacommons.org/hyperlinkgraph/)

#### RDF Graphs ####
RDF (Resource Description Framework) graph is one special kind of graph, with node and edge labeled (possibly multi-labeled). There are a lot of RDF data available, but the data quality can be a problem. To use RDF data as graph data, some transformation needs to be done beforehand (e.g., id mapping).

- DBPedia
  - Maybe the most popular RDF source to start with.
  - [link](http://dbpedia.org/About)
- Infochimps
  - A collection of RDF data.
  - [link](http://www.infochimps.com/tags/rdf)
- Collection from W3C
  - [link](http://www.w3.org/wiki/DataSetRDFDumps)

### Synthetic Graph Generators
Graph generators are handy to play with. They have controllable behavior, so are good for system test and proof of concept. Graph generators come from different perspectives. Benchmarking is one of the most common usecase. Many generators make use of the R-MAT model [1] to generate really big graphs.

- GTgraph
  - Generate different types of graphs. Works in main memory.
  - [link](http://www.cse.psu.edu/~madduri/software/)
- Graph500
  - [link](http://www.graph500.org)
- RDF benchmarking tools (RDF graph generators)
  - [link](http://www.w3.org/wiki/RdfStoreBenchmarking)
- LinkBench
  - From facebook.
  - [link](https://github.com/facebook/linkbench)

---
[1] Chakrabarti, Deepayan, Yiping Zhan, and Christos Faloutsos. "R-MAT: A recursive model for graph mining." Computer Science Department (2004): 541.
