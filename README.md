BSV
===

A visualization tool for NetLogo BehaviorSpace runs.

Goals
---
- [ ] Import arbitrary CSV in intelligently, allowing easy access from NetLogo code.
    - Currently supports basic, unquoted csv, focusing on BehaviorSpace output.
- [x] Visualize data as points with attributes (xcor, ycor, color, label, size) set to arbitray reporters based on data.
- [x] Intelligent defaults for attribute scaling.
- [x] Easily transition between different visualizations.
- [x] Group data based on arbitrary keys.
    - Example use case: Be able to visualize mean values for repeated runs.
- [ ] Ability to visualize a single row as multiple points, each point using different columns.
    - Example use case: Suppose you have data from a single run tracking three populations. You want to be able to plot each population over time simultaneously.
- [ ] Mix grouping and splitting
    - Example use case: Have multiple runs of three populations. You want to be able to plot the means of each population across the runs simultaneously.
- [ ] Build-in clustering algorithms.
    - Example use case: Color clusters in scatter plot.
    - Example use case: Use clusters as groups, so you could get means within clusters.
- [ ] Be able to handle 2 uniform inputs with one output. A heatmap would be one way to do this.
- [ ] Visualize changes over time.
    - One simple thing to help this is just add a `connect-to` reporter, which woud create a link from a point to another point if the reporter is true for that point.
    - A more sophisticated way would be "sliding window" points.

Ultimate test case: Be able to visualize model state space, averaged across runs. Be able to visualize the vector field of the state space would be pretty awesome too.

