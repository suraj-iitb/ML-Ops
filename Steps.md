## Steps of ML Process

1. Data Extraction: Selection and integration the relevant data from various data sources
2. Data Analysis: Perform exploratory data analysis (EDA) to understand the available data. This process leads to the following:
    - Identifying the data preparation that are needed for the model
3. Data Preparation: The data is prepared for the ML task. This preparation involves:
    - Data Splitting: Split the data into training, validation, and test sets
    - Data Transformations
    - Feature Engineering
     
   **Output**: The data splits in the prepared format
4. Model Training:
    - Implements different algorithms/models/architectures with prepared data
    - Hyperparameter tuning for a particular algorithm
   
   **Output** The trained model
5. Model Evaluation: The model is evaluated on a holdout test set to evaluate the model quality

   **Output**: Set of metrics to assess the quality of the model
6. Model Validation: The model is confirmed to be adequate for deployment (its predictive performance is better than a certain baseline)
7. Model Serving: The validated model is deployed to a target environment to serve predictions. This deployment can be one of the following:
    - Microservices with a REST API to serve online predictions
    - An embedded model to an edge or mobile device
    - Part of a batch prediction system
8. Model Monitoring: The model predictive performance is monitored to potentially invoke a new iteration in the ML process

**Note**: These steps can be completed manually or by an automatic pipeline
