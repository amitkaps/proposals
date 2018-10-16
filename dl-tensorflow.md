# Tensorflow.js: Deep Learning in the Browser

## Objective 
We will build three live-demos of doing deep learning (DL) in the browser - for building model inference applications, for rapid prototyping and training ML model and for building explorable explanations to aid insight - using tensorflow.js and other emerging client-side Javascript libraries.

## Abstract
The browser is the most common end-point consumption of Deep learning models. It is also the most ubiquitous platform for programming available. The maturity of the client-side JavaScript ecosystem across the deep learning process e.g. dataframe support (arrow.js), WebGl accelerated learning frameworks (deeplearn.js), declarative interactive visualisation (vega-lite.js), have made it easy to start playing with Deep Learning in the browser.

This hack session is designed to learn how to do deep learning in the browser. We will focus on exploring three particular use cases where deep learning models can be used for inference, training and explanation in the browser directly. 

1. **Introduction** (10 mins): We will start with a quick introduction to javascript libraries including [tensorflow.js](https://js.tensorflow.com) for the session. We will introduce and use a browser based interactive notebook - [observablehq.com](https://observablehq.com) to 

2. **Model Inference** (10 mins): Inference is the most common use case and the browser allows you to 'bring your DL model to the data'. It also allows you test how the model works, when executed on the edge. We start with a simple application to load a pretrained model for image classification and running on the browser. We will understand some browser specific optimization - like weight quantization needed to manage models on the client side. 

3. **Rapid Prototyping** (15 mins): Training of DL models is now possible in the browser itself, if done smartly. We will build a *rapid prototyping image classification* example which allows the user to play with transfer learning to build a model specific for a user-generated image input. We will understand some nuances on data loading, preferred layers and memory management required for browser training.

4. **Explorable Explanations** (15 mins): Explaining the DL model and allowing the users to build intuition on the model helps in generating insight. We will build an *explorable explanation for our image model*, which allows the user to explore the feature space and threhold boundaries using interactive visualisations to understand what the model has learnt.

5. **Conclusion & Way Forward** (10 mins): We will end the session with how we see the ecosystems of tools for DL in the browser emerging and making it easy for everyone to start doing this.

To follow along the hack session - you would need a desktop with a modern browser (e.g. Chrome, Firefox) and a Github id to save your work on notebook.
