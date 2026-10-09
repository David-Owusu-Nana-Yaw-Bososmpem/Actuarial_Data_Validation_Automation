# Actuarial Data Validation & Reporting Automation

## Overview

This project is an Excel VBA-based data validation and reporting tool designed to automate the review of actuarial and financial data.

The workbook organizes quarterly data, performs automated calculations, maps primary and granular data points, and applies reasonability checks to identify values requiring further review.

## Project Objectives

The project was developed to:

- Automate actuarial data validation and reporting
- Compare current and prior quarterly values
- Perform automated reasonability checks
- Identify potentially unusual financial results
- Map actuarial data into standardized reporting structures
- Reduce repetitive manual validation procedures
- Improve consistency in quarterly data review

## Data Validation Workflow

The workbook processes quarterly financial and actuarial information across multiple valuation periods.

The validation workflow incorporates:

1. Source data organization
2. Current and prior period identification
3. Primary data-point calculations
4. Granular data-point calculations
5. Continuity-group mapping
6. Reasonability checks
7. Automated flags and review notes

## Financial Data

The workbook evaluates several financial components, including:

### Expenses

- Advertising
- Development
- Interest
- Maintenance and repairs
- Office supplies
- Property and insurance
- Taxes
- Wages
- Other expenses
- Expected claims
- Compensation

### Revenue

- Premiums
- Commission
- Investment earnings
- Other revenue

### Financial Results

The model also evaluates:

- Total expenses
- Total revenue
- Net income

## Current vs. Prior Period Analysis

The workbook distinguishes between **current** and **prior** valuation periods.

Dynamic formulas retrieve the appropriate quarterly values and support comparisons across reporting periods.

This structure allows the validation process to adapt as the selected valuation quarter changes.

## Reasonability Checks

Automated reasonability checks evaluate key financial results and generate review messages.

The checks cover:

- Total Expenses
- Total Revenue
- Net Income

Results falling within established expectations are identified as reasonable, while unusual results are flagged for further investigation.

## Primary and Granular Data Points

The workbook maps financial data at two levels.

### Primary Data Points

Primary calculations include:

- Beginning total expenses
- Ending total expenses
- Change in expenses
- Beginning total revenue
- Ending total revenue
- Prior-period net income
- Current-period net income

### Granular Data Points

Granular calculations provide additional detail for individual expense and revenue components, including premiums, commissions, investment earnings, wages, taxes, and other financial items.

## Workbook Structure

The workbook contains the following worksheets:

- `Continuity Group`
- `Continuity Group for Primary`
- `Continuity Group for Granular`
- `Primary Values`
- `Granular Values`
- `Actuarial Data`
- `Checks & Inferences`
- `Provided Data`
- `Primary Data Point Formulas`
- `Granular Data Point Formulas`

Together, these worksheets support data mapping, calculations, validation, and reporting.

## Excel & VBA Functionality

The project uses Excel and VBA functionality to support:

- Automated data processing
- Current/prior period comparisons
- Conditional validation
- Reasonability checks
- Data-point mapping
- Dynamic quarterly calculations
- Financial reporting workflows
- Automated review messages

Excel formulas such as conditional logic and aggregation functions are also used to retrieve and validate the appropriate financial values.

## Repository Structure

```text
Actuarial-Data-Validation-Automation/
│
├── Actuarial_Data_Validation_Automation.xlsm
└── README.md
```

## Skills Demonstrated

- Actuarial data validation
- Excel VBA automation
- Financial data analysis
- Data quality assurance
- Reasonability testing
- Current and prior period analysis
- Actuarial reporting
- Microsoft Excel
- Financial reporting automation
- Data mapping and reconciliation

## Author

**David Nana Yaw Owusu Bosompem**

BSc Actuarial Science  
SOA Exam P & FM

**Interests:** Actuarial Science | Insurance Analytics | Predictive Modeling | Statistics
