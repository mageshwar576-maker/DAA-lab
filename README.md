
# 📚 Design and Analysis of Algorithms (DAA) – Python Implementation
## 📌 Repository Overview

This repository contains the implementation of five important **Design and Analysis of Algorithms (DAA)** programs using **Python**.

Each program demonstrates a fundamental algorithm, compares its performance with alternative approaches where applicable, and includes practical examples to help understand the algorithm's working and efficiency.

The repository is useful for:

- 🎓 Computer Science students
- 📖 DAA Laboratory
- 💼 Placement preparation
- 🏆 Coding interview preparation
- 📚 Learning classical algorithms

---

# 📂 Programs Included

## 1️⃣ Interpolation Search vs Binary Search

### 📌 Description

This program implements the **Interpolation Search Algorithm** and compares its performance with the **Binary Search Algorithm**.

Interpolation Search estimates the likely position of the target based on its value instead of always checking the middle element like Binary Search.

The program also performs a performance analysis on arrays of different sizes.

### Features

- Implementation of Interpolation Search
- Implementation of Binary Search
- Number of comparisons
- Execution time measurement
- Performance comparison table
- Random test case generation

### Time Complexity

| Algorithm | Best | Average | Worst |
|------------|--------|------------|-----------|
| Interpolation Search | O(1) | O(log log n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |

### Concepts Covered

- Searching Algorithms
- Divide and Conquer
- Performance Analysis
- Complexity Analysis

---

## 2️⃣ String Matching Algorithms

### 📌 Description

This program compares three classical pattern matching algorithms:

- Naive String Matching
- Knuth-Morris-Pratt (KMP)
- Rabin-Karp Algorithm

The program identifies pattern occurrences inside a text and compares the number of character comparisons performed by each algorithm.

### Features

- Naive Pattern Matching
- KMP Algorithm
- Rabin-Karp Algorithm
- LPS Array Construction
- Comparison Counter
- Performance Analysis

### Time Complexity

| Algorithm | Average | Worst |
|------------|------------|-----------|
| Naive | O(nm) | O(nm) |
| KMP | O(n+m) | O(n+m) |
| Rabin-Karp | O(n+m) | O(nm) |

### Concepts Covered

- Pattern Matching
- Hashing
- Prefix Function
- String Processing

---

## 3️⃣ Minimum Spanning Tree (Prim's & Kruskal's Algorithm)

### 📌 Description

This program implements two famous Minimum Spanning Tree algorithms:

- Prim's Algorithm
- Kruskal's Algorithm

The program constructs the Minimum Spanning Tree of a weighted graph and compares the total cost obtained using both algorithms.

### Features

- Prim's Algorithm
- Kruskal's Algorithm
- Union-Find Data Structure
- Path Compression
- Union by Rank
- Priority Queue
- Graph Representation
- MST Cost Calculation

### Time Complexity

| Algorithm | Complexity |
|------------|----------------|
| Prim | O(E log V) |
| Kruskal | O(E log E) |

### Concepts Covered

- Greedy Algorithms
- Graph Theory
- Minimum Spanning Tree
- Disjoint Set (Union-Find)

---

## 4️⃣ Dijkstra's Shortest Path Algorithm

### 📌 Description

This program implements **Dijkstra's Algorithm** using a **Min Heap (Priority Queue)** to compute the shortest path from a source vertex to every other vertex in a weighted graph.

The program also reconstructs the shortest path for every destination node.

### Features

- Dijkstra's Algorithm
- Min Heap
- Priority Queue
- Path Reconstruction
- Shortest Distance Table
- Graph Representation

### Time Complexity

| Operation | Complexity |
|------------|---------------|
| Dijkstra | O((V + E) log V) |

### Concepts Covered

- Greedy Algorithms
- Graph Algorithms
- Shortest Path
- Priority Queue

---

## 5️⃣ Divide and Conquer – Minimum & Maximum Element

### 📌 Description

This program finds the **minimum** and **maximum** element of an array using the **Divide and Conquer** technique.

It also compares the algorithm with the traditional **Naive Method** by counting the number of comparisons performed.

### Features

- Divide and Conquer Approach
- Recursive Solution
- Naive Method
- Comparison Counter
- Formula Verification
- Performance Analysis

### Time Complexity

| Method | Complexity |
|------------|---------------|
| Divide & Conquer | O(n) |
| Naive Method | O(n) |

Number of comparisons:

- Divide & Conquer ≈ **3n/2 − 2**
- Naive = **2(n−1)**

### Concepts Covered

- Divide and Conquer
- Recursion
- Algorithm Analysis
- Comparison Counting

---

# 🛠 Technologies Used

- Python 3
- Heap Queue (heapq)
- Random Module
- Time Module

---

# 📖 Learning Outcomes

After studying this repository, you will understand:

- Searching Algorithms
- Graph Algorithms
- Greedy Algorithms
- Divide and Conquer
- String Matching Algorithms
- Minimum Spanning Tree
- Shortest Path Algorithms
- Time Complexity Analysis
- Performance Comparison Techniques
- Recursive Algorithms

---

# ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Go to the repository

```bash
cd your-repository-name
```

Run any program

```bash
python program1.py
python program2.py
python program3.py
python program4.py
python program5.py
```

---

# 📁 Repository Structure

```
DAA-Algorithms/
│
├── program1.py   # Interpolation Search vs Binary Search
├── program2.py   # String Matching Algorithms
├── program3.py   # Prim's & Kruskal's MST
├── program4.py   # Dijkstra's Shortest Path
├── program5.py   # Divide and Conquer Min-Max
│
└── README.md
```

---

# 🎯 Applications

These algorithms are widely used in:

- Search Engines
- GPS Navigation Systems
- Computer Networks
- Route Optimization
- Compiler Design
- Bioinformatics
- Data Compression
- Database Systems
- Artificial Intelligence
- Operating Systems

---

# ⭐ Key Highlights

- ✅ Clean Python Implementation
- ✅ Well Commented Code
- ✅ Beginner Friendly
- ✅ Performance Comparison
- ✅ Time Complexity Analysis
- ✅ Real-world Algorithm Applications
- ✅ Suitable for DAA Laboratory
- ✅ Placement & Interview Preparation

---

# 👨‍💻 Author

**MAGESHWAR**

Computer Science Engineering Student

---

## ⭐ If you found this repository useful, don't forget to Star ⭐ the repository!
