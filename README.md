# 🧠 Brain Tumor Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect brain tumors from MRI images. The model is built with TensorFlow and trained on a dataset of labeled brain scans (`yes` for tumor, `no` for no tumor).

---

## 📁 Project Structure

```
brain_tumor_detection/
│
├── brain_tumor_dataset/       
├── venv/                      
├── .gitignore                 
├── BRAIN-TUMOR-DETECTION.ipynb 
└── README.md                  
```

---

## 📦 Requirements

- Python 3.8+
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- scikit-learn
- seaborn

Install dependencies:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install tensorflow numpy opencv-python matplotlib scikit-learn seaborn
```

---

## 🚀 How to Run

1. Clone the repo  
2. Activate the virtual environment  
3. Launch Jupyter Notebook  

```bash
jupyter notebook
```

4. Open `BRAIN-TUMOR-DETECTION.ipynb` and run all cells step-by-step.

---

## 📊 Features

- 📥 Image Preprocessing (resizing, normalization)  
- 🧠 CNN Model built with:  
  - Conv2D, MaxPooling2D  
  - Flatten, Dense, Dropout  
- 📈 Training with train/test split  
- 📉 Evaluation with classification report and confusion matrix  
- 🖼️ Custom image prediction  


---

## ✅ Output Example

```
🧠 Prediction: Tumor Detected (Yes)
```

---

## 📷 Prediction on Sample Image

<img src="brain_tumor_dataset/yes/Y1.jpg" alt="Predicted Tumor Image" width="400"/>

> This image was used for prediction and classified as having a brain tumor.
