#  Building Machine Capbailities

Building and scaling machine learning capability is an imperative for enterprises and startups aiming to adopt a data-driven lens for their business. However, crafting a successful data-science strategy is not straightforward and requires answering the following questions:

- **Strategy & Tactics**: What part of the business should I target first for adoption? Should I take a jump-start approach or a bootstrap approach?
- **Process & Systems**: How should I set up an initial process for machinie learning? How to I integrate data-driven processes with existing business systems?
- **Structure & Roles**: Should I adopt a functional or a business-focussed ML structure? What specialised roles should I be hiring for: Data engineering, ML expert, Visualisation expert, and /or Data Analyst?
- **Tools & Stack**: Should I build a vertical or horizontal machine learning stack? How do I integrate machine learning models with existing applications and data? 
- **Engineering & Technical**: What are the pitfalls to watch out for? How to avoid pre-mature over-engineering of ML systems? How to manage the ongoing technical debt for ML?
- **Skills & Competencies**: How do I up-skill and build differentiated ML competency across the organisation?



The following are the key topics to be covered for buiding **Process & Systems** capabilities for Machine Learning



### Scope & Frame

- Assess user needs and business impact

  - Intersection of workflows and ML/DL possibilities
  - Assess automation Vs augmentation
  - Define success(es) for the user and business
  - Size the impact to business: cost, service, quality, experience

- Translate user and business needs to ML/DL problem
  - Define ML/DL objective metrics

    - Success, Errors & Failures
    - Feedback & Control
    - Explainabiliity & Trust

  - Define data requirements and sources

    

### Discover Data & Features

- Assess, source and collect data for:
  - Relevance & predictive power
  - Fairness, Privacy and Security

- Schemas and data formats
- Dynamic Vs Static Features
- Create features 
  - Functional: Refine, Transform, Explore
  - Weak Supervision: Business heuristics
  - Manual: Rating and Labeling

- Build feature store

  - Access schema : API, Search
  - Visual Exploration Interface

  

### Build Models

- Model Scope

  - Heuristics
  - Simple, standard, shallow ML models
  - Deep Learning

- Train/Test/Evaluate data

  - Subsample
  - Identify bias

- Model Training and Tuning

  - Hyper parameter optimization
  - Cross-validation

- Model Evaluation and Visualization

  - Metrics and Sensitivity
  - What-if and Scenario testing
  - Model Visualization
  - Explainability

  

### Deploy Experiments

- Designing Experiments
  - Experiment scope
  - Defiining success, effect size, measurement
  - Reproducability and cloning experiments
  - Notebooks vs Code Editors

- Deploying and Measuring Experiments

  - Puttinig experiment on production

  - Measuring and A/B testing

    

###Deploy Continuous

- Feature Store Updates

  - Updating feature stores
  - Dynamic Vs Static Features
  - Cacheing Vs Invalidation

- Model Serving

  - Designing and Documenting APIs
  - Model Serving Service and Endpoints
  - Scaling to meet usage

  

- Live online inference

- Model Serving

  - Model refresh and eventual consistency
  - Identifying training and prediction skew
  - Synchronous (live) Vs Asynchronous (batch) Inference
  - Canary and Staging Environments

  

### Montor & Manage 

- Model Management
  - Versioning and Metadata
  - Colloboration and Integration

- Performance Monitoring & Logging
  - Request rate & latencies
  - Failures and problem detection
  - Logging requests and predictions
  - Effectiveness metrics e.g. accuracy, drift
- Model Drift, Bias and Retraining
  - Model retraining - how and how often?
  - Daily vs Live/online training
  - Feedback loops
- Upgrading Features and Models
  - New models, features and experiments
  - A/B Testing experiments
  - Feature and Model expansions





