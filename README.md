# Decision-Tree

Machine Learning: Decision Tree. Function Approximation.

## Assumptions
Grow tree just big enough to fit correct labeled data.
So short decision tree is more preferable than long.
* Occam's razor: prefer the simplest hypothesis that fit the data

## Properties
- can approximate any discrete function
- we should should choose first parameter which reduce maximum of entropy (ID3)

```
I(X,Y) = H(X) - H(X|Y)

where:
H(X) = - sum(P(X=i) * log2(P(X=i))) for i in [1, n]
H(X|Y=v) = -sum(P(X=i|Y=v) * log2(P(X=i|Y=v)) for i in [1, n]
H(X|Y) = sum(P(Y=v) * H(X|Y=v)) for v in Y
```

<img width="1440" alt="screenshot 2019-01-23 at 11 31 27 am" src="https://user-images.githubusercontent.com/35291991/51586300-a6c78500-1f02-11e9-9671-e0e4b352387c.png">



## Souces- 
1. [Decision Tree -- Python Machine Learning Book](https://github.com/rasbt/python-machine-learning-book/blob/master/faq/decision-tree-binary.md) </br>
2. [Decision Tree Example PDF](https://homepage.cs.uri.edu/faculty/hamel/courses/2015/spring2015/csc481/lecture-notes/ln481-018.pdf)
