# Accident Severity Prediction

This repository contains the implementation of a machine learning pipeline to predict accident severity using the US Accidents dataset. The project involves data preprocessing, feature engineering, model training, optimization, and deployment.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

This project predicts the severity of traffic accidents using machine learning techniques. The primary goals include:

- Analyzing the factors influencing accident severity.
- Developing a predictive model to classify accidents by severity levels (1 to 4).
- Optimizing the model to reduce its size and deployment overhead.

## Dataset

The dataset used is the [US Accidents Dataset](https://example.com). It contains detailed information about traffic accidents in the United States, including:

- Temporal and spatial attributes.
- Weather conditions.
- Proximity to points of interest.
- Traffic control measures.

### Key Features

| Feature                | Description                                      |
|------------------------|--------------------------------------------------|
| Severity              | Accident severity (1: low, 4: high impact).      |
| Start_Time            | Start time of the accident.                      |
| Weather_Condition     | Weather at the time of the accident.             |
| Distance(mi)          | Distance affected by the accident.               |
| Traffic_Calming       | Presence of traffic calming measures.            |
| Visibility(mi)        | Visibility at the time of the accident.          |

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/kxngh/accident-severity-pred.git
   cd accident-severity-prediction
   ```

2. Set up a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```


## Results

- **Accuracy:** 85%
- **Model Size:** 900 MB after optimization.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

