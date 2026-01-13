🧠 AI vs Real – Image Authenticity Detection Extension
📌 Overview

AI vs Real is a browser-based extension that helps users identify whether an image is AI-generated or real.
The project combines deep learning (ResNet50) with a browser extension interface, making AI image detection accessible in real time.

This tool is designed to address the growing challenge of AI-generated media (deepfakes & synthetic images) by providing a fast, lightweight, and user-friendly solution.

✨ Key Features

🔍 Detects AI-generated vs real images

⚡ Fast inference using a pre-trained deep learning model

🌐 Browser extension-based UI for easy access

🧠 Uses CNN (ResNet50) for high-accuracy classification

🎯 Lightweight and scalable architecture

🛠️ Tools & Technologies Used
🧩 Frontend (Extension)

HTML5

CSS3

JavaScript

Browser Extension APIs

Custom Icons (16px, 48px, 128px)

🧠 Backend / ML

Python 3.11

PyTorch

ResNet50 (CNN Architecture)

Pre-trained Model (.pth)

📦 Environment & Utilities

Virtual Environment (venv)

pip

Git & GitHub

🏗️ Project Structure
AI vs Real Extension/
│
├── Extension_10-final/
│   ├── icons/
│   │   ├── icon16.png
│   │   ├── icon48.png
│   │   └── icon128.png
│   │
│   ├── models/
│   │   └── classifier_resnet50.pth
│   │
│   ├── background.js
│   ├── content.js
│   ├── popup.html
│   ├── popup.js
│   ├── popup.css
│   └── manifest.json
│
├── venv/
│   └── (Python virtual environment files)
│
└── README.md

⚙️ How It Works

User opens the browser extension.

An image is selected or detected.

The image is passed to the ResNet50-based classifier.

The model predicts whether the image is AI-generated or real.

The result is displayed instantly in the extension UI.

🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-vs-real-extension.git
cd ai-vs-real-extension

2️⃣ Set Up Python Environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt

3️⃣ Load Extension in Browser

Open Chrome / Edge

Go to chrome://extensions/

Enable Developer Mode

Click Load Unpacked

Select the Extension_10-final folder

📊 Model Details

Architecture: ResNet50 (CNN)

Framework: PyTorch

Model File: classifier_resnet50.pth

Task: Binary Image Classification (AI vs Real)

🎯 Use Cases

Detecting AI-generated images on the web

Academic research on synthetic media

Media verification & awareness

AI ethics & digital authenticity projects

🔮 Future Enhancements

📈 Improve accuracy with larger datasets

🖼️ Support for video frame detection

☁️ Cloud-based inference for scalability

📱 Mobile browser support

🔐 Explainable AI (confidence scores & heatmaps)

🤝 Authors
Anam Fatima, Aftab Alam, Arjita Sahu

📜 License

This project is licensed under the MIT License.
