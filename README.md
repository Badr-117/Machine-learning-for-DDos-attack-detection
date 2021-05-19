# Machine-learning-for-DDos-attack-detection

## Project description 

The detection of DDoS attacks in network communication streams using various learning algorithms that learn the normal pattern of network traffic, behavior of network protocols, and identifies compromised network flows.

## Experiment plan 

There is two types of experiments, the first one is a binary classification where my model was just trying to identify if an attack took place or not and so I had 2 classes, benign (which means no attack) and non_benign (which means that there has been an attack).

In the second one the classification was multi-class, once again I had a benign class (i.e. no attack), but also several other classes which said that there was an attack and specified what kind of DDoS attack it was, for example if it was (MSSQL, Portmap, UDP, UDPLag, ect ...)

Each of my experiments consisted of 3 steps: the first is the feature selection, the second is the classification using various supervised classification algorithms, and the third is the evaluation of these same algorithms using different metrics.

## Results 

### Binary classification

<img width="432" alt="image" src="https://user-images.githubusercontent.com/44711173/118894652-a96bf680-b8d2-11eb-8fd1-8b48c0f2c587.png">


### multiclass classification

<img width="203" alt="image" src="https://user-images.githubusercontent.com/44711173/118894711-c6a0c500-b8d2-11eb-94d9-4865d2daf5ab.png">  <img width="203" alt="image" src="https://user-images.githubusercontent.com/44711173/118894730-cf919680-b8d2-11eb-92b2-11974e01da22.png">

## Conclusion

To conclude, we can see that different methods and algorithms were used in order to solve our attack detection problem. So for the binary classification we saw that the best algorithm used was the random forest combined with the k fold cross validation method. While for multi-class classification we can either use the random forest or the decision tree combined with the stratified k fold cross validation method.
