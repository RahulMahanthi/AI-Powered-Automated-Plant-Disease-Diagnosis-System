# 🌱 Plant Leaf Disease Detection 🌿

This project utilizes a deep learning model to detect plant leaf diseases based on an uploaded image. The model classifies the plant leaf image into different disease categories and provides detailed care instructions for each predicted disease.

## Features
- 🖼️ **Image Upload**: Upload a plant leaf image (JPEG/PNG format).
- 🔍 **Disease Prediction**: The model predicts the disease based on the uploaded leaf image.
- 📝 **Detailed Care Information**: For each disease, the application provides prevention tips, chemical treatments, watering advice, and additional care guidelines.

## Technologies Used
- 🌐 **Streamlit**: For creating the user interface.
- 🧠 **TensorFlow/Keras**: For the deep learning model to predict plant leaf diseases.
- 🔢 **NumPy**: For image array processing.
- 📸 **PIL (Python Imaging Library)**: For handling image preprocessing and display.
- 🐙 **GitHub**: For version control and project hosting.

## Model Description
The model used for prediction is trained on various plant leaf diseases and their corresponding images. It classifies the image into one of the predefined disease categories and provides a confidence score for the prediction.

### Classes:
- 🌶️ Pepper__bell___Bacterial_spot
- 🌶️ Pepper__bell___healthy
- 🥔 Potato___Early_blight
- 🥔 Potato___Late_blight
- 🥔 Potato___healthy
- 🍅 Tomato_Bacterial_spot
- 🍅 Tomato_Early_blight
- 🍅 Tomato_Late_blight
- 🍅 Tomato_Leaf_Mold
- 🍅 Tomato_Septoria_leaf_spot
- 🍅 Tomato_Spider_mites_Two_spotted_spider_mite
- 🍅 Tomato__Target_Spot
- 🍅 Tomato__Tomato_YellowLeaf__Curl_Virus
- 🍅 Tomato__Tomato_mosaic_virus
- 🍅 Tomato_healthy

## How to Use

### Step 1: Upload an Image 📤
- Click on the "📤 Upload an image" button and select a leaf image in `.jpg`, `.jpeg`, or `.png` format.

### Step 2: View Prediction ✅
- After uploading, the model will analyze the image and display the predicted disease label along with the confidence score.

### Step 3: Receive Care Instructions 🩺
- If the model detects a known disease, detailed care instructions will be displayed, including prevention methods, recommended chemicals, watering advice, and additional care tips.

## Setup

### Prerequisites
Make sure you have the following Python libraries installed:
- 🛠️ `streamlit`
- 🤖 `tensorflow`
- 🖼️ `Pillow`
- 🔢 `numpy`

You can install them using pip and run :
```bash
pip install streamlit tensorflow pillow numpy
streamlit app.py

