# Data Visualization Project
Understanding how sales evolve, across regions, and across product lines is crucial for companies like BMW as they navigate global markets. This project analyzes BMW Sales Data (2010–2024) using interactive, web-based visualizations built in D3.js on VizHub.
Over twelve weeks, I moved from initial sketches to fully interactive dashboards, experimenting with maps, stacked bar charts, animated scatterplots, and multi-line charts. What began as exploratory practice evolved into a cohesive analytics tool designed to surface meaningful insights for business decision-making.
This report walks through that journey, from the dataset, to design decisions, to prototypes, to the final dashboard—serving as both documentation and portfolio piece.

## Dataset Overview
The dataset used is the BMW Sales Data (2010–2024), comprising 50,000 entries. It is provided in CSV format for this course. Comparable public datasets also exist (e.g., BMW Sales 2010–2024 on Kaggle
).
Key Fields:
Year
Model
Country / Region
Color
Fuel_Type
Transmission
Engine_Size_L
Mileage_KM
Price_USD
Sales_Volume
Sales_Classification
This diversity enables multi-dimensional insights: trends over time, geographic patterns, product performance, and customer preferences.

## Data Analysis Plan
Data Cleaning – Address missing values, duplicates, and inconsistencies.
Exploratory Data Analysis (EDA) – Use descriptive statistics and visual summaries to explore trends.
Visualization Prototypes – Apply different techniques (bar charts, line charts, scatter plots, stacked bars) to answer the research questions.
Marketing Insights Extraction – Translate findings into actionable insights for marketing and strategic positioning.

## Questions & Tasks
The project explored the following research questions:
1. Sales Trends Over Time
How have BMW’s global sales evolved across 15 years?
2. Model Performance
Which models dominate? How does their momentum shift?
3. Regional Differences
Which countries and regions drive BMW’s sales?
4. Customer Preferences
Are characteristics like engine size, price, or color correlated with high sales?
5. Strategic Implications
What can marketing managers and production teams learn from these patterns?

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

## Week 11 task
In week 11, I made the colour legend display on top of the stacked bar chart, showing the model of BMW cars under consideration,
making the stacked bar chart more interactive. making it clickable and adding hovers such that when a colour legend is selected all other colors disappear.
Prof Curren's Week 10 notes inspired this.
Additionally, I created a hoverable, multi-coloured line graph of sales by Region, Similar to a bar chart. I also created a multi-line graph for each country in question, making them hoverable. I also made the BMW sales world map rotatable.
Attached are detailed links to the weeks notes:
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/b0d96a20964df1772a3a2b582dfdfe1e07d865ad/BMW%20Global%20Sales%20Analytics%20Dashboard.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/ce5d4396eba70751e6cb527cdb665b3687dbd911/Rotatable%20world%20map.png)
https://vizhub.com/bsarfo/96ec0b61c2a144858da3b56b129da40f
https://vizhub.com/bsarfo/755f0398cfad41eb820356c89cacd053

## Week 12 task
For this week’s visualization update, I transformed the BMW sales dataset into a fully animated bubble chart that progresses year by year, similar to the dynamic style in a course member's work about volleyball analysis I found so captivating. Each (country, model) combination is now represented by a persistent bubble that smoothly transitions across years, with size mapped to sales volume and a double-ring visual style for clarity. I also added interactive country checkboxes, tooltip enhancements, and a cleaner legend to give users more control and interpretability. Overall, the chart is now more engaging, visually consistent, and analytically insightful compared to previous versions.
https://vizhub.com/bsarfo/0be35af995e34f408ef5494caf139149
https://vizhub.com/bsarfo/af0bcb685bd3442e9547f3008cff38ff
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/ec711cb069379ef515274277050c2c1c649c23ff/A%20Circle%20Bubble%20of%20BMW%20Sales.png)
In brief this week, I refined: Colour legend placement, Label clarity, Hover behaviour, Layout and typography for readability, and I also added annotations summarising insights directly in the dashboard. The attached link is a brief video discription https://youtu.be/dhEVM67VyzQ

