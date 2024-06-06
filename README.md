# Face Detection Application

A simple face detection application using OpenCV and Streamlit for real-time face detection through a webcam.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Notes](#notes)

## Introduction

This project provides a real-time face detection application using OpenCV for image processing and Streamlit for creating an interactive web interface. It captures video from your webcam and uses a pre-trained Haar Cascade classifier to detect faces.

## Features

- Real-time face detection through webcam.
- Simple and interactive user interface using Streamlit.
- Easy to set up and run.
- Uses Haar Cascade classifiers for face detection.

## Dependencies

The main dependencies required for this project are:

- Python 3.x
- OpenCV (`opencv-python`)
- Streamlit
- NumPy

All dependencies are listed in the `requirements.txt` file.

## Installation

To install the necessary dependencies, run the following command in your project directory:

```bash
pip install -r requirements.txt
```
## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Shreyaprasad21/A_Basic_Chatbot.git

2. Run the chatbot script:
      ```sh
   Chatbot.ipynb

3. Follow the prompts to interact with the chatbot. Type 'exit' to end the conversation.

## File Structure
- `Chatbot.ipynb`: Main script implementing the chatbot functionality.
- `dialogs.txt`: Dataset containing pre-stored general questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.
- `contractions.py`: Helper functions for handling contractions in text.
- `README.md`: Instructions and information about the project.
- `LICENSE`: License information.

## Deployment

1. Start the chatbot by running:
  ```
  python Chatbot.ipynb
  ```

2. Interact with the chatbot in the console. Type 'exit' to end the conversation.

## Notes
- The project was developed using Python, with the main chatbot functionality implemented in `Chatbot.ipynb`.
- `nlp_utils.py` contains helper functions for text normalization.
- The dataset (`dialogs.txt`) is provided and contains sample questions and responses.
- Sentiment analysis and word cloud visualization are integrated into the chatbot.
- TF-IDF vectorization is used to match user queries with stored questions.
- The project can be extended to cover more queries and provide more detailed responses.
