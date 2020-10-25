STEP 1: Learning what is A* finding Algorithm and how it works.

A* finding algorithm is a informed search algorithm which finds the best path to the given goal node having the smallest cost (least distance travelled, shortest time, etc.)\

Imagine a node grid with a starting node A and ending node B
(its like graph paper)

G cost = distance/time needed to travel from starting node(A)
H cost = distance/time needed to travel to ending node(B)

S cost = G cost + H cost
Each node will have a S cost

The algorithm will follow the lowest cost to find the path to the given goal with the lowest cost.

Step 2: Code a visualisation tool
prerequsites: Pygame

