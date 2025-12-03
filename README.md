# ca-quant

Quantify the results of ratiometric calcium imaging data at both a single cell and aggregate level.

## Overview

This repository provides a complete workflow for analyzing calcium imaging experiments. The pipeline is automated using a CellProfiler script, supports customizable calcium thresholding, and performs downstream analysis using R scripts.

## Workflow

1. **CellProfiler Automation**: Automated cell segmentation and intensity measurement using CellProfiler project files (`.cpproj`)
2. **Customizable Calcium Thresholding**: Flexible thresholding parameters to identify calcium-expressing cells
3. **R Script Analysis**: Downstream statistical analysis and visualization at both single-cell and aggregate levels

## Contents

- `CamilaV5_7_10_25.cpproj` - CellProfiler project for automated cell detection and measurement
- `CamilaV5_7_10_25_10_25_Update_additionalremove.cpproj` - Updated CellProfiler project with additional filtering
- `CamilaV5.Rmd` - R Markdown script for aggregate-level analysis and visualization
- `camila_ViolinV3_ (1).Rmd` - R Markdown script for single-cell analysis with mixed model statistics
