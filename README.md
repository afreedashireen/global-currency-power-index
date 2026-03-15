# Global Currency Power Index (CCPI)

A data analytics and visualization project analyzing the structural strength of global currencies using economic indicators from 2000–2024.

## Project Goal

The project builds a Composite Currency Power Index (CCPI) to measure the relative economic strength of countries based on:

- GDP
- Inflation
- Foreign exchange reserves
- Trade openness
- Current account balance

The objective is to identify global economic patterns and structural shifts in currency power.

## Dataset

Source: World Bank – World Development Indicators

Countries analyzed: 100+

Time period: 2000–2024

Variables used:
- GDP (USD)
- Inflation (CPI %)
- Trade (% GDP)
- Foreign Reserves
- Current Account Balance
- Exchange Rate

## Tools & Technologies

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Plotly  
Scikit-learn  

## Key Techniques

- Data cleaning and preprocessing
- Min-Max normalization
- Composite index construction
- Correlation analysis
- PCA (Principal Component Analysis)
- K-Means clustering
- Animated data visualizations

## Key Insights

- China overtook the United States in structural currency power around 2008.
- Four distinct economic regimes were identified through clustering.
- Reserve accumulation strongly correlates with currency strength.
- Global currency power is highly persistent over time.

## Visualizations

### Correlation Heatmap
Shows relationships between economic indicators.

### Animated Bubble Chart
Visualizes GDP, inflation, reserves, and CCPI simultaneously.

### PCA + Clustering
Identifies structural economic groups among countries.

### Global Choropleth Map
Shows geographic distribution of currency power.

### Bar Chart Race
Displays ranking changes from 2000–2024.

## Interactive Dashboard

An interactive dashboard was built using Streamlit to explore the CCPI dataset dynamically.

Run locally:
