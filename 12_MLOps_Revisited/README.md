# MLOps Revisited — By Nitish Sir

This section covers MLOps fundamentals, MLOps tool stacks, DevOps, CI/CD, ML pipelines, data versioning, experiment tracking, MLflow, model deployment, Docker, AWS infrastructure, monitoring, and model retraining.

## 1. Introduction to MLOps

### Session 1: Introduction to MLOps

- What Is MLOps?
- **Problems in Old Methods of ML Projects**
  - Cricket Score Forecast Project Explanation
  - The Data Problem
  - The Code Problem
  - The Versioning Problem
  - Automation
  - The Experimentation Problem
  - The Deployment Problem
  - The Drift Problem
  - The Infrastructure Problem
  - The Collaboration Problem
  - The Legal Problem
- Aspects of MLOps

## 2. MLOps Tools Stack

### Session 2: MLOps Tools Stack

- Plan and Recap of Core Aspects
- Benefits of MLOps
- Challenges in MLOps
- Prerequisites of MLOps
- **MLOps Tool Stack**
  - End-to-End MLOps Platforms
    - AWS SageMaker
    - Azure ML
  - Data Management Tools
    - Data Ingestion — Kafka
    - Data Transformation — Apache Spark
    - Data Storage

### Session 3: MLOps Tools Stack — Part 2

- Continuing with Data Management Tools
  - Data Pipeline Integration — Airflow
  - Data Validation
  - Data Versioning — DVC
  - Data Annotation
- Data Observability
- Data Security
- Data Governance
- Metadata Store
- Feature Store

### Session 4: MLOps Tools Stack — Part 3

- Recap
- Code Management
- Model Building
- AutoML
- Hyperparameter Tuning
- Model Explainability
- Experiment Tracking
- Model Registry

## 3. DevOps Fundamentals

### Session 5: DevOps Fundamentals

- Revisiting MLOps
- What Are Virtual Machines?
- Containerization
- Deploying a Container
- Container Orchestration

### Session 6: DevOps — Continued

- Recap
- Monolithic Architecture
- Microservices
- Kubernetes
- Container Orchestration Services

## 4. CI/CD and Cloud Infrastructure

### Session 7: MLOps Tool Stack — CI/CD

- **Continuous Integration — GitHub Actions**
  - Steps Executed During the CI Workflow
  - YAML File Explanation
- **Continuous Deployment**
  - Continuous Deployment Workflow
  - Sample Workflow — YAML
- Continuous Deployment vs. Continuous Delivery
- Model Serving

### Session 8: MLOps Tool Stack — Cloud Infrastructure

- **Cloud Platforms**
  - AWS vs. GCP vs. Azure
- **Provisioning**
  - Provision Resources
    - Example Terraform Script
  - Configure Environments
    - Example Bash Script
  - Deploy Services
  - Set Up Networking
  - Implement Security Measures
- **Load Balancers**
  - What, Why, and How
  - Load Balancing Algorithms
- Auto Scaling

## 5. ML Pipelines Using DVC

### Session 9: ML Pipelines Using DVC

- Building an ML Pipeline — Tweet Emotion Project
- Working of DVC — `dvc.yaml` File
- Building a Pipeline from Scratch
  - Data Ingestion
  - Data Preprocessing
  - Feature Engineering
  - Model Building
  - Model Evaluation

### Session 10: Improving ML Pipelines

- Creating `params.yaml`
- Improving Pipelines Using:
  - Functions
  - Type Hinting
  - Exception Handling
  - Logging

## 6. Version Control and Data Versioning

### Session 11: Version Control

- Steps for Starting an ML Project with MLOps
- Code Versioning — Git
- Data Versioning
  - Why Data Versioning?
  - Why Not Use Git for Data Versioning?

### Session 12: Data Versioning Using DVC

- DVC Working
- Step-by-Step Process for Data Versioning
  - Data Ingestion Project — eCommerce

### Session 13: Pipeline × Data Versioning × AWS S3

- **DVC Pipeline and Data Versioning**
  - Emotion Detection Project — Continued
  - `dvc repro`
- **DVC with AWS S3 Storage**
  - Step-by-Step Setup

## 7. Experiment Tracking

