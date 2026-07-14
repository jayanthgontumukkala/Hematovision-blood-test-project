🩸 HematoVision — Blood Cell Classification using Transfer Learning
📌 Project Overview

HematoVision is an AI-powered web application that classifies microscopic blood cell images into different categories using deep learning and transfer learning.
The system helps medical professionals perform faster and more accurate blood cell analysis.

This project uses pre-trained Convolutional Neural Networks (CNNs) to improve classification accuracy while reducing training time.

🎯 Features

User login & signup

Upload blood cell image

Image preprocessing

Deep learning prediction

Displays cell type result

Simple web interface

🧠 Blood Cell Classes

The model classifies images into:

Eosinophil

Lymphocyte

Monocyte

Neutrophil

🏗️ Tech Stack
Frontend

HTML

CSS

Bootstrap

Backend

Python

Flask

AI / Model

TensorFlow / Keras

Transfer Learning (Pre-trained CNN)

Database

SQLite (optional)

📂 Project Structure
HematoVision/
│── app/
│   │── app.py
│   │── model_utils.py
│   │── templates/
│   │── static/
│
│── dataset/
│── model/
│── README.md
│── requirements.txt
⚙️ Installation
1️⃣ Clone Repository
git clone <your-repo-link>
cd HematoVision
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Application
python app.py

Open browser:

http://localhost:5000
🧪 Model Workflow.

User uploads image

Image preprocessing

Transfer learning model prediction

Display result

📊 Results

High classification accuracy (~90–95%)

Fast prediction time

Supports multiple blood cell types

✅ Advantages

Reduces manual effort

Fast diagnosis support

Scalable AI solution

User friendly

⚠️ Limitations

Depends on dataset quality

Requires GPU for faster training

Limited cell categories

🚀 Future Scope

Add more blood cell types

Deploy to cloud

Mobile app version

Disease prediction

Hospital integration

📚 Dataset

Kaggle Blood Cell Image Dataset

👨‍💻 Author

G.Jayanth kumar
