# Scholarship-Prediction-Project
## 📌 Overview
This project predicts whether an Erasmus applicant will receive a scholarship based on their exam scores and grant-related features. 

- **Dataset:** [Kaggle: Erasmus Applicants Exam & Grant Data](https://www.kaggle.com/datasets/acareren/exam-and-grant-data-of-erasmus-applicants)

## 📊 Dataset
The dataset contains:
- Exam scores
- Grant eligibility criteria
- Other applicant details

## 🛠️ Tech Stack
- **FastAPI** for serving the ML model
- **Scikit-learn** for training
- **Joblib** for model serialization
- **NumPy & Pandas** for data handling

## 🚀 How to Run
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/Erasmus-Scholarship-Prediction.git
   cd Erasmus-Scholarship-Prediction
   ```
2. Install dependencies
   ```
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
   ```
   pip install -r requirements.txt
   ```
3. Run FastAPI Server
   ```
   uvicorn app:app --reload
   ```
   ```
   http://127.0.0.1:8000/docs
   ```
   



