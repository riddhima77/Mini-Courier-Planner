# Mini-Courier Planner

## Project Overview
Mini-Courier Planner is a Python-based project that helps plan parcel deliveries by prioritizing parcels, optimizing box capacity, and finding efficient delivery routes.

## Features
- Parcel prioritization using sorting.
- Optimal parcel selection using Dynamic Programming (0/1 Knapsack).
- Shortest path calculation using Dijkstra's Algorithm.
- Delivery route optimization using Nearest Neighbor TSP approximation.
- Performance analysis using runtime measurements and graphs.

## Algorithms Used
1. Sorting Algorithm
2. Dynamic Programming (0/1 Knapsack)
3. Dijkstra's Shortest Path Algorithm
4. Nearest Neighbor TSP Approximation

## Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Structure
- mini_courier_planner.ipynb: Main project code.
- requirements.txt: Required Python libraries.
- datasets/: Parcel and delivery graph datasets.
- images/: Performance graphs.
- README.md: Project documentation.

## How to Run
1. Install Python.
2. Install the required libraries using:

   pip install -r requirements.txt

3. Open Jupyter Notebook.
4. Open mini_courier_planner.ipynb.
5. Run all cells from beginning to end.

## Performance Analysis
The project measures the execution time of sorting, Knapsack, Dijkstra, and TSP algorithms on different dataset sizes.

## Conclusion
This project demonstrates how sorting, dynamic programming, graph algorithms, and approximation techniques can be combined to solve a practical courier delivery planning problem.

## Algorithm Complexity Analysis

| Algorithm | Time Complexity | Space Complexity |
|---|---|---|
| Sorting | O(n log n) | O(n) |
| Knapsack (Dynamic Programming) | O(n x C) | O(n x C) |
| Dijkstra | O((V + E) log V) | O(V + E) |
| Nearest Neighbor TSP | O(V^2) | O(V) |

Where:
- n = Number of parcels
- C = Knapsack capacity
- V = Number of graph vertices
- E = Number of graph edges

## Performance Analysis

The project evaluates four algorithms using different input sizes.

- Sorting: Fast execution for larger parcel datasets.
- Knapsack: Execution time increases with the number of parcels.
- Dijkstra: Efficient shortest-path calculation on tested graphs.
- Nearest Neighbor TSP: Execution time increases significantly for larger graphs.

Performance graphs are available in the images/ folder.

Detailed performance results are available in performance_report.txt.
