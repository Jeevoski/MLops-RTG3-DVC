# Week 3: Data Version Control (DVC)

## Overview

This week focused on understanding Data Version Control (DVC), a tool designed to manage datasets, machine learning models, and experiment tracking alongside Git. Since traditional Git is not optimized for handling large datasets and model files, DVC extends version control capabilities to machine learning workflows, enabling reproducibility, collaboration, and efficient data management.

## Topics Covered

### 1. Introduction to DVC

* What is DVC?
* Why DVC is important in MLOps
* Limitations of Git for large datasets
* Benefits of versioning data and models

### 2. DVC Setup and Initialization

* Installing DVC
* Initializing DVC in a Git repository
* Understanding the `.dvc` directory and configuration files
* Integrating DVC with existing Git workflows

### 3. Data Versioning

* Tracking datasets using DVC
* Creating `.dvc` files
* Adding data to version control
* Understanding data hashes and metadata tracking

### 4. Remote Storage

* Configuring remote storage
* Concepts of local and remote data repositories
* Pushing tracked data to remote storage
* Pulling datasets from remote storage

### 5. DVC and Git Integration

* Tracking code with Git
* Tracking data with DVC
* Synchronizing Git commits and DVC versions
* Maintaining reproducible machine learning pipelines

### 6. Data Management Workflow

* Adding new datasets
* Updating existing datasets
* Restoring previous dataset versions
* Sharing datasets across team members

## Key Commands Practiced

```bash
dvc init
dvc add data/sample_data.csv
git add .
git commit -m "Track dataset with DVC"

dvc remote add -d storage <remote-url>
dvc push
dvc pull
dvc status
```

## Key Outcomes

By the end of Week 3, I was able to:

* Understand the role of DVC in MLOps workflows.
* Initialize and configure DVC within a Git repository.
* Track datasets separately from source code.
* Manage dataset versions efficiently.
* Connect DVC to remote storage systems.
* Push and retrieve data using DVC commands.
* Maintain reproducible machine learning workflows.
* Understand how Git and DVC work together to manage code and data.

## Reflection

Learning DVC provided valuable insight into one of the core challenges of machine learning engineering: managing datasets and model artifacts effectively. By combining Git for code versioning and DVC for data versioning, it becomes possible to build reproducible, collaborative, and scalable ML projects. This week established an important foundation for advanced MLOps concepts such as experiment tracking, pipeline automation, and model management.
