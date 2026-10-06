# Advanced Algorithms in Python

A structured and progressive repository for learning, implementing, analyzing, and benchmarking algorithms in Python — from programming foundations to advanced algorithmic methods, numerical computing, optimization, and algorithmic machine learning.

This repository is developed alongside my **Master’s studies in Mathematical Sciences at AIMS Senegal**, while intentionally going beyond the classroom through deeper mathematical analysis, from-scratch implementations, experiments, benchmarks, and applied projects.

---

## Objectives

The main goals of this repository are to:

- Strengthen my foundations in Python, Linux, Git, and GitHub.
- Develop rigorous algorithmic thinking.
- Understand and analyze time and space complexity.
- Implement classical and advanced algorithms from scratch.
- Study fundamental data structures and algorithm design paradigms.
- Explore graph algorithms, randomized methods, approximation algorithms, and computational geometry.
- Build strong foundations in numerical algorithms and mathematical optimization.
- Connect algorithms with scientific computing, machine learning, and engineering applications.
- Benchmark implementations and compare theoretical complexity with empirical performance.
- Build a long-term academic and research-oriented algorithmic portfolio.

---

## Learning Philosophy

The repository follows a simple progression:

```text
Course Foundations
        ↓
Python Programming
        ↓
Algorithmic Foundations
        ↓
Data Structures
        ↓
Algorithm Design Paradigms
        ↓
Graph Algorithms
        ↓
Numerical Algorithms
        ↓
Optimization
        ↓
Advanced Algorithms
        ↓
Algorithmic Machine Learning
        ↓
Research-Oriented Projects
```

For every important topic, the goal is not only to write code, but to understand the complete reasoning process:

```text
Problem
   ↓
Mathematical Formulation
   ↓
Naive Approach
   ↓
Algorithm Design
   ↓
Correctness
   ↓
Complexity Analysis
   ↓
Python Implementation
   ↓
Testing
   ↓
Benchmarking
   ↓
Visualization
   ↓
Applications
```

---

## Repository Structure

```text
advanced-algorithms-python/
│
├── 00_course_foundations/
├── 01_algorithmic_foundations/
├── 02_data_structures/
├── 03_algorithm_design/
├── 04_graph_algorithms/
├── 05_string_algorithms/
├── 06_randomized_algorithms/
├── 07_approximation_algorithms/
├── 08_computational_geometry/
├── 09_numerical_algorithms/
├── 10_optimization_algorithms/
├── 11_advanced_topics/
├── 12_algorithmic_ml/
│
├── theory/
├── notebooks/
├── projects/
├── benchmarks/
├── tests/
├── challenges/
└── references/
```

---

## 00 — Course Foundations

This section contains the foundations directly connected to my coursework and computational workflow.

### Topics

- Linux command line
- Shell basics
- Git
- GitHub
- Python fundamentals
- Files and directories
- Functions
- Lists
- Dictionaries
- Basic project organization

The objective is to master the tools used throughout the rest of the repository.

---

## 01 — Algorithmic Foundations

Core concepts required for algorithm analysis and design.

### Topics

- Asymptotic analysis
- Big-O notation
- Big-Omega notation
- Big-Theta notation
- Recursion
- Recurrence relations
- Searching algorithms
- Sorting algorithms
- Empirical complexity analysis

Examples include:

- Linear Search
- Binary Search
- Bubble Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort

---

## 02 — Data Structures

Implementation and analysis of fundamental and advanced data structures.

### Topics

- Arrays
- Linked Lists
- Stacks
- Queues
- Hash Tables
- Heaps
- Binary Trees
- Binary Search Trees
- AVL Trees
- Red-Black Trees
- Tries
- Disjoint Sets
- Segment Trees
- Fenwick Trees
- Bloom Filters

---

## 03 — Algorithm Design Paradigms

This section focuses on the main strategies used to design efficient algorithms.

### Paradigms

- Brute Force
- Divide and Conquer
- Greedy Algorithms
- Dynamic Programming
- Backtracking
- Branch and Bound

Representative problems include:

- Knapsack
- Longest Common Subsequence
- Longest Increasing Subsequence
- Matrix Chain Multiplication
- N-Queens
- Graph Coloring
- Travelling Salesman Problem

---

## 04 — Graph Algorithms

Graphs are a major component of this repository because of their importance in optimization, networks, routing, machine learning, transportation, and engineering systems.

### Topics

- Graph representations
- Breadth-First Search
- Depth-First Search
- Shortest paths
- Minimum Spanning Trees
- Connectivity
- Strongly Connected Components
- Network Flow

### Algorithms

- BFS
- DFS
- Dijkstra
- Bellman-Ford
- Floyd-Warshall
- A*
- Prim
- Kruskal
- Tarjan
- Kosaraju
- Ford-Fulkerson
- Edmonds-Karp
- Dinic
- Min-Cost Flow

---

## 05 — String Algorithms

Algorithms for efficient text processing and pattern matching.

### Topics

- Naive String Matching
- Knuth-Morris-Pratt
- Rabin-Karp
- Z Algorithm
- Tries
- Suffix Arrays
- Aho-Corasick

---

## 06 — Randomized Algorithms

This section explores algorithms that use randomness as part of their logic or analysis.

### Topics

- Randomized QuickSort
- Randomized Selection
- Reservoir Sampling
- Monte Carlo Methods
- Random Walks
- Randomized Hashing

---

## 07 — Approximation Algorithms

Approximation methods for computationally difficult optimization problems.

### Topics

- Vertex Cover
- Set Cover
- Approximate Knapsack
- Travelling Salesman Approximation
- Approximation ratios
- Computational complexity

---

## 08 — Computational Geometry

Algorithms for geometric and spatial problems.

### Topics

