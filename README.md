# MSDS19014_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

## VGG - Unfreeze FC Layer Only

Accuracy

Training Data
90%

Testing Data
94.5%

Confusion Matrix

Training Data

[[12976  1584]
 [ 2684 14450]]
 
Validation Data

[[13561  1668]
 [ 2714 14847]]
 
Testing Data

[[570  45]
 [ 22 583]]


## RESNET - Unfreeze FC Layer Only

Accuracy

Training Data
89%

Testing Data
93%

Confusion Matrix

Training Data

[[12762  1551]
 [ 2898 14483]]
 
Validation Data

[[13315  1608]
 [ 2960 14907]]
 
Testing Data

[[524   9]
 [ 68 619]]
 
## VGG - Unfreeze Convolutional Layers

Accuracy

Training Data
91.38%

Testing Data
95%

Confusion Matrix

Training Data

[[12762  1551]
 	[ 2898 14483]]
 
Validation Data

[[13315  1608]
 [ 2960 14907]]
 
Testing Data

[[524   9]
 [ 68 619]]
 
## VGG - Unfreeze All Layers

Accuracy

Training Data
90.09%

Testing Data
95%

Confusion Matrix

Training Data

[[12989  1414]
 [ 2671 14620]]
 
Validation Data

[[13510  1449]
 [ 2765 15066]]
 
Testing Data

[[553  11]
 [ 39 617]]

## RESNET - Unfreeze Convolutional Layers

Accuracy

Training Data
88.90%

Testing Data
94%

Confusion Matrix

Training Data

[[11795  1524]
 [ 3865 14510]]
 
Validation Data

[[12276  1554]
 [ 3999 14961]]
 
Testing Data

[[533  13]
 [ 59 615]]
 
## RESNET - Unfreeze All Layers

Accuracy

Training Data
90.18%

Testing Data
93%

Confusion Matrix

Training Data

[[12063  1640]
 [ 3597 14394]]
 
Validation Data

[[12552  1675]
 [ 3723 14840]]
 
Testing Data

[[528  20]
 [ 64 608]]

 ## Part 2
 ## VGG - With Focal Loss
 
 Accuracy

Training Data
87.15%

Testing Data
87.30%

Confusion Matrix

Training Data

[[[6000 0] 
[ 189 11]] 
[[1848 352] 
[ 231 3769]] 
[[3766 234] 
[ 345 1855]]]

Validation Data 

[[[600 0] 
[ 28 0]] 
[[187 41] 
[ 15 385]] 
[[383 17] 
[ 43 185]]]
 
F1 Score

Training Data

0.88073

Validation Data 

0.8674

## RESNET - With Focal Loss
 
Accuracy

Training Data
65%

Testing Data
63.23%

Confusion Matrix

Training Data

[[[5995 5] 
[ 200 0]] 
[[1816 384] 
[ 111 3889]] 
[[3945 55] 
[2009 191]]]

Validation Data 

[[[600 0] 
[ 28 0]] 
[[195 33] 
[ 13 387]] 
[[399 1] 
[216 12]]]
 
F1 Score

Training Data 

0.64128

Validation Data 

0.6101
