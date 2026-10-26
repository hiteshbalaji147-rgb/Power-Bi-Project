# Contoso Sales Insights: Power BI Dashboard

An interactive Power BI report that analyses sales opportunities for the fictional company Contoso. It uses Power BI's AI visuals to explain **what drives won deals**, **where revenue comes from**, and **when revenue behaves unusually**.

> Data: Contoso sample sales data, as shown in the report. All figures are fictional and for learning purposes.

## Report pages

### 1. Key Influencers: what influences a deal to be Won?
![Key Influencers](images/1-key-influencers.png)

- Close rate by product category: Computers 75.6%, Furniture 71.2%, Software 64.4%, Electronics 53.1%.
- Revenue won by product is led by the Design app at about $10M.
- The Key Influencers visual shows that a higher discount is the strongest factor linked to winning a deal (2.76x likelihood per 0.02 increase in discount), followed by sales owner, product and campaign.

### 2. Decomposition Tree: where does revenue come from?
![Decomposition Tree](images/2-decomposition-tree.png)

- Total sales opportunity is $29.6M.
- Software is the largest category ($12.8M), and within it the Design app ($10.1M) is the biggest product.
- North America dominates the opportunity count (8.5K) and the Design app's regional revenue ($7.6M).
- Email is the top campaign type by sales opportunity ($4.0M).

### 3. Anomalies in Revenue Won
![Revenue Anomalies](images/3-revenue-anomalies.png)

- Time range: June 2020 to May 2021.
- Revenue won peaked in November 2020 at about $1.63M, and was lowest in July 2020 at about $1.25M.
- Includes a smart narrative summary and a Q&A box for natural-language questions.

## Power BI features used
- Key Influencers visual
- Decomposition Tree
- Line chart with an expected-range band to spot anomalies
- Smart narrative
- Q&A visual
- Slicers and date filters, custom navigation and branding

## Repository contents
```
/images   Screenshots of each report page
/report   PDF export of the full report
README.md
```
The `.pbix` source file can be added to a `/dashboard` folder.

## How to view
Open the PDF in `/report` or browse the screenshots above. If a `.pbix` file is included, open it in Power BI Desktop (free) to explore the interactive visuals.

## Author
Hitesh. Built as part of data analytics learning and portfolio work.
