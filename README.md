## Fuel Delivery Optimization (OR problem)

### Overview

This challenge revolves around optimizing fuel delivery to various service stations using a
fleet of trucks. The goal is to minimize the `total distance traveled`, the `overall fuel
consumption`, the `total driving time`, and the `computational time` required to determine the
optimal routes. The challenge incorporates elements of the Traveling Salesman Problem
(TSP) and the Capacitated Vehicle Routing Problem (CVRP). 

>-  Go to the description file **"Description.pdf"** for more information
>-  Go to the Excel file **"coordonnée GPS et type camion.xlsx"** to have an overview about the dataset.

### Problem Statement
The goal is to determine the optimal routes for the fleet of trucks to deliver fuel to the service, satisfying the following constraints:
- Each truck has a maximum capacity of fuel it can carry
- Each service station has a specific demand for fuel (no more).

And reaching the following optimization objectives:
- Minimize the total distance traveled by all trucks combined.
- Minimize the total amount of fuel consumed by all trucks.
- Minimize the total driving Time.

And one optional objective:
- Minimize the time taken by the algorithm to compute the optimal routes.

---
The problem was solved in Python and Jupyter using the following libraries:
- **pandas** for data manipulation
- **numpy** for numerical operations
- **networkx** for graph visualization
- **ortools** for optimization
- **time** for time calculation
