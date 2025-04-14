# Blood Group Detection Using Fingerprint

This project is aimed at detecting a person's Blood Group using their Fingerprint Image with the help of Deep Learning and Flask Deployment.

---

## Project Structure
BloodGrp_Using_Fingerprint/ │ ├── dataset_blood_group/ # Dataset Images (Fingerprint categorized in 8 Blood Groups) │ ├── BldGrp_detect.ipynb # Initial Model Training Notebook using ResNet50 │ ├── 03_Fine_Tuning_ResNet50.ipynb # Model Fine-Tuning & Analysis Notebook │ ├── app.py # Flask Application for Deployment │ ├── templates/ # Frontend UI (HTML Files) │ ├── index.html │ └── result.html │ ├── requirements.txt # Python Dependencies └── .gitignore # Ignore Model Files (.h5, .keras, .tar.gz)

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


