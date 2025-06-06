# Software Design Document (SDD)

Project Title: <br/>
Version: <br/>
Date: 5/19/2025 <br/>
Author(s): Emmanuel Tannor <br/>

## 1. Introduction

### 1.1 Purpose

This document exists to record progress made on my project for Arch. It should be viewed by those looking for insight into why I made certain decisions or how I did certain things.

### 1.2 Scope

The project itself will be a linear regression model for stock market prediction, specifically Google's (GOOGL) stock prices, trained and evaluated based off of a data set containing Google stock prices from 2004 to today.

### 1.3 Definitions, Acronyms, and Abbreviations

List and define any terms, acronyms, or abbreviations used in this document.

### 1.4 References
[IBM - What is Linear Regression?](https://www.ibm.com/think/topics/linear-regression)<br/>
[Kaggle API Documentation](https://www.kaggle.com/docs/api)<br/>
[Scikit-learn User Guide (Linear Models)](https://scikit-learn.org/stable/modules/linear_model.html)<br/>
### 1.5 Overview

The rest of this document will explain the architechural design of my Google Sock Price Predictive Model. The __System Overview__ will outline the components that make up the system and how they interact with one another. __Design Considerations__ will go over assumptions, constraints, dependencies, goals and guidelines that influenced the design of the model. __Architecture Design__ will include helpful diagrams with descriptions to visualize every part of the system's processes. __Detailed Design__ will then  go into more detail when it comes to each component making up the larger system. Following that, the document will address __Data Design__, __Interface Design__, __Security Considerations__, __Performance Considerations__, __Testing and Validation__ will be covered for completeness. Following that will be __Appendices__ containing additional information.

## 2. System Overview

The system should consist of 6 different components.

#### 1. Data import
The data will be imported from kaggle using their Kaggle API, then downloaded locally as a CSV file, and enabling the model to interact with the data. This will enable my system to be updated with the latest information.
#### 2. 

## 3. Design Considerations

### 3.1 Assumptions and Dependencies

List any assumptions and external dependencies (hardware, third-party libraries, etc.).

### 3.2 Constraints

Identify design constraints (e.g., language, platform, performance, security).

### 3.3 Goals and Guidelines

Define specific goals or design guidelines (e.g., maintainability, scalability).

## 4. Architecture Design

### 4.1 Overview

Architectural diagram and description of system modules/components.

### 4.2 Component Diagram(s)

Show and describe major components and their relationships.

### 4.3 Data Flow Diagrams

Explain how data moves through the system.

## 5. Detailed Design

### 5.1 Module/Component 1
	•	Purpose
	•	Inputs/Outputs
	•	Interfaces
	•	Dependencies
	•	Pseudocode or Logic Description

### 5.2 Module/Component 2

(Repeat as necessary for each module)

## 6. Data Design

### 6.1 Data Model

ER diagrams, schemas, or data flow between components.

### 6.2 Data Storage

Description of how and where data will be stored.

## 7. Interface Design

### 7.1 User Interface (if applicable)

Wireframes, mockups, and behavior description.

### 7.2 API Interfaces

List of APIs (endpoints, methods, parameters, responses).

## 8. Security Considerations

Explain how data and access will be secured.

## 9. Performance Considerations

Discuss expected performance and optimization strategies.

## 10. Testing and Validation

### 10.1 Unit Testing Strategy

Approach to test individual components.

### 10.2 Integration Testing Strategy

Approach to test component interactions.

### 10.3 System Testing Strategy

In order to test the system as a whole, I will use a smaller

## 11. Appendices

Any additional material, diagrams, or information.
