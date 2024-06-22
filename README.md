# Air Traffic Prediction Model

## Overview

Welcome to the Air Traffic Prediction Model repository. This project demonstrates a data-driven approach for predicting airspace sector demand and aircraft positions in Brazilian airspace. Leveraging high-resolution radar synthesis data along with flight tracks, weather conditions, and air traffic flow management restrictions, this model aims to enhance air traffic flow and capacity management.

## Features

- **Two-Step Prediction Process**: Determines if an aircraft has landed and predicts its latitude and longitude if still in flight.
- **Machine Learning Techniques**: Utilizes XGBoost, Random Forests, and Artificial Neural Networks for high-accuracy predictions.
- **Robust Evaluation**: Tested under various scenarios including high traffic periods, public holidays, and adverse weather conditions to ensure reliability.
- **High-Resolution Radar Data**: Integration of detailed radar data to enhance predictive accuracy.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries: numpy, pandas, scikit-learn, xgboost, keras, matplotlib, plotly

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/air-traffic-prediction.git
    cd air-traffic-prediction
    ```

2. Install the required Python libraries:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook Air_Traffic_Prediction_Model.ipynb
    ```

2. Follow the instructions within the notebook to run the model. The notebook includes cells for data loading, preprocessing, model training, and evaluation.

### Dataset

The dataset includes:
- High-resolution radar synthesis data
- Flight tracks
- Weather conditions
- Air traffic flow management restrictions

Ensure that you have access to these datasets and have placed them in the appropriate directory as specified in the notebook.

## Results

The results demonstrate that the data-driven approach significantly outperforms baseline models relying on mean velocity estimates. Key findings include:
- Superior performance of the XGBoost model in predictive accuracy for both landing predictions and position estimations.
- Robustness and adaptability of the models under challenging conditions.
- Substantial benefits of integrating high-resolution radar data for improved predictive accuracy.

## Future Work

Future improvements could focus on:
- Retraining the models using the full resolution of radar data.
- Incorporating more training data, especially for near-landing predictions.
- Applying reinforcement learning to enable continuous adaptation to new data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

This project was developed as part of a thesis on predictive modeling in air traffic management. Special thanks to ICEA for providing the computational resources necessary for this work.
