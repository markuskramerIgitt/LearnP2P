
#### DHT and PEX
[DHT in BEP05](http://bittorrent.org/beps/bep_0005.html) (2008-2020), [PEX in BEP11](http://bittorrent.org/beps/bep_0011.html) (2015-2017)
- DHT is intended to bootstrap/discover peers/swarms.
- PEX is intended to reflect which peers a client is currently connected to, PEX provides better liveness information than DHT

[DHT](https://en.wikipedia.org/wiki/Distributed_hash_table) and [PEX](https://en.wikipedia.org/wiki/Peer_exchange) in Wikipedia:
- PEX cannot be used on its own to introduce a new peer to a swarm. To make initial contact with a swarm, each peer must either connect to a tracker using a ".torrent" file, or else use a router computer called a bootstrap node to find a DHT which describes a swarm's list of peers.
