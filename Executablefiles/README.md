# 🥦 Smart Bridge - AI Powered Produce Classifier 🍎

**Smart Bridge** is an AI-powered web application that detects whether fruits and vegetables are *fresh* or *rotten* using deep learning (VGG16). Built with a modern UI and deployed on Render, this tool provides instant quality analysis with a single image upload.

---

## 🚀 Live Demo

🔗 **[Smart Bridge Live App](https://smartsort-backend.onrender.com)**
 Click the link and wait a minute to load the application and then refresh or open in a new tab
---

## 📸 Demo Visuals

### 🏠 Home Page  
![Home](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/home1.JPG)
![Home](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/home2.JPG)

### 🔍 Predict Page  
![Predict](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/predict.JPG)

### 📈 Result Output  
![Result](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/result1.JPG)

### About
![About](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/about.JPG)

### Contact
![Contact](https://raw.githubusercontent.com/RAFIROCK/smart-bridge/main/Executablefiles/static/img/contact.JPG)

## 🎥Demo Video:
https://drive.google.com/file/d/1EcAr1ilwNYb5LmQCAqHbLeSSfQie_aP0/view?usp=drive_link

# 📄Project Documents 

https://drive.google.com/drive/folders/1qFkje3qVwev1YwJdh9Jbb_gxJ2Suvy4A?usp=sharing
## access all the project related templates and reports here 

## 💡 Features

- ✅ Upload an image of a fruit or vegetable  
- ✅ Predict whether it’s **Healthy** or **Rotten**  
- ✅ Stunning modern UI with dark theme and glassmorphism  
- ✅ Fully responsive for all devices  
- ✅ Backend powered by Flask + TensorFlow (VGG16)  
- ✅ Hosted & Live on Render

---

## ⚙️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python Flask  
- **Deep Learning:** TensorFlow, Keras, VGG16  
- **Deployment:** Render (Backend), GitHub Hosting  

---
## 🗂️ Project Structure
```
smart-sorting/
│
├── app.py # Flask backend
├── healthy_vs_rotten.h5 # Trained model
├── requirements.txt
│
├── templates/ # HTML files
│ ├── index.html
│ ├── about.html
│ ├── contact.html
│ ├── predict.html
│ └── output.html
│
├── static/
│ ├── css/
│ │ └── style.css
│ └── img/
│ ├── banner.jpg
│ ├── email.png
│ ├── github.png
│ └── linkedin.png
│
└── screenshots/
├── home.png
├── predict.png
└── contact.png


```


## 📦 How to Run Locally
```
# Clone the repository
git clone https://github.com/RAFIROCK/smart-bridge.git
cd smart-bridge

# Optional: create virtual environment
python -m venv venv
venv\Scripts\activate     # For Windows
# source venv/bin/activate  # For macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Run the Flask application
python app.py


Then open http://127.0.0.1:5000 in your browser.


```
## 👥 Development Team

| Name             | Role               | GitHub Profile                          |
|------------------|--------------------|------------------------------------------|
| V MAHAMMAD RAFI   | Project Lead & Developer| [@RAFIROCK](https://github.com/RAFIROCK) |

## 🎯 Use Cases-
🏭 Factories: Automated sorting of fresh vs rotten produce

🛒 Supermarkets: Quality check at delivery docks

🏠 Smart Homes: Alert users to use produce before it spoils

🙌 Acknowledgements-
Kaggle Dataset – for the fruit and vegetable dataset

TensorFlow – deep learning framework

VGG16 – pre-trained model for transfer learning

Flask – lightweight Python web framework

# ✍️ Author
## 🧑🏻‍💻 V MAHAMMAD RAFI
## 🔗 GitHub: https://github.com/RAFIROCK
## 🔗 Repository: https://github.com/RAFIROCK/smart-bridge

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
