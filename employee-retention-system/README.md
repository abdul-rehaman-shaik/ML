# Employee Retention System

This project focuses on building a machine learning model to predict employee retention/attrition.

## Repository Information

**Current Location**: This project is currently part of the [abdul-rehaman-shaik/ML](https://github.com/abdul-rehaman-shaik/ML) repository in the `employee-retention-system/` subdirectory.

**Project Path**: [https://github.com/abdul-rehaman-shaik/ML/tree/main/employee-retention-system](https://github.com/abdul-rehaman-shaik/ML/tree/main/employee-retention-system)

## Files

- `employee_retention_model.ipynb`: Main Jupyter notebook containing the employee retention analysis and model training using stacking classifier.

## Overview

The notebook implements a stacking ensemble model to predict employee retention based on various employee attributes such as:
- Employee Number
- Job Role
- Department
- And other relevant features

The trained model is saved as 'stacking_clf.pkl' for deployment and prediction purposes.

## Creating a Standalone Repository

If you want to move this project to a separate repository named `employee-retention-system`, follow these steps:

### Option 1: Manual Copy
1. Create a new repository on GitHub: [employee-retention-system](https://github.com/new?name=employee-retention-system&owner=abdul-rehaman-shaik)
2. Clone the new repository locally
3. Copy the contents of this directory to the new repository
4. Commit and push

### Option 2: Using Git Subtree
```bash
# From the ML repository root
git subtree split -P employee-retention-system -b employee-retention-system-branch

# Create and push to new repository
git push https://github.com/abdul-rehaman-shaik/employee-retention-system.git employee-retention-system-branch:main
```

Once moved, the project will be available at: [https://github.com/abdul-rehaman-shaik/employee-retention-system](https://github.com/abdul-rehaman-shaik/employee-retention-system)
