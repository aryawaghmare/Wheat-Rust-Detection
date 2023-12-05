# Wheat Rust Detection

## Overview
This project aims to detect wheat rust in agricultural images using computer vision techniques. Wheat rust is a common disease affecting wheat crops, and early detection can help farmers take timely preventive measures.

## Features
- **Image Classification**: Utilizes a trained model to classify images as either infected or healthy wheat.
- **Albumentations**: Applies image augmentation techniques to improve model generalization.
- **Streamlit Web App**: Provides a user-friendly interface for uploading and testing images.

## Libraries Used
- **PyTorch**: Deep learning framework for building and training the wheat rust detection model.
- **Albumentations**: Image augmentation library for preprocessing input images.
- **Streamlit**: Web app framework for creating an interactive user interface.
- **OpenCV**: Computer vision library for image processing.
- **PIL**: Python Imaging Library for handling image data.
- **NumPy**: Library for numerical operations in Python.

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Streamlit app: `streamlit run app.py`
3. Upload an image through the web interface to get the wheat rust detection result.

## Project Structure
- `app.py`: Streamlit web app for user interaction.
- `model.py`: Defines the wheat rust detection model.
- `utils.py`: Utility functions for image processing and model inference.

## Data
The model was trained on a dataset of wheat images containing both infected and healthy samples. Due to data sensitivity, the dataset used for training is not included in this repository.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The model architecture is based on [EfficientNet](https://github.com/lukemelas/EfficientNet-PyTorch).

Feel free to contribute, report issues, or provide suggestions to enhance the wheat rust detection model!
