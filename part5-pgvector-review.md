# Part 5: Review of pgvector with Python and Go

pgvector is a PostgreSQL extension that enables storage and similarity search over vector embeddings. It is widely used in modern AI-driven applications that rely on semantic search and retrieval-augmented generation.

## Capabilities and Ecosystem

pgvector supports exact and approximate nearest neighbor search using cosine similarity, inner product, and Euclidean distance. It integrates cleanly with PostgreSQL indexing mechanisms and supports popular ANN techniques.

In Python, pgvector is commonly used with libraries such as psycopg, SQLAlchemy, and LangChain. In Go, it can be accessed using PostgreSQL drivers such as pgx, enabling high-performance backend services.

## Advantages for a Knowledge Base

pgvector enables semantic similarity search over entities, documents, and concepts, complementing symbolic knowledge graphs. This hybrid approach allows systems to combine structured relationships with embedding-based retrieval.

Using pgvector within PostgreSQL simplifies deployment and reduces system complexity compared to managing a separate vector database.

## Disadvantages for a Knowledge Base

pgvector may not match the raw performance of specialized vector databases such as FAISS or Milvus for extremely large-scale workloads. Careful tuning of indexes and query patterns is required to achieve optimal performance.

Additionally, pgvector provides similarity search but does not handle higher-level reasoning or graph semantics on its own.

## References

pgvector GitHub Repository. https://github.com/pgvector/pgvector
