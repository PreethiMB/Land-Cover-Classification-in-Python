# Land-Cover-Classification-in-Python
This project demonstrates a workflow for land cover classification in the Central Valley, California, leveraging Google Earth Engine (GEE) for cloud-based data access and preprocessing, combined with Python libraries such as geemap, rasterio, scikit-learn, and geopandas for local analysis and machine learning.

# Features
- Access and process Sentinel-2 imagery and ESA WorldCover data directly from the cloud without downloading large datasets locally.
- Compute spectral indices like NDVI and NBR to enhance classification performance.
- Sample training data from reference datasets and train a Random Forest classifier in Python.
- Export processed imagery from GEE and perform pixel-wise classification using scikit-learn.
- Conduct accuracy assessment using metrics such as overall accuracy, producer’s/user’s accuracy, and Kappa coefficient.
- Visualize classified maps and compare with reference land cover data.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Google Earth Engine Python API(https://developers.google.com/earth-engine/guides/python_install)
- geemap
- rasterio
- scikit-learn
- geopandas
- numpy
- matplotlib

Install required packages with:

```bash
pip install geemap rasterio scikit-learn geopandas numpy matplotlib

This project can be run either in Google Colab or a local Jupyter Notebook environment.



