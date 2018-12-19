Hello everybody, I'm Matthieu,

Conflict-Free Replicated Data Types, CRDTs for short, are data structures which behave the same as traditional ones, like the Set or the Sequence
but which are designed for distributed systems, to be shared and replicated on many nodes.

They are widely used in the software industry, from the multi-master
replication mode in the Redis database to the Atom’s Teletype’s collaborative
editing features.

To work, many CRDTs add some metadata for each element in the data structure.
However, the overhead for each element is not bounded and grows over time, reducing the efficiency of the CRDT

This leads us to our research question which is "How to reduce this overhead introduced by CRDTs" ?

If you're interested, feel free to drop by !
