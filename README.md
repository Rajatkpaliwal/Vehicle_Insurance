# 🚗 Vehicle Insurance Prediction System 📊🤖

An end-to-end **Machine Learning Vehicle Insurance Prediction Project** designed with a complete production-ready pipeline.

This project includes:

- Data Ingestion & Validation  
- Data Transformation  
- Model Training & Evaluation  
- MongoDB Integration  
- AWS S3 Model Deployment  
- FastAPI Web Interface  

It follows real-world industry standards for scalable ML systems.

---

## 🚀 Key Features

✅ Complete ML pipeline architecture  
✅ Modular component-based design  
✅ MongoDB used for dataset storage  
✅ AWS S3 integration for model pushing  
✅ Automated CI/CD workflow using GitHub Actions  
✅ FastAPI + HTML frontend for predictions  
✅ Dockerized deployment support  

---

## 🧠 Project Architecture

The system is divided into multiple stages:

- **Data Ingestion** → Collects and loads insurance dataset  
- **Data Validation** → Ensures schema consistency  
- **Data Transformation** → Feature engineering & preprocessing  
- **Model Trainer** → Trains ML model (RandomForest, etc.)  
- **Model Evaluation** → Compares with previous best model  
- **Model Pusher** → Uploads final model to AWS S3  
- **Prediction Pipeline** → Provides real-time predictions via API  

---

## 🛠️ Tech Stack

### Machine Learning
- Pandas, NumPy  
- Scikit-learn  
- Imbalanced-learn  

### Backend & Deployment
- FastAPI  
- Uvicorn  
- Jinja2 Templates  
- MongoDB  
- AWS S3 (boto3)  
- Docker  

### Visualization
- Matplotlib  
- Plotly  
- Seaborn  

---

## 📂 Folder Structure

```bash
Vehicle_Insurance/
│
├── .github/workflows/          # AWS CI/CD workflow
│   └── aws.yaml
│
├── config/                     # YAML configuration files
│   ├── model.yaml
│   └── schema.yaml
│
├── notebook/                   # Experiments & model trials
│   ├── data.csv
│   ├── exp_notebook.ipynb
│   ├── mongoDB_demo.ipynb
│   └── rf_model.pkl
│
├── src/
│   ├── components/             # Core ML pipeline components
│   │   ├── data_ingestion.py
│   │   ├── data_validation.py
│   │   ├── data_transformation.py
│   │   ├── model_trainer.py
│   │   ├── model_evaluation.py
│   │   └── model_pusher.py
│   │
│   ├── configuration/          # MongoDB & AWS connections
│   │   ├── aws_connection.py
│   │   └── mongo_db_connection.py
│   │
│   ├── cloud_storage/          # AWS storage utilities
│   │   └── aws_storage.py
│   │
│   ├── pipeline/               # Training & Prediction pipeline
│   │   ├── training_pipeline.py
│   │   └── prediction_pipeline.py
│   │
│   ├── utils/                  # Helper utilities
│   │   └── main_utils.py
│   │
│   ├── logger/                 # Logging module
│   └── exception/              # Custom exception handling
│
├── static/css/                 # CSS styling
│   └── style.css
│
├── templates/                  # Frontend HTML template
│   └── vehicledata.html
│
├── app.py                      # FastAPI main application
├── demo.py                     # Demo script
├── requirements.txt            # Dependencies
├── Dockerfile                  # Containerization
└── README.md                   # Documentation
```

---


```md
## 📷 Project Demo Screenshot

![Vehicle Insurance Prediction]Vehicle_insurance.png
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Rajatkpaliwal/Vehicle_Insurance.git
cd Vehicle_Insurance
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate     # Linux/Mac
venv\Scripts\activate        # Windows
```

---

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run Training Pipeline

```bash
python src/pipeline/training_pipeline.py
```

---

### 5️⃣ Run FastAPI Application

```bash
uvicorn app:app --reload
```

App runs at:

```
http://127.0.0.1:8000
```

---

## 🎯 Use Cases

- Insurance companies risk analysis  
- Customer premium prediction  
- Automated ML pipeline deployment  
- Real-time vehicle insurance classification  

---

## 📌 Future Enhancements

🚀 Add deep learning models  
🚀 Deploy using AWS EC2 + Docker  
🚀 Build React frontend dashboard  
🚀 Add monitoring & logging pipelines  

---

## 👨‍💻 Author

**Rajat Kumar Paliwal**  
🎓 Computer Science Engineer | AI/ML Engineer  

🔗 GitHub: [Rajatkpaliwal](https://github.com/Rajatkpaliwal)

---

## ⭐ Support

If you like this project, don’t forget to give it a ⭐ on GitHub!
