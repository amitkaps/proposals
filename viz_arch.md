# Architectural Considerations for Interactive Visualization

## Summary

Visualisation for data science requires an interactive visualisation setup which works at scale. In this talk, we will explore the key architectural design considerations for such a system and illustrate using examples the four key tradeoffs in this design space - rendering for data scale, computation for interaction speed, adaptive to data complexity and responsive to data velocity. 

## Detailed Abstract

Visualisation is an integral part of data science process - EDA to understand the shape of the data, Model visualisation to unbox the model algorithm and, Dashboard visualisation to communicate the insight. This task of visualisation is increasingly shifting from a static & narrative setup to an interactive & reactive setup, which presents a new set of challenges for those designing interactive visualisation applications.

The talk covers the four major areas that impact the architecture design of interactive visualization at scale and will illustrate the different design trade-offs involved using exemplars and case studies for each.

1. **Rendering for Data Scale**: Envisioning how the visualization can be displayed when data size is small is not hard. But how do you render interactive visualization when data points is in millions or billions of data points?
   - Bin-Summarize-Smooth e.g. Datashader, BigVis
   - WebGL based Rendering e.g. Deck.gl

2. **Computation for Interaction Speed**: Making the visualisation reactive requires the user to have the ability to interact, drill-down, brush and link multiple visual views to gain insight. But how do you reduce the latency of the query at the interaction layer, so that the user can interact with the visualisation?.
   - Aggregation & In-Memory Cubes e.g. Hashcubes, inMems, Nanocubes
   - Approximate Query Processing / Sampling e.g. VerdictDB
   - GPU based Databases e.g. MapD

3. **Adaptive to Data Complexity**: Choosing a good visualisation design for a singular dataset is possible after a few experiments and iteration.  But how do you ensure that the visualisation will adapt to the variety, volume and edge cases in the real data?
   - Responsive Visualisation to Space & Data
   - Handling High Cardinality e.g. Facet-Dive
   - Multi-Dimensional Reduction e.g. Embedding Projector

4. **Responsive to Data Velocity**: Designing for periodic query based visualisation refreshes is one thing. But streaming data adds a whole new level of challenge to interactive visualisation. So how do you trade-offs between real-time vs. near real-time data and its impact on refreshing visualization?
   - Optimizing for near real-time visual refreshes
   - Handling event / time based streams

## Target Audience

Data Scientists, Data Analysts, Data Visualization Analysts,  Business Intelligence Designers, Product Managers

## Key Takeaways

1. Ideas on the architecture design for making an interactive visualisation application for large data 
2. Approaches to balance the different trade-off - rendering, computation, adaptive and responsiveness - inherent in the design.
3. Insight and learnings on how others have addressed these trade-offs

