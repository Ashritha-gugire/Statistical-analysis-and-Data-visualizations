## Education vs Prison Costs & Handgun Homicides Analysis

### Project Overview
This comprehensive data visualization project analyzes the relationship between education funding, prison costs, and handgun homicides across US states. The project redesigns ineffective pie charts and dot plots into interactive, insightful visualizations that reveal critical patterns in government spending priorities.

### Problem Statement
The original visualizations from CNN Money presented education vs prison cost data and handgun homicide statistics in a way that made it difficult to:

Compare spending disparities between education and incarceration
Identify regional patterns in violence and funding
Understand the correlation between underfunded education and crime rates

### Key Findings
Spending Disparities

Prison costs average 3.4x higher than education costs per person
States like New York and New Jersey show the highest disparities (up to $40K difference)
Only 4 states show relatively balanced funding between education and prison systems

Regional Patterns

Gulf Coast & East Coast regions show highest handgun death rates
California and Texas lead in absolute death counts (866 and 497 respectively)
Midwest states generally show lower violence rates but maintain high prison spending

Critical Insights

68% of inmates are individuals who lacked educational support during their studies
States with higher poverty rates correlate with increased handgun violence
The funding gap suggests a reactive rather than preventive approach to crime

### Technical Implementation
Data Processing & Analysis

R Programming: Used for data extraction, cleaning, and statistical analysis
Libraries: tidyverse, ggplot2, plotly, maps, usmap, viridis
Data Sources: CNN Money interactive graphics, FBI Crime Reports, state budget data

Visualization Techniques

Dot Plots: Replaced pie charts with ordered dot plots for better comparison
Dumbbell Charts: Showed spending differences between education and prison costs
Choropleth Maps: Regional analysis with geographic context
Interactive Elements: Plotly integration for enhanced user engagement

### Web Dashboard

Frontend: HTML5, CSS3, JavaScript (D3.js, Plotly.js)
Features:

Interactive filtering by region
Real-time statistics updates
Responsive design for all devices
Hover tooltips with detailed information



### Methodology
Data Collection

Extracted data from original CNN Money visualizations
Supplemented with poverty rate data by state
Created regional classifications (East Coast, Midwest, Gulf Coast, West Coast)

Redesign Process

Analysis: Identified weaknesses in original pie chart format
Data Restructuring: Organized data for comparative analysis
Visualization Selection: Chose appropriate chart types for each insight
Regional Mapping: Implemented geographic context for pattern recognition
Interactivity: Added filters and controls for exploratory analysis

Statistical Analysis

Calculated spending ratios and differences
Performed regional aggregations
Identified correlation patterns between variables

Design Principles
Visual Hierarchy

Used color coding to distinguish between education (blue) and prison (pink) costs
Implemented size encoding for death count visualization
Applied consistent typography and spacing

User Experience

Progressive disclosure of information
Intuitive navigation with region filters
Mobile-responsive design
Accessible color schemes and contrast ratios

### Key Visualizations

Spending Comparison Chart: Side-by-side comparison of education vs prison costs
Death Rate Map: Geographic visualization of handgun homicides
Regional Analysis: Separated views for detailed regional patterns
Difference Analysis: Highlighting the funding gap across states

Impact & Results
Improved Data Communication

Transformed confusing pie charts into clear, actionable insights
Enabled users to identify patterns impossible to see in original format
Provided interactive exploration capabilities

Policy Implications

Highlighted states where education investment could reduce crime
Identified regions requiring targeted intervention
Demonstrated correlation between education funding and public safety

Technical Skills Demonstrated

Advanced R programming for statistical analysis
Data visualization best practices
Interactive web development
Geographic information systems (GIS)
UI/UX design principles

### Technologies Used
Analysis & Visualization:

R Studio, ggplot2, plotly
Maps, usmap, viridis libraries
Statistical modeling packages

Web Development:

HTML5, CSS3, JavaScript
D3.js, Plotly.js
Responsive design frameworks

Data Sources:

CNN Money interactive graphics
FBI Crime in the United States reports
State education department budgets
US Census poverty data


Data Analysis: Statistical analysis, pattern recognition, data cleaning
Visualization: Chart selection, color theory, information design
Programming: R, JavaScript, HTML/CSS
Research: Data collection, source validation, methodology design
Communication: Clear storytelling, insight presentation

Future Enhancements

Integration with real-time data sources
Machine learning models for predictive analysis
Additional socioeconomic variables (unemployment, graduation rates)
Time-series analysis for trend identification
Mobile app development for broader accessibility


This project demonstrates the power of effective data visualization in transforming complex policy data into actionable insights for decision-makers and the public.
