# Capacitated VRP - CVRP

## Problem Statement

Write an algorithm to solve the vehicle routing problem. The problem is mathematically formulated in the following way: We are given a list of locations `N = 0 . . . n − 1` . By convention, location `0` is the warehouse location, where all of the vehicles start and end their routes. The remaining locations are customers. Each location is characterized by three values `⟨d<sub>i</sub>, x<sub>i</sub>, y<sub>i</sub>⟩ i ∈ N` a demand `d<sub>i</sub>` and a point `x<sub>i</sub>,y<sub>i</sub>`. The fleet of vehicles `V = 0...v − 1` is fixed and each vehicle has a limited capacity `c`. All of the demands assigned to a vehicle cannot exceed its capacity `c`. For each vehicle `i ∈ V`, let `T<sub>i</sub>` be the sequence of customer deliveries made by that vehicle and let `dist(c<sub>1</sub>, c<sub>2</sub>)` be the Euclidean distance between two customers. Then the vehicle routing problem is formalized as the following optimization problem.

* *__n__* Locations, *__v__* Vehicles
* For each location
  * demand *__di__* and location *__xi,yi__*
* The capacity of the vehicles *__c__*

## Title

### Title
