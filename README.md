# Data Analytics in Python

This repository contains various assignments and classwork related to data analytics using Python. The assignments involve reading, analyzing, and visualizing data using libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.

---

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Assignments](#assignments)
  - [Assignment 2](#assignment-2)
  - [Assignment 3](#assignment-3)
  - [Assignment 5](#assignment-5)
  - [Assignment 6](#assignment-6)
  - [Assignment 7](#assignment-7)
- [Classwork](#classwork)
  - [In Class Assignment 5](#in-class-assignment-5)
  - [Reading and Writing Data](#reading-and-writing-data)
- [License](#license)

---

## Installation

To run the notebooks, you need to have Python installed along with the required libraries. Install the necessary libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn

# Usage and Assignments Overview

## Usage
Clone the repository and navigate to the directory containing the Jupyter notebooks. Open and run the notebooks using [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io/).

---

## Assignments

### Assignment 2
This assignment involves temperature conversions between Fahrenheit, Celsius, and Kelvin.

- **Question 1:** Convert Fahrenheit to Celsius.
- **Question 2:** Convert Celsius to Kelvin.
- **Question 3:** Convert Fahrenheit to Kelvin using the previous functions.
- **Question 4:** Explanation of variable scope within functions.

### Assignment 3
This assignment focuses on Object-Oriented Programming (OOP) concepts.

- **Question 1:** Explanation of OOP vs Procedural Programming.
- **Question 2:** Advantages of OOP over Procedural Programming.
- **Question 3:** True/False questions about OOP.
- **Question 4:** Implementation of a `Numbers` class with methods for addition, multiplication, difference, and value retrieval.

### Assignment 5
This assignment involves working with the `surveys.csv` dataset.

- **Question 1:** Read the dataset into a DataFrame.
- **Question 2:** Determine the number of rows and columns.
- **Question 3:** Display the first 10 rows.
- **Question 4:** Display data types and count categorical and quantitative variables.
- **Question 5:** Print column names.
- **Question 6:** List all unique species.
- **Question 7:** Obtain descriptive statistics for numerical variables.
- **Question 8:** Group by `sex` and compute descriptive statistics.
- **Question 9:** Group by `species_id` and compute descriptive statistics.

### Assignment 6
This assignment involves analyzing a loans dataset.

- **Question 1:** Read the `loan.csv` dataset into a DataFrame.
- **Question 2:** Plot the distribution of homeownership.
- **Question 3:** Create a stacked bar plot of homeownership by grade.
- **Question 4:** Create a grouped bar plot of homeownership by grade.
- **Question 5:** Compare the appropriateness of the plots.
- **Question 6:** Plot the distribution of loan grade by homeownership.
- **Question 7:** Plot the distribution of loan grades.

### Assignment 7
This assignment involves further analysis of the loans dataset.

- **Question 1:** Read the `loans.csv` dataset into a DataFrame.
- **Question 2:** Plot histograms of loan amounts.
- **Question 3:** Plot histograms with different bin widths.
- **Question 4:** Plot histograms of loan amounts by homeownership.
- **Question 5:** Create subplots for different bin widths.
- **Question 6:** Plot a density plot of loan amounts.
- **Question 7:** Create a boxplot of interest rates.
- **Question 8:** Create a boxplot of interest rates by loan grade.
- **Question 9:** Create a boxplot of annual income by homeownership.

---

## Classwork

### In Class Assignment 5
This assignment involves working with the Portal Teaching dataset.

- **Data Description:** The dataset contains information about species and weight of animals caught in study sites.
- **Questions:** Various questions related to reading, analyzing, and visualizing the dataset using `pandas`.

### Reading and Writing Data
This notebook covers reading and writing data using `pandas`.

- **Reading CSV Files:** Using `read_csv` and `read_table` functions.
- **Writing CSV Files:** Using `to_csv` function.
- **Reading Excel Files:** Using `read_excel` function.
- **Reading CSV from URL:** Using `read_csv` with a URL.
