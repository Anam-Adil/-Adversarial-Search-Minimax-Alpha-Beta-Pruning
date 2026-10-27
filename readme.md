# AI Lab 5 – Minimax and Alpha-Beta Pruning

## Introduction
This lab focuses on understanding game-tree search using the Minimax algorithm and Alpha-Beta Pruning. It demonstrates how both algorithms find the optimal value and how Alpha-Beta Pruning can reduce unnecessary leaf evaluations.

## Lab Tasks

### Task 1: Minimax Tree Handwritten Trace
- Perform a handwritten trace of the Minimax algorithm on the given game tree.
- Identify MAX and MIN nodes.
- Calculate the values of the tree from the leaf nodes to the root.

### Task 2: Minimax and Alpha-Beta Pruning with Leaf Counter
- Implement the Minimax algorithm in Python.
- Implement the Alpha-Beta Pruning algorithm in Python.
- Add a leaf-evaluation counter to both algorithms.
- Compare their root values and the number of leaves evaluated.

### Task 3: Reorder Branches and Observe Pruning
- Change the order of the leaf values in the game tree.
- Run Minimax and Alpha-Beta Pruning on both arrangements.
- Compare the root values and leaf-evaluation counts.
- Observe how branch ordering affects Alpha-Beta Pruning.

## Technologies Used
- Python
- Visual Studio Code (VS Code)
- Python `math` module

## Files Included
- `lab5_minimax.py` – Python implementation of Minimax and Alpha-Beta Pruning, including leaf counters and branch reordering.
- `README.md` – Lab description, tasks, and instructions.
- `LAB-5 Report.docx` – Lab report containing the handwritten trace, implementation details, outputs, and conclusion.

## How to Run the Code
1. Install Python on your computer.
2. Open the project folder in VS Code.
3. Open the terminal.
4. Run the following command:

```bash
python lab5_minimax.py
```

If necessary, use `py lab5_minimax.py` on Windows.

## Expected Results
- Both algorithms return the same optimal root value for the tested trees.
- Minimax evaluates all leaf nodes.
- Alpha-Beta Pruning can skip some leaf evaluations depending on branch ordering.
- Reordering branches can change the number of leaves evaluated without changing the optimal root value.

## Conclusion
This lab demonstrates the working of Minimax and Alpha-Beta Pruning. The leaf counters help compare the performance of both algorithms. It also shows that branch ordering can affect pruning efficiency while preserving the optimal decision.

## Learning Outcomes
- Understand MAX and MIN nodes in a game tree.
- Implement Minimax using Python.
- Apply Alpha-Beta Pruning.
- Count leaf evaluations.
- Understand the effect of branch ordering on search efficiency.
