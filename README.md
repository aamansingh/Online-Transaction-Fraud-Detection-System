# Online-Transaction-Fraud-Detection-System
User Manual: Online Transaction Fraud Detection System
The Online Transaction Fraud Detection System is designed to identify fraudulent transactions using a machine learning model. The project includes a frontend interface developed with HTML and CSS, a backend server using Flask, and a machine learning model trained in Google Colab and saved as a .pkl file.
System Requirements
Python 
Flask
HTML/CSS
Machine Learning Libraries (e.g., scikit-learn, pandas, numpy)
Google Colab (for model training)
Installation and Setup
User Manual: Online Transaction Fraud Detection System
The Online Transaction Fraud Detection System is designed to identify fraudulent transactions using a machine learning model. The project includes a frontend interface developed with HTML and CSS, a backend server using Flask, and a machine learning model trained in Google Colab and saved as a .pkl file.
System Requirements
Python 
Flask
HTML/CSS
Machine Learning Libraries (e.g., scikit-learn, pandas, numpy)
Google Colab (for model training)
Installation and Setup

Clone the project repository from GitHub:
git clone https://github.com/yourusername/online-transaction-fraud-detection.git
cd online-transaction-fraud-detection
Create a virtual environment and install the required packages:
python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Place the Model File
Ensure that the fraud_detection_model.pkl file is placed in the model/ directory.
Run the Flask Application
Start the Flask server: python app.py The application will be available at http://127.0.0.1:5000.
Troubleshooting
Issue: Flask server not starting
Solution: Ensure all dependencies are installed and the virtual environment is activated.
Issue: Model not found 
Solution: Check that the fraud_detection_model.pkl file is correctly placed in the model/ directory.




git clone https://github.com/yourusername/online-transaction-fraud-detection.git
cd online-transaction-fraud-detection
Create a virtual environment and install the required packages:
python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Place the Model File
Ensure that the fraud_detection_model.pkl file is placed in the model/ directory.
Run the Flask Application
Start the Flask server: python app.py The application will be available at http://127.0.0.1:5000.
Troubleshooting
Issue: Flask server not starting
Solution: Ensure all dependencies are installed and the virtual environment is activated.
Issue: Model not found 
Solution: Check that the fraud_detection_model.pkl file is correctly placed in the model/ directory.




