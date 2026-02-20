#  Brain Tumor Detection and Segmentation using U-Net + GAN
#GPU- TESLA P100
## Project Overview
This project focuses on automatic brain tumor detection and segmentation from MRI scans using a hybrid deep learning model combining U-Net and Generative Adversarial Network (GAN). 

The model is trained on the BraTS 2020 dataset and achieves:
- 99% Classification Accuracy
- 0.74 Dice Coefficient (Segmentation)

---

## Objective
To develop an automated system capable of:
- Detecting the presence of brain tumors
- Segmenting tumor regions accurately
- Assisting in early diagnosis using deep learning

---

## Dataset
- Dataset: BraTS 2020 (Brain Tumor Segmentation Challenge)
- Modality: MRI Images
- Includes tumor masks for segmentation

---

## Model Architecture

  ###Generator (U-Net)
  - Encoder
  - Bottleneck
  - Decoder
  - Skip connections

  ###Discriminator (GAN)
  - Classifies real vs generated segmentation masks

  The U-Net performs segmentation while GAN improves mask quality through adversarial learning.

  ---

##Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib

---

##Performance Metrics
- Accuracy: 99%
- Dice Score: 0.74
- Loss Function: Binary Crossentropy + Dice Loss

---

## How to Run
1. Clone the repository
2. Install dependencies
3. Load BraTS dataset
4. Run training notebook
5. Evaluate model

---

## Results
The hybrid U-Net + GAN model improves segmentation quality compared to standard U-Net by refining tumor boundaries.

---

##Future Scope
- Improve Dice score above 0.85
- Deploy as web-based medical application
- Extend to multi-class tumor segmentation
- Optimize model for real-time inference

---

## Author
AFFAN AHMAD
Final Year Project - 2026
