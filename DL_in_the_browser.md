# Machine Learning in the Browser: Explorable Explanations, Model Inference and Rapid Prototyping

## Abstract
We showcase three live-demos of doing machine learning in the browser - for building explorable explanations for insight, for building model inference applications and even, rapid prototyping for training ML model - using the emerging client-side Javascript libraries for ML.

## Description
The browser is the most common end-point consumption of Deep learning models. It is also the most ubiquitous platform for programming available. The maturity of the client-side JavaScript ecosystem across the machine learning process e.g. dataframe support (arrow.js), WebGl accelerated learning frameworks (deeplearn.js), declarative interactive visualisation (vega-lite.js), have made it easy to start playing with Deep Learning in the browser.

This talk is designed in the "Show not Tell" format. We will focus on showcasing three particular use case (live-demos) where Machine learning (Shallow and Deep Models) can be used for explanations, inference and training on the browser directly. The examples will also show the application for three different types of data problems - tabular, text and image.

1. **Explorable Explanations**: Explaining the ML model and allowing the users to build intuition on the model helps in generating insight. We showcase an *explorable explanation for  loan default ML model*, which allows the user to explore the feature space and threshold boundaries using interactive visualisations to drive decision making.

2. **Model Inference**: Inference is the most common use case and the browser allows you to 'bring your DL model to the data'. We showcase an *comments sentiment* application in the browser, which can identify and warn about the toxicity of the comments as you type in a text box.

3. **Rapid Prototyping**: It is now possible to start training ML models, even deep learning models in the browser itself. We showcase a *rapid prototyping image classification* example which allows you to play with transfer learning to build a model specific for a user-generated image input.  

We will end the talk on how we see the ecosystems of tools for ML in the browser emerging and making it easy for everyone to start doing this. One key trend, is the emergence of easy authoring tools like [visdown](http://visdown.com/), [http://idyll-lang.org/editor/] and eventually [Observable](https://observablehq.com/) to do this on the browser.

For those more curious about how all these demos will actually happen, we will be leveraging the following libraries in javascript.

- [Arrow.js](https://github.com/apache/arrow/tree/master/js) for data loading, and type inference 
- [Facets](https://pair-code.github.io/facets/) for exploratory data analysis.
- [SimpleStatistic.js](http://https://simplestatistics.org/) for statistical inference
- [Ml.js](https://github.com/mljs/) for traditional machine learning model training and inference.
- [Deeplearn.js](https://deeplearnjs.org/) for deep learning model training and inference.
- [Vega and Vega-lite](https://vega.github.io/) for interactive dashboard

The final working demos will be available on the web and open-source code on Github, before the talk. 