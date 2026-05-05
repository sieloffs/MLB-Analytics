# MLB Analytics Portfolio

This repository contains a collection of baseball analytics and machine learning projects built using publicly available MLB data, primarily sourced from FanGraphs and Statcast.

The goal of this project is to explore different applications of data science in baseball, including player evaluation, performance prediction, and advanced statistical modeling.

---

## Repository Structure

All datasets used in the projects are stored in the `Data/` directory.  
Each project will have its own notebook or folder containing analysis, modeling, and results.

---

## Current Projects

### 1. WAR Prediction Model

The first project in this repository focuses on predicting Wins Above Replacement (WAR) using player level offensive and positional metrics.

This model explores how well underlying skill based statistics such as:
- Plate discipline (BB%, K%)
- Quality of contact (Barrel%, Exit Velocity)
- Batted ball profile (Launch Angle, LD%, GB%, FB%)
- Speed
- Defensive position

can explain overall player value.

The project includes:
- Feature selection and correlation analysis
- Linear regression modeling
- Position encoding
- Model evaluation (MSE, R²)
- Residual and outlier analysis

---

## Ongoing Work

This repository is actively being developed. Additional projects will be added over time, including:

- Pitch level outcome prediction using Statcast data
- Nonlinear and neural network models for player evaluation
- Breakout season prediction models
- Advanced clustering of player archetypes

---

## Goal

The goal of this repository is to build a portfolio of applied baseball analytics projects that demonstrate:
- Machine learning skills
- Feature engineering ability
- Statistical reasoning
- Domain knowledge in baseball performance analysis

---

## Data Sources

- FanGraphs Leaderboards
- MLB Statcast / Baseball Savant

All data is publicly available and used for educational and analytical purposes only.
