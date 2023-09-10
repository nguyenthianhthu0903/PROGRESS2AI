# PROGRESS2AI
Description:</br>
- Given a matrix of m x n, a cell consists of a non-negative integer or it is blank.
- Each cell has 9 “adjacent” neighbors, including itself and 8 cells around.
- Players color cells by red or green so that the number of green cells which are
“adjacent” to a cell is exactly the number inside.
- There is no constraint for blank cells.
-  Use propositional logic to solve the problem
+ Assign a propositional symbol to each cell (true -> green, false -> red)
+ Enumerate cells to generate CNF clauses representing constraints.
+ Find a model satisfying all clauses using Glucose3 of PySAT.</br>
pip install python-sat==0.1.7.dev12
