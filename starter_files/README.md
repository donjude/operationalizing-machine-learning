*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Operationalizing Machine Learning

*TODO:* Write an overview to your project.
This project is part of the Udacity Azure ML Engineer Nanodegree. It is the second project after the first project [Optimizing a Pipeline in Azure](https://github.com/donjude/nd00333_AZMLND_Optimizing_a_Pipeline_in_Azure-Solution), to build an Azure Auto ML model and productionalize the model.

The main focus of the project is about Productionalizing a Machine Learning Model, so we would not be focusing on optimization or creating a perfect machine learning model, but rather show the processes and the steps in which machine learning models in Azure are productionalized.

This project focuses on two parts using the bankmarketing dataset as described in [Project One](https://github.com/donjude/nd00333_AZMLND_Optimizing_a_Pipeline_in_Azure-Solution)

## Architectural Diagram
*TODO*: Provide an architectual diagram of the project and give an introduction of each step. An architectural diagram is an image that helps visualize the flow of operations from start to finish. In this case, it has to be related to the completed project, with its various stages that are critical to the overall flow. For example, one stage for managing models could be "using Automated ML to determine the best model". 

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps.
Below are the various descriptions of the Key steps that were followed for the model productionalization.

1. **Authentication:** It is the process of verfifying the identify of a user or a process. In this project the authentication process that is used to authenticate the Azure Machine Learning workspace is the **Service Principal** authentication workflow. The service principal was used because of the automated process that is required for authentication during modeling training, updates and deployment processes that wouldn't require user interaction.

    > **Service Principal:** is a security identity used by user-created applications, services and automation tools to access specific Azure resources.

    **Authentication and Services principal configuration image**
![Service principal creation confirmation](images/service_p1.png)
![](images/service_p2.png)
![](images/service_p3.png)
![](images/service_p4.png)
![](images/service_p5.png)


2. **Automated ML Experiment:** At this step the machine learning experiment is created using Automated ML. This experiment consist of setting up your workspace, setting up your auto ml configurations, configuring a compute cluster and using the compute cluster to run the experiment. Several machine learning models are produced by this step in addition to the best model.

    **Registered Dataset**
    ![Registered Dataset](images/dataset1.png)
    ![Registered Dataset](images/dataset2.png)


    **Completed Experiment**
    ![Completed experiment](images/experiment1.png)

    **Best Model**
    ![Best model](images/best_model1.png)
    ![Best model](images/best_model2.png)


3. **Deploy the best model:** 
Enable logging
Swagger Documentation
Consume model endpoints
Create and publish a pipeline
Documentation

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
