# ImageXclassY
Image Classification using CNN Model 

This is a innovative Streamlit application seamlessly integrates the powerful MobileNetV2 and CIFAR-10 models for advanced image classification. Users can effortlessly upload their images and receive detailed predictions along with confidence scores from either model. The app boasts a sleek and intuitive navigation bar, allowing for easy switching between models and real-time results. This makes it an ideal tool for both learning and practical applications, providing a user-friendly experience for all.

## Key Features

- **Dual Model Support**:
  - **MobileNetV2 (ImageNet)**: Recognizes 1,000 different classes from the ImageNet dataset, including everyday objects, animals, and vehicles.
  - **Custom CIFAR-10 Model**: Specializes in classifying images into one of ten specific categories such as airplanes, automobiles, and birds.

- **Intuitive Interface**:
  - **Navigation Bar**: TO switch between MobileNetV2 and CIFAR-10 models using a sleek sidebar menu.
  - **Real-Time Classification**: Upload an image to receive immediate predictions with confidence scores.

- **Educational and Practical Use**:
  - Ideal for learning about deep learning models and their performance.
  - Useful for practical applications where image classification is needed for better performance.

## Getting Started ###

### Prerequisites

- Python 3.7 or later
- A web browser (Google Chrome, Mozilla Firefox, or equivalent to access the Streamlit interface.)

### Installation steps

1. **Create and activate a virtual environment**:
    #open cmd promot where the source code is saved
    python -m venv venv
    venv\Scripts\activate  #for Windows
2. **Install the required packages**:
    pip install -r requirements.txt

3. **Start the Streamlit app**:
    streamlit run app.py

4. **Open the app**: 
    The app will open in your default web browser. If not, navigate to http://localhost:8501


### Usage
  1. Use the navigation bar to select either the MobileNetV2 or CIFAR-10 model.
  2. Upload an image file (JPG or PNG or JPEG) FORMAT.
  3. View the classification results and confidence scores WITH ACCURACY VALUE.


### Acknowledgements
  - Streamlit
  - TensorFlow
