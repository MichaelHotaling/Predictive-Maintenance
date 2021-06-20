# Predictive Maintenance

## Abstract

With the dawn of IoT and Industry 4.0, it is now possible to monitor manufacturing machinery to predict failures before they occur. Most manufacturing systems built today have an array of sensors that report a wide range of variables depending on what kind of work the machinery is designed to do. These sensors can report several key variables that impact production including speed of components, torque measurements, temperature measurements, vacuum levels, laser power and more.  All of this can be analyzed on-the-fly in data warehouse systems to detect anomalies and process variations before they have a chance to impact the product. 
---
## Problem Statement

These two techniques of preventive maintenance and corrective maintenance are both extremes, with one prioritizing uptime while risking the health of machinery and product while the other prioritizes machine health over uptime. With the dawn of IoT and Industry 4.0, it is ow possible to monitor manufacturing machinery to predict failures before they occur. Most manufacturing systems built today have an array of sensors that report a wide range of variables depending on what kind of work the machinery is designed to do. These sensors can report several key variables that impact production including speed of components, torque measurements, temperature measurements, vacuum levels, laser power and more.  All of this can be analyzed on-the-fly in data warehouse systems to detect anomalies and process variations before they have a chance to impact the product. 
Using this data, we can create a predictive model that can send us alarms when our process starts to trend out of spec, preventing any unnecessary unscheduled downtime and loss of material, while also reducing scheduled downtime by isolating issues down to a single source. This will ensure that our machines remain in good health while operating at the maximum possible availability.

## Data Used

[One Year Industrial Component Degradation](https://www.kaggle.com/inIT-OWL/one-year-industrial-component-degradation)
The Vega shrink-wrapper from OCME is deployed in large production lines in the food and beverage industry. The machine groups loose bottles or cans into set package sizes, wraps them in plastic film and then heat-shrinks the plastic film to combine them into a package. The plastic film is fed into the machine from large spools and is then cut to the length needed to wrap the film around a pack of goods. The cutting assembly is an important component of the machine to meet the high availability target. Therefore, the blade needs to be set-up and maintained properly. Furthermore, the blade can not be inspected visually during operation due to the blade being enclosed in a metal housing and its fast rotation speed. Monitoring the cutting blades degradation will increase the machines reliability and reduce unexpected downtime caused by failed cuts.

[Turbofan Engine Degradation Simulation Data Set](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan)
The N-CMAPSS dataset provides synthetic run-to-failure degradation trajectories of a fleet of turbofan engines with unknown initial health states subject to real flight conditions. The N-CMAPSS dataset contains eight sets of data from 128 units and seven different failure modes affecting the flow and efficiency of all the
rotating sub-components


The following topics will be covered in this project:
* Importing the Data
  * Iterating over multiple files to combine our data
* Exploratory Data Analysis
  * Plotting the data to discover sequences, trends, and correlations 
* Data Wrangling
  * Data Restructuring
  * Attribute Creation
  * NaN Imputation/Removal
* Model Development
  * Principal Component Analysis
  * One-SVM
  * Survival Statistics

