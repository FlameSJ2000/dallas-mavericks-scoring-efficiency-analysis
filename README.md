## Overview

This project analyzes the scoring efficiency of Dallas Mavericks players during the 2025–2026 NBA season.

The objective is to evaluate player performance beyond traditional scoring statistics by combining scoring volume and shooting efficiency into a custom metric called MSEI (Mavericks Scoring Efficiency Index).

The project covers data preparation, metric development, dashboard design, and player segmentation using Power BI and Python.

The analysis includes:

* Exploratory Data Analysis (EDA)
* Data Cleaning and Feature Engineering
* Custom MSEI Development
* Interactive Power BI Dashboard
* Player Comparison Analysis
* Player Clustering Analysis

---

## Dashboard Preview

### Overview Dashboard

![Overview Dashboard](dashboards/screenshot/overview.png)

Provides a high-level summary of team scoring efficiency, player rankings, and key performance indicators.

### Efficiency Analysis Dashboard

![Efficiency Analysis Dashboard](dashboards/screenshot/efficiency_analysis.png)

Examines scoring efficiency across players using TS%, PTS per FGA, and MSEI.

### MSEI Ranking Dashboard

![MSEI Ranking Dashboard](dashboards/screenshot/msei_ranking.png)

Ranks players based on the custom MSEI metric and highlights top performers.

### Scoring Drivers Dashboard

![Scoring Drivers Dashboard](dashboards/screenshot/scoring_drivers.png)

Explores relationships between scoring metrics and overall scoring efficiency.

### Player Comparison Dashboard

![Player Comparison Dashboard](dashboards/screenshot/player_comparison.png)

Allows side-by-side comparison of selected players across multiple performance measures.

### Player Clusters Dashboard

![Player Clusters Dashboard](dashboards/screenshot/player_clusters.png)

Groups players into scoring archetypes based on efficiency and scoring volume.

---

## Dataset

The dataset contains Dallas Mavericks player statistics from the 2025–2026 NBA season.

Key variables include:

* PTS
* TS%
* PTS per FGA
* Projected PTS per 36 Minutes
* MSEI
* Cluster Labels

Raw statistics were collected and transformed into an analytical dataset for dashboard development.

---

## Methodology

### Data Preparation

Player statistics were collected, cleaned, and standardized using Python.

### Metric Development

A custom metric called MSEI was developed to evaluate scoring efficiency using multiple scoring-related variables.

### Dashboard Development

Power BI was used to create a five-page dashboard for player performance analysis.

### Clustering Analysis

Players were grouped into scoring archetypes to identify different scoring profiles within the roster.

---

## Tools

* Python
* Pandas
* NumPy
* Power BI
* DAX

---

## Repository Structure

```text
dataset/
dashboards/
notebooks/
output/
```

---

## Author

Siripaiboon Janpetch

Master of Science in Data Analytics

The University of Texas at San Antonio

```
```
