# Practical - 4

## Aim
Calculate cost and effort estimation for the given project definition using Function Point (FP) calculation (Simple, Average, and Complex) and the COCOMO model. Consider Object-Oriented Programming as the language.

## Tools Used
- FP Calculator by Tiny Tools

## Theory

### 1. Function Point (FP) Calculation
Function Point Analysis (FPA) is a standardized method to measure the functional size of software. It estimates the size of the software project based on user functionalities and is independent of the programming language used. 

FP calculation involves identifying and categorizing user functions into five components:
- **External Inputs (EI)**
- **External Outputs (EO)**
- **External Inquiries (EQ)**
- **Internal Logical Files (ILF)**
- **External Interface Files (EIF)**

Each component is weighted as **Simple**, **Average**, or **Complex**, depending on its characteristics. The total function points (FP) are calculated by summing up the weighted function points for each category.

### 2. COCOMO Model
The Constructive Cost Model (COCOMO) is a predictive model that estimates the cost, effort, and schedule for a software project. It uses the size of the project (often in lines of code or FP) as a primary input and provides estimates based on the type of project:

- **Basic COCOMO**: Provides rough estimates based on the project's size.
- **Intermediate COCOMO**: Adds more factors like product, hardware, and personnel attributes to improve the estimate.
- **Detailed COCOMO**: Includes additional factors such as the project's life cycle and cost drivers for more precise estimates.

For object-oriented programming projects, these models help in planning resources, budgeting, and scheduling by providing a systematic approach to estimate the effort and cost required.

## Practical

### FP Calculation Case 1: Simple

- **Description**: [Provide the description for the simple case]

### FP Calculation Case 2: Average

- **Description**: [Provide the description for the average case]

### FP Calculation Case 3: Complex

- **Description**: [Provide the description for the complex case]

## Questions & Answers

- **Does the system need to support different user roles with varying permissions?**
  - **Answer**: Yes, the system requires handling multiple roles, such as Users and Admins, with distinct access levels and permissions. This adds complexity in managing role-based access control.

- **Is real-time data synchronization between system components necessary?**
  - **Answer**: Yes, the system requires real-time updates, such as when a payment is made or when user details are updated. This ensures that all modules reflect the latest data instantly, increasing system complexity.
