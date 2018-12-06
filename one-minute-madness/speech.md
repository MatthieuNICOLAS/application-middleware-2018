Hello everybody, I'm Matthieu,

Today I will present my preliminary work which is titled Efficient Renaming In Conflict-Free Replicated Data Types, CRDTs for short.

CRDTs are data structures which behave the same as traditional ones, like the Set or the Sequence
but which are designed to be shared and replicated by many nodes.

They are widely used in the industry, from the multi-master replication mode from Redis database to Atom's Teletype's collaborative editing features.

To work, many CRDTs add some metadata for each element in the data structure.
Unfortunately, the overhead for each element is not bounded and grows over time, reducing the efficiency of the CRDT

This leads us to our research question which is "How to reduce this overhead introduced by CRDTs" ?

If you're interested, feel free to drop by !
