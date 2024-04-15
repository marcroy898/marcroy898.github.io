---
permalink: /resume/
title: "Resume"
---

## Education
#### University of Colorado Boulder 
Boulder, Colorado 

GPA: 3.96

Relevant Coursework: Programming and Data Structures, Algorithms, Computer Systems, Linear Algebra,
Data Mining, Numerical Computation, Data Science, Database Systems, Intro to AI, Machine Learning,
Object Oriented Analysis and Design, Calculus 3, Physics 2, Intro to Robotics


## Experience
#### Machine Learning Engineer Intern
May 2023 - Present

Viasat

* Building full-stack machine learning app for determining if a supplier issue is systemic in a historical record of text
based documents that track supplier problems. Accomplished this by implementing an open source embedding
model for Dense Passage Retrieval to determine if similar documents/issues have been seen before and how often
that problem has occurred.
* Deployment stack includes a Vue.js frontend, Weaviate vector database backend, an embedding model hosted on
AWS Sagemaker & tied into Weaviate, an Argo ETL refresh process to ingest new documents as they are written,
and a FastAPI proxy in between Vue and Weaviate. Built app infrastructure using Helm/Kubernetes/Docker

#### Data Science Intern
May 2022 - November 2022

Lockheed Martin

* Queried, cleaned, and transformed 450 million time series IIOT data points.
* Engineered and tested features by feeding them into various models (PCA, Random Forest, LSTM) and identifying
anomalies for predictive maintenance.
* Recreated several Python scripts in Tableau using SQL to reach end users easier.
* Created a KPI for Industrial CNC machine productivity and progress using IIOT data and Grafana. Deployed on
factory floor for machine operators to monitor progress.
* Processed large corpora of text investment data using spaCy for determining investment and ROI in specifiic
categories. (Lbl2Vec, Topic Modeling)

#### Reinforcement Learning Research Assistant
June 2021 – September 2021

University of Colorado Boulder

* Built birds eye view car simulation using Python. Car was approximated using a simple kinematic bicycle model
and collision detection and reference lanes were built with pygame.

* Integrated the simulation with a Deep Q-learning neural network with custom environment and reward system for
the purpose of navigating paths. Tested different observation and action spaces as well as different network sizes
and hyperparameters
