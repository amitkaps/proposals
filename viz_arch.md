# Architectural Considerations for Interactive Visualization

**Summary**

A key measure that defines the success of a data science project is in how well it communicates the insights to the stakeholders. Interactive visualization gives the power to the end-user. The end-user is no longer constrained by the narrative the analyst wants to provide her. She is free to explore further. But how to architect an interactive visualization? What are its design considerations? What are the tradeoffs?

The speakers discuss various methodologies on how to set up such a system that's robust to scale and velocity of data.


### Detailed Abstract

The talk covers the five major areas that impact interactive visualization

**Scale of data**

It is easy to envision how interactive visualization would look like when data is manageable. But how to handle interactive visualization when data is in millions or billions of data points? An example of this is demonstrated using datashader

**Velocity of data**

What's the impact of velocity on interactive visualization? The following are discussed:

1. Impact of lambda architecture
2. Using verdict to sample 
3. Interactive Charttypes that are effective for high velocity data


**Type and Cardinality of data**

The following are discussed

1. How to handle mixed types?
2. How to handle time?
3. How to handle high cardinality data?

**Space available for visualization**

The amount of space available for interactive visualization impacts design and architecture choices. This section will discuss some choices developers need to be aware about when working with high volume/velocity data.

**Responsiveness**

The trade-offs between real-time Vs near real-time and its impact on refreshing visualization is discussed in this section.


**Target Audience**

Data Scientists, Data Analysts, Data Visualization Analysts, Journalists, Product Managers

**Key Takeaways**

The audience will learn the following: 
1. How to architect interactive visualization
2. What's the impact of scale of data on interactive visualization
3. What's the impact of velocity of data on interactive visualization
4. What's the impact on variety and cardinality of data on interactive visualization
