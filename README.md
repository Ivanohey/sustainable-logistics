# Optimization of Measles vaccine supply chain in Pakistan
Repository containing the project of Sustainable Logistics class of String 2023 at HEC Lausanne

## Scope of the project

For this project we performed an optimization of a Capacitated Vehicle Routing problem for the delivery of Cold Chain Vaccine boxes in Sindh region of Pakistan using 3 trucks and a train.
- We minimized the total distance of the route knowing that this has a direct impact on the fuel, maintenance and labour costs.
- The routing covers 15 cities with specific demands of vaccines
- We used two airports as the depot

## Running the project
The project consists of two parts. We used R to gather data and clean it and we used Python to build and compute our optimization problem.


## Python dependencies
ORtools:
```
pip install ortools
```
Geopy:
```
pip install geopy
```
