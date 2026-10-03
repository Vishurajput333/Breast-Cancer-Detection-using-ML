# 🩺 Breast Cancer Detection using Machine Learning

This project is a **Flask web application** that predicts whether a breast tumor is **malignant** or **benign** based on cell nuclei measurements from the Breast Cancer Wisconsin dataset.

The machine learning model was trained using `scikit-learn` and deployed in a simple web interface for user interaction.

---

## 🚀 Features
- **User-friendly Web Interface** built with Flask
- **Real-time Predictions** based on user input
- **Model trained** using real-world breast cancer dataset
- Displays a clear result: **"Cancer Detected"** or **"No Cancer Detected"**

---

## 🛠️ Tech Stack
- **Python 3**
- **Flask** – Web framework
- **NumPy & Pandas** – Data handling
- **scikit-learn** – Machine learning model
- **Joblib** – Model serialization

## 📂 Project Structure
---
📦 Breast-Cancer-Detection-using-ML
├── app.py # Flask app
├── breast_cancer_detector.pickle # Trained ML model
├── templates
│ ├── index.html # Input form
│ ├── yes.html # Positive result page
│ └── no.html # Negative result page
└── README.md # Project documentation

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
      ```bash
       git clone https://github.com/Vishurajput333/Breast-Cancer-Detection-using-ML.git
       cd Breast-Cancer-Detection-using-ML```

2. **Create Virtual Environment (Optional but Recommended)**
   
       python -m venv venv
       venv\Scripts\activate   # For Windows
       source venv/bin/activate  # For Mac/Linux

3.**Install Dependencies**


    pip install -r requirements.txt 

4.**Place the Model File**

*Ensure breast_cancer_detector.pickle is in the root project folder.

*Update model_path in app.py if your file location is different.

5.**Run the Application**


    python app.py
    
*The app will run locally at:*

    http://127.0.0.1:5000/
   

📊 Input Features
The form requires 30 numerical inputs corresponding to:

Mean, Error, and Worst values of radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

These are derived from breast cancer cell nuclei measurements.


📜 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.

👤 Author
Vishwajeet singh manhas

GitHub: @Vishurajput333





