# Brain Tumor Detection using Machine Learning

This project aims to detect brain tumors from MRI images using machine learning models. The application uses a Tkinter-based GUI to allow users to upload MRI images and get real-time tumor detection results.

## Features

- Preprocess and resize MRI images for consistent input to the machine learning model.
- Train Support Vector Machine (SVM) and Logistic Regression classifiers for brain tumor detection.
- Provide a user-friendly interface using Tkinter for easy image upload and prediction display.

## Dataset

The dataset contains 5712 MRI images of brain tumors categorized into four classes:
- No Tumor
- Pituitary Tumor
- Glioma
- Meningioma

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/nguyendinhhieu1309/Brain_Tumor_Detection.git
    cd Brain_Tumor_Detection
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Ensure the dataset is placed in the correct directory structure:
    ```
    brain_tumor
    ├── Training
    │   ├── notumor
    │   ├── pituitary
    │   ├── glioma
    │   └── meningioma
    ```

## Usage

1. Run the application:
    ```sh
    python brain_tumor_detection.py
    ```

2. Use the Tkinter interface to upload an MRI image and get the prediction result.
