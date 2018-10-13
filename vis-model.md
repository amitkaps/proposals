# Visualizing Machine Learning Models

## Overview  

Even though data visualisation (data-vis) is an integral part of the data science pipeline and helps us understand the portrait of the data, we rarely leverage the power of visualisation for understanding machine learning (ML) models better. Even though data visualisation is an integral part of the data science pipeline and helps us understand the portrait of the data, we rarely leverage the power of visualisation for understanding machine learning models better.  In this talk, the speakers discuss how to visualize ML models to help data scientists and their stakeholders understand the model better and take appropriate decisions.


## Abstract

Model evaluation is still largely restricted through numerical summaries. Visualising Machine Learning Models(model-vis) can help us better understand - the shape of the model, the impact of parameter on the model, the impact of different input data on the model, the fit of the model and where it can be improved.

This talks will build up the grammar of model-vis for ML using real-life datasets with regression and classification problems. It would illustrate the key concepts in model-vis around the following blocks:- 

[0] Visualise the data space   
[1] Visualise the predictions in the data space  
[2] Visualise the errors in model fitting  
[3] Visualise the features in the model  
[4] Visualise with different model parameters   
[5] Visualise with different input datasets   
[6] Visualise the entire model space   
[7] Visualise the many models together   

It will also highlight the n/p/N challenges in conducting model-vis: large observations (n), high dimensionality (p) and model explosion (N)


## Outline

We will be covering four examples of machine learning model visualisation during the workshop. It will highlight the n/p/N challenges in conducting model-vis: large observations (n), high dimensionality (p) and model explosion (N).

1. **Introduction to Model Visualisation (ModelVis)** (15 mins, Conceptual 100%)
	- Role of Visualisation in Machine Learning (ML)
	- Tidy Data :: Data Vis and Tidy Model :: Model Vis
	- Static vs. Interactive Visualisation for ML Modelling 
	
2. **ML ModelVis: Simple Model** (45 mins, Theory 20%, Practice 80%)
	- The Seven Steps of ML ModelVis  
			[0] Visualise the data space 
			[1] Visualise the predictions in the data space 
			[2] Visualise the errors in model fitting 
			[3] Visualise the features in the model 
			[4] Visualise with different model parameters 
			[5] Visualise with different input datasets 
			[6] Visualise the entire model space 
			[7] Visualise the many models together
  - Simple Classification Examples (n ~ 50,  p ~ 4) 
  - Exercise #1: Extending the Simple Classifications 
  
3. **ML ModelVis: Large Observations (n)** (45 mins, Theory 20%, Practice 80%)
	- **Bin - Sample - Smooth** approach for Handling Large Observations (n)
	- Generating decision boundaries for large data
	- Exercise #2: Classification example with n > 100,000

4. **ML ModelVis: High Dimensionality (p)** (30 mins, Practice)
	- The curse of dimensionality and challenges in scaling decision boundaries
	- Combining dimensionality reduction technique - PCA, KNN, and t-SNE for data and model visualisation together.
	- Exercise #3: Classification example with p > 20

5. **ML ModelVis: Model Explosion (N)** (30 mins, Theory 20%, Practice 80%)
	- Interactively exploring **data and model** space
	- Visualising performance of many models together: Uncovering strength and weaknesses of different models
	- Exercise #4: Classification example with N-models > 10

6. **Wrap-up and Conclusion** (15 mins, Theory 100%)

We will be using the following main libraries for conducting the workshop:
- **Vega & Vegalite / Altair** for interactive visualisation
- **plotnine & matplotlib** for static visualisation
- **Scikit-learn** for Machine Learning Models
- **Pandas** for data wrangling

We are also wrapping the common functions and developing the **ModelVis** package for Model Visualisation which should be available on PyPI for the workshop.


### Notes  
A version of this talks was presented at Strata Hadoop New York 2016. Slides can be found [here](https://www.slideshare.net/amitkaps/model-visualisation-66569635)
