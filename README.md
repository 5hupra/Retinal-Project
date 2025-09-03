# 🩺 Retinal Image Analysis for Disease Detection & Prognosis

This project focuses on using **retinal fundus images** to build a deep learning model capable of detecting and predicting systemic or ocular diseases.  
The retina provides a **non-invasive "window" to the vascular system**, making it a powerful biomarker for various conditions.

---

## 📌 Objectives
- Build a baseline **Convolutional Neural Network (CNN)** model to analyze retinal images.
- Classify images into **disease vs. healthy** categories.
- Explore possibility of **multi-class classification** (if multiple diseases are annotated).
- (Optional) Combine with clinical/lifestyle data for **prognosis**.

---

## 📊 Datasets
We plan to start with freely available retinal image datasets such as:

- **Messidor** – Diabetic Retinopathy images with grading labels  
  [Download here](https://www.adcis.net/en/third-party/messidor/)

- **RFMiD** – Retinal Fundus Multi-Disease Dataset (45 retinal diseases, multi-label)  
  [Download here](https://ieee-dataport.org/open-access/retinal-fundus-multi-disease-image-dataset-rfmid)

- **DRIVE / STARE** – Retinal vessel segmentation datasets  
  [DRIVE Link](https://drive.grand-challenge.org/) | [STARE Link](https://cecas.clemson.edu/~ahoover/stare/)

*(You can update this section once you finalize which dataset you’ll use.)*

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **PyTorch** – deep learning framework
- **Torchvision** – for pretrained CNN models (ResNet, EfficientNet)
- **OpenCV / Pillow** – image preprocessing
- **Matplotlib / Seaborn** – visualization
- **Grad-CAM** – model explainability

---

## 🔄 Workflow
1. **Dataset Preparation** – Download and preprocess images (resize, normalize, augment).
2. **Model Selection** – Use pretrained CNN (ResNet18/50) and fine-tune.
3. **Training & Validation** – Split data, train, evaluate using metrics like Accuracy, ROC-AUC.
4. **Explainability** – Visualize important regions using Grad-CAM.
5. **Extension** – Optionally add clinical data for multimodal prediction.

---

## 🚀 Future Scope
- Extend to **multi-disease classification** (RFMiD dataset).
- Add **tabular clinical data fusion** (NHANES or institutional dataset).
- Explore **deployment** (web app/mobile app) for real-world screening.

---

## 📄 Citation / References
- Gulshan V. et al., *Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs*, JAMA 2016.
- Poplin R. et al., *Prediction of Cardiovascular Risk Factors from Retinal Fundus Photographs via Deep Learning*, Nature Biomedical Engineering 2018.

---

## 👥 Contributors
- Shubham Prakash  
- Vaibhav tiwari  
- Soharab Ali  
- Sumit Shukla  

Guide: **Mr. Param Goel**

---

## ⚠️ Disclaimer
This project is for **research and educational purposes only** and is not intended for direct clinical use without validation.
