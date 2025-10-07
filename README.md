# Data Visualization Project
This project analyses BMW sales data from 2010 to 2024 to uncover sales patterns and customer preferences that can inform both marketing and strategic decision-making. By combining exploratory data analysis with visualisation techniques, I aim to reveal insights about model performance, regional demand, and evolving trends in the automotive market.

This work is part of my data visualisation project, where I will develop prototypes, iterate on sketches, and eventually deliver an interactive visualisation dashboard.
## Data

The dataset used is the BMW Sales Data (2010–2024), comprising 50,000 entries. It is provided in CSV format for this course. Comparable public datasets also exist (e.g., BMW Sales 2010–2024 on Kaggle
).

Key Fields

Year – Sales year (2010–2024).

Model – Specific BMW model sold.

Region – Geographic sales area (Asia, North America, Africa, Europe, and Middle East).

Color – Vehicle color preference.

Fuel_Type – Petrol, Diesel, Hybrid, etc.

Transmission – Manual vs Automatic.

Engine_Size_L – Engine size in liters.

Mileage_KM – Mileage of the vehicle.

Price_USD – Price of the vehicle in USD.

Sales_Volume – Number of units sold.

Sales_Classification – Sales performance (High or Low).

## Data Analysis Plan

Data Cleaning – Address missing values, duplicates, and inconsistencies.

Exploratory Data Analysis (EDA) – Use descriptive statistics and visual summaries to explore trends.

Visualization Prototypes – Apply different techniques (bar charts, line charts, scatter plots, stacked bars) to answer the research questions.

Marketing Insights Extraction – Translate findings into actionable insights for marketing and strategic positioning.

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:
Sales Trends Over Time – How have BMW’s sales volumes evolved between 2010 and 2024?

Model Performance – Which BMW models consistently dominate sales, and how has this changed?

Regional Differences – Which regions prefer which models, and how do fuel types or transmission choices vary geographically?

Customer Preferences – Do features like color, engine size, or price correlate with higher sales?

Strategic Insights – What lessons can BMW’s marketing team draw from these patterns?

## Sketches
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/master/sketch%20of%20clickable%20stacked%20barchart.png?raw=true)
This is a foundational sketch of BMW sales in the major populated countries representing each of the seven continents in the world.
(https://vizhub.com/bsarfo/43162b9dad6b482a9f8481048969f608?file=data.js)
## Prototypes

Planned Visualizations for BMW Data

Bar Chart – Top 10 BMW models by sales volume.

Line Chart – Sales trends over time (2010–2024).

Stacked Bar Chart – Sales volume breakdown by region.

Scatter Plot – Engine size vs. price, colored by sales classification.

Interactive Prototype (VizHub)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/c76e550aa59893049b50a2c37985022266f2198c/bar%20chart.png)

I also developed an interactive bar chart (using a population dataset) on VizHub to experiment with hover-tooltips and clickable bars:
👉 Interactive Bar Chart Prototype.
My week six sketch is a build-up of what I did in week 5. Two stacked bar charts were developed, and one is clickable. Week six improvement adds 
to the ineffectiveness of my data development, as can be seen below.
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/32377794002064dba9f9b276dfbf08f2905a27d8/BMW%20SALES%20STACKED%20BAR%20CHART%201.png)
https://vizhub.com/bsarfo/55c352b9e2cc4c3682d7c42667d8b47b?file=data.csv&tabs=data.csv%7EREADME.md
This interaction model will later be applied to BMW sales data (e.g., hovering to see sales volumes, filtering by region or model).
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/master/stacked%20bar%20chart%202.png?raw=true)
https://vizhub.com/bsarfo/50b293e1fb584805808ced58b1025468
## Progress as at October 7, 2025
In week 7 I refactored the clickable bar chart by forking it to display a deep blue colour (indicating the area with the highest volume of BMW sales), sea blue (indicating the region with the high volume of sales) and light blue colour indicating the region with the low level of sales. this is shown in this link https://vizhub.com/bsarfo/6b50aa9a3e194e9080a0f1b1fe1d8e47
In other to let viewers get a better picture of how the sales really affect management decision as to where to increase production. I forked the bar chart using the assistance of AI to depict these BMW Sales Volume on the world map. I used Ai because I had difficulty using week 7 lecture approach. But it turned out to be great. Attached is the link. https://vizhub.com/bsarfo/6b50aa9a3e194e9080a0f1b1fe1d8e47
## Open Questions

I am confident about the direction of the project, but I do have a few concerns. Since the dataset is synthetic, I’m not sure how realistic some fields (like mileage or sales classification) are, which may affect the authenticity of insights. I also want to explore regional differences, but I may not have access to detailed geographic shapes or data for mapping. Finally, while I’ve sketched interactive ideas like hover-tooltips and filters, I’m uncertain about how smoothly I can implement them in D3.js. These challenges may require me to simplify some aspects, but they will also push me to learn through iteration.

## Milestones

Week 1: Define project scope, document dataset fields, and draft initial research questions. Create first static sketches (bar chart practice with population data).

Week 2: Clean and explore the BMW dataset. Generate descriptive statistics and begin simple visualizations (bar chart of top models, line chart of total sales by year).

Week 3: Develop refined sketches and prototype visualizations. Experiment with different encodings (colors, labels, highlights) and iterate on clarity.

Week 4: Introduce interactivity (hover-tooltips, sorting, filtering) using VizHub or D3.js. Connect prototypes to BMW dataset instead of practice data.

Week 5: Combine insights into a more cohesive dashboard. Add annotations and highlight key findings (e.g., top-selling models, regional differences).

Week 6: Polish visuals, finalize README writeup, and ensure interactivity works smoothly. Prepare final submission with a clear narrative linking research questions to visualizations and insights.
