## Project Description
This project aims to build a machine learning model that can recognize hand gestures such as rock, paper, scissors, spock, and lizard using TensorFlow.js and a webcam.

## Objective
The objective of this project is to develop a model capable of recognizing various hand gestures.

## Tools and Methodologies
- **TensorFlow.js**: A library for building and training neural network models.
- **MobileNet**: A pretrained model used for feature extraction.
- **Webcam**: Used to capture real-time images of hand gestures.
- **RPSDataset**: A class to manage training data and labels.

## Approach and Process
1. **Preparation**: Set up the webcam and load the pretrained MobileNet model.
2. **Data Collection**: Collect sample images of hand gestures with various labels (rock, paper, scissors, spock, lizard).
3. **Dataset Formation**: Convert the collected data into a format suitable for training the model.
4. **Model Building**: Configure the neural network architecture using appropriate layers for classifying hand gesture images.
5. **Training**: Train the model using the collected data and the Adam optimizer.
6. **Evaluation**: Evaluate the model's performance using appropriate metrics.
7. **Prediction**: Integrate the model into an application to predict labels from real-time hand gesture images.
8. **Optimization**: Optimize the model and training process to improve performance and efficiency.

## Results
- The trained model can recognize various hand gestures with adequate accuracy.
- The application integrating this model can provide quick and accurate responses to user hand gestures.

## How to Run the Project
Clone this repository:
   ```bash
   git clone https://github.com/gardakhoerunnisa/Pengenalan-Gestur-Tangan-dengan-TensorFlow.git
