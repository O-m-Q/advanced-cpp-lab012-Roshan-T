# Binary Search Tree Analysis Laboratory

## Core goal
Students must implement a binary search tree storing integer values and supporting insertion, search, removal, height, traversal, and balancing checks.

## Required operations
Students must implement and analyze:

- `insert(value)`
- `remove(value)`
- `contains(value)`
- `search(value)`
- `min()` and `max()`
- `height()`
- `isBalanced()`
- `clear()`
- traversal methods: inorder, preorder, postorder, and level-order

## Analysis expectations
Students should explain:

- average-case and worst-case complexity of insertion, search, and deletion;
insertion search and deletion use search so log n, then deletion.
- how tree shape affects cost;
skewed = O(n), becomes linear, balanced /full/ complete = O(log n)
- why balanced trees improve performance;
Because skewed trees lead a sequential "straight" path. Balanced do the opposite.
- traversal behavior and the ordering guarantees of different traversals;
Pre Order: Parent-> L -> R
In Order: L-> Parent -> R
Post Order: L -> R -> Parent
- what happens when the tree becomes skewed.
operations degrade to O(n), linear search

## Big-O focus
Students should describe Big-O for:

- insert average O(log n) | worst O(n)
- search average O(log n) | worst O(n)
- remove average O(log n) | worst O(n)
- min/max traversal average O(log n) | worst O(n)
- height average O(n) | worst O(n)
- inorder/preorder/postorder average O(n) | worst O(n)
- level-order traversal average O(n) | worst O(n)

A rigorous answer should include both average and worst-case behavior.