- Convex Hull
- Closest Pair of Points
- Line Intersection
- Point-in-Polygon
- Voronoi Diagrams

---

## 09 — Numerical Algorithms

A central component for connecting algorithmics with mathematical sciences and scientific computing.

### Root Finding

- Bisection Method
- Newton-Raphson Method
- Secant Method

### Linear Systems

- Gaussian Elimination
- Jacobi Method
- Gauss-Seidel Method
- Conjugate Gradient Method

### Eigenvalue Problems

- Power Iteration
- QR Algorithm

### Numerical Integration

- Trapezoidal Rule
- Simpson's Rule
- Monte Carlo Integration

---

## 10 — Optimization Algorithms

Algorithms for solving mathematical optimization problems.

### Deterministic Methods

- Gradient Descent
- Newton's Method
- Conjugate Gradient
- Projected Gradient
- Penalty Methods
- Simplex Method

### Metaheuristics

- Genetic Algorithms
- Simulated Annealing
- Particle Swarm Optimization
- Ant Colony Optimization
- Differential Evolution

---

## 11 — Advanced Topics

Topics intended to go significantly beyond introductory coursework.

### Areas

- Online Algorithms
- Streaming Algorithms
- Parallel Algorithms
- Distributed Algorithms
- Probabilistic Algorithms
- Approximation Complexity
- Parameterized Algorithms
- Complexity Theory

Long-term topics include:

- P
- NP
- NP-hard
- NP-complete
- Polynomial-time reductions

---

## 12 — Algorithmic Machine Learning

The objective of this section is to understand machine learning algorithms from an algorithmic and mathematical perspective rather than relying only on high-level libraries.

### From-Scratch Implementations

- Linear Regression
- Logistic Regression
- K-Nearest Neighbors
- K-Means
- Principal Component Analysis
- Decision Trees
- Neural Networks

Whenever possible, implementations are first developed from scratch and then compared with established scientific Python libraries.

---

## Mathematical Perspective

Algorithms in this repository are studied not only as code, but also through their mathematical foundations.

Examples include recurrence relations such as

\[
T(n)=2T(n/2)+n
\]

leading to

\[
T(n)=\Theta(n\log n),
\]

shortest-path formulations,

\[
d(s,v)=\min_{p:s\rightarrow v} w(p),
\]

linear systems,

\[
Ax=b,
\]

eigenvalue problems,

\[
Av=\lambda v,
\]

and optimization problems,

\[
\min_x f(x).
\]

---

## Experiments and Benchmarks

The repository includes empirical experiments to compare theoretical complexity with actual computational behavior.

Typical experiments include:

- execution-time measurements,
- scalability analysis,
- memory profiling,
- algorithm comparison,
- input-size sensitivity,
- convergence analysis,
- numerical error analysis.

Example:

```text
Input Size
   ↓
Run Algorithm
   ↓
Measure Runtime
   ↓
Measure Memory
   ↓
Compare with Theory
   ↓
Visualize Results
```

---

## Projects

The repository also contains applied projects where multiple algorithms are combined to solve larger problems.

Examples include:

- Senegal Temperature Analyzer
- Pathfinding Visualizer
- Dakar–Mbour Route Optimizer
- Task Scheduling Optimizer
- Network Flow Simulator
- Epidemic Graph Model
- Electric Grid Optimization
- Edge AI Algorithm Optimizer

These projects are intended to connect mathematical reasoning, algorithms, scientific computing, and engineering applications.

---

## Testing

Implementations are progressively validated using automated tests.

Typical workflow:

```bash
pytest
```

The objective is to verify:

- correctness,
- edge cases,
- numerical stability,
- regression errors,
- consistency between alternative implementations.

---

## Development Workflow

Typical contribution workflow:

```bash
git switch -c feature/topic-name

git add .
git commit -m "feat: implement algorithm name"

git push
```

Commit messages are kept concise and descriptive.

Examples:

```text
feat: implement binary search
feat: add merge sort benchmark
test: add dijkstra edge cases
docs: explain dynamic programming recurrence
refactor: improve graph representation
```

---

## Current Learning Direction

My current progression follows:

```text
Python
  ↓
Algorithmic Complexity
  ↓
Searching and Sorting
  ↓
Data Structures
  ↓
Algorithm Design
  ↓
Graph Algorithms
  ↓
Numerical Computing
  ↓
Optimization
  ↓
Advanced Algorithms
  ↓
Machine Learning Algorithms
```

The long-term objective is to develop a strong foundation at the intersection of:

**Mathematics + Algorithms + Scientific Computing + Optimization + Artificial Intelligence + Engineering**

---

## Tools

Main technologies used throughout the repository:

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter
- Pytest
- Git
- GitHub
- Linux

The emphasis remains on **from-scratch implementations** whenever this provides educational or mathematical value.

---

## References

The `references/` directory contains selected:

- textbooks,
- scientific papers,
- courses,
- online resources,
- algorithm references.

Major references will progressively include material related to:

- algorithms and complexity,
- graph theory,
- numerical analysis,
- mathematical optimization,
- probability,
- machine learning,
- scientific computing.

---

## Status

This repository is an ongoing learning and research project.

Algorithms and notes are added progressively as I study, implement, test, benchmark, and apply each topic.

> The goal is not to collect implementations, but to understand why algorithms work, when they work, how efficiently they work, and how they can be used to solve real mathematical and computational problems.

---



**Exaucé Kambale Maruba**  
Master’s Student | Regular Program in Mathematical Sciences  
AIMS Senegal | African Institute for Mathematical Sciences  

Email: [kambale.m.exauce@aims-senegal.org](mailto:kambale.m.exauce@aims-senegal.org)

---

## License

This repository is intended primarily for educational, academic, and research purposes.

See the `LICENSE` file for details.