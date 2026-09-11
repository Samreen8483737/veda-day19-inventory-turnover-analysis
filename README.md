# Day 19: Inventory Turnover Analysis

## Objective
Analyze stock movement and calculate inventory turnover ratios to evaluate supply chain efficiency and identify slow-moving products.

## Technical Implementation
Utilized Google Sheets to process raw inventory data and execute standard supply chain efficiency formulas.
1. **Average Inventory Baseline:** Calculated the average stock held over the period using the formula `= (Beginning_Inventory + Ending_Inventory) / 2`.
2. **Turnover Ratio:** Calculated the velocity of sales by dividing `Units_Sold` by the calculated `Avg_Inventory`.
3. **Threshold Identification:** Established a baseline ratio of 4.0. Any product falling below this threshold was flagged for inefficiency. 

## Analysis & Findings
* **Highest Performer:** Printer Paper demonstrated the highest inventory efficiency with a turnover ratio of 8.0, indicating strong, consistent sales relative to stock held.
* **Slow Mover Identified:** The **Standing Desk** was identified as a critical slow-mover, registering a turnover ratio of just 3.0. 
* **Business Recommendation:** The slow-moving Standing Desks represent tied-up capital and excess warehouse holding costs. I recommend the marketing team run a targeted discount campaign to liquidate this stagnant inventory and free up warehouse space for higher-velocity items like the Laptop Pro or Printer Paper.
