# afghanistan-air-quality-sentinel5p
Exploring air pollution patterns in Afghanistain's major cities using Sentinel-5P satellite data.

Project Plan

Goal:
Use Sentinel-5P satellite data to analyze air pollution patterns (NO₂) in major Afghan cities—Kabul, Herat, Mazar-e-Sharif, Kandahar, and Jalalabad.

Outline
1. Data Acquisition
    Download Sentinel-5P NO₂ data using the Google Earth Engine Python API
    Extract data for 5 city bounding boxes
    Export daily / weekly / monthly averages

2. Data Cleaning & Preparation
    Convert satellite values to usable units
    Clip rasters by city boundaries
    Produce monthly time-series for each city
    Create geospatial rasters for mapping

3. Visual Analysis
    Heatmaps showing NO₂ concentration hotspots
    Time-series line charts comparing monthly pollution
    Seasonal pattern analysis (winter vs summer)
    Cross-city comparison plots

4. Insights
    Examples of questions the analysis will explore:
    Which cities show the highest NO₂ levels?
    How does Kabul’s winter pollution compare to summer?
    Which neighborhoods appear as recurring hotspots?
    Are there long-term trends (improving/worsening)?

5. Outputs
    Maps (PNG)
    Time-series charts
    A final Jupyter notebook
    A written report summarizing key findings
