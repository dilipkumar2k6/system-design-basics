# Scalable system problems
- Parallel requests
- Geo location
- Data size limitation
- Single point of failure 
- Server hotspot
- Data hotspot
# Building blocks
## App server behind the a load balancer
## Data replication
## Data sharding
## Caching
# Micro Services Design pattern
- Key thing is to have loosly coupled
- Able to scale individual services separately 
# Logical and physical storages
## Logical storage
- Relational model
- Key Value pair
- Graph model
## Physical Storage
- Column family
- Row major format
- Column major format
## Indexing
- Hash index - support exact match
- B tree index - not exact/range based match
- Combination index
## Sharding
Goals:
- Partition data horizontally
- near even distributions of shards
- Add new shards easily
- Shards are not available
Approaches
- Simplistic
Based on x%n where n is number of shards
- Consistent hashing
## Replication
- Eventual consistencies
- Consistent model
    - Quorum reads
    - Quorum writes

- Available model
## CAP Theorem
- Consistent
- Available
- Partition tolerant
You can only get two.

# Caching
- What is stored?
- Size
- Type of cache
- Physical topology

## Type of cache
- Write through 
- Write around
- Write latter 

## Physical topology
- Shard
- Replicas
- Physical server

# DB Comparison
## Capability
## RDBMS
## NO SQL






