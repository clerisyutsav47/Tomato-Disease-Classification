# Tomato-Disease-Classification
This is a Streamlit web application for Image Recognition using Neural Networks that has been trained to recognize disease in Tomatoes. The model was trained using Scikit-learn, Keras and Tensorflow libraries.

# Installation

Clone the repository and navigate to the root folder:
```terminal
git clone https://github.com/yourusername/yourproject.git
cd yourproject
```

Create a virtual environment: 
```terminal
python3 -m venv venv
```

Activate the virtual environment:  
On Windows:  
```terminal
venv\Scripts\activate
```

On Linux or macOS:
```terminal
source venv/bin/activate
```

Install the dependencies: 
```terminal
pip install -r requirements.txt
```

# Usage
To run the application, navigate to the root folder and execute the following command:  
```terminal
streamlit app.py
```
Then, open a web browser and go to http://localhost:5000/.
Upload an image and the application will predict the disease of tomato in the image using the pre-trained deep learning model.

# Files
* app.py: This is the Streamio web application that serves as the main entry point of the program. It uses the machine learning model to predict the disease in an uploaded image.

* main.py: This is the Python script that trains the machine learning model using Scikit-learn, Keras and Tensorflow libraries.

* model.pkl: This is the pre-trained machine learning model.

* dataset: This directory contain the data used for training the model.

* test_images: This is the directory which contain test datasets for the classification.

* requirements.txt: This is the text files which contains all the necessary dependencies with their versions.

# License
This project is protected by the MIT License. See the LICENSE file for more details.

# Credits
* This project was created by Utsav Acharya.
* The face recognition model was trained using Kaggle Dataset arjuntejaswi/plant-village.
* The Scikit Learn, Keras and Tesnorflow were used for image detection and model training.
* The Streamlit web framework was used to create the web application.




