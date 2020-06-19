# Segment Trees

Binary tree

## Use-cases
* Range queries in an array; E.x. Minimum value of the array between the index(i, j)

https://www.geeksforgeeks.org/overview-of-data-structures-set-3-graph-trie-segment-tree-and-suffix-tree/


## Time and Space Complexity
Build - O(N) => Worst case 4N
Query - O(log N)  Worst case - O(4 log N)
Space - O(N)


## Length of the segment tree

Length of Input is a multiple of 2 => (length * 2) -1;
Else => (Length's Next multiple of 2 * 2) -1

## Traversal
Check the given range in the node's range.

* Total overlap   -> Return node value
* No overlap      -> Return Max value (Default)
* Partial overlap -> Traverse the tree


## Lookups

Left child  = 2*idx + 1
Right Child = 2*idx - 1
Parent      = (i - 1)/2
