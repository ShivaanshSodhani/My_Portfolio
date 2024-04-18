# Unpacking Economic Dynamics through Cluster Analysis

This repository contains the research work "Unpacking Economic Dynamics through Cluster Analysis," authored by Shubham Lulu, Arjun Sankholkar, and Shivaansh Sodhani. This project explores the intricate relationship between trade, economic crises, and economic integration from 2000 to 2021. Using data-driven cluster analysis, the research identifies how countries' economic groupings are influenced by global crises.

## Problem Statement

The global economic landscape is perpetually in flux, influenced by a myriad of factors including geopolitical events, trade policies, and financial crises. Understanding how these dynamics affect national economies is crucial for policymakers, investors, and international organizations. Specifically, the challenge lies in identifying and quantifying the impact of global economic events on the trade volumes and GDPs of nations, and how these impacts, in turn, affect countries' economic classifications over time.

Our project aims to unpack these economic dynamics by analyzing how countries cluster based on trade volume and GDP—two pivotal indicators of economic health and activity—and how these clusters evolve in response to global economic events. Using data spanning from 2000 to 2021, we seek to:
1. Develop a clustering model that groups countries into distinct categories based on their trade volume and GDP, allowing us to observe the economic hierarchy and its progression.
2. Investigate the role of major crises, such as the 9/11 attacks, the 2008 financial crisis, the European debt crisis, and the COVID-19 pandemic, in influencing these cluster assignments.
3. Determine the factors contributing to the promotions and demotions of countries within these economic clusters, revealing the underlying causes behind these shifts.
4. Assess the effectiveness of clustering during different periods, particularly in times of crisis, using the silhouette score as a measure of clustering quality.
5. Validate the model’s findings against known economic trends and theories, thereby offering a grounded interpretation of the results.

This project will contribute to a deeper understanding of the interplay between trade, economic crises, and national economic performance, providing a data-driven foundation for future economic predictions and policy formulation.

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
