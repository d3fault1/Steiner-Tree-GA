# Steiner Tree

A Jupyter notebook that searches for a low-cost set of edges connecting a required set of vertices.

---

## Overview

- Reads a graph from a text file.
- Searches for a cheap subset of edges that covers the required vertices.
- Prints the edges and the cost.

---

## Tech Stack

| Component | Technology |
| --- | --- |
| **Language** | Python 3 |
| **Notebook** | Jupyter |

---

## Project Structure

```
Steiner-Tree-GA/
├── steiner_tree_ga.ipynb
├── input.txt
└── large_input.txt
```

---

## Prerequisites

- Python 3
- Jupyter

No extra packages.

---

## Setup

```text
pip install jupyter
```

---

## Run

```text
jupyter notebook steiner_tree_ga.ipynb
```

Run the cells from the top. The notebook reads `input.txt`.

The file format is:

```text
n m r
required vertex ids
u v weight
```

`n` is the vertex count, `m` is the edge count, and `r` is the number of required vertices. One line follows for each edge.
