# California-Wildfire-Prediction

This project aims to predict wildfire hotspots using advanced feature engineering and LightGBM, a gradient boosting framework. By analyzing California wildfire data from 2000 to 2022, we implement a binary classification model to identify areas with a high probability of experiencing wildfires. Our approach emphasizes spatial precision, temporal context, and the utilization of historical wildfire occurrences to enhance prediction accuracy.

## Project Overview

Wildfires pose significant ecological, economic, and social threats. Early identification of potential hotspots can help in mitigating these risks through targeted management and resource allocation. Our solution leverages detailed feature engineering and the LightGBM algorithm to classify regions as potential wildfire hotspots based on historical data.

### Key Features

- **Advanced Feature Engineering:** Reduction of spatial resolution and incorporation of temporal features to capture localized and temporal patterns of wildfires.
- **Binary Classification with LightGBM:** Utilizing LightGBM for efficient and effective hotspot prediction.
- **Historical Context Integration:** Analysis of fire occurrence patterns over the past two decades to identify probable hotspot areas.

## Dataset

The dataset includes California wildfire incidents from 2000 to 2022, featuring:
- Date
- Longitude
- Latitude
- Confidence Level
- Satellite Information
- Instrument Used

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- pandas
- numpy
- lightgbm
- scikit-learn

## Model
The model is trained using data from 2000 to 2019, validated on 2020-2021 data, and tested on 2022 data. It predicts whether a given location is a potential wildfire hotspot based on the engineered features.

## Evaluation
The model is evaluated on precision, recall, F1-score, and accuracy metrics to assess its performance in identifying wildfire hotspots.

## Output
![Alt text](/screenshot.jpeg?raw=true "Optional Title")
