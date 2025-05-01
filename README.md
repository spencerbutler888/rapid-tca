# rapid-tca

Spencer Butler  
May 2025

## Overview

**Rapid TCA** is a Jupyter Notebook that performs on-demand trade cost analysis (TCA) for US equity orders when such analysis is not available through an order management system (OMS) or third-party provider. The tool ingests fill-level execution data, enriches it with market data, and computes trading performance metrics to provide immediate, high-level feedback on execution quality.

## Key Features

- **Completion Rate**
- **Percentage of Volume**
- **Implementation Shortfall**
- **Interval VWAP Comparison**
- **Venue Analysis**

## File Contents

- `rapid_tca.ipynb` – Main Jupyter Notebook that reads, enriches, analyzes, and visualizes trade execution data.
- `Rapid TCA.pdf` – Short write-up describing the purpose of the tool, the key metrics, and how to interpret the results.

## Tools & Technologies

- **Python:** Data analysis and visualization with `pandas` and `matplotlib`
- **Bloomberg API:** Market data access via `xbbg`

## Disclaimer

- Example data is randomly generated and does not reflect real trades.
- This project does **not** constitute investment advice.
