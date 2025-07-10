## 🧠 Deepfake Detection with Python & OpenCV

This project demonstrates a simple but effective Deepfake detection pipeline using Python, OpenCV, and image similarity metrics like **MSE** (Mean Squared Error) and **SSIM** (Structural Similarity Index).

We extract frames from **real** and **fake** videos and compare them frame-by-frame to detect visual discrepancies. This is a beginner-friendly approach inspired by core principles in digital media forensics.

---

### 📁 Dataset

Video clips used in this project are sourced from Kaggle:
🔗 [Deepfake Example Video Clips – by anlthms](https://www.kaggle.com/code/anlthms/deepfake-example-video-clips)

---

### 🔧 Technologies Used

* Python 3.x
* OpenCV
* Matplotlib
* NumPy
* scikit-image
* Google Colab (for GPU-backed runtime)

---

### 📊 Metrics Used

* **MSE (Mean Squared Error):** Measures average squared difference. Lower = more similar.
* **SSIM (Structural Similarity Index):** Measures perceptual similarity. Higher = more similar.

---

### 📌 To-Do / Future Improvements

* [ ] Automate face detection using MTCNN or Dlib
* [ ] Classify real/fake using a CNN-based model
* [ ] Add GUI or web interface for uploading and checking videos
* [ ] Integrate more robust datasets for training ML models

---

### 🧑‍💻 Author

Built by [Ranveer Ganna](https://github.com/ranveerganna)
Inspired by [The Clever Programmer](https://www.thecleverprogrammer.com)

