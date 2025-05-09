🌾 AGRISENCE – A Smart Farming System
AGRISENCE is an AI-powered smart farming system that leverages Machine Learning (ML) and Deep Learning (DL) for optimized irrigation scheduling, fertilizer prediction, and crop yield forecasting. Designed for real-world agricultural deployment, the system integrates sensor data, image classification, and cloud-based analytics to enhance decision-making for farmers.

🚀 Features
💧 Predict optimal irrigation schedules using ML regression models

🧪 Fertilizer recommendations via CNN-based crop image classification

🌾 Yield forecasting using crop health, weather, and historical yield data

🌐 Web-based interface using Streamlit

📈 Data visualization and continuous learning model pipeline

☁️ Optional cloud integration for large-scale deployment

🧠 Technologies Used
Languages: Python 3.7+

Frameworks: PyTorch, TensorFlow, Keras, Scikit-learn

Libraries: OpenCV, Dlib, Pandas, NumPy, Matplotlib, Torchvision

Web: Streamlit, Flask (optional)

Database: SQLite/PostgreSQL

Optional: FAISS, AWS/GCP for cloud deployment

🧱 System Modules
Irrigation Management

Predicts water requirements using real-time sensor data and weather APIs.

Regression models: Linear Regression, Decision Tree.

Fertilizer Prediction

CNN model classifies crop health from leaf images.

Provides treatment advice and fertilizer recommendations.

Yield Forecasting

Combines tabular data (soil, weather) and image data to estimate yield.

Visualization & Interface

Web interface built in Streamlit.

Real-time feedback with charts, images, and recommendations.

📦 Installation
bash
Copy
Edit
git clone https://github.com/your-username/agrisense-smart-farming.git
cd agrisense-smart-farming
pip install -r requirements.txt
▶️ How to Run
bash
Copy
Edit
streamlit run app.py
Upload images of crops or input sensor values to get predictions.

📁 Project Structure
kotlin
Copy
Edit
Agrisense/
├── app.py
├── model/
│   ├── cnn_crop_classifier.pth
│   └── class_indices.pkl
├── data/
│   ├── sample_images/
│   └── training_csvs/
├── utils/
│   └── preprocess.py
├── requirements.txt
└── README.md
📈 Results
✅ Fertilizer prediction accuracy: ~94%

📊 Irrigation model R² score: 0.89

📷 CNN yield forecasting model accuracy: ~92%

⏱️ Real-time inference latency: <2.5 seconds

🧑‍💻 Authors
Arunkumar M (221501013)

Deependra S (221501025)
Department of Artificial Intelligence and Machine Learning
Rajalakshmi Engineering College, Thandalam

🔮 Future Enhancements
Integration with drones and multispectral imagery

Advanced weather forecasting integration

Mobile app version for offline usage

Real-time automated irrigation control

Farmer collaboration platform for sharing insights

Supply chain integration and smart marketplace predictions

📜 License
This project is licensed under the MIT License.
