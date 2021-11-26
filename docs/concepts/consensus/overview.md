# Consensus protocols

GoQuorum implements the following Proof of Authority consensus protocols:

* [IBFT](../../HowTo/Configure/Consensus-Protocols/IBFT.md)
* [QBFT](../../HowTo/Configure/Consensus-Protocols/QBFT.md)
* [Raft](../../HowTo/Configure/Consensus-Protocols/Raft.md)
* [Clique](../../HowTo/Configure/Consensus-Protocols/Clique.md).

!!! warning

    QBFT is currently an early access feature. It is not recommended for production networks with business critical impact.

!!! note

    You can't create a network of GoQuorum nodes using different consensus protocols.
    GoQuorum nodes configured with one consensus protocol can only work correctly with other nodes running the same protocol.