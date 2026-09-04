[[Cache]]

---
[Redis Chai aur Code - YouTube](https://www.youtube.com/playlist?list=PLkravDUKJN0JWfllRfj0cEcTn2etynCdO)  : Only Lecture is needed


Redis 
https://www.instagram.com/p/DauLDv9Bsc4/

---

What is Redis?
Why ? 
What Problem Does it Solve ?
InMemory DB
Redis vs Traditional Database
Why is Redis so fast?
Why is Redis single-threaded?
Redis vs (L1 , L2 Cache)


---
When to use Redis ?
Redis Data Storage  : Key-Value 
What are Redis Data Types?
1. String
2. HashMap
3. List
4. Set
5. Ordered Set
6. Max Element that can be Stored


String  String : SET GET
HashMap    Hashes : HMSET HGETALL
List  List lpush/ lrange
Set  RedisSet sadd / smemebers
Ordered Set  SortedSet zadd ZRANGEBYSCORE
Max Element 2^32-1
Is it case sensitive ?
Does it support Atomic Operation



---

Redis UseCase
1. Return Frequently Used Data
2. Session Management 
3. Rate Limiting 
4. OTP
5. Job Queue (Sending Email in Small Batch of 10 )
6. Background Jobs

Redis Persistence 
RDB vs AOF
It Depends Upon Configuration.
1. RDB (Redis Data Backup)
2. AOF (Append Only File)

Thundering Herd Problem
https://www.instagram.com/reel/Db8YSsrzb3q/?utm_source=ig_web_copy_link&igsi=NTc4MTIwNjQ2YQ==

Redis LifeCycle 

Redis Eviction Policy
- LRU Least Recently Used
- LFU Least Frequently Used
- TTL
- noeviction

Redis UseCase
1. Return Frequently Used Data
2. Session Management 
3. Rate Limiting 
4. OTP
5. Job Queue (Sending Email in Small Batch of 10 )
6. Background Jobs


What happens if Redis crashes?
1. If Persistance Enabled
2. Otherwise

---


---


SpringBoot-Redis 
	1. Approach 1 — Spring Cache abstraction
	2. Approach 2 — Direct Redis operations


Spring Boot Caching Basics (@Cacheable, @CachePut, @CacheEvict)
@CachePut(value = "users", key = "#user.id")
public User updateUser(User user) {
    return userRepository.save(user);
}

Redis in Spring Boot
    @Cacheable
    @CachePut
    @CacheEvict
	How to enable it ?
	Pom.xml Dependency name 
How does @Cacheable actually work?



Redis 
Two Approaches

              Your Service
                   |
              @Cacheable
                   |
                   v
          Spring Cache Abstraction
                   |
       +-----------+-----------+
       |                       |
   Caffeine                  Redis
       |                       |
   Local Cache            Distributed Cache


---
Redis & How do we configure it ??
Redis Cache Aside Pattern 
HOSTIP
HOSTNAME
ENVIRONMENT VARIABLE 
https://www.instagram.com/p/DamfDmthK8T/

---
Redis vs MemCached
https://www.instagram.com/p/DaxfGAuhKzB/

---
Bloom Filter 
https://www.instagram.com/p/DXrH10bCGdJ/

---
What is Redis Pub/Sub? What is Pub/Sub ? Command ? Redis Pub/Sub vs Queue(KAFKA) ?
What is Redis Pipeline?
What is Redis Replication? Types of Replication ? Is it sufficient to handle failover ?
Redis Sentinel ? Redis Sentinel vs Redis Cluster ? Single Point of Failure ? Vertical Scaling
Redis Cluster ? Is it Successor of Redis Sentinel ? Horizontal Scaling
Redis Distributed Lock

---


https://www.instagram.com/reels/DcJQcuyRBDk/
Redis Sentinel 
Async
Replication Lag
Primary & Replica
Redis Sential 
Corm
Primary Promote
Wait Command 
Enable Healthy Replica


https://www.instagram.com/reels/DcOYfNczM50/
More than Single Server 
Redis Cluster 
Redis Node Sharde
Hot Key
Cluster Aware Client

---
Redis-Reentract Lock
https://www.instagram.com/engineerinazure/reel/DcTl19KNfP-/
Atomic Release
Fencing Token
Stale Write



Redis Pub-Sub vs Redis-Stream
Redis Pub-Sub  
At-most-Delivery
Event Miss , No Business Impact

Redis-Stream
Duplicate Delivery
Stream Consumer Ideoptment 
Database Unique Constraint
https://www.instagram.com/engineerinazure/reel/Dcd5XvkzTCt/



TTL Expiry vs Eviction
https://www.instagram.com/engineerinazure/reel/Db52XAXTqUp/

TTL Expiry 
Analogy of Milk Expiry 

Lazy Expiration
Active Expiration

Cache Evicition Policy 
Analogy of Fridge 

Max Memory Pressure


---
Redis Command : 

| Topic               | Command       |
| ------------------- | ------------- |
| Cache expiry        | EXPIRE / TTL  |
| Batch operation     | MSET / MGET   |
| Atomic counter      | INCR          |
| Distributed lock    | SET NX EX     |
| Queue               | LPUSH / RPUSH |
| Leaderboard         | ZADD          |
| Production scanning | SCAN          |
| Performance         | PIPELINE      |
