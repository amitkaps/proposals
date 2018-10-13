# Flatlands: 2D Visualisation of Multi-Dimensional Data

## Description 

Even though exploring data visually is an integral part of the data analytic pipeline, we struggle to visually explore data once the number of dimensions go beyond three. This talk will focus on showcasing techniques to visually explore multi dimensional data (p > 4) through both representation and projection based approach by visualising it in two dimensions. The aim would be show examples of the possible techniques to navigate this flatlands, using one exemplar dataset. 


## Outline

- Visualising Multi-Dimensional Data (5 mins)
  - The Curse of Dimensionality
  - Representations and Projections
  - Trade-offs in moving to Flatlands
  
- Representation Approaches (10 mins)
  - Aggregation: TableLens
  - Small Multiples: Facets 
  - Alternate Coordinates: Parallel
  - Pixel based: Space Filling Curves
  - Stacked based: Hierarchical

- Projection Approaches (10 mins)
  - Linear Transformation: PCA
  - Optimization Based: t-SNE
  - Manifold Based: IsoMap
  - Graph based: Nearest Neighbour
  - Neural Nets: Auto-encoder

- Navigating Flatlands (5 mins)
  - Using Interaction to aid discovery
  - Guidance on choosing the right method

The code is for the talk will be available at http://amitkaps.com/multidim/ in both Python and Javascript. 

## Notes on the talk

The intent is to help the audience build intuition about each of these methods using both code and visuals. Each technique makes a different trade-off in visualisation and the audience would have a better understanding of those. In order to do so, I will be using a singular dataset, so I have to introduce the dataset once at the start of the talk.

In the representation section, I will be only changing one or two aspect of the visualisation, to ensure there is a flow and the audience can easily follow.

Raw Data Table -> Heatmap (Add Color to table) -> Table Lens (Do Aggregation) -> Facets (Make 2-d Scatter Charts) -> Parallel Coord (Change coordinate to parallel, Use lines) -> Pixel Based (Use color bars instead of lines) -> Hierarchical (Stack in an order)

In the projection section, I will be explaining the trade-off that the projection makes in making a two representation. Most of the code will be a 4-5 lines of sci-kit / ml.js and few lines of vis code. Again the idea is to build an intuition on the trade-offs each method is making.

I have deliberately left out interaction based methods - guideds tours etc. (Escaping Flatlands!) out of the discussion.

Obviously, the talk is the starting point of the learning journey for the audience. Hence, to continue the same there would be Jupyter Notebooks with all the code available on Github. Also a more long-form write-up on this (including simpler methods and interaction) would be available at http://amitkaps.com/multidim/ (It is in early stages of development, but you can see the table of content at the moment there.)

The following libraries would be used for the data loading, transformation and visualisation
- Data Loading and Transfomration (Datalib.js & Arrow.js in JS / Pandas in Python)
- Visualisation (Vega.js & Vegalite.js in JS / Altair in Python
- Projections (Ml.js & Deeplearn.js in JS / Sci-kit learn in Python)

## About the Speaker

The speaker has been involved in doing analytics and visualisation for more than fifteen years and has been actively involved in teaching Data Visualisation and Data Science for the last seven years. 

An earlier version of this talk focussed on simpler representations can be viewed at Fifth Elephant 2015: Visualising Multi-Dimensional Data - https://www.youtube.com/watch?v=X8rNDvPNg30

You can also see his speaking profile at [http://amitkaps.com/talks](http://amitkaps.com/talks)

The intent is to help the audience build intuition about each of these methods using both code and visuals. Each technique makes a different trade-off in visualisation and the audience would have a better understanding of those. The code would 5-6 lines for each (using matplotlib based vis-libraries and numpy / sci-kit learn for transformations) and would be shown along with the visualisation.

In order to do so, I will be using a singular dataset, so I have to introduce the dataset once at the start of the talk.

In the representation section, I will be only changing one or two aspect of the visualisation, to ensure there is a flow and the audience can easily follow.

Raw Data Table -> Heatmap (Add Color to table) -> Table Lens (Do Aggregation) -> Facets (Make 2-d Scatter Charts) -> Parallel Coord (Change coordinate to parallel, Use lines) -> Pixel Based (Use color bars instead of lines) -> Hierarchical (Stack in an order)

In the projection section, I will be explaining the trade-off that the projection makes in making a two representation. Most of the code will be a 4-5 lines of sci-kit learn and one line of  vis code. Again the idea is to build an intuition on the trade-offs each method is making.

I have deliberately left out interaction based methods - like brushing / linking, tours etc. (Escaping Flatlands!) out of the discussion.


Obviously, the talk is the starting point of the learning journey for the audience. Hence, to continue the same there would be Jupyter Notebooks with all the code available on Github. Also a more long-form write-up on this (including simpler methods and interaction) would be available at http://amitkaps.com/multidim/ (It is in early stages of development, but you can see the table of content at the moment there.)


## Audience

The talk is ideal for those using Python for Data Analysis and Machine Learning and want to understand and learn how to visualise multi-dimensional data. They should have some basic experience with simple visualisation of 2 -3 dimensional data. Post the talk, the will have a richer understanding of the approach to take for visualising multi-dimensional data in their own domain.  


## Additional 

The speaker has been involved in doing analytics and visualisation for more than fifteen years and has been actively involved in teaching Data Visualisation and Data Science for the last seven years. 

An earlier version of this talk focussed on simpler representations can be viewed at Fifth Elephant 2015: Visualising Multi-Dimensional Data - https://www.youtube.com/watch?v=X8rNDvPNg30

You can also see his speaking profile at [http://amitkaps.com/talks](http://amitkaps.com/talks)

*Select Talks and Workshops in the Last three Year*
- Fifth Elephant 2016 (India's biggest data science conference): Workshop on HackerMath for Machine Learning 
- Strata Singapore 2016: The Power of Ensembles - [https://www.youtube.com/watch?v=I6PuK7A1l6A](https://www.youtube.com/watch?v=I6PuK7A1l6A)
- Strata Singapore 2016: Deep Learning for Text - [https://www.youtube.com/watch?v=hrKFHZ2Gh1o](https://www.youtube.com/watch?v=hrKFHZ2Gh1o)
- Strata New York 2016: Visualising Machine Learning Models - [https://www.youtube.com/watch?v=xqAbfMgmBas](https://www.youtube.com/watch?v=xqAbfMgmBas)
- PyCon Singapore 2016: Workshop on Data Analysis and Machine Learning