---
layout: default
title: Big Graph Platforms
---

## Big Graph Analytical Platforms ##
Here we try to make a list of all systems targeting big graph analytics. All systems appear in some academic papers at some point. Open source implementations are preferred.
We annotate each system with links, paper and some highlights.
Please let us know if something is missing. We appreciate it a lot.

We view analytical platforms as in two categories, programming platforms and graph databases. The line between the two is bluring. Programming platforms interact with user via programming languages (scripts), therefore are much more flexible. Graph databases achieve that via graph query languages, in a more controled, concise way. Declarative languages may play a bigger role in the field later, but only with the functionalities (such as aggregation) added; just like what happend in OLAP systems.

### Programming Platforms ###
Major players in the field are MapReduce model and vertex-centric programming model.

#### MapReduce ####
Though many people argue that MR is not the suitable platform for graph algorithms, MR is still the most common parallel infrastructure people have access to. The ability to handle billion node graph in a reasonable amount of time is good enough in many cases. Insights that are gained from designing in MR algorithms are certainly useful for other platforms (and vice versa).

- Hadoop
  - Definitely the biggest player in the field.
  - White, Tom. Hadoop: the definitive guide. O'Reilly, 2012.
- Spark
  - A full stack platform, from UC Berkeley. Also has a vertex-centric programming model.
  - Zaharia, Matei, et al. "Spark: cluster computing with working sets." Proceedings of the 2nd USENIX conference on Hot topics in cloud computing. 2010.
  - [link](http://spark.incubator.apache.org/), [code](https://github.com/amplab)
- Hyracks
  - A full stack platform, from UCI. Also has a vertex-centric programming model.
  - Borkar, Vinayak, et al. "Hyracks: A flexible and extensible foundation for data-intensive computing." Data Engineering (ICDE), 2011 IEEE 27th International Conference on. IEEE, 2011.
  - [link](http://hyracks.org/)
- Storm
  - from Twitter.
  - [link](http://storm-project.net/)

#### Vertex-Centric Programming ####
Vertex-centric programming is an natural way of expressing many graph algorithms.

- Pregel
  - The inspiration of many others.
  - Malewicz, Grzegorz, et al. "Pregel: a system for large-scale graph processing."Proceedings of the 2010 ACM SIGMOD International Conference on Management of data. ACM, 2010.

- Giraph
  - The Apache's answer to Pregel.
  - [link](http://giraph.apache.org)
  - Ching, Avery, and C. Kunz. "Giraph: Large-scale graph processing infrastructure on Hadoop." Hadoop Summit (2011).
- Mizan
  - Khayyat, Zuhair, et al. "Mizan: a system for dynamic load balancing in large-scale graph processing." Proceedings of the 8th ACM European Conference on Computer Systems. ACM, 2013.
  - [link](http://thegraphsblog.wordpress.com/the-graph-blog/mizan/)
- Grace
  - single node multi-core
  - Guozhang Wang, Wenlei Xie, Alan Demers, Johannes Gehrke. Asynchronous Large-Scale Graph Processing Made Easy. CIDR 2013. 
  - [link](http://www.cs.cornell.edu/bigreddata/grace/) 
- GPS
  - from Stanford
  - S. Salihoglu and J. Widom. Optimizing Graph Algorithms on Pregel-like Systems. Technical Report, September 2013.
  - [link](http://infolab.stanford.edu/gps/)
- Signal-Collect
  - Stutz, Philip, Abraham Bernstein, and William Cohen. "Signal/collect: Graph algorithms for the (semantic) web." The Semantic Web–ISWC 2010. Springer Berlin Heidelberg, 2010. 764-780.
  - [link](http://uzh.github.io/signal-collect/)
- GraphLab and GraphChi
  - very hot right now
  - Low, Yucheng, et al. "GraphLab: A New Framework For Parallel Machine Learning."
  - [link](http://graphlab.org/)

#### Platforms use Declarative Languages ####
- SociaLite
  - SociaLite uses Datalog as the query language, and can implement many graph algorithms. It has both single machine and distributed version now.
  - Seo, Jiwon, Stephen Guo, and Monica S. Lam. "SociaLite: Datalog extensions for efficient social network analysis." Data Engineering (ICDE), 2013 IEEE 29th International Conference on. IEEE, 2013.
- More can be found at [Wikipedia](http://en.wikipedia.org/wiki/Graph_database#Distributed_Graph_Processing)


### Graph Databases ###
Graph databases interacts with the user via graph query languages.

- Neo4j
  - Maybe the most popular graph database around.
  - [link](http://www.neo4j.org/)
- Faunus
  - tbd
  - [link](http://thinkaurelius.github.io/faunus/) 
- Many more from [Wikipedia](http://en.wikipedia.org/wiki/Graph_database#Graph_database_projects)






  
