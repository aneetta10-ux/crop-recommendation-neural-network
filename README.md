# crop-recommendation-neural-network
Crop recommendation using a neural network with ReLU and tanh activation functions.
# Crop Recommendation Using Neural Network

## Project Description
This project uses a neural network to recommend suitable crops based on soil nutrients and environmental conditions.

## Dataset
- Total samples: 2,200
- Input features: 7
- Crop categories: 22

### Input Features
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall

## Model Development
Two neural network models were developed to compare ReLU and tanh activation functions.

The models contain:
- Input layer: 7 features
- Hidden layer 1: 16 neurons
- Hidden layer 2: 8 neurons
- Output layer: 22 neurons with Softmax activation

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras
- Gradio

## Results

| Model | Test Accuracy |
|---|---:|
| ReLU | 96.14% |
| tanh | 93.86% |

The ReLU model achieved better test accuracy in this experiment.

## How to Run
1. Download the project notebook.
2. Open it in Google Colab.
3. Upload the required dataset.
4. Run the notebook cells in order.
5. Launch the Gradio interface to get crop recommendations.