## Week 13
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/c69c764ea53b8797f14e7dc2cfc3ec1fff3e12de/BMW%20SALES%20DASHBOARD%2011.21.png)
![image alt](https://github.com/bsarfo/dataviz-project-template-proposal/blob/master/BMW%20REGIONAL%20SALES%2011.21.png)
![image alt]()
https://vizhub.com/bsarfo/54a9fdfc0c2c452bbba8d1bcf280d9e9, https://vizhub.com/bsarfo/8583151136bc41e68febeb7d145e7f48, https://vizhub.com/bsarfo/627bcb7ae3504a4293294cb4398ea382, https://vizhub.com/bsarfo/eb041619509e43038cac046c2fee75c9
## Pre-Final Dashboard: BMW Global Sales Insights (2010–2024)
The completed dashboard includes:
A. Overview Panel
Stacked bar chart showing BMW’s global sales distribution over time.
B. Regional Trend Lines
Compare long-term growth across key markets.
C. Model Leaderboard
Top-selling models in 2024.
D. Market Share Snapshot
Pie or doughnut chart summarising regional shares.
E. Dynamic Scatterplot
Interactive bubble chart showing model popularity across countries.
F. Country-Level Line Charts
Detailed decade-long trend by region and country.
G. Global Heatmap
Rotatable world map showing geographic performance.
<img width="1892" height="651" alt="Image" src="https://github.com/user-attachments/assets/4bd7bbc0-16dd-470f-8895-55d3d06f33f4" />
https://vizhub.com/bsarfo/a3dcbe93a6f14d63a6a3dc562c149df5

## Next Steps

If time permits, potential enhancements include:
1. Animated transitions between dashboard sections
Switching views smoothly (e.g., bar → map → scatter).
2. Full map drill-down
Country → city → dealership → model.
3. Cross-filtering (Brushing & Linking)
Clicking a model filters all charts simultaneously.
4. Predictive Layer
Adding simple forecasting (ARIMA, linear regression).
These are outside the immediate scope but align with real-world BI dashboards.

## Conclusion
This project reflects a complete journey from exploratory sketches to a multi-layered analytical dashboard. It demonstrates skills in:
D3.js
Data cleaning and modeling
Interaction design
Visual storytelling
Iterative design refinement
The final product serves as a portfolio-quality artifact showcasing both technical and analytical capabilities.

## Open Questions
I am confident about the project's direction, but I do have a few concerns. I want to explore regional differences, but I may not have access to detailed geographic data or maps. Finally, while I’ve sketched interactive ideas like hover-tooltips and filters, I’m uncertain about how smoothly I can implement them in D3.js. These challenges may require me to simplify some aspects, but they will also push me to learn through iteration.

## Milestones
Week 1: I defined project scope, documented dataset fields, and drafted initial research questions. I then created the first static sketches (bar chart practice with population data).
Week 2-3: Clean and explore the BMW dataset. Generate descriptive statistics and begin simple visualizations (bar chart of top models, line chart of total sales by year).
Week 3-5: Develop refined sketches and prototype visualizations. Experiment with different encodings (colors, labels, highlights) and iterate on clarity.
Week 4-7: Introduce interactivity (hover-tooltips, sorting, filtering) using VizHub or D3.js. Connect prototypes to BMW dataset instead of practice data.
Week 9 -10: Combine insights into a more cohesive dashboard. Add annotations and highlight key findings (e.g., top-selling models, regional differences).
Week 11-12: Polish visuals, finalize README writeup, and ensure interactivity works smoothly. Prepare final submission with a clear narrative linking research questions to visualizations and insights. In week 13, I incorporated colleagues' suggestions for improvement, which prompted me to purse the chart height so it could fit more bubbles when it became crowded but after the attempt I realized that it was a great suggestion but that need does not quite fit well with the needs of my dataset. However, I implemented her quest for me to add other layers of visualization. In doing this I refacted a stacked bar chart with movable filters, and made sure all bugs are removed, colors improved and looking more interactive with hovers and bubbles.
