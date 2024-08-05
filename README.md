
# OpenVINO Face Detection and Emotion Recognition Project

This project demonstrates how to use OpenVINO to perform face detection and emotion recognition on images and videos using Google Colab.

## Features

- Face detection using a pre-trained OpenVINO model.
- Emotion recognition using a pre-trained OpenVINO model.
- Support for processing images and videos.
- Annotated results saved as images or videos.
- Interactive user interface for uploading files and displaying results.


## Usage
### Google Colab
Open the notebook in Google Colab:
OpenVINO_Project.ipynb

Follow the steps in the notebook to install dependencies, download models, and run inference on images and videos.

### Local Setup
#### Install OpenVINO and dependencies:

pip install openvino
apt-get install -y libgtk2.0-dev
pip install numpy opencv-python-headless ipywidgets
#### Download the models:


wget -P models/ https://storage.openvinotoolkit.org/repositories/open_model_zoo/2021.4/models_bin/1/face-detection-0204/FP16/face-detection-0204.xml
wget -P models/ https://storage.openvinotoolkit.org/repositories/open_model_zoo/2021.4/models_bin/1/face-detection-0204/FP16/face-detection-0204.bin
wget -P models/ https://storage.openvinotoolkit.org/repositories/open_model_zoo/2021.4/models_bin/1/emotions-recognition-retail-0003/FP16/emotions-recognition-retail-0003.xml
wget -P models/ https://storage.openvinotoolkit.org/repositories/open_model_zoo/2021.4/models_bin/1/emotions-recognition-retail-0003/FP16/emotions-recognition-retail-0003.bin
#### Run the project:

Open the notebook notebooks/OpenVINO_Project.ipynb in your local Jupyter environment.
Follow the steps in the notebook to run inference on images and videos.
## Project Structure
models/: Contains the pre-trained models for face detection and emotion recognition.
images/: Example images for testing.
videos/: Example videos for testing.
notebooks/: Jupyter notebook for running the project.
README.md: Project documentation.
requirements.txt: List of required Python packages.
## Example
Image Processing

Video Processing


## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
OpenVINO
Google Colab

