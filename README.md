# Glacier Centerline Extraction using OGGM

This repository contains a Jupyter Notebook (`centerline.ipynb`) that demonstrates how to extract glacier centerlines using the [OGGM (Open Global Glacier Model)](https://oggm.org/) framework. It is primarily intended for glacier research and educational use, particularly in glaciological applications such as mass balance and flowline modeling.

## Contents

- `centerline.ipynb`: A step-by-step notebook showcasing how to:
  - Set up OGGM
  - Download and preprocess glacier data
  - Compute centerlines of selected glaciers
  - Visualize glacier outlines and centerlines

## Getting Started

### Requirements

Make sure you have the following Python packages installed:
- `oggm`
- `matplotlib`
- `geopandas`
- `xarray`
- `shapely`
- `pyproj`

You can install OGGM and its dependencies using:
```bash
pip install oggm
