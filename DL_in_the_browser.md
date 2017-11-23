# Deep Learning in the Browser: Explorable Explanations, Model Inference & Rapid Prototyping

## Abstract
We showcase three live-demos of doing deep learning (DL) in the browser - for building explorable explanations to aid insight, for building model inference applications and even, for rapid prototyping and training ML model - using the emerging client-side Javascript libraries for DL.

## Description
The browser is the most common end-point consumption of Deep learning models. It is also the most ubiquitous platform for programming available. The maturity of the client-side JavaScript ecosystem across the deep learning process e.g. dataframe support (arrow.js), WebGl accelerated learning frameworks (deeplearn.js), declarative interactive visualisation (vega-lite.js), have made it easy to start playing with Deep Learning in the browser.

This talk is designed in the "Show, not Tell" format. We will focus on showcasing three particular use case (live-demos) where deep learning models can be used for explanations, inference and training on the browser directly. The demos will also show the application from three different types of data types - tabular, text and image.

1. **Explorable Explanations**: Explaining the DL model and allowing the users to build intuition on the model helps in generating insight. We showcase an *explorable explanation for loan default DL model*, which allows the user to explore the feature space and threshold boundaries using interactive visualisations to drive decision making.

2. **Model Inference**: Inference is the most common use case and the browser allows you to 'bring your DL model to the data'. We showcase an *comments sentiment* application in the browser, which can identify and warn about the toxicity of the comments as you type in a text box.

3. **Rapid Prototyping**: Training of DL models is now possible in the browser itself. We showcase a *rapid prototyping image classification* example which allows the user to play with transfer learning to build a model specific for a user-generated image input.  

We will end the talk on how we see the ecosystems of tools for DL in the browser emerging and making it easy for everyone to start doing this. One key trend, is the emergence of easy authoring tools like [visdown](http://visdown.com/), [Idyll](http://idyll-lang.org/editor/) and eventually [Observable](https://observablehq.com/) to do this on the browser.

For those more curious about how all these demos will actually happen, we will be leveraging the following newer libraries (and some traditional ones like d3.js) in javascript.

- [Arrow.js](https://github.com/apache/arrow/tree/master/js) for data loading, and type inference 
- [Facets](https://pair-code.github.io/facets/) for exploratory data analysis.
- [Ml.js](https://github.com/mljs/) for traditional machine learning model training and inference.
- [Deeplearn.js](https://deeplearnjs.org/) for deep learning model training and inference.
- [Vega and Vega-lite](https://vega.github.io/) for interactive dashboard

The working demos will be available on the web and open-source code on Github. 