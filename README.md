# FUGW Network Analyzer

This project performs **network resilience analysis** using **Fused Unbalanced Gromov-Wasserstein (FUGW)** metrics to evaluate how the removal of edges affects network structure and node demands.

## Features
- Computes shortest-path distance matrices.
- Analyzes critical edges via FUGW across multiple alpha values.
- Parallel processing for speed.
- Generates detailed visualizations:
  - Critical edge maps
  - FUGW heatmaps and line plots
  - Distribution, ranking, and correlation analyses

## Requirements
Install dependencies:
```bash
pip install -r requirements.txt
