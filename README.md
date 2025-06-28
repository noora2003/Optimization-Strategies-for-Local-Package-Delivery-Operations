# Optimization-Strategies-for-Local-Package-Delivery-Operations
Optimization Strategies for Local Package Delivery Operations

###################################
Project Overview:
You are responsible for running the operations of a small package delivery shop. Every day, you receive a set
of packages. Each package is characterized by a destination location, a weight in kilograms, and a priority (a
number between 1 and 5, with a lower number indicating higher priority). Your task is to assign each package
to one of the available delivery vehicles that you have and also determine the route that each vehicle will
follow to minimize the operational cost, which is defined by the total distance traveled by all vehicles. While
the goal is to prioritize delivering higher-priority packages first, this is not a strict constraint and can be
violated if doing so would result in significantly higher costs. Each vehicle has a limited capacity (in kg). You
need to ensure that the total weight of the packages assigned to a vehicle does not exceed its capacity.
#####################################
Project Goal:
The goal of this project is to implement a system that solves the package-to-vehicles assignment problem,
minimizing the total traveled distance by all the vehicles in the shop. For simplicity, assume that there is a
direct straight-line route between any two locations (i.e., the distance between two locations is calculated using
the Euclidean distance formula). The location of your shop and the destination location of any package is
represented by (x, y) coordinates.
#######################################
Requirements:
- Implement both of the following algorithms: simulated annealing, and genetic algorithms. At run
time, the user should be able to choose which algorithm to use to generate the solution.
- You must tune the parameters of the implemented algorithms (for example, mutation rate,
temperature schedule, ...etc.)
- To test the system, the user should be able to specify the number of available vehicles, their capacity,
and the specifications of the packages in the store to be delivered.
- Your system should include a user-interface that displays the generated solution of your algorithm
