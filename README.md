<h1 align="center">
  <img src="https://raw.githubusercontent.com/johnscott7/PL-Goal-Chains/main/docs/assets/1230_UseofDataInFootball.webp" 
  alt="Premier League Expected xG Analysis Banner" 
  width="1000">
  <br>
</h1>

# How Premier League Clubs Concede Chances: Analyzing and Visualizing xG-Chains

## Table of Contents
- [1. Project Motivation](#1-project-motivation)
- [2. Project Goals](#2-project-goals)
- [3. Data Sources](#3-data-sources)
- [4. Project Structure](#4-project-structure)
- [5. Methodology](#5-methodology)
- [6. Results and Insights](#6)

## 1. Project Motivation
Premier League clubs increasingly rely on analytics to evaluate not only how to create goal-scoring chances, but also how to minimize the high-xG opportunities they concede to opponents. This project examines defensive patterns for each club in the Premier League using open-source data and event sequences derived from match footage.

The goal is to analyze the chains of play leading to high expected-goal (xG > 0.30) opportunities by each team. By examining the sequences of events leading up to high-quality shot opportunities, this analysis focuses on:
- recurring defensive breakdowns or structural weaknesses  
- the roles of key players and key areas of the pitch for each team  
- tactical patterns in approach for each club  

This analysis includes event types (ground passes, aerial passes, dribbles, interceptions, headers), player involvements, and pitch zones for all high expected-goal opportunities in the 2025–2026 Premier League season.


The **primary dataset** comes from **Understat**, supplemented with user-tagged data collected from match broadcasts.

--
##  2. Project Goals
This analysis supports:
- tactical evaluation of defensive vulnerabilities and attacking approaches, and  
- fan engagement through clear visualizations of tactical trends and patterns of play used by each club.


## 3. Data Sources
### Primary Dataset
- [Understat EPL Match Data] (https://understat.com/league/EPL/2025)

### Related Datasets
All supporting data is manually generated through Premier League match broadcasts.


## 4. Project Structure
```bash
data/           # raw and cleaned datasets
notebooks/      # Jupyter notebooks for exploration and visualization
scripts/        # Python scripts for analysis
visuals/        # figures and charts
docs/           # documentation and static assests
```

## 5. Methodology
- Detailed methodology in progress.


## 6. Results and Insights
- Results and Insights to come.