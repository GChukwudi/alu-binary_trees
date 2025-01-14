# Binary Trees

This project focuses on implementing various operations and algorithms related to binary trees in C. It covers fundamental concepts including creation, traversal, and analysis of binary trees.

## Project Overview

- **Team Members**: Joshua Alana, King Chukwumere, God'sfavour Chukwudi
- **Environment**: Ubuntu 20.04 LTS

## Learning Objectives

By completing this project, we were able to grasp:

- What a binary tree is and its characteristics
- The difference between a binary tree and a Binary Search Tree
- Time complexity advantages compared to linked lists
- Concepts of depth, height, and size in binary trees
- Different traversal methods for binary trees
- Types of binary trees (complete, full, perfect, balanced)

## Requirements

### Data Structures

The following data structures is used for binary trees:

```c
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```

## Tasks

The project consists of multiple tasks implementing various binary tree operations:

1. Creating a new binary tree node
2. Inserting nodes (left and right)
3. Deleting entire binary tree
4. Checking node properties (leaf, root)
5. Traversal methods (pre-order, in-order, post-order)
6. Measuring tree properties (height, depth, size)
7. Counting leaves and nodes
8. Calculating balance factor
9. Checking tree properties (full, perfect)
10. Finding node relationships (sibling, uncle)

## Usage

To compile the programs:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o binary_tree
```

## Resources

- [Binary tree (note the first line: Not to be confused with B-tree.)](https://en.wikipedia.org/wiki/Binary_tree)
- [Data Structure and Algorithms - Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)
- [Tree Traversal](https://www.programiz.com/dsa/tree-traversal)
- [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree)
- [Data structures: Binary Tree](https://www.geeksforgeeks.org/binary-tree-data-structure/)
