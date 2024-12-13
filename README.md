# FP-Growth-Algo
This repository contains a from-scratch implementation of the FP-Growth algorithm in Python. The code demonstrates core concepts including FP-tree construction, frequent pattern mining, and conditional pattern base generation. It includes functions for data loading, tree traversal, and pattern extraction, showcasing the efficiency.


# FP-Growth Algorithm Implementation

This repository contains a Python implementation of the FP-Growth (Frequent Pattern Growth) algorithm built from scratch. The project demonstrates the fundamental concepts behind efficient frequent itemset mining.

## Features

- FP-tree construction
- Frequent pattern mining
- Conditional pattern base generation
- Header table management
- Tree traversal and pattern extraction

## Files

- `FP-Growth.ipynb`: Jupyter notebook containing the implementation and examples

## Usage

To use this implementation:

1. Clone the repository
2. Open the `FP-Growth.ipynb` Jupyter notebook
3. Run the cells to see the FP-Growth algorithm in action

## Learning Outcomes

This project helps in understanding:

- How FP-trees efficiently represent transaction databases
- The process of mining frequent patterns without candidate generation
- Recursive construction of conditional FP-trees
- Performance benefits of FP-Growth over Apriori algorithm

## Implementation Details

The FP-Growth implementation includes:

- `treeNode`: Class for creating tree nodes
- `createTree`: Function for constructing the FP-tree
- `updateHeader`: Function for managing the header table
- `ascendTree`: Function for traversing the tree upwards
- `findPrefixPath`: Function for finding conditional pattern bases
- `mineTree`: Main function for mining frequent patterns

Feel free to explore, learn, and contribute!
