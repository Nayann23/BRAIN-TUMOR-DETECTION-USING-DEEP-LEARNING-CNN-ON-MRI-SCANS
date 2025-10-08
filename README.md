# 🧠 Brain Tumor Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect brain tumors from MRI images. The model is built with TensorFlow and trained on a dataset of labeled brain scans (`yes` for tumor, `no` for no tumor).

---
## File Structure

| Path | Type | Description |
|------|------|-------------|
| `brain_tumor_detection/` | Directory | Project root. |
| `brain_tumor_dataset/` | Directory | Dataset folder containing subfolders:<br>`yes/` — MRI scans with tumors<br>`no/` — MRI scans without tumors |
| `visuals/` | Directory | Generated visuals and plots:<br>`Brain MRI Images Samples.png`<br>`Brain Tumor Confusion Matrix.png`<br>`No Tumor Detection.png`<br>`Training vs Validation Accuracy & Loss.png`<br>`Tumor Detection.png` |
| `venv/` | Directory | Python virtual environment (local; usually excluded from VCS). |
| `.gitignore` | File | Files and folders to ignore (e.g., `venv/`, cache, checkpoints). |
| `requirements.txt` | File | List of Python dependencies required to run the project. |
| `BRAIN-TUMOR-DETECTION.ipynb` | File | Main Jupyter Notebook with training, evaluation, and visualizations. |
| `README.md` | File | Project documentation, setup & usage instructions, and notes. |

---

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
- 🧠 CNN Model built with: Conv2D, MaxPooling2D ,Flatten, Dense, Dropout  
- 📈 Training with train/test split  
- 📉 Evaluation with classification report and confusion matrix  
- 🖼️ Custom image prediction  


---

## ✅ Output Example Prediction on Sample Image

🧠 Prediction: Tumor Detected (Yes)
<img src="brain_tumor_dataset/yes/Y1.jpg" alt="Tumor Predicted Image" width="400"/>

----
🧠 Prediction: Tumor Detected (No)
<img src="brain_tumor_dataset/no/10 no.jpg" alt="No Tumor Predicted Image" width="400"/>

> This images was used for prediction and classified as having a brain tumor or not.

---

## 📜 License

This project is open-source and licensed under the [MIT License](LICENSE). See the LICENSE file for full details.

---

## 👤 Author:  **Nayan Darokar** 

## GitHub
```bash
https://github.com/Nayann23
```

## Email:
```bash
reachout.nayan@gmail.com  
```
## Portfolio: 
```bash
https://nayan-datascience-portfolio.vercel.app/
```
