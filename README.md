## Blood Group Detection Using Fingerprint
This project is aimed at detecting a person's Blood Group using their Fingerprint Image with the help of Deep Learning and Flask Deployment.

It leverages a Convolutional Neural Network (CNN) model based on ResNet50 architecture to classify fingerprint images into 8 Blood Group categories:

A+, A-, B+, B-, AB+, AB-, O+, O-

This project automates Blood Group identification in a non-invasive and rapid manner. It can have potential applications in:

Healthcare Systems

Smart Medical Devices

Biometric-based Identification Systems

A simple Web Interface is provided using Flask to upload Fingerprint images and view the predicted Blood Group.
---

## Project Structure
BloodGrp_Using_Fingerprint/
│
├── dataset_blood_group/        # Dataset Images (Fingerprints categorized into 8 Blood Groups)
│
├── BldGrp_detect.ipynb         # Initial Model Training using ResNet50
│
├── 03_Fine_Tuning_ResNet50.ipynb  # Fine-Tuning & Model Improvement
│
├── app.py                      # Flask Deployment Code
│
├── templates/                  # HTML Templates for UI
│   ├── index.html
│   └── result.html
│
├── requirements.txt            # Python Dependencies
│
└── README.md                   # Project Documentation


yaml
Copy
Edit

---

## Tech Stack Used
- Python 3
- TensorFlow / Keras (Deep Learning)
- ResNet50 (Pretrained Model)
- Flask (Web Deployment)
- HTML + CSS (Frontend UI)

---

## Dataset Description
| Blood Group | No. of Images |
|-------------|----------------|
| A+          | 750 |
| A-          | 750 |
| B+          | 750 |
| B-          | 750 |
| AB+         | 750 |
| AB-         | 750 |
| O+          | 750 |
| O-          | 750 |

Total Images = 6000+

---

## Project Timeline (Development Journey)

| Month | Work Done |
|-------|-----------|
| October 2024 | Dataset Collection & Image Preprocessing |
| November 2024 | Initial Model Training using ResNet50 |
| December 2024 | Fine-Tuning Model & Analysis (Improved Accuracy) |
| January 2025 | Flask Deployment with Frontend UI Integration |

---

## How to Run Locally
1. Clone the Repository:
```bash
git clone https://github.com/Aayush-1104/Blood-Group-Detection-Using-Fingerprint.git
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run Flask App:

bash
Copy
Edit
python app.py
Open in Browser:

cpp
Copy
Edit
http://127.0.0.1:5000/
Model Files
Note: Model files are not uploaded here due to GitHub size restrictions.

You can download the trained model files from:

bash
Copy
Edit
Google Drive Link: [Add your drive link here]
Final Output
Upload Fingerprint Image

Predict Blood Group

Clean and Simple Web UI


