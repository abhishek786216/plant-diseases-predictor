# 🌿 Crop Disease Prediction Web page

This is a **Streamlit web app** that detects plant leaf diseases from images using a **TensorFlow Lite model**. Upload an image of a leaf, and the app will predict the disease (if any) with confidence.

🔗 **Live Demo**: https://plant-diseases-predictor.streamlit.app/*(Add your deployed app link here once available)*

---

## 🧠 How It Works

1. User uploads an image of a plant leaf (JPG/PNG).
2. The image is resized and passed to a pre-trained **TFLite model**.
3. The model predicts the **disease category** from 38 possible classes.
4. Output includes:
   - Disease name (or "Healthy")
   - Confidence score (0 to 1)

---

## ✅ Features

- 📸 Upload custom images or use built-in samples
- 🧪 Real-time prediction with confidence score
- 🔍 Pre-trained model with 38 crop disease classes
- 📱 Lightweight and fast using **TensorFlow Lite**

---

## 🏷️ Disease Classes

Includes common and significant crop diseases across multiple plants like:

- Apple Scab, Black Rot, Cedar Apple Rust
- Tomato Leaf Mold, Yellow Leaf Curl Virus
- Potato Early Blight, Late Blight
- Grape Black Rot, Esca
- Corn Common Rust, Leaf Blight
- Orange Citrus Greening
- And many more...

*(Full list of 38 classes is in the code as `class_name`)*

---

## 🖼️ Built-in Sample Images

You can test the app using:
- 🥔 **Potato - Early Blight**
- 🍅 **Tomato - Yellow Curl Virus**
- 🍏 **Apple - Cedar Rust**

No need to upload anything manually!

---

## 📁 Project Structure

