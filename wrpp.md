---
layout: page
title: WRPP
---
# Mountain Bike Routing with the Windy Rural Postman Problem
I got hooked on mountain biking shortly after moving to Seattle in 2018. My favorite place to ride is [Tiger Mountain State Forest](https://www.trailforks.com/region/tiger-mountain-state-forest/), east of Seattle near Issaquah, WA. For many years I've heard fellow mountain bikers talk about the challenge of riding all the purpose-built MTB trails there in a single day and debate over the best route to take to do it. As more trails are built there, both the physical challenge and the route planning keep getting harder! Inspired by all these conversations and my goal of taking on the challenge someday, I decided to use my optimization skills to solve this problem for Tiger.

Reviewing the literature led me to discover that the problem of determining the best route was exactly equivalent to the *Windy Rural Postman Problem* (WRPP), a niche but fairly well-studied problem in network optimization. This problem closely resembles the famous Traveling Salesman Problem in which we try to find the shortest tour that visits every node on a graph -- however, in the WRPP, our goal is to find the shortest route that traverses a specific subset of edges in the graph. All other optional edges can be used as "shortcuts" to decrease the length of the optimal tour.

As a class project for IND E 570: Supply Chain Systems at UW in Spring 2021, I wrote Python code to solve this problem with both exact and heuristic methods, based on trail network data acquired with the `osmnx` package that reads OpenStreetMap data as a `networkx` graph object. You can see the solution animated below! The solution is now due for an update to bring in a couple more trails that have opened in the years since.

![Optimal mountain bike tour around Tiger Mountain](/tiger_soln.gif)

The resulting ride is huge, totaling over 45 miles of mountainous terrain!