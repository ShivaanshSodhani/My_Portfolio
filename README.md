# Unpacking Economic Dynamics through Cluster Analysis

This repository contains the research work "Unpacking Economic Dynamics through Cluster Analysis," authored by Shubham Lulu, Arjun Sankholkar, and Shivaansh Sodhani. This project explores the intricate relationship between trade, economic crises, and economic integration from 2000 to 2021. Using data-driven cluster analysis, the research identifies how countries' economic groupings are influenced by global crises.

## Abstract

Our research analyzes trade volume, cluster label changes, and silhouette scores to discern patterns of economic behavior and adjustments in national groupings during periods of economic crisis. The work presents a deep dive into four major crises: the 9/11 terrorist attacks, the 2008 financial crisis, the European debt crisis, and the COVID-19 pandemic. This investigation helps understand how global crises correlate with shifts in economic clusters defined by trade volumes and GDP per capita.

## Key Findings

- **Crisis and Cluster Dynamics**: A correlation between major economic crises and increased cluster turnover, suggesting significant reshaping of economic groupings in response to global events.
- **Effectiveness of Clustering During Crises**: The silhouette index indicates a decline in clustering effectiveness during crises, reflecting the challenges of accurately capturing economic changes with traditional metrics.

## Repository Structure

- `data/`: Contains the datasets used for analysis.
- `src/`: Includes all source code for the cluster analysis, data visualization, and statistical tests.
- `figures/`: Graphical representations of data and results, including histograms, decision region plots, and silhouette scores.

## Usage

Instructions on how to run the analyses:

```bash
# Example command to run the analysis script
python src/analysis.py
