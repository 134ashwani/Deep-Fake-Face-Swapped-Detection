# Deepfake Video Detection using Machine Learning

This project is a college-level machine learning application developed to detect deepfake videos. It uses frame-level facial analysis and temporal feature patterns to classify videos as either **Real** or **Fake**.

Colab Notebook Link: https://colab.research.google.com/drive/1K9hIeYwzJkjqUS4tPwjvpM3H7Ok0uu-9?usp=sharing

---

## 📌 Project Summary

With the rise in manipulated media, detecting fake video content has become a major challenge. This project uses video processing and machine learning techniques to identify fake content in videos by analyzing facial features and movements over time.

---

## 🎯 Objectives

- Extract frames from videos and detect faces
- Analyze sequences of face data to find irregular patterns
- Train a machine learning model to distinguish between real and fake videos
- Build a small application interface for testing video predictions

---

## 🧰 Tools & Technologies

- **Language:** Python
- **Libraries:** OpenCV, Scikit-learn, NumPy, Matplotlib, Seaborn
- **Platform:** Google Colab / Jupyter Notebook
- **Frontend:** HTML, CSS

---

## 🧩 Workflow Overview

1. **Video Frame Extraction**
   - Splits video into individual frames for processing

2. **Face Detection**
   - Uses standard computer vision techniques to extract faces from frames

3. **Feature Generation**
   - Converts face sequences into numerical data (flattened arrays or features)

4. **Model Training**
   - Applies traditional ML algorithms like Random Forest or SVM
   - Labels data as “Real” or “Fake” for supervised learning

5. **Prediction and Evaluation**
   - Model predicts on unseen video frames
   - Evaluates using accuracy, precision, recall, and F1-score

6. **Frontend App**
   - A simple HTML form for uploading a video and viewing results

---

## 📁 Project Structure


---

## 📈 Results

- Accuracy: ~70%
- Robust against basic manipulation techniques
- Detects inconsistencies in face movement and expressions

---

## 📚 References

- Python Official Docs
- Scikit-learn Documentation
- OpenCV Library
- Related research articles on fake media detection

---

## 👨‍💻 Team Members

- Ashwani Kumar Chaurasiya (2231141)  
- Anand Shekhar Mishra (2231134)  
- Manvendra Tiwari (2231158)  
- Anubhav Singh (2231138)

**Guide:** Rahul Dev Sir, Assistant Professor, Department of AI & DS, CGC Jhanjeri

---

## 📜 License

This project is for academic and educational purposes only.
