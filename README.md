# Customer Product Reviews Analysis and Sentiment Classification using AutoML

## Introduction

This project aims to process, analyze, and classify customer product reviews using various AWS services. Our main objective is to transform raw review data, visualize its contents, detect biases in the dataset, and train sentiment classifiers. We employ AWS Glue, Amazon Athena, AWS Data Wrangler, Amazon SageMaker Clarify, Amazon SageMaker Autopilot, and the SageMaker BlazingText built-in algorithm.

## Table of Contents

1. **Data Bias Analysis using Amazon SageMaker Clarify**
    * Analyze the dataset
    * Analyze class imbalance on the dataset
    * Balance the dataset
    * Analyze bias on balanced dataset

2. **Sentiment Analysis Model Training with Amazon SageMaker Autopilot**
    * Review transformed dataset
    * Configure and launch the Autopilot job
    * Track Autopilot job progress
    * Feature engineering
    * Model training and tuning
    * Deploy and test best candidate model

3. **Sentiment Analysis using Amazon SageMaker BlazingText**
    * Prepare dataset
    * Train the model
    * Deploy the model
    * Test the model

## Assumptions

1. **Dataset**: 
   * Customer feedback dataset exists in CSV format.
   * The feedback messages have a label representing positive, neutral, or negative sentiment.

2. **Environment**: 
   * AWS SageMaker instance is set up and active.
   * Necessary permissions for SageMaker to run jobs, access S3, and other related services are available.

3. **Tools & Libraries**:
   * Python SDK for AWS is set up.
   * Pandas and other required libraries are available.


## Key Features:

### 1. Bias Detection using Amazon SageMaker Clarify
* Dataset transformed into a pandas dataframe.
* Analyses for dataset imbalances using Clarify.
* Bias report generation and examination.
* Dataset balancing procedures.

### 2. Sentiment Classification using Amazon SageMaker Autopilot
* A walkthrough of Autopilot job configuration, launching, and tracking.
* Feature engineering and model training steps with visualization.
* Deployment and testing of the best candidate model.
  
### 3. Sentiment Classification using SageMaker BlazingText
* Dataset preparation and transformation suitable for BlazingText.
* Training the sentiment classifier model.
* Deployment of the trained model.
* Testing the deployed model for sentiment predictions.

## Conclusion

This project offers a comprehensive approach to understanding biases in customer feedback data and predicting sentiments from the feedback. By leveraging AWS SageMaker's suite of tools, we can efficiently analyze, train, deploy, and test models for real-world applications.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

* Amazon SageMaker Clarify documentation
* Amazon SageMaker Autopilot documentation
* Amazon SageMaker BlazingText documentation
