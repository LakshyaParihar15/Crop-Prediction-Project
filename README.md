# 🌾 Crop Prediction Project
A machine learning-based web application designed to recommend the most suitable crop for cultivation based on specific soil and environmental parameters. This tool aims to assist farmers and agricultural enthusiasts in making informed decisions to optimize yield and resource utilization.

# 🔗 Live Demo
Try the application live:
👉 Crop Prediction Web App

# 🚀 Features
- User-Friendly Interface: Input soil and environmental parameters through a simple web form.
- Real-Time Predictions: Receive immediate crop recommendations based on input data.
- Machine Learning Model: Utilizes a trained model to predict the best-suited crop.
- Web Deployment: Built with Flask, HTML, and CSS for seamless web integration.

# 🧠 How It Works
1. Data Input: Users provide values for:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

2. Model Prediction: The application processes the input through a pre-trained machine learning model (model.pkl) to predict the most suitable crop.

3. Result Display: The recommended crop is displayed on the web interface for the user.

# 🗂️ Project Structure
├── Crop Recommendation.py       # Script for training the ML model

├── Crop_recommendation.csv      # Dataset containing soil and environmental parameters

├── app.py                       # Main Flask application

├── model.pkl                    # Serialized trained ML model
├── requirements.txt             # Python dependencies
├── templates/
│   └── index.html               # HTML template for the web interface
├── static/
│   ├── style.css                # CSS styling for the web interface
│   └── ...                      # Additional static assets
└── .idea/                       # IDE configuration files

# 📊 Dataset
The dataset (Crop_recommendation.csv) comprises various records with features such as:
- Soil Nutrients: Nitrogen, Phosphorus, Potassium
- Environmental Factors: Temperature, Humidity, pH, Rainfall
- Target Variable: Crop label indicating the most suitable crop for the given conditions

# 🛠️ Installation & Usage
1. Clone the Repository:
git clone https://github.com/LakshyaParihar15/Crop-Prediction-Project.git
cd Crop-Prediction-Project

2. Create a Virtual Environment (Optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Dependencies:
pip install -r requirements.txt

4. Run the Application:
python app.py

5. Access the Web Interface:
Open your browser and navigate to http://127.0.0.1:5000/

# 🤖 Model Training
To train or retrain the machine learning model:
- 1. Ensure the Dataset is Present: Confirm that Crop_recommendation.csv is in the project directory.
- 2. Run the Training Script:
python "Crop Recommendation.py"
This will process the dataset and generate a new model.pkl file.

📌 Requirements
Python 3.x

Libraries specified in requirements.txt, including:

Flask

scikit-learn

pandas

numpy

📷 Screenshots
Include relevant screenshots of the web interface here to provide visual context.

📄 License
Specify the license under which the project is distributed, e.g., MIT License.

🙌 Acknowledgements
Inspired by the need to integrate machine learning into agriculture for better decision-making.

Dataset sourced from Kaggle.

📬 Contact
For any inquiries or feedback:

GitHub: LakshyaParihar15

Live App: crop-predication-lgkr.onrender.com
