# 🩺 Diabetes Prediction Web Application



---

## 🧠 Overview

**Diabetes Prediction Web App** combines Machine Learning with a user-friendly web interface to provide fast and accurate diabetes risk prediction.

The app allows users to:
- Enter medical details such as glucose level, BMI, age, etc.
- Predict diabetes using trained ML models.
- View results instantly on the web interface.  
- Order herbs online from verified herbal partners *(coming soon!)*  
- Use a responsive and simple UI. 


---

## 🧩 Key Features

- 💬 **ML-Based Prediction** – Predicts diabetes using trained Machine Learning models.
- 📊 **User Input Form** – Enter patient health parameters
- ⚡ **Instant Result** – Shows prediction result in real-time


---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, JavaScript,  |
| **Backend** | Flask |
| **Python Frameworks** | NumPy, Pandas, Matplotlib / Seaborn, Scikit-learn |
| **Dataset** | PIMA Indians Diabetes Dataset (Kaggle / UCI) |
| **Deployment** | Render / Railway / Localhost |
| **Environment** | .env for API keys and secret configuration |

---

## 📁 Folder Structure

```
Diabetes_Prediction/
│               
├── template/               
│   ├── home.html/
│   ├── show.html/
├── diabetes.csv 
├── pima_Nulls.ipynb
├── pima_Viz.ipynb 
├── prep_model.ipynb               
├── requirements.txt      
├── README.md             # Project documentation
└── LICENSE               # License (MIT recommended)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ScripterX-00/Diabetes_Prediction.git
cd Diabetes_Prediction
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate       # For Windows
# OR
source venv/bin/activate    # For macOS/Linux
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application
```bash
python main.py
```

Now visit 👉 http://127.0.0.1:6000 in your browser.

---

## 🌐 Deployment

You can easily deploy this Flask app using:

### 🔹 Railway (Recommended for Simplicity)
1. Push your repo to GitHub.  
2. Create a new Railway project.  
3. Connect your GitHub repository.  
4. Add environment variables from `.env`.  
5. Deploy — it auto-detects Flask apps!

### 🔹 Render
1. Create a new web service.  
2. Connect your repo.  
3. Set build command:
   ```bash
   pip install -r requirements.txt
   ```
4. Set start command:
   ```bash
   gunicorn app:app
   ```

---

## 📊 Dataset

The dataset contains medical attributes such a

- Pregnancies
- Glucose
- Blood Pressure
- Insulin
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Source: Kaggle – PIMA Indians Diabetes Dataset

## 🤖 Machine Learning Algorithms

Join our growing community of herbal enthusiasts and developers!

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📈 Results


- Model Accuracy: 89%
- Best Performing Model: Support Vector Machine (SVM)


## 🧪 Testing

Manual testing:

- Enter sample patient data
- Click Predict
- View result
- Verify prediction accuracy
```

## 🤝 Contributing

We welcome contributions from the open-source community!

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push and submit a Pull Request  

Please make sure to include clear commit messages and test your feature before PR submission.

---

## 👨‍💻 Author

**Developed by:** Dibyajyoti Jana  

---


