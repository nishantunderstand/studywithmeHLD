
Session-Based and Token-Based [[Authentication]] 
https://www.instagram.com/p/DbpVnW1hy9M/

[[APIGateway]]
https://www.instagram.com/p/DYeuY9VJkbN/

[[SAGAPattern]], Types
https://www.instagram.com/p/Dbw0w9Mhtpr/

Consistent [[Hashing]] , Virtual Nodes
https://www.instagram.com/p/DbubdnWh8Je/

RBAC, ABAC, ReBAC 
Authentication : Token , Session, StickySession
Authorization : Role vs Permission vs Attribute, RBAC, ABAC, ReBAC 
401 vs 403
https://www.instagram.com/p/Dbr0CzshpWO/

[[JWT]] 
https://www.instagram.com/p/Dbm1O24hbjN/

[[Docker]] 
https://www.instagram.com/p/Dbk4EL8BhxX/

[[Authentication]] and [[Authorization]]
https://www.instagram.com/p/Dbf-wDHhRQn/

Monolithic vs [[Microservice]]

[[Idempotency]] API 
GET , DELETE  , POST 
Idempotency key, Double Payment 
PATH Case 1 : Value Save , case 2 Value Increment 
https://www.instagram.com/p/DbXSkYuhuY2/


[[Redis]] 
https://www.instagram.com/p/DauLDv9Bsc4/

[[Redis]] vs Memcached
https://www.instagram.com/p/DaxfGAuhKzB/

Access vs Refresh [[Token]]
https://www.instagram.com/p/DbyBzSfTDqT/

[[APIGateway]] vs Reverse Proxy
Tradeoff : Server Hidden
https://www.instagram.com/p/DbvIZY4xRAQ/

[[S3]] Database Uploading
Pre-Signed URL , Metadata , Database vs Blob Storage
https://www.instagram.com/p/DbVYgAvR80D/
[[S3-Working-Explained]]

Paper Draw | Saturday, August 8, 2026 10:03:20 PM | Not Working | Try Later

CI/CD 
[[Jenkins]] | Docker
https://www.instagram.com/p/Da5DvvEx_EM/

[[RateLimiting]] 
429 vs 503
Redis, API Gateway
Algorithm
https://www.instagram.com/p/DaVAlW3z5il/
Algorithm
Fixed Window, Sliding Window, Token Bucket 

[[Redis]] & How do we configure it ?
Redis Cache Aside Pattern 
HOSTIP
HOSTNAME
ENVIRONMENT VARIABLE 
https://www.instagram.com/p/DamfDmthK8T/

[[Cache]] Invalidation vs Cache Stampede vs Cache Warming
https://www.instagram.com/p/DaiNiicBhsj/

[[Cache]] Aside Pattern vs Read Through vs Write Through Cache
Banking Application / No Stale Data : Write Through

Read Through vs Write Through [[Cache]]
Cache Miss 
DB vs Cache , Which is updated first ?
How to decide ?
DB + Cache Management
https://www.instagram.com/p/DacLvBEBkq-/


[[Cache]] Aside Pattern												
Pro , Cons , Stale Data								
https://www.instagram.com/p/DaW1bKzB-OR/

[[Cache ]]
Cache Hit, Cache Miss, Cache Hit Ratio
https://www.instagram.com/p/DaU2LHuhjXA/

[[Scalability]], [[Availability]] , [[Reliability]]
Scalability
Availability : Replication, redundant servers, and automatic failover.
Reliability : idempotency, retries, and automated testing.
https://www.instagram.com/p/DaJ1PxRhN6l/


5 Pillars for [[CapacityEstimation]]
Traffic
Storage
Bandwidth —Ingress and Egress
Memory — 80-20 rule: 
Peak Load 
https://www.instagram.com/p/DaHttXXBDZV/

Why [[CapacityEstimation]] 
https://www.instagram.com/p/DaCVtu2Bmhv/


[[Database]] Replication vs Sharding
Replication : Read Data
Sharding : Split Data
https://www.instagram.com/satyam.scripts/

[[Database]] Hash-Based Sharding and Range-Based Sharding
Hot Partitions
https://www.instagram.com/p/DZE5iWxh0ub/

[[Database]] Sharding
Shards
Why Sharding? Data Backup , Smaller Index , Faster Write
Read
Write 
https://www.instagram.com/reel/DZCJ2XVhAXr/

[[Database]] Replication Lag
Sync vs Async Replication
Failover vs Split Brain
https://www.instagram.com/reel/DY_hXYXBTBB/


[[Database]] Replication
Read, Operation +  Write, Insert, Delete Operation
Master-Slave Architecture
Synchronous vs Asynchronous replication 
https://www.instagram.com/reel/DY7M28ghL5N/


Normalization vs Denormalization
Redundancy
Clean vs Unclean Data
Consistency 
Read Heavy System
1NF ensures atomic columns
2NF removes partial dependencies
3NF removes transitive dependencies
Pro & Cons Normalization , Denormalization
Pro & Cons Normalization
https://www.instagram.com/reel/DY1avEoBoN-/

[[Database]] Clustered vs Non-Clustered [[Indexing]]
Primary Key is By Default Clustered index
Clustered Index : physically sorts and stores table data on disk
Only one Clustered Index is possible per table
Non-Clustered Index
B-Tree structure index value with pointers to actual row addresses
Multiple Non-Clustered Indexes can exist on one table.
https://www.instagram.com/p/DYz4Y3ph4MH/

[[Database]] [[Indexing]]
Why 
Tradeoff
Read vs Write Performance 
B-Tree
Clustered vs Non-Clustered Indexes
https://www.instagram.com/p/DYwbevlhHrk/

API Versioning 
4 approaches: URL Path, query params, custom headers, content negotiation.
Breaking Change
How to Decide ? Public , Private(Internal)
https://www.instagram.com/p/DYtq17HBIDr/

Statefull vs Stateless Service
Statefull vs Stateless Architecture
Statefull vs Stateless API

ReverseProxy vs APIGateway
APIGateway is a type of ReverseProxy vice-versa not valid
APIGateway  : Microservice architectures , Request aggregation, circuit breaking, API versioning, and analytics
https://www.instagram.com/p/DYo6N40BqqU/

Latency vs Throughput
https://www.instagram.com/p/DYmK29jBAGV/
