# 👋 HandSpeak – AI Sign Language Recognition

HandSpeak is a real-time AI-powered Sign Language Recognition application that converts hand gestures into text using computer vision and deep learning.

The application detects hand landmarks using **MediaPipe**, processes gesture data, and predicts signs using trained **TensorFlow/Keras models** for both:

- American Sign Language (ASL)
- Indian Sign Language (ISL)

Built with an interactive **Streamlit web interface**, the system allows users to construct sentences using live webcam gesture recognition.

---

## 🚀 Features

✅ Real-time webcam gesture recognition  
✅ Supports ASL & ISL alphabets  
✅ AI gesture prediction using deep learning models  
✅ Sentence construction system  
✅ Stable prediction filtering (noise reduction)  
✅ Interactive Streamlit UI  
✅ Hand landmark visualization  
✅ Space, Backspace & Clear controls  

---

## 🧠 How It Works

1. Webcam captures live hand gestures.
2. MediaPipe detects 21 hand landmarks.
3. Landmarks are normalized and preprocessed.
4. TensorFlow model predicts the gesture class.
5. Stable predictions form readable sentences.
6. Output updates live in Streamlit interface.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Streamlit | Web Interface |
| OpenCV | Camera Processing |
| MediaPipe | Hand Tracking |
| TensorFlow / Keras | Deep Learning Model |
| NumPy | Numerical Processing |
| Pandas | Data Handling |

---

## 📂 Project Structure
