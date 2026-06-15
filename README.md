# Phishing URL Detection Dashboard

## Project Overview

This project analyzes a phishing URL dataset and presents insights through an interactive Power BI dashboard. The goal is to identify patterns that distinguish phishing websites from legitimate websites using various URL-related features.

## Files Included

* **Phishing_URL_Dataset.xlsx** – Dataset containing URL characteristics and labels.
* **Phishing_detection.pbix** – Power BI dashboard file for visualization and analysis.

## Dataset Information

The dataset contains **1,000 records** and **8 columns**:

| Column Name        | Description                                            |
| ------------------ | ------------------------------------------------------ |
| URL                | Website URL                                            |
| URL_Length         | Length of the URL                                      |
| HTTPS              | Whether HTTPS is used                                  |
| Domain_Age_Months  | Age of the domain in months                            |
| Number_of_Dots     | Number of dots in the URL                              |
| Special_Characters | Count of special characters                            |
| IP_Address_Used    | Indicates if an IP address is used instead of a domain |
| Label              | Classification (Phishing or Legitimate)                |

## Dashboard Features

* Distribution of Phishing vs Legitimate URLs
* HTTPS Usage Analysis
* URL Length Analysis
* Domain Age Comparison
* Special Character Analysis
* IP Address Usage Detection
* Interactive Filters and Visualizations

## Tools Used

* **Microsoft Power BI**
* **Microsoft Excel**

## Objective

To identify suspicious URL patterns and provide insights that help detect phishing websites more effectively.

## How to Use

1. Open `Phishing_detection.pbix` in Power BI Desktop.
2. Refresh the dataset if required.
3. Explore the interactive dashboard and visualizations.
4. Use filters to analyze phishing indicators.

---

**Author:** Rudra Bharat
**Project:** Phishing URL Detection Analysis & Dashboard
# phishing-url-detection
