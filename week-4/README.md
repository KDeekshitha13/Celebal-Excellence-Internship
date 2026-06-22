# Assignment 4: Azure Cloud Fundamentals and Data Pipeline Implementation using ADF

## Note
- All resources in this assignment were created in the **Central India** region as instructed.

## Overview
This assignment focuses on understanding Azure cloud fundamentals and building an end-to-end data pipeline using Azure Storage and Azure Data Factory (ADF).

## Task 1: Resource Group Creation
Created a Resource Group in Azure to organize all project-related resources in one place. This acts as a logical container for managing services used in the assignment. It also helps in easier monitoring, management, and deletion of related resources.

## Task 2: Storage Setup
Created an Azure Storage Account and blob containers for storing data. Uploaded the source CSV file into blob storage for pipeline processing. This storage acts as the source and destination location for data movement.

## Task 3: Azure Data Factory (ADF)
Created an Azure Data Factory instance and explored ADF Studio features such as **Author, Monitor, and Manage**. Configured a **Linked Service** to connect ADF with Azure Storage. This enabled communication between the pipeline and storage resources.

## Task 4: Pipeline Development
Created source and destination datasets and configured pipeline activities. Set up the workflow required for data movement. Proper dataset configuration ensured correct file access and processing.

## Task 5: Pipeline Execution
Used **Get Metadata** activity to validate file details and **Copy Data** activity to transfer data from source to destination. Executed the pipeline using **Debug/Trigger** and monitored successful completion. Pipeline monitoring helped verify activity status and execution results.

## Task 6: Assigning Roles
Explored Azure IAM (Identity and Access Management) and reviewed access roles such as **Owner** and **Reader**. Understood how role-based permissions help secure Azure resources. This provided insight into access control and security management in Azure.
