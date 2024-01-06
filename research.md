---
layout: page
title: Research
---

# My Research
![Buses charging in Gothenburg, Sweden.](/gbg_bus.png)
*In front of the fast electric bus chargers at Heden terminal, Gothenburg, Sweden.*

My PhD research is focused on battery-electric buses (BEBs). Transit agencies across the U.S. (as well as the rest of the world) have ambitious plans to reduce their emissions and BEBs will be an important technology to support that goal. However, they also present challenges to bus operators due to limited driving ranges and slow recharging times in comparison with buses that use liquid fuels. My work on BEBs consists of two main thrusts:

1) Optimization models for both long-range planning and daily operations of transit systems using BEBs. This includes planning for recharging infrastructure and scheduling charging during the day. These problems are simple to understand and state, but solving them turns out to be very computationally challenging.

2) Software tools to facilitate running these models and visualizing their results. This includes one public-facing tool so far, the [Zero-Emission Bus Range & Recharging Assessment (ZEBRA)](https://bit.ly/zebra-app). This public web app is compatible with most American transit agencies' public GTFS data and processes data on vehicle blocks (daily trip assignments for each bus) to determine range requirements and potential recharging needs.

## Technical Expertise
The technical side of my work centers on optimization, particularly mixed-integer linear programming. My experience with operations research dates back to my final year of undergrad in 2016-17 (thank you to my awesome professor [Susan Martonosi](https://www.hmc.edu/mathematics/people/faculty/martonosi/) for getting me into this subject!) and I've been working in this field ever since, both at UW and in my previous job at [Pacific Northwest National Laboratory](https://www.pnnl.gov). My expertise includes:
* Developing optimization models across a variety of domains, but especially transportation, power systems, and network models.
* Integer programming algorithms, including:
  * Branch-and-cut (and its application in modern solvers using callbacks)
  * Decomposition methods such as Benders Decomposition and Lagrangian Relaxation
* Solving optimization models with modern software tools, especially. I'm particularly familiar with the solver-agnostic `pyomo` library and Gurobi's `gurobipy`, both of which I have used extensively. I have also used MATLAB, GAMS, and AMPL for optimization work.
* Data processing and visualization tools to help with optmization inputs and outputs. I have several years of experience with major Python libraries like `pandas`, `numpy`, `matplotlib`, and `plotly`.

## Publications
**McCabe, D.**, X.J. Ban., and B. Kulcsár. Recharging Scheduling for Electric Buses with Exact Delay Propagation. In preparation for *Transportation Research Part E: Logistics and Transportation Review.*

**McCabe, D.** and X.J. Ban. Optimal Locations and Sizes of Layover Charging Stations for Electric Buses. *Transportation Research Part C: Emerging Technologies* 152 (2023): 104157. 

**McCabe, D.** Selecting Layover Charging Locations for Battery-Electric Buses: Mixed-Integer Linear Programming Models. Master's thesis, University of Washington, 2021. Available at: [http://hdl.handle.net/1773/47413](http://hdl.handle.net/1773/47413)

See my [CV](/cv) for a full list of publications and presentations.

![Two BEBs plugged in to charge.](/heden_pantographs.jpeg)
