# Mini-Project (ML for Time Series) - MVA 2023/2024

Authors:
- Adib Habbou (adibhabboupro@gmail.com)
- Teddy Alexandre (teddyalexandre1@gmail.com)

Date: December 12, 2023

## 1 Introduction

The paper [1] under review focuses on time series discords, addressing the challenge of selecting the optimal subsequence length for anomaly detection without user-defined parameters. Introducing MERLIN, an innovative algorithm based on DRAG [2], the study aims to significantly enhance anomaly detection precision.

## 2 Method

The paper details the DRAG algorithm's two main phases and introduces MERLIN's iterative approach to adapt the parameter value 'r' for optimal discord detection.

## 3 Data

### 3.1 Toy Examples
Explores constant, sinusoidal time series, and their anomalies to validate the implementation.

### 3.2 New York Taxi Dataset
Limited to November 2018, the dataset presents anomalies caused by Daylight Saving Time and Thanksgiving, analyzed for periodicity and anomalies.

### 3.3 Yahoo Dataset
Comprises real and synthetic time-series, highlighting anomalies, trends, and potential anomalies through boxplots.

### 3.4 Ultra Subtle Anomalies
Generated sinusoidal time series with minute anomalies, testing MERLIN's sensitivity.

### 3.5 Twin Freak
Created a twin-freak anomaly time series to test the algorithm's performance on similar anomalies.

## 4 Results

Summarizes findings across toy examples, real datasets (New York Taxi and Yahoo), ultra subtle anomalies, and twin freak cases, highlighting challenges and limitations in MERLIN's anomaly detection.

## 5 References

Lists relevant papers and resources used in the project, including MERLIN++ and PALMAD for improved anomaly detection.

## Appendix

Provides visual representations of data, MERLIN outputs, and analyses conducted across various datasets.
