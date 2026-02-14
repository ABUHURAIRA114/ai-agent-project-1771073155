# Graph Generation in Console
==========================

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Example Graphs](#example-graphs)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
Graph Generation in Console is a Python project that generates various types of graphs in the console. The graphs are represented using ASCII characters, making it easy to visualize and understand the structure of the graph.

## Requirements
* Python 3.8 or higher
* No external dependencies required

## Installation
To install the project, simply clone the repository and navigate to the project directory:
```bash
git clone https://github.com/your-username/graph-generation-in-console.git
cd graph-generation-in-console
```

## Usage
To generate a graph, run the `graph.py` script and follow the prompts:
```bash
python graph.py
```
You will be asked to choose the type of graph you want to generate (e.g., adjacency list, adjacency matrix, etc.). Once you have made your selection, the graph will be generated and displayed in the console.

## Example Graphs
The following are some examples of graphs that can be generated using this project:

* Adjacency List:
```
  A -> B, C
  B -> A, D
  C -> A, F
  D -> B
  E -> F
  F -> C, E
```
* Adjacency Matrix:
```
  | A B C D E F
------------------
A | 0 1 1 0 0 0
B | 1 0 0 1 0 0
C | 1 0 0 0 0 1
D | 0 1 0 0 0 0
E | 0 0 0 0 0 1
F | 0 0 1 0 1 0
```

## Contributing
Contributions are welcome! If you have any ideas for new features or improvements, please submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.