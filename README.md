KDTree
======

An (imbalanced) two-dimensional KDTree that can be quickly queried for points within a given range.
A balanced KDTree can be created by using the QuickSelect algorithm to choose the partition pivot (modify KDSort function).
This is a trade-off between the time it takes to build the tree and the time it takes to query the tree.
Imbalanced == faster builds, Balanced == faster queries
