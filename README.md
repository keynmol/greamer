# Continuous graph visualisation protocol

## Problem
To gain insights into a process that involves constantly changing graph, we need some good visualisations. Graphviz is good only for static stuff and it re-arranges picture for every 

## Solution
A simple, possibly binary protocol that sends graph changes over socket. Like, "Edge 25: new class = genflow" or "Node 144: new value=0.6586".

On the visualisation side we can set update speed and fix certain nodes, for example, if they're presumed to be immutable.