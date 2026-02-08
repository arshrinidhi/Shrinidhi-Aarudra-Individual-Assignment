# Part 2: Review of Memgraph as a Graph Database

Memgraph is a high-performance, in-memory graph database designed for real-time graph analytics and operational workloads. It follows the property graph model and uses the Cypher query language, making it accessible to users familiar with Neo4j-style graph querying.

## Architecture and Design

Memgraph stores graph data primarily in memory, with optional durability through snapshots and write-ahead logging. This architecture enables extremely fast traversal and pattern-matching queries, which are critical for knowledge graph workloads that rely on multi-hop relationship exploration.

The database supports streaming data ingestion and integrates well with real-time data sources, making it suitable for continuously evolving knowledge graphs.

## Query Language and Analytics

Memgraph uses Cypher as its primary query language, allowing expressive graph queries such as pattern matching, path finding, and aggregation. In addition, it supports graph algorithms such as centrality, community detection, and shortest paths, which are valuable for analyzing knowledge graph structure.

## Relevance to the Term Project

For the term project, Memgraph serves as an effective store for the knowledge graph layer, enabling fast querying and exploration of entities and relationships extracted from raw documents stored in PostgreSQL. Its performance characteristics align well with interactive querying and iterative graph analysis.

## Limitations

Despite its strengths, Memgraph has a smaller user community compared to more established graph databases, which can limit the availability of examples and third-party tooling. Additionally, its in-memory design may require careful capacity planning for very large graphs.

## References

Memgraph Documentation. https://memgraph.com/docs
