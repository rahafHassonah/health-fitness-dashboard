# Health & Fitness Tracking Dashboard

An interactive multi-tab R Shiny dashboard analyzing health and fitness patterns across **687,701 records** from January–December 2024.

## Overview

This dashboard enables exploratory analysis of a large-scale fitness dataset, surfacing insights about activity types, calorie burn, intensity levels, and wellness metrics through dynamic, interactive visualizations.

## Dataset

- **687,701 records** · 22 attributes · Full year 2024 (Jan 1 – Dec 25)
- **Demographics:** Age, gender, height, weight
- **Activity data:** Activity type, duration, intensity, steps, calories burned, average heart rate
- **Wellness metrics:** Sleep duration, hydration level, blood pressure, smoking status, fitness level

## Dashboard Tabs

### Activity Tracker Tab
- **Treemap** — Calories distribution by activity type and intensity level
  - HIIT burns the most total calories (~305,390 cal), followed by Running (~239,923 cal) and Cycling (~216,597 cal)
  - Medium intensity dominates calorie contribution across most activity categories
- **Line Chart** — Monthly calories burned trend across the full year, revealing seasonal activity patterns and peak workout periods

### Health Metrics Tab
- **Scatter plot** — Exercise duration vs. average heart rate by intensity level
- Additional interactive filters for exploring patterns across user groups

## Key Insights

- HIIT is the most calorie-intensive activity; Yoga and Walking burn significantly fewer calories
- Medium intensity workouts contribute the most to total calorie burn across nearly all activity types
- Monthly trends reveal consistent seasonal fluctuations in overall fitness activity

## Tech Stack

- **R** · **Shiny** · **ggplot2** · **dplyr**
- RStudio · Interactive filtering and visualization

## Authors

Rahaf Hassonah · Noor Almazaydeh  
Department of Data Science, University of Jordan — 2025
