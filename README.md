# Gapminder Data Visualization with Plotly

## Overview
This repository contains an interactive data exploration and visualization project using the Gapminder dataset. The analysis examines the relationships between life expectancy, GDP per capita, and population across countries and time periods from 1952 to 2007, with a focus on creating dynamic, interactive visualizations.

## Dataset
The project uses the built-in Gapminder dataset available through Plotly Express, which includes:
- Country and continent information
- Population data
- Life expectancy statistics
- GDP per capita metrics
- Time series data spanning from 1952 to 2007

## Analysis Highlights
The notebook performs a progressive data exploration with increasingly complex visualizations:

1. **Data Exploration**
   - Interactive tabular view of the dataset
   - Initial summary statistics and structure examination

2. **Single Country Analysis**
   - Focus on Canada as a case study
   - Population trends over time
   - Enhanced visualizations with multiple metrics (population, life expectancy, GDP)

3. **Cross-Country Comparisons**
   - Snapshot analysis of 1997 data
   - Relationship between GDP per capita and life expectancy
   - Continental patterns and differences

4. **Advanced Visualizations**
   - Bubble charts with multiple dimensions (GDP, life expectancy, population, continent)
   - Faceted visualizations separating data by continent
   - Log-scale transformations for better distribution visualization

5. **Time Series Animations**
   - Animated bubble charts showing development trends over decades
   - Choropleth map animations displaying global life expectancy changes

## Key Insights
- Visualization of Hans Rosling's famous observations about global development
- Clear continental patterns in development metrics
- Temporal evolution of global health and wealth indicators
- Interactive exploration of multidimensional relationships in the data

## Technologies Used
- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and analysis
- **Plotly**:
  - Plotly Express for high-level chart creation
  - Plotly Figure Factory for tables
  - Plotly Offline for notebook integration
  - Interactive visualizations including animations and geographic mapping

## Getting Started
To run this analysis:

1. Clone this repository
```
git clone https://github.com/VarunPahuja/gapminder-visualization.git
```

2. Install required dependencies
```
pip install pandas numpy plotly
```

3. Open the Jupyter notebook
```
jupyter notebook gapminder_analysis.ipynb
```

## Interactive Features
This project leverages Plotly's interactive capabilities:
- Hover information for detailed data points
- Zoom and pan functionality
- Animation controls for time series visualizations
- Filtering and selection tools
- Export options for visualizations

## Future Work
Potential extensions to this analysis:
- Additional socioeconomic indicators beyond the core Gapminder metrics
- Statistical analysis of development trends and correlations
- Predictive modeling of future development trajectories
- Integration with current data beyond 2007
- Custom region groupings beyond continental divisions


