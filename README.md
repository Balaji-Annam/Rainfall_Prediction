Rainfall Prediction Overview

Rainfall is a vital part of the Earth’s water cycle, occurring when water vapor condenses and falls as precipitation. 
It is influenced by factors such as temperature, humidity, pressure, and wind, and is typically measured in millimeters (mm). 
Accurate rainfall prediction is important for agriculture, flood management, and climate studies.
Rainfall data is inherently spatio-temporal, meaning it varies across both location and time, making prediction a complex task.

Algorithms Used

This project uses two deep learning models to capture rainfall patterns:

ConvLSTM (Convolutional LSTM)

Combines convolutional layers and LSTM
Captures both spatial (location-based) and temporal (time-based) features
Suitable for grid-based weather data

TCN (Temporal Convolutional Network)

Uses dilated causal convolutions
Captures long-range temporal dependencies
Faster and more stable than traditional RNN models