### Session 14 (Part 1): Experiment Tracking Using DVC — Without Pipeline

- Journey Till Now
- Need for Experiment Tracking
- What Is Experiment Tracking?
  - Benefits
  - Tools for Experiment Tracking
- DVC Experiment Tracking Demo Without Pipeline

### Session 14 (Part 2): Experiment Tracking Using DVC — With Pipeline

- DVC Experiment Tracking Demo with Pipeline
  - Step-by-Step Process
- `dvc repro` vs. `dvc exp run`

### Session 15: Introduction to MLflow

- Recap
- Limitations of DVC
- **MLflow**
  - Introduction to MLflow
  - MLflow Demo
  - What Can MLflow Track?
  - MLflow Tracking Server

### Session 16 (Part 1): MLflow Remote Tracking Using DagsHub

- Recap
- Plan of Attack for the MLflow Remote Tracking Server
- **DagsHub**
  - Introduction
  - Demo

### Session 16 (Part 2): MLflow Remote Tracking Using AWS

- **AWS Setup for MLflow**
  - Create IAM User
  - Create S3 Bucket
  - Create EC2 Instance
- Steps to Start the MLflow Server
- Working Demo of MLflow on AWS

### Session 17 (Part 1): Autologging in MLflow

- TBD

### Session 17 (Part 2): Hyperparameter Tuning in MLflow

- TBD

## 8. Model Registry, Mini Project, and Model Serving

### Session 18: Model Registry

- TBD

### Session 19: Mini Project

- TBD

### Session 20: Model Serving

- TBD

## 9. Continuous Integration and Deployment

### Session 21: Fundamentals of CI

- TBD

### Session 22: CI in MLOps

- TBD

### Session 23: CI in MLOps — Continued

- TBD

## 10. Docker and Deployment

### Session 24 (Part 1): Docker Fundamentals — Theory

- Docker Fundamentals — Theory

### Session 24 (Part 2): Docker Fundamentals — Practical

- Docker Fundamentals — Practical

### Session 25: Docker in MLOps

- Docker in MLOps

### Session 26: Deployment on AWS EC2

- Deployment on AWS EC2

### Session 27: Deployment on AWS EC2 × AWS ECR

- Deployment on AWS EC2 × AWS ECR

### Session 28 (Part 1): Multi-Container Deployment on EC2

- Multi-Container Deployment on EC2

### Session 28 (Part 2): AWS EC2 × Load Balancer × Auto Scaling

- AWS EC2
- Load Balancer
- Auto Scaling

## 11. Deployment Strategies

### Session 29 (Part 1): Updating Deployment

- Updating Deployment

### Session 29 (Part 2): Deployment Using AWS CodeDeploy

- Deployment Using AWS CodeDeploy

### Session 30 (Part 1): Deployment Strategies — Rolling Deployment

- Rolling Deployment

### Session 30 (Part 2): Deployment Strategies — Blue-Green Deployment

- Blue-Green Deployment

### Session 31: CI/CD with AWS CodeDeploy

- CI/CD with AWS CodeDeploy

## 12. Monitoring and Observability

### Prometheus

- Prometheus — Part 1
- Prometheus — Part 2
- Prometheus — Part 3

### Grafana

- Grafana

### Model Monitoring

- Monitoring ML Models Locally
- Monitoring on AWS
- Monitoring on ASG
- Concepts of Alerting in Prometheus
- Alerting on AWS — Complete

## 13. Model Retraining

- Model Retraining Concepts
- Model Retraining Implementation

## 14. Additional Sessions

- MLOps Doubt Clearance Session

---

## Learning Objectives

- MLOps fundamentals and the challenges of traditional ML workflows.
- MLOps tools for data management, model building, tracking, and deployment.
- DevOps concepts, Docker, Kubernetes, and container orchestration.
- CI/CD workflows using GitHub Actions and AWS CodeDeploy.
- ML pipelines, code versioning, and data versioning using Git and DVC.
- Experiment tracking and model management using MLflow and DagsHub.
- Cloud infrastructure, AWS EC2, ECR, S3, load balancing, and auto scaling.
- Deployment strategies, including rolling and blue-green deployments.
- Monitoring and alerting with Prometheus and Grafana.
- Model retraining concepts and implementation.
