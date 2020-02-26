# Getting Started with Amazon SageMaker Studio

This folder contains a [Jupyter notebook that demonstrates the main features of Amazon SageMaker Studio](xgboost_customer_churn_studio.ipynb). It's designed to be run from within Studio. It shows how to create a model to predict customer churn using the XGBoost algorithm.

## Features

* [Amazon SageMaker Experiments](https://docs.aws.amazon.com/sagemaker/latest/dg/experiments.html)
  * Manage multiple trials
  * Experiment with hyperparameters and charting
* [Amazon SageMaker Debugger](https://docs.aws.amazon.com/sagemaker/latest/dg/train-debugger.html)
  * Debug your model 
* [Model hosting](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-hosting.html)
  * Set up a persistent endpoint to get predictions from your model
* [SageMaker Model Monitor](https://docs.aws.amazon.com/sagemaker/latest/dg/model-monitor.html)
  * Monitor model quality 
  * Set alerts for when model quality deviates 

## Prerequisites

To use this notebook, you must have [onboarded with Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-studio-onboard.html) and be able to sign in to Studio.

## How to run this notebook

1. Sign in to [Amazon SageMaker Studio](https://us-east-2.console.aws.amazon.com/sagemaker/home?region=us-east-2#/studio/).

2. In Studio, open a terminal.

![open a terminal](./images/open_a_terminal.gif)

3. Clone this repository with the following command.

```bash
git clone https://github.com/awslabs/amazon-sagemaker-examples.git
```

![clone the repo](./images/clone_the_repo.gif)

4. Use the Studio file manager to find and open the notebook.

![find the notebook](./images/find_and_open_the_notebook.gif)

