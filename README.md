# Abnormal Cholesterol in U.S. Young Adults: NHANES 2021–2023

## Project Overview

This project analyzes abnormal cholesterol among U.S. young adults aged 18–26 using data from the National Health and Nutrition Examination Survey (NHANES), August 2021–August 2023.

The current analysis focuses on Research Question 1: estimating the weighted prevalence of abnormal cholesterol overall and comparing prevalence by sex and weight status.

This project was developed as part of a data management and analysis plan for a public health data analysis project.

## Research Question

**RQ1. What is the prevalence of abnormal cholesterol among U.S. young adults aged 18–26 years, and how does it vary by sex and body weight status?**

## Data Source

Data were obtained from the public-use NHANES August 2021–August 2023 files.

The following NHANES files were used:

- `DEMO_L.xpt`: Demographic data
- `BMX_L.xpt`: Body measures
- `TCHOL_L.xpt`: Total cholesterol
- `HDL_L.xpt`: HDL cholesterol

NHANES is a cross-sectional survey conducted by the National Center for Health Statistics to monitor the health and nutritional status of the U.S. civilian noninstitutionalized population.

## Analytic Sample

The analytic sample was restricted to NHANES participants aged 18–26 years with available cholesterol measurements.

## Outcome Definition

Abnormal cholesterol was defined as having at least one of the following measures:

- **High total cholesterol:** total cholesterol ≥ 200 mg/dL
- **Low HDL-C:** HDL cholesterol < 40 mg/dL
- **High non-HDL-C:** non-HDL-C ≥ 145 mg/dL

Non-HDL-C was calculated as:

```text
Non-HDL-C = Total cholesterol - HDL cholesterol
