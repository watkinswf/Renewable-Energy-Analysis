# Renewable-Energy-Analysis
Using skills from Google Data Analyst certificate in collaboration with Gemini to analyze trends in renewable energy adoption
# Project: Global Trends in Renewable Energy Adoption

**Author:** Wil Watkins
**Date:** June 7, 2025

## 1. Project Objective
To analyze global and regional trends in renewable energy adoption between 2000 and 2020, identifying key drivers, leading countries, and regional differences. This project demonstrates skills in data acquisition, cleaning, processing, analysis, and visualization, aligned with the Google Data Analytics Professional Certificate curriculum.

## 2. Data Source
The data for this project was sourced from the World Bank's World Development Indicators dataset.

## 3. Tools Used

Python (Pandas, Matplotlib, Seaborn)
Google Colab / Jupyter Notebook

## 4. The Process
1. **Data Acquisition:** Gathered four indicators related to renewable energy consumption and production from the World Bank.
2. **Data Cleaning & Processing:** Cleaned and transformed the raw data. This included handling missing values, standardizing formats, and reshaping the data from a wide to a long format for analysis.
3. **Data Merging:** Consolidated the four clean datasets into a single, comprehensive master DataFrame.
4. **Exploratory Data Analysis (EDA):** Performed a multi-level analysis:
* Analyzed high-level global trends.
* Investigated the composition of renewable electricity (e.g., share of renewable vs. non-renewable).* Created leaderboards to identify top-performing countries.
* Compared the energy transition journeys of different world regions and specific countries.`

## 5. Key Findings & Visualizations
This analysis revealed several key insights into the state of global renewable energy. Below are the "greatest hits" that tell the core story of the data.

Finding 1: The share of renewables in the global electricity mix shows slow but accelerating growth.
While the share of renewables in total energy (including transport and heat) has been slow to change, the electricity sector shows a more promising story. The pace of this transition has clearly quickened in the last decade.

The renewable share of global electricity grew from approximately 19% in 2000 to over 28% in 2020.
This growth is primarily driven by the expansion of modern renewables like solar and wind, which have begun to meaningfully "squeeze" the share of non-renewable sources.

Finding 2: "Leadership" in renewable energy is complex and depends entirely on the metric used.
A crucial insight from this project is that a country's status as a renewable energy leader can be misleading without proper context.

Leaders in Total Energy Consumption are typically developing nations with high reliance on traditional biomass (e.g., wood for cooking). This is not indicative of a modern, green electricity grid.
Leaders in Renewable Electricity Output are countries with massive hydropower/geothermal resources (e.g., Norway, Iceland) or those with aggressive, modern green policies.
This distinction is critical for an accurate understanding of the energy transition; the data shows that "renewable electricity share" is the more relevant metric for tracking progress.

Finding 3: Nations and regions follow unique energy transition pathways, shaped by geography and policy.
There is no one-size-fits-all journey. By comparing different countries and regions, we can see distinct patterns.

Some regions, like Latin America, have been long-standing leaders due to legacy hydropower infrastructure built over decades.
Others, like the European Union, show rapid recent growth driven by strong, coordinated policy initiatives that incentivize new technologies like wind and solar.
Countries like Chile demonstrate a "V-shaped" transition, overcoming initial challenges with a massive, successful push into new solar and wind capacity.

### Finding 1: Global electricity production from renewables grew from ~19% to ~28% between 2000 and 2020, with growth accelerating after 2010.
https://github.com/user-attachments/assets/3eb07845-47b5-441f-bca8-0e8b100678c2

### Finding 2: A country's renewable energy leadership depends heavily on the metric used. Leaders in *total* renewable energy (often due to traditional biomass) are very different from leaders in *renewable electricity* (driven by hydro, solar, and wind).
https://github.com/user-attachments/assets/fef42ea7-833a-48f8-8552-41bc606c5d97

### Finding 3: Different regions and countries are on unique energy transition journeys, driven by geography (e.g., Latin America's hydro) or policy (e.g., the EU's coordinated push).
https://github.com/user-attachments/assets/19c328d0-0de9-4cb3-9c97-ad3c19208143

## 6. How to Use This Repository
The full analysis is contained within the Jupyter Notebook file (Renewable_Energy_Analysis.ipynb). The raw data files are also included in this repository.
