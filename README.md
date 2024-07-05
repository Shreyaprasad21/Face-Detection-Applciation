# Streamlit Face Detection Application

This repository contains a Streamlit application for webcam-based face detection. The application uses OpenCV and a Haar Cascade classifier to detect faces from the webcam feed.

## Contents

- `LICENSE`: License file for the project.
- `README.md`: This file. Provides an overview of the project.
- `Streamlit_cam.py`: Main Streamlit application script.
- `haarcascade_frontalface_default.xml`: Haar Cascade XML file for frontal face detection.
- `webcam_cv3.py`: Python script for webcam operations using OpenCV3.

## Installation

1. Clone the repository:
    ```bash
    https://github.com/Shreyaprasad21/Face-Detection-Applciation.git
    cd Face-Detection-Application
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages

## Usage

1. To run the Streamlit application:
    ```bash
    streamlit run Streamlit_cam.py
    ```
    or
   ```
   python -m streamlit run Streamlit_cam.py
    ```

3. The application will start and can be accessed at `http://localhost:8501` in your web browser.

## Files Description

- **Streamlit_cam.py**: This is the main script for the Streamlit application. It initializes the webcam, captures the video stream, and applies the Haar Cascade classifier to detect faces.
- **haarcascade_frontalface_default.xml**: Pre-trained Haar Cascade model for detecting frontal faces.
- **webcam_cv3.py**: An alternative script for handling webcam feed using OpenCV3 directly. It can be used for testing and debugging purposes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
