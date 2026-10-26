# Sepsis Prediction System Using LSTM

## Overview
The **Sepsis Prediction System** is a machine learning project that uses Long Short-Term Memory (LSTM) neural networks to analyze patient vital-sign sequences and help identify potential sepsis risk.

The project includes data preprocessing, feature engineering, sequence generation, model training, evaluation, risk classification, and a dashboard for viewing predictions.

## Objectives
- Analyze time-series patient data.
- Prepare and transform data for LSTM model input.
- Predict sepsis-related risk from sequential features.
- Categorize predictions into risk levels.
- Present results through a dashboard.

## Technologies Used
- **Programming Language:** Python
- **Deep Learning:** LSTM, TensorFlow/Keras
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib
- **Application:** Python backend and HTML dashboard

## Project Structure

```text
sepsis_lstm_project/
├── 01_load_data.py
├── 02_eda.py
├── 03_clean_data.py
├── 04_feature_engineering.py
├── 05_sequence_creation.py
├── 06_build_model.py
├── 07_train_model.py
├── 08_evaluate_model.py
├── 09_test_explainability.py
├── 10_risk_bucketing.py
├── 11_generate_full_predictions.py
├── app.py
├── backend.py
├── dashboard.html
├── explainability.py
├── lstm_model.py
├── figures/
├── models/
└── README.md
```

## Workflow
1. Load the input dataset.
2. Explore and preprocess the data.
3. Engineer features from patient observations.
4. Convert observations into sequences.
5. Build and train the LSTM model.
6. Evaluate model performance.
7. Generate predictions and classify risk levels.
8. Display prediction results in the dashboard.

## Installation

Clone the repository:

```bash
git clone https://github.com/komala-28/sepsis_lstm_project.git
cd sepsis_lstm_project
```

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the required dependencies after creating a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Running the Project

Run the application using the entry point configured in the project:

```bash
python app.py
```

If your application uses a separate backend service, follow the startup instructions defined in your code.

## Important Notes
- The trained model files and processed datasets are excluded from the Git repository.
- Provide the required dataset locally before running the complete training pipeline.
- This project is intended for educational and research purposes only.
- Predictions are experimental and must not be used as a substitute for professional medical assessment.

## Future Enhancements
- Improve model performance through further evaluation and tuning.
- Add real-time vital-sign monitoring.
- Improve dashboard visualizations.
- Explore explainable AI techniques.
- Evaluate the system on appropriate independent datasets.

## Author
**Komala Reddy**

GitHub: [@komala-28](https://github.com/komala-28)
