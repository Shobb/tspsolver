# TspSolver: Solving the Traveling Salesman Problem

**TspSolver** is a powerful software application designed to tackle the **Traveling Salesman Problem (TSP)**. Whether you're a logistics expert, a researcher, or just curious about optimization, TspSolver has you covered. Let's dive into the details:

## Key Features

1. **Two Solving Modes**:
    - **Heuristic Solver (Genetic Algorithm)**: This mode quickly finds near-optimal solutions. It leverages natural selection principles to explore the solution space efficiently.
    - **Exact Mode (MIP Solver)**: For those seeking the absolute best solution, this mode uses Mixed Integer Linear Programming (MILP). It can handle instances with up to 200 cities. You can even use the results from the heuristic solver as an initial solution for the exact solver.

2. **Input and Output in Excel Format**:
    - Load your distance matrix (in Excel format) into TspSolver. The matrix can be symmetric or asymmetric, with up to 350x350 entries. All distances must be non-negative.
    - Save the results into an Excel workbook with two sheets:
        - One sheet contains the indices of points in the best route.
        - Another sheet provides more detailed information, including distances between points.

3. **Directories**:
    - **Data**: Contains input matrices.
    - **Solutions**: Includes some exact solutions obtained using the above-described methods.

## Get Started

Ready to solve the TSP? Download TspSolver from the [Microsoft Store](https://www.microsoft.com/store/apps/9PHQJQQDQGZ0) and start optimizing your routes!

🚚🌐

---

Feel free to explore TspSolver, experiment with different settings, and find the best routes for your traveling salesman challenges! If you have any questions or need further assistance, don't hesitate to ask. Happy solving! 🛤️🌟
