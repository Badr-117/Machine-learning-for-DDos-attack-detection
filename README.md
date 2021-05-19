# Machine-learning-for-DDos-attack-detection

## Project description 

The detection of DDoS attacks in network communication streams using various learning algorithms that learn the normal pattern of network traffic, behavior of network protocols, and identifies compromised network flows.

## Experiment plan 

There is two types of experiments, the first one is a binary classification where my model was just trying to identify if an attack took place or not and so I had 2 classes, benign (which means no attack) and non_benign (which means that there has been an attack).

In the second one the classification was multi-class, once again I had a benign class (i.e. no attack), but also several other classes which said that there was an attack and specified what kind of DDoS attack it was, for example if it was (MSSQL, Portmap, UDP, UDPLag, ect ...)

Each of my experiments consisted of 3 steps: the first is the feature selection, the second is the classification using various supervised classification algorithms, and the third is the evaluation of these same algorithms using different metrics.

