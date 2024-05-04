**Project Demo Video:**

[Watch the video demonstration](https://youtu.be/2doXGQKbA1I?si=UKmR_Y27c5m7rlJN)

Mango Disease Prediction CNN Deep Learning Project using Streamlit

Description:

This project tackles the challenge of accurately identifying and classifying mango diseases using a Convolutional Neural Network (CNN) deep learning model built with TensorFlow. The project leverages the power of Streamlit to create a user-friendly web application for real-time mango disease prediction.

Key Features:

CNN-based Disease Classification: A robust CNN model trained on a comprehensive dataset of mango disease images is employed to effectively distinguish between healthy and diseased mangoes, along with various disease.

Streamlit Web Application: The project provides a user-friendly interface for seamless interaction. Users can simply upload mango images, and the model will deliver real-time predictions.
Getting Started:

Prerequisites:

Python 3.10
TensorFlow
Streamlit

Installation:

Clone this repository: git clone https://github.com/<your-username>/Mango_disease_prediction_cnn_deepleanring_project_using_streamlit.git
Navigate to the project directory: cd Mango_disease_prediction_cnn_deepleanring_project_using_streamlit
Create a virtual environment: python -m venv env 
Activate the virtual environment: source env/bin/activate 
Install dependencies: pip install -r requirements.txt 
Data Preparation :

Download the mango disease image dataset 
Ensure the data is organized in a compatible format 
Explore data preprocessing steps in the provided code .
Training the Model :

Run the training script: python train.py 
This script might take some time depending on the dataset size and hardware.
Monitor training progress (loss, accuracy) through visualizations or logging.
Run the Streamlit App:

Start the Streamlit app: streamlit run app.py (or the script name for your app)
This will launch the web app in your default browser (usually at http://localhost:8501).
Usage:

Upload a mango image using the file upload widget in the Streamlit app.
The model will process the image and predict the disease, if any.
The predicted disease class will be displayed on the app.
Customization:

Fine-tune the hyperparameters of the CNN model for potentially better performance (learning rate, optimizer, etc.).
Experiment with different deep learning architectures for CNNs.

Enhance the Streamlit app interface with additional features (image preprocessing options, disease descriptions, etc.).

Kaggle Dataset Link: https://www.kaggle.com/datasets/tusharthokdar/mango

Trained Model Link: https://drive.google.com/file/d/1vwXbMyZyK0gE2k6yFAEAilvipmUrMEkX/view?usp=sharing

NoteBook : https://colab.research.google.com/drive/187zn4vIHukjB3JzURgRlRCi4jo2U87Tr?usp=drive_link
