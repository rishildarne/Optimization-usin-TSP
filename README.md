# Optimization-using-HC
Optimizing a delivery scenario using Hill Climb Algorithm.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/101949683/184755597-78af0aab-3206-4189-bb1f-435091a64cbd.png">

The goal is to find the best strategy such that every store receives its delivery, and the warehouses have the correct number of vehicles at the end of the day to carry out the deliveries the following day.

The first step of the problem is to determine which warehouse should supply a given store. To identify this, I divided the stores into two different lists based on how close a store is to the warehouse. For example, if a store is 10 miles away from warehouse 1 (W1) and 12 miles away from warehouse 2 (W2), it will be supplied by warehouse 1.

By dividing the stores into two different lists, I converted the task into two Traveling salesperson problems. The combined cost of optimal paths in each of the problems will give the required solution.

> Copyright 2022 @ Rishil Darne
