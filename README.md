# Brain Tumor Detection using Deep Learning
![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=plastic&logo=numpy&logoColor=white) 
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23white.svg?style=plastic&logo=opencv&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=plastic&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=plastic&logo=scikit-learn&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-%23FF6F00.svg?style=plastic&logo=Tkinter&logoColor=white)
![OS](https://img.shields.io/badge/os-%23F7931E.svg?style=plastic&logo=linux&logoColor=white)

This project aims to detect brain tumors from MRI images using deep learning models. The application uses a Tkinter-based GUI to allow users to upload MRI images and get real-time tumor detection results.

## Features

- Preprocess and resize MRI images for consistent input to the deep learning model.
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
    pip install numpy pandas matplotlib scikit-learn opencv-python-headless Pillow
    ```

3. Ensure the dataset is placed in the correct directory structure:
    ```
    BrainTumorDetection
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
## Example
1. Use image test from computer
   ![image](https://github.com/nguyendinhhieu1309/Brain_Tumor_Detection/assets/163109800/21196894-473d-4fb3-97bf-4b5171b9dafd)

2. Use image from internet(google)
   ![image](https://github.com/nguyendinhhieu1309/Brain_Tumor_Detection/assets/163109800/8aebdc3b-b93d-4b9a-9c5a-57d2b7200718)

