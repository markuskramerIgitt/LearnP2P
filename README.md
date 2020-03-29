
#### DHT and PEX
[DHT is BEP05 2008-2020](http://bittorrent.org/beps/bep_0005.html), [PEX is BEP11 2015-2017](http://bittorrent.org/beps/bep_0011.html).

PEX provides an alternative peer discovery mechanism for swarms once peers have bootstrapped via other mechanisms such as DHT.

PEX is intended to reflect which peers a client is currently connected to, this ensures that PEX provides better liveness information than other peer discovery mechanisms.
