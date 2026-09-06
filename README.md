# N-Queens Problem Using Backtracking

## 📌 Project Overview

This project implements the **N-Queens Problem** using the **Backtracking Algorithm** in Python.

The N-Queens problem is a classic algorithmic problem in which N queens must be placed on an N × N chessboard so that no two queens attack each other.

No two queens should be placed in the same:

* Row
* Column
* Diagonal

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Backtracking Algorithm

## 🧠 Algorithm Used

The solution uses the **Backtracking technique**.

The algorithm places queens row by row. Before placing a queen, it checks whether the position is safe.

If a safe position is found, the queen is placed and the algorithm proceeds to the next row.

If no safe position is available, the algorithm goes back to the previous row and changes the position of the previously placed queen.

This process continues until a valid solution is found.

## ▶️ How to Run

1. Clone or download this repository.
2. Open `Nqueens.ipynb` using Jupyter Notebook.
3. Run the cells.
4. Enter the required number of queens when prompted.

Example:

```text
Enter the queens value: 4
```

## 📊 Example Output

For N = 4, one possible solution is:

```text
. Q . .
. . . Q
Q . . .
. . Q .
```

Here, `Q` represents a queen and `.` represents an empty position.

## 🎯 Learning Outcomes

Through this project, I learned:

* How the N-Queens problem works.
* How backtracking can be used to solve constraint-based problems.
* How to check whether a queen can be safely placed.
* How recursion works in backtracking algorithms.
* How to implement and test an algorithm using Python.
* How to upload and manage a coding project using GitHub.


Vaishnavi
