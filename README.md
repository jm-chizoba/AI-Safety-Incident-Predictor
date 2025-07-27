# **AI-Powered Safety Incident Predictor**

## **Overview**
This project leverages **machine learning algorithms** to predict the likelihood of workplace accidents or safety incidents based on historical and simulated data.  
The goal is to provide **proactive risk assessment** tools for Health, Safety, and Environment (HSE) managers in industries such as **construction, oil & gas, and manufacturing**.

## **Key Features**
- **Data Preprocessing:** Cleans and encodes historical incident data.  
- **Machine Learning Models:** Logistic Regression, Random Forest, and Gradient Boosting for risk prediction.  
- **Risk Scoring:** Generates a probability score for potential safety incidents.  
- **Visualization:** Interactive charts for incident trends and high-risk conditions.  
- **Deployment Ready:** Model can be served via a simple **Streamlit app** or **Flask API**.

## **Use Case in HSE**
- Identify **high-risk shifts or conditions** in advance.  
- Optimize safety measures such as PPE allocation or staff training.  
- Reduce incidents and improve compliance with ISO 45001 standards.

## **Tech Stack**
- **Programming Language:** Python (3.8+)  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Optional:** Streamlit (for dashboard UI)

## **Dataset**
- **Type:** Simulated dataset containing variables such as:  
  - Worker shift duration  
  - Weather conditions  
  - Past incidents  
  - Equipment used  
  - Safety training frequency  
- **Note:** You can replace with **real anonymized datasets** if available.

## **Project Structure**
AI-Safety-Incident-Predictor/
│
├── data/
│ ├── incidents.csv
│ └── weather_data.csv
│
├── notebooks/
│ ├── data_preprocessing.ipynb
│ ├── model_training.ipynb
│ └── evaluation.ipynb
│
├── src/
│ ├── train_model.py
│ ├── predict.py
│ └── utils.py
│
├── app/
│ └── streamlit_dashboard.py
│
└── README.md

## **Installation**
```bash
# Clone the repository
git clone https://github.com/your-username/AI-Safety-Incident-Predictor.git
cd AI-Safety-Incident-Predictor

# Install required libraries
pip install -r requirements.txt
```

## **Usage**
```bash
# Train the Model
python src/train_model.py

# Run the Dashboard
streamlit run app/streamlit_dashboard.py
```


## **Future Improvements**
- Integrate real-time IoT data (temperature, gas levels).  
- Add ensemble models for better accuracy.  
- Deploy on a cloud platform (Heroku, AWS).


## **License**
MIT License – open for educational and research use.


## **Author**
**Chizoba Mejulu**  
- [LinkedIn](https://www.linkedin.com/in/chizobamejulu/)  
- HSE Specialist | AI Safety Innovation | Digital Health & Safety Advocate
