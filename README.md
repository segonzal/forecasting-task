## Overview

This task is designed to assess your skills in data analysis, image processing, and deriving insights from environmental data. You will be working with a dataset of chlorophyll satellite images to extract useful information and present your findings. As context, chlorophyll is a pigment found in phytoplankton, microscopic organisms that form the base of the marine food web. By analyzing chlorophyll concentrations in ocean waters, scientists can gain valuable insights into marine ecosystems, nutrient cycling, and overall ocean health. These insights are crucial for our clients in desalination, fisheries, and marine conservation.

Our goal with this task is to assess your expertise to analyze and interpret remote sensing data. Also, even though it is not mandatory, we encourage you to modelate and forecast the chlorophyll concentration in the ocean waters (on the image or time series domain). Feel free to formulate the problem as you wish.

## Dataset

The dataset consists of satellite images capturing chlorophyll concentrations in ocean waters. These images are crucial for understanding marine ecosystems, phytoplankton distributions, and overall ocean health.

Chlorophyll Data:

- File: chl_cmems_obs-oc_glo_bgc-plankton_my_l4-gapfree-multi-4km_P1D.nc
- Format: NetCDF.
- Time Range: 1997-09-04 ... 2024-08-14.
- Spatial Coverage: Latitude ranges from -27.98 to -21.02, Longitude ranges from -72.98 to -69.02. (Antofagasta Region, Chile).
- Spatial Resolution: ~4km.
- Time resolution: Daily.
- Reference: https://data.marine.copernicus.eu/product/OCEANCOLOUR_GLO_BGC_L4_MY_009_104/description

Additional Environmental Data: Sea Surface Temperature (optional):

- File: thetao_cmems_mod_glo_phy-thetao_anfc_0.083deg_P1D-m.nc
- Format: NetCDF.
- Time Range: 2022-06-01 ... 2024-09-01.
- Spatial Coverage: Latitude ranges from -27.98 to -21.02, Longitude ranges from -72.98 to -69.02. (Antofagasta Region, Chile).
- Spatial Resolution: 0.083deg.
- Time resolution: Daily.
- Reference: https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_PHY_001_024/description

For a more localized analysis, you can focus on a specific region around the coordinates (-23.627534, -70.396026).

## Task Requirements

To complete this task, please use Python, Jupyter Notebooks, and xarray for data analysis. You are free to use any additional libraries or tools you find necessary. Your analysis should cover the following aspects:

### Data Loading and Preprocessing

Load the satellite images into your preferred analysis environment. Perform any necessary preprocessing steps (e.g., handling missing data).

### Exploratory Data Analysis

Visualize the chlorophyll distributions across different time periods. Identify any patterns or anomalies in the data.

### Time Series Analysis

Analyze how chlorophyll concentrations change over time. Detect any seasonal patterns or long-term trends.

### Spatial Analysis

Investigate spatial patterns in chlorophyll concentrations. Identify areas of consistently high or low chlorophyll levels.

### Correlation with Environmental Factors

If provided, analyze how chlorophyll levels correlate with other environmental data (e.g., sea surface temperature).

### Insight Generation

Based on your analysis, what insights can you derive about marine productivity, ecosystem health, or potential environmental changes?

### Visualization and Reporting

Create clear, informative visualizations to support your findings.
Prepare a concise report (max 5 pages) summarizing your methodology, key findings, and conclusions.

## Evaluation Criteria

Your submission will be evaluated based on:

- Accuracy and depth of analysis
- Appropriateness of methods used
- Quality and clarity of visualizations
- Insightfulness of conclusions drawn
- Code quality and reproducibility
- Clarity and conciseness of the written report

## Submission Guidelines

Submit your code (with comments) in a Jupyter notebook. Include your report as a separate PDF document. Ensure all necessary dependencies are listed in a requirements.txt file. Submit your work via Github fork.

## Timeline

- Task Release Date: 2024-09-12 12:00.
- Submission Deadline: 2024-09-27 12:00.

Good luck! We look forward to seeing your innovative approaches and insights.
