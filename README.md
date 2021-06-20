# Random-Graphs-according-to-Erdos-Renyi-Model
First assingment of algo 2
Written by guygeller and AssafGolani.

Erdos Renyi Model:
Mission:
-Generating random graphs.
-Creating functions that checks the following: Connectivity, Diameter of the graphs and if there's an Isolated node in the graph.

Connectivity:
Has a treshold of (lnv / v)
if p < threshold, the probability of the graph to be not connected is high
if p > threshold, the probability of the graph to be connected is high

isIsolated:
Has a treshold of (lnv / v)
if p < threshold, the probability of the appearance of an isolated node in the graph is high
if p > threshold, the probability of the appearance of an isolated node in the graph is low

Diameter:
has a treshold of sqrt{2lnv / v}
if p > treshold then the probability of the diameter of the graph to be equal to 2 is high, otherwise, it would be greater than 2

