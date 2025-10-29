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
In week 7 I refactored the clickable bar chart by forking it to display a deep blue colour (indicating the area with the highest volume of BMW sales), sea blue (indicating the region with the high volume of sales) and light blue colour indicating the region with the low level of sales. This is shown in this link https://vizhub.com/bsarfo/6b50aa9a3e194e9080a0f1b1fe1d8e47
In other to let viewers get a better picture of how the sales really affect management decisions as to where to increase production. I forked the bar chart using the assistance of AI to depict the BMW Sales Volume on the world map. I used AI because I had difficulty using the week 7 lecture approach. But it turned out to be great. Attached is the link: https://vizhub.com/bsarfo/106ca9d49d2b4a45ae0d6ce8abd4ac02
It turned out that the volume of BMW sales in Asia was the highest, followed by the West and Africa.
## Progress as at October 22, 2025 (Week 9)
(1) https://vizhub.com/bsarfo/741f16fb7a044162b742b19542717c23 and (2) https://vizhub.com/bsarfo/831a2e84b63f46b9addde45331ff7490?file=script.js these links display a suggestion from Discord, by Shourya Kasiliwal, who suggested "Refine Region Grouping: You've grouped regions into large continents (Asia, Africa, North America, Europe, South America, Middle East). For real-world business decisions, BMW often focuses on countries (e.g., China, the USA, Germany). If the underlying data allows, a map segmented by major market countries would provide a much more actionable insight for management regarding new plant locations or production increases". This suggestion sounds convincing, and so the data was cleaned to make adjustments for peer suggestions. The results show a visualisation that presents a more actionable insight for stakeholders to make refined decisions.
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/068414d652d344323aa6ff4b6db6bf0356a9afa7/BMW%20SALES%20REGIONAL%20MAP.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/e3c011f44c153e0e09297a1e9cbb6c2a304560b9/W9%20BMW%20CLICKABLE%20STACK%20BAR%20CHART.png)
## Dashboard:
BMW Global Sales Insights (2010 – 2024):
| Section                      | Visualization                               | Purpose                                   | Annotation Example                                                                       |
| ---------------------------- | ------------------------------------------- | ----------------------------------------- | ---------------------------------------------------------------------------------------- |
| **A. Overview**              | *Stacked bar chart* (your current one)      | Show total BMW sales by country over time | “Global sales peaked in 2022 (+8 % YoY), driven by USA & China.”                         |
| **B. Regional Trend Lines**  | *Multi-line chart* (x = Year  /  y = Sales) | Compare growth paths of each region       | “China’s sustained climb contrasts with plateau in Germany.”                             |
| **C. Model Leaderboard**     | *Horizontal bar chart* for 2024             | Highlight top-selling models              | “BMW X5 leads 2024 with 220 k units.”                                                    |
| **D. Market Share Snapshot** | *Donut or pie chart* for 2024               | Visualize relative regional shares        | “USA and China account for > 50 % of sales.”                                             |
| **E. Key Takeaways Panel**   | *Text annotations / cards*                  | Synthesize narrative                      | “BMW’s recovery post-COVID was strongest in the U.S. and China; Europe remained stable.” |
https://vizhub.com/bsarfo/de65e41bff6a4c3eba54992b263e1dc9, So, in week 9, I combine insights into a more cohesive dashboard. Adding annotations and highlighting key findings, which display top-selling models, regional differences and country-specific sales volume

## Week 10
So for week 10 I added an interactive scatter plot to visualize how sales vary from year to year, showing the types of BMW cars with the highest sales across different countries. Each bubble represents a country, with its color indicating the type of cars and its sales volume reflecting popularity. The visualisation also includes checkbox filters that let users toggle sales on or off, dynamically updating the chart to focus on specific countries.
https://vizhub.com/bsarfo/368d3fb0366c4af4bb996f6185e2aa28 
I also combine insights into a more cohesive dashboard. Adding annotations and highlighting key findings, top-selling models, regional differences, total sales volume, average selling price, and yearly sales trend
https://vizhub.com/bsarfo/3b706d93b27048c7a9a72e3df3286b92 
(https://vizhub.com/bsarfo/552194b3e4e64f9188be2a3e222d5bf0 
https://vizhub.com/bsarfo/a53951033cae4f9d926d20fae8bc5bba
I also added a Bar Chart with Hover of the year with the highest volume of BMW Sales, which was inspired by Prof Curren's week 10 lecture 
https://vizhub.com/bsarfo/3648eb96ce2a43ae9dbdc9aacfa848d1 
Details shown below
)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/daa88fd4731f5467cdffcdfa490790ed054843d3/Bar%20Chart%20of%20Sales%20volume.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/ccc6895dc7c8d66d11ae69798d72a5c87ddfcbcf/Scatter%20plot%20with%20hover.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/641d0eaf83ced4c6fcd42707ba815178448adf30/Peak%20year%20Bar%20Chart%20with%20Hover.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/32c6f8bbb3dd42829b80076a275607998a1afbf6/Interactive%20Stacked%20Bar%20Chart%20with%20Drop%20down%20menu.png)
## Week 10 dashboard
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/4f1fdf1cce5bc2f89a2956bc96ad3bbbfb87629a/BMW%20SALES%20ANALYTICS.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/e3f6865d036f652a23ee4561b77170a898ea1a84/SALES%20VOLUME%20BY%20COUNTRIES%20LINE%20CHART.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/9b82dff8e475a15218e6a659187f9484bf7f280c/TOP%2010%20SELLING%20MODELS%20and%20Regional%20sales%20distribution.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/43cbf99b5b9e7239992f0b893ca22cdc37d92ae2/sales%20by%20fuel%20and%20yearly%20sales%20trend.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/bd7a3d9a543b8aa2c27e6b479b59b1318daf99eb/KEY%20FINDINGS.png)

## Open Questions

I am confident about the project's direction, but I do have a few concerns. Since the dataset is synthetic, I’m not sure how realistic some fields (like mileage or sales classification) are, which may affect the authenticity of insights. I also want to explore regional differences, but I may not have access to detailed geographic shapes or data for mapping. Finally, while I’ve sketched interactive ideas like hover-tooltips and filters, I’m uncertain about how smoothly I can implement them in D3.js. These challenges may require me to simplify some aspects, but they will also push me to learn through iteration.

## Milestones

Week 1: Define project scope, document dataset fields, and draft initial research questions. Create first static sketches (bar chart practice with population data).

Week 2-3: Clean and explore the BMW dataset. Generate descriptive statistics and begin simple visualizations (bar chart of top models, line chart of total sales by year).

Week 315: Develop refined sketches and prototype visualizations. Experiment with different encodings (colors, labels, highlights) and iterate on clarity.

Week 4-7: Introduce interactivity (hover-tooltips, sorting, filtering) using VizHub or D3.js. Connect prototypes to BMW dataset instead of practice data.

Week 9 -10: Combine insights into a more cohesive dashboard. Add annotations and highlight key findings (e.g., top-selling models, regional differences).

Week 12: Polish visuals, finalize README writeup, and ensure interactivity works smoothly. Prepare final submission with a clear narrative linking research questions to visualizations and insights.
