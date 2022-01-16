# Basic Distributed Hash Table


Distributed Hash Table (DHT):

``` "a distributed system that provides a lookup service similar to a hash table: key-value pairs are stored in a DHT, and any participating node can efficiently retrieve the value associated with a given key." [0] ```

## Basic DHT Components
1. An abstract keyspace
2. A key space paritioning scheme
3. Overlay network to connect nodes (Use Apache Thrift RPC[1] to do this)




Sources:

[0] https://en.wikipedia.org/wiki/Distributed_hash_table 
[1] https://thrift.apache.org/
