# DataVisualization_project
Data Visualization coursework for CSS - 2024-2025 term

Overview

This project analyzes Body Mass Index (BMI) trends among Olympic athletes by comparing the 1960 and 2016 Summer Olympic Games. The analysis includes both replication of an existing visualization and development of improved alternative plots using R.

Project Structure
1. Replication

The project begins by replicating the original plot that displays mean weight and height by sport for athletes aged 20 and older at the 1960 and 2016 Summer Olympics. The replication process is documented step by step, including:

Data filtering and cleaning
BMI calculation and categorization
Tile-based visualization with color-coded BMI categories
Faceting by gender and Olympic year
Custom styling with fonts, colors, and annotations

2. Alternative Visualizations
3. 
After identifying limitations in the original plot (difficulty tracking trends over time, overlapping labels, redundant BMI categories), two improved versions are developed:

Alternative Plot 1: A slope chart focusing on male athletes across 19 common sports, designed with retro 8-bit aesthetics inspired by classic sports video games. The visualization uses dotted lines connecting 1960 and 2016 BMI values, making temporal trends immediately visible.

Alternative Plot 2: An enhanced version incorporating both male and female athletes, addressing feedback from the initial presentation. This version includes two facets (11 male sports, 7 female sports) with improved spacing, visibility, and balance.

Methodology
The analysis follows a gradual, iterative approach:

Data import and preprocessing
Step-by-step replication of the original plot with detailed explanations
Identification of visualization weaknesses
Incremental development of alternative plots with design improvements
Refinement based on feedback

Key Findings

Most Olympic sports show increasing BMI trends from 1960 to 2016
Defenders in team sports consistently favor older, heavier athletes
BMI patterns vary significantly by sport type and gender
Women's sports representation was limited in 1960, creating data challenges

Technical Details

Language: R
Key packages: tidyverse, ggplot2, ggrepel, showtext, viridis, gridExtra
Data source: Kaggle Olympic Athletes dataset
Fonts: Google Fonts (Press Start 2P, VT323 for retro aesthetic)

Files

Data Visualization.Rmd: Complete R Markdown document with code and analysis
athlete_events.csv: Source dataset

Design Philosophy
The alternative plots embrace an 8-bit retro gaming aesthetic, paying homage to classic sports games like Track & Field. Custom color palettes, pixel-style fonts, and dotted line connections create a nostalgic visual style while maintaining analytical clarity.
