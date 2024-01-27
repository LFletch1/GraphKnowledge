# Purpose
This repository is simply a place to track important or interesting graph algorithms, frameworks/libraries, and tools that I have come across. Feel free to submit a PR to add any information relating to all thing graphs.  

## Graph Algorithms

### Clique Counting/Enumeration
+ **[Pivoter](https://github.com/sjain12/Pivoter):** Parallel clique counting algorithm which uses a data structure called succinct clique tree (SCT) to store a compressed unique representation of all cliques.
  ([2020 Paper](https://dl.acm.org/doi/abs/10.1145/3336191.3371839))

### Centralities
+ **[K-path](https://dl.acm.org/doi/abs/10.1145/1989656.1989657):** Vertices of higher importance have are more frequently traversed when sampling simple paths of length at most K.
  ([2011 Paper](https://dl.acm.org/doi/10.1145/1989656.1989657))

### PageRank, Personalized PageRank
+ **[PPR via Random Walks](https://www.tandfonline.com/doi/abs/10.1080/15427951.2005.10129104):** Earliest paper I could find that calculated personalize PageRank by      simiulating many random walks.
    - [PowerWalk](https://dl.acm.org/doi/pdf/10.1145/2983323.2983713) also describes a similar algorithm to calculate PPR along with an implementation.
  
### Parallel Graph Algorithms
+ **[Pivoter](https://github.com/sjain12/Pivoter):** Parallel clique counting algorithm which uses a data structure called succinct clique tree (SCT) to store a compressed unique representation of all cliques.
  ([2020 Paper](https://dl.acm.org/doi/abs/10.1145/3336191.3371839))

### Distributed Graph Algorithms


## General Graph Frameworks/Libraries
### Shared Memory

### Distributed Memory

+ **[Apache Giraph](https://giraph.apache.org/):** Giraph is the open-source implementation of Pregel. Communication is facilitated via Apache Hadoop map/reduce operations.
+ **[Gemini](https://github.com/thu-pacman/GeminiGraph):** A computation-centric distributed graph processing system. Uses MPI for inter-process communication.
  ([2016 Paper](https://www.usenix.org/conference/osdi16/technical-sessions/presentation/zhu))
+ **[Plato](https://github.com/Tencent/plato/):** Tencent's high-performance distributed graph framework. Uses Apache Hadoop for inter-node communication.
+ **[Pregel](https://dl.acm.org/doi/abs/10.1145/1807167.1807184):** Framework developed at Google that introduced the think like a vertex model and employs a [BSP](https://en.wikipedia.org/wiki/Bulk_synchronous_parallel) communication.

  
### GPU Centric

## Algorithm/Workload Specific Graph Frameworks

### Graph Mining
+ **[Arabesque](https://github.com/qcri/Arabesque):** Distributed graph mining system that supports general graph mining algorithms. Utilizes Hadoop for communication.
  ([2015 Paper](https://dl.acm.org/doi/abs/10.1145/2815400.2815410))
### Random Walks
+ **[FlashMob](https://github.com/flashmobwalk/flashmob):** Cache-efficient shared-memory graph random walk system.
  ([2021 Paper](https://github.com/flashmobwalk/flashmob/tree/sosp21-ae))
+ **[KnightKing](https://github.com/KnightKingWalk/KnightKing/):** Distributed general random walk frame work which supports static, dynamic, and higher order random walks.
  ([2019 Paper](https://github.com/KnightKingWalk/KnightKing/blob/master/resources/sosp2019_paper.pdf))

