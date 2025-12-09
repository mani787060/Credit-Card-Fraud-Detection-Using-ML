# Credit Card Fraud Detection System using Machine Learning

This project builds a **Machine Learning-based system** to identify whether a credit card transaction is **legit** or **fraudulent**.  
The dataset is highly imbalanced, and the project demonstrates how to handle such imbalance and create an accurate classification model.

The project includes:
- Data exploration & preprocessing
- Feature scaling
- Handling imbalanced data
- Train–test split
- Logistic Regression / Random Forest classification
- Performance evaluation
- User Input Prediction System

---

## Project Workflow

### 1. Data Preprocessing
- Checking missing values  
- Understanding imbalance  
- Scaling features using StandardScaler  
- Splitting dataset into train & test  

### 2. Model Training
Models used:
- Logistic Regression  
- (Optional) Random Forest Classifier  

### 3. Model Evaluation
Metrics:
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  
- ROC Curve / AUC  

### 4. Prediction System
The notebook contains **two prediction modes**:

#### Sample-based prediction  
Predicts using any transaction row from the dataset.

#### User Input Prediction System  
User manually enters all feature values →  
Model predicts **Legit** or **Fraudulent**.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  

---

## 💡 Final Output  
The model predicts whether a transaction is:  
- **LEGIT Transaction**, or  
- **FRAUDULENT Transaction**  
along with a **confidence score**.

This project demonstrates complete ML workflow and fraud detection logic useful in financial applications.

