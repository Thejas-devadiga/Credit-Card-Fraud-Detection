# Credit-Card-Fraud-Detection


## 📊 Dataset

- **File**: `balanced_credit_card_fraud_dataset.csv`
- **Description**: Contains credit card transaction data with labels indicating fraudulent or non-fraudulent transactions.
- **Source**: Publicly available dataset (e.g., Kaggle or other source, specify here if applicable).

## 🧠 Model

- A Decision Tree classifier is trained using the balanced dataset.
- The trained model is saved as `dt_model.pkl`.
- Features used are saved in `model_features.pkl`.

## 🛠️ How to Run

### 1. Install Requirements

```bash
pip install -r requirements.txt
```
### 2. Train the Model (if needed)
```python train_model.py```

3. Run the Web App
```python app.py```
Open your browser and navigate to http://127.0.0.1:5000 to access the UI.

🌐 Web Interface
The web app (built with Flask) allows users to:

Input transaction features manually

Get predictions on whether the transaction is fraudulent or legitimate

📦 Files Description.

File	Description.

```app.py```	Main Flask application

```index.html```	Frontend UI template

train_model.py	Training and model serialization script

dt_model.pkl	Trained ML model

model_features.pkl	Pickled feature list used in training

test_data.pkl	Sample data for testing

balanced_credit_card_fraud_dataset.csv	Training dataset





🔒 Disclaimer

This project is for educational purposes only and should not be used for real-world fraud detection without rigorous testing and compliance checks.

📌 Author

Thejas-devadiga
