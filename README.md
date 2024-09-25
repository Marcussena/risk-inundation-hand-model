# Inundation Risk Mapping with the HAND Model
This repository contains a Jupyter Notebook that demonstrates a workflow for mapping flood risk using the Height Above Nearest Drainage (HAND) model. The workflow is implemented in Python and focuses on assessing inundation risk in urban areas using Digital Elevation Models (DEM) and various hydrological tools.
## Workflow Overview
The notebook guides you through the following steps:

1. Data Preparation: Acquiring and preprocessing DEM data.
2. Flow Direction and Accumulation: Calculating flow direction and accumulation to delineate the drainage network.
3. Drainage Network Extraction: Identifying stream networks from the DEM.
4. HAND Model Calculation: Computing the HAND model to determine the height above the nearest drainage.
5. Flood Risk Classification: Classifying the area into different risk zones (low, medium, high) based on HAND values.
6. Visualization: Creating a flood risk map to visualize high-risk areas.
## Requirements
To run this workflow, the following Python libraries are required:

* matplotlib
* numpy
* richdem
* matplotlib
* whiteboxtools

You can install the dependencies using:
```
pip install -r requirements.txt
```
## Usage
1. Clone this repository:
```
git clone https://github.com/your-username/risk-inundation-hand-model.git
```
2. Open the Jupyter Notebook:
```
jupyter notebook inundation_risk_mapping.ipynb
```
3. Follow the step-by-step guide to map flood risks in your area of interest.
