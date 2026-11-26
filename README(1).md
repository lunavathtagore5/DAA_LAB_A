# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search 

# PRACTICAL 3 : Min-Heap and Max-Heap Sort
Description:

This project implements Heap Sort in Python using heapq.

Min-Heap: Sorts elements in ascending order.
Max-Heap: Sorts elements in descending order.
Features
Takes user input for array elements.
Uses heapq.heapify() and heapq.heappop().
Measures execution time using time.perf_counter().
Displays time complexity.
Example

Min-Heap:

Input: 25, 14, 36, 85, 96
Output: [14, 25, 36, 85, 96]

Max-Heap:

Input: 25, 78, 89, 45, 56, 33
Output: [89, 78, 56, 45, 33, 25]
Complexity
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Space Complexity: O(n)
Requirements
Python 3
heapq and time modules (built-in)
Conclusion

The program demonstrates how Min-Heap and Max-Heap can be used to efficiently sort an array in ascending and descending order.

# PRACT-4:iterative & recursive methods
In this practical, we learned how to find the factorial of a number using two different methods: iterative and recursive. In the iterative method, we use a loop to multiply the numbers from 1 to the given number. In the recursive method, the function calls itself with a smaller value until it reaches the base condition. Both methods give the same factorial result, but they work in different ways. CONCLUSION: From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem. CONCLUSION: From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods ar

# practical-5: Knapsack Problem
This project is a Python program that solves the 0/1 Knapsack Problem using Dynamic Programming. The program takes the number of items, their weights, values, and the maximum capacity of the knapsack as input. It then finds the maximum value that can be carried without exceeding the given capacity. The program also displays the selected items and the execution time. This project is simple and useful for understanding the basic concept of Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named knapsack.py and run it using the command python knapsack.py in the terminal.

Example

For 4 items with weights 2, 3, 4, 5 and values 3, 4, 5, 6, with a knapsack capacity of 5, the maximum value is 7 and items 1 and 2 are selected.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the 0/1 Knapsack Problem. It helps in finding the best combination of items while keeping the total weight within the given capacity. The project is simple and helpful for learning Python and Dynamic Programming.

# PRACTICAL-6 MATRIX CHAIN MULTIPLICATION

Matrix Chain Multiplication is a Dynamic Programming problem that finds the most efficient way to multiply a sequence of matrices.

The main objective is to determine the optimal order of matrix multiplication that minimizes the total number of scalar multiplications. The order of the matrices remains unchanged; only the placement of parentheses is optimized.

This project implements the Matrix Chain Multiplication algorithm using Python and Dynamic Programming.


# PRACTICAL 7:Coin Change Problem Using Dynamic Programming
This project provides a Python solution to the Coin Change Problem using Dynamic Programming. The program determines the minimum number of coins required to make a given target amount from a set of available coin denominations.

The algorithm builds a dynamic programming table to store the minimum coins needed for every amount from 0 to the target value. By reusing previously computed results, it efficiently finds the optimal solution and avoids redundant calculations.

If the target amount can be formed, the program returns the minimum number of coins required. Otherwise, it returns -1 to indicate that no valid combination exists.

Features
Efficient Dynamic Programming approach
Finds the minimum number of coins required
Handles impossible cases by returning -1
Simple and easy-to-understand Python implementation
Complexity
Time Complexity: O(n × amount)
Space Complexity: O(amount)
This project is useful for learning Dynamic Programming concepts, practicing algorithm design, and preparing for coding interviews.

# PRACT8-(DAA)
SUMMARY :

Graph traversal is an important technique used to visit all the vertices of a graph systematically. DFS explores a graph deeply by visiting a vertex and then recursively visiting its unvisited neighbors. BFS explores the graph level by level using a queue data structure. Both DFS and BFS have a time complexity of O(V + E), where V is the number of vertices and E is the number of edges. These searching techniques are widely used in path finding, network analysis, and many other computer science applications.

CONCLUSION :

The graph traversal program successfully implements both DFS and BFS searching techniques using Python. DFS uses a depth-based approach, while BFS visits vertices level by level. Both methods efficiently traverse the vertices and edges of a graph. The program accepts user input, making it flexible for different graph structures and starting vertices. Thus, DFS and BFS are useful and fundamental techniques for solving various graph-based problems.
# practical-9  PRIM's Algorithm
Prim's Algorithm is a greedy algorithm used to find the Minimum Spanning Tree (MST) of a connected, weighted, undirected graph. It starts with an arbitrary vertex and repeatedly selects the minimum-weight edge that connects a visited vertex to an unvisited vertex without forming a cycle. This process continues until all vertices are included in the spanning tree, resulting in the minimum total edge weight. Prim's Algorithm is widely used in network design and optimization problems.

# practical-10 KRUSKAL's Algorithm
Kruskal's Algorithm is a greedy algorithm used to find the Minimum Spanning Tree (MST) of a weighted, undirected graph. It works by sorting all edges in ascending order of their weights and selecting the smallest edges one by one, ensuring that no cycle is formed. The process continues until the spanning tree contains exactly \(V-1\) edges, where \(V\) is the number of vertices. Kruskal's Algorithm is useful in network design and optimization problems where minimizing the total connection cost is important.
