# Handwritten Digit Recognition App

This project demonstrates a **Handwritten Digit Recognition** app built using a pre-trained neural network on the **MNIST** dataset. The app allows users to either view predictions for random images from the dataset or upload their own images to classify digits in real-time.

## Features

- **Random MNIST Test Predictions**: The app selects random images from the MNIST test set and predicts the digit.
- **Upload Your Own Image**: Users can upload their own handwritten digit images, and the app will predict the digit using the trained model.
- **Interactive Interface**: The app is built with **Streamlit**, providing an intuitive and user-friendly interface.
  
## Live Demo

Check out the live demo of the app [here](https://cyberfantics-handwritten-digit-recognization-app-bhp9rc.streamlit.app/).

## How to Use

1. **Random Predictions**: Use the slider on the sidebar to select the number of images (from 1 to 20) to view and predict.
2. **Upload Your Own Image**: Upload a grayscale image of a handwritten digit (28x28 size preferred), and the model will predict the digit.

## Installation

To run the app locally, follow these steps:

   ```bash
   git clone https://github.com/cyberfantics/handwritten-digit-recognization.git
   cd handwritten-digit-recognization
   pip install -r requirements.txt
   streamlit run app.py
   ```

## Project Structure
- **app.py:** The main Streamlit app file.
- **model/mnist_model.keras:** Pre-trained neural network model for digit classification.
- **requirements.txt:** List of required Python packages.

## Developer
Developed by Syed Mansoor ul Hassan Bukhari.

## Links

- [GitHub Repository](https://github.com/cyberfantics/handwritten-digit-recognization)
- [Live App Demo](https://cyberfantics-handwritten-digit-recognization-app-bhp9rc.streamlit.app/)
