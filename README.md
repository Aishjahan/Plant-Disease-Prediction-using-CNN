Plant Disease Prediction using CNN
==================================

This project aims to develop a deep learning model that can classify various plant diseases using a Convolutional Neural Network (CNN). The model leverages image data of plant leaves, training the network to identify disease patterns and classify them accurately into different categories.

The system processes images of plant leaves, extracts relevant features through convolutional layers, and classifies them into specific disease categories using a fully connected layer. The project leverages modern techniques in image classification, which are critical for automating plant disease detection.

Demo
-----

![Plant Disease Classification Model](Screenshot_2024-12-03_125238.png)

![Plant Disease Classification Model](Screenshot_2024-12-03_125257.png)



Features
--------

*   **Upload an image** of a plant leaf affected by a disease.
    
*   **Model predicts** the disease using a pre-trained CNN model.
    
*   **Streamlit** app for easy interaction.
    
*   **Classifies plant diseases** based on a custom dataset.
    
*   **Pre-trained model** and class indices included in the repository.
    

Prerequisites
-------------

Before running the project, make sure you have the following installed:

*   Python 3.10 or above
    
*   pip for installing Python packages
    

Installation
------------

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/plant-disease-prediction.git
    ```
    
2.  Create a virtual environment (optional but recommended):
    ```bash
    python3.10 -m venv venv
    source venv/bin/activate  # For Linux/macOS
    venv\Scripts\activate     # For Windows  
    ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

Files in the Repository
-----------------------

*   `main.py` : The main Python script that runs the Streamlit app.
    
*   `trained\_models/plant\_disease\_prediction\_using\_CNN.h5` : The pre-trained CNN model file.
    
*   `class\_indices.json` : A JSON file that maps the predicted class indices to plant disease names.
    
*   `requirements.txt` : Python dependencies for the project.
    

Usage
-----

1. ```bash streamlit run main.py```
    
2.  Open the app in your web browser (usually at `http://localhost:8501`).
    
3.  Upload an image of a plant leaf, and click **Classify** to see the predicted disease.
    

Model Training (Optional)
-------------------------

If you want to train your own model, follow these steps:

1.  Prepare a dataset with images of plant leaves labeled with their corresponding diseases.
    
2.  Train a CNN model using the TensorFlow/Keras library.
    
3.  Save the trained model as `plant\_disease\_prediction\_using\_CNN.h5`.
    
4.  Update the `class\_indices.json` file to reflect the new class names.
