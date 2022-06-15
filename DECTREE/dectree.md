# DECISION TREE

[DT in Wiki](https://en.wikipedia.org/wiki/Decision_tree)

### A **decision tree** is a decision support tool that uses a tree-like model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.

### Decision trees are commonly used in operations research, specifically in decision analysis, to help identify a strategy most likely to reach a goal, but are also a popular tool in machine learning. 

![](https://upload.wikimedia.org/wikipedia/commons/a/ad/Decision-Tree-Elements.png)

## Entropy:
## **$H(S) = -(p(0) * log(P(0)) + p(1) * log(P(1)))$**
---
## Gain:
## **$Gain(S,A) = H(S) - \Sigma(v \in V(A)) |Sv/S| * H(Sv) $**