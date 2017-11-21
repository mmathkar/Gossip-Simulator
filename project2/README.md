# Project2 Gossip Simulator

## Project Members

Tasneem Sheikh (UFID-01360914) and Mugdha Mathkar (UFID-54147979)

## What's working?
This version introduces n failure nodes (taken as a command line parameter).
Before the protocol is initiated, we kill n random nodes to observe the behavior of networks.
We have tested our code on ALL topologies namely Line, Full, 2D and imp2D.
We have used this code to successfully observe various patterns in Gossip and PushSum algorithms.

## Highest number of nodes

Could see convergence for some topologies for 10000 nodes for both Gossip and Push-sum.

In theory, the code could handle more actors as well.