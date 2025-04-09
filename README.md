# End to end machine learning  project 
## Student Performance Predictor

🔮 Machine Learning Web App | 📊 88.04% Accuracy (R² Score)

## Live Demos
1. **Primary Deployment (Render - Permanent)**  
   [https://ml-project-student-performance-e17w.onrender.com/predictdata](https://ml-project-student-performance-e17w.onrender.com/predictdata)

2. **Legacy Deployment (AWS - May Expire)**  
   [http://student-new-env.eba-g3fech2f.us-east-2.elasticbeanstalk.com/predictdata](http://student-new-env.eba-g3fech2f.us-east-2.elasticbeanstalk.com/predictdata)

## Key Features
- Predicts student math scores based on 7 input factors
- Achieved **0.8804 R² score** using Random Forest Regressor
- Production-ready Flask API with gunicorn
- Responsive web interface

## Technical Highlights
```python
# Model Performance
# By running data_ingestion.py
from sklearn.metrics import r2_score
>>> Model Accuracy: 0.8804
```
## Local setup
```
git clone https://github.com/mantra0519/ml_project.git
cd ml_project
pip install -r requirements.txt
python application.py  # Access at http://localhost:5000/predictdata
