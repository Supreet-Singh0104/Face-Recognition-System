Here's the updated README file with your repository URL:

---

# Face Recognition System

This project implements a face recognition system using OpenCV and Haar Cascade classifiers. The system can detect faces from a live camera feed and recognize them.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Dependencies](#dependencies)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/Supreet-Singh0104/Face-Recognition-System.git
    cd Face-Recognition-System
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Ensure you have OpenCV installed. If not, install it using:
    ```sh
    pip install opencv-python
    ```

## Usage

1. **Face Detection**:
    - Run the `Camera-OpenCV.ipynb` notebook to start the camera and detect faces.
    - The notebook uses the Haar Cascade classifier provided in the `haarcascade_frontalface_alt.xml` file to detect faces.

2. **Face Recognition**:
    - Run the `Final Face Reco.ipynb` notebook for face recognition.
    - Ensure you have pre-processed data for the faces you want to recognize.

## File Descriptions

- `Camera-OpenCV.ipynb`: Jupyter Notebook to capture video from the camera and detect faces using Haar Cascade classifiers.
- `Final Face Reco.ipynb`: Jupyter Notebook to perform face recognition.
- `haarcascade_frontalface_alt.xml`: Haar Cascade classifier for face detection.

## Dependencies

- OpenCV
- NumPy
- Matplotlib (optional, for visualization in notebooks)
- Jupyter Notebook

## Acknowledgements

This project utilizes the OpenCV library and the Haar Cascade classifier provided by Intel Corporation. Special thanks to Rainer Lienhart for creating the Haar Cascade classifier used in this project.

