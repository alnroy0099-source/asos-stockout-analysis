# asos-stockout-analysis
# ASOS Product Stock-Out & Phantom Revenue Analysis

## Project Overview
This project analyses ASOS product listings to explore product availability, brand representation, and potential revenue opportunities associated with unavailable clothing sizes.

## Business Objectives
- Identify brands represented in the product dataset.
- Compare product counts across brands.
- Identify clothing sizes explicitly marked as out of stock.
- Analyse stock-out patterns by brand.
- Estimate potential phantom revenue associated with unavailable sizes.
- Present findings through data visualisations.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Regular Expressions
- Google Colab

## Methodology
1. Loaded and explored the product dataset.
2. Cleaned and prepared the data using Pandas.
3. Extracted brand names from product URLs.
4. Identified sizes explicitly labelled as out of stock.
5. Aggregated stock-out metrics by brand.
6. Estimated potential phantom revenue using product prices and unavailable size counts.
7. Created charts to communicate the findings.

## Key Business Metric: Estimated Phantom Revenue
The analysis uses a simplified estimate based on product price multiplied by the number of sizes explicitly marked as out of stock, assuming one hypothetical lost sale per unavailable size.

**Important limitation:** This is an illustrative proxy, not verified lost revenue. It does not account for customer substitution, actual demand, conversion rates, or whether an unavailable size would have resulted in a sale.

## Key Findings

- Brand with the highest number of listed products: Asos design
- Brand with the highest number of explicitly out-of-stock sizes: Asos design
- Total estimated phantom revenue: £351,820.88
- Most important business insight:
  ASOS Design has the highest number of listed products and explicitly out-of-stock sizes, suggesting that stock availability may be an important area to   investigate for this brand. The analysis estimates a potential phantom revenue opportunity of £351,820.88 across the dataset, highlighting the possible commercial value of monitoring size-level stock-outs and improving inventory management. However, this figure is a hypothetical estimate rather than confirmed lost revenue.
## Repository Contents
- ASOS_Stockout_Analysis.py — notebook containing the analysis, calculations, and visualisations.
- products_asos_sample.csv — source dataset( this is the sample data set not the whole dataset)

## Disclaimer
This is an independent data analytics portfolio project. The estimated metrics are based on the available dataset and assumptions and should not be interpreted as actual ASOS financial results.
