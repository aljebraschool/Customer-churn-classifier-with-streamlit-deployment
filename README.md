# Customer-churn-classifier-with-streamlit-deployment

📌 Overview
This project is a Customer Churn Prediction model deployed using Streamlit. The application helps businesses predict customer churn based on various factors, allowing them to take preventive actions.

🚀 Features
- User-friendly Streamlit web interface
- Pretrained classification model for predicting customer churn
- Encoders for categorical feature transformation
- Scaler for numerical feature normalization
- Easy deployment and execution

## Demo
Access the deployed app here: [Customer churn classifier](https://customer-churn-classifier-with-app-deployment-9etrrrg4ch7rvfz9.streamlit.app/).

## **Below is a demonstration of the app's interface:**
![image](https://github.com/user-attachments/assets/1935b936-84a9-47b4-9084-3a28aa4f29b4)

📂 Repository Structure

``` bash
📦 customer-churn-classifier-with-streamlit-deployment
├── README.md                  # Project documentation
├── Churn_Modelling.csv        # Dataset used for training the model
├── app.py                     # Streamlit app script
├── chun_modeling.ipynb        # Jupyter Notebook for model training & evaluation
├── model.h5                   # Trained classification model (Keras/TensorFlow)
├── label_encoder_gender.pkl   # Label encoder for gender feature
├── onehot_encoder_geography.pkl # One-hot encoder for geography feature
├── scaler.pkl                 # Scaler for feature normalization
├── prediction.ipynb           # Notebook for prediction testing
├── requirements.txt           # Dependencies required for running the project
├── LICENSE                    # Project License

```

📥 Installation & Setup

1. Clone the repository
   ``` bash
      git clone https://github.com/your-username/customer-churn-classifier-with-streamlit-deployment.git
      cd customer-churn-classifier-with-streamlit-deployment
   ```
2. Create a virtual environment (optional but recommended)
   ``` bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate     # On Windows

   ```
3. Install dependencies
   ``` bash
      pip install -r requirements.txt
   ```

▶️ Running the Streamlit App

Run the following command to start the Streamlit application:

``` bash
  streamlit run app.py
```
This will launch a local web application in your browser.

📊 How It Works

- Open the Streamlit app.
- Upload customer details such as age, credit score, balance, etc.
- Click the Predict button to get the churn prediction.

🛠 Model & Technologies Used

- Machine Learning Model: Classification (Trained using TensorFlow/Keras)
- Libraries:
  - Streamlit: Web-based UI for model interaction
  - Scikit-learn: Feature encoding & scaling
  - TensorFlow/Keras: Model training and inference
  - Pandas/Numpy: Data manipulation

💡 Future Improvements

- Improve model accuracy with additional feature engineering
- Implement real-time data integration
- Deploy as a REST API for better scalability
- 
🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

📜 License
This project is licensed under the MIT License.

🌟 Don't forget to star ⭐ the repository if you find it useful!
Happy coding! 😊







