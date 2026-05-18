# Smart-Traffic-Management-Using-AI-Analytics
This Smart Traffic Management leverages real-time data from sensors/cameras and historical traffic patterns to dynamically adjust traffic signal timings, predict congestion, and optimize vehicle flow across intersections based on AI Analytics


# Features : 
✅ Dynamic Signal Control
    Adjusts traffic light durations based on real-time vehicle density at each lane.

✅ Congestion Detection
    Uses computer vision (or simulated data) to detect traffic buildup and trigger alerts.

✅ Traffic Flow Prediction
    Predicts peak hours and congestion using ML models (e.g., LSTM, Random Forest).

✅ Web Dashboard
    Real-time monitoring of all intersections via an intuitive admin dashboard.

✅ Emergency Vehicle Priority
    Grants green light priority to ambulances/fire engines via RFID/GPS detection.

✅ Data Analytics & Reporting
    Visualize daily traffic trends, bottlenecks, and system performance.

✅ Cross-Platform Compatibility
    The system is uniquely designed to run efficiently on both Raspberry Pi and smartphones, enabling low-cost, scalable deployment.


# 🛠️ Tech Stack
•	Component    :  Technology Used                                                                                                                             
•	Backend      :	Python / Flask                                                                                                                               
•	Frontend     :	HTML, CSS, JavaScript, Bootstrap                                                                                                               
•	Database     :	MySQL                                                                                                                                          
•	Machine Learning : 	Scikit-learn, TensorFlow                                                                                                                   
•	Simulation   :	OpenCV (for object detection)                                                                                                                  
•	Deployment   : 	Docker (optional), Gunicorn                                                                                                                    
•	Hosting      :	Local Server / Cloud (for demo)    


# 📦 Installation & Setup
# Prerequisites

•	Python 3.8 or higher
•	pip package manager
•	Git


# Steps

    1. Clone the repository :-
    github https://github.com/krishnazawar26/Smart-Traffic-Management-Using-AI-Analytics/
    cd Smart Traffic Management Using AI Analytics

    2. Create virtual environment (recommended) :-
    python -m venv venv
    source venv/bin/activate   

    3. Install dependencies :-
    pip install -r requirements.txt

    4. Run the application :-
    python app.py

# 🖼️ Project Structure
    Smart Traffic Management
    │
    ├── app.py                    # Main Python application
    ├── config.py                 # Configuration settings
    ├── models/                   # ML models & training scripts
    │   ├── train_model.py
    │   └── predict.py
    ├── static/                   # CSS, JS, images
    │   ├── css/
    │   ├── js/
    │   └── images/    
    ├── templates/                # HTML templates
    │   ├── index.html
    │   ├── dashboard.html
    │   └── ...
    ├── utils/                    # Helper functions
    │   ├── camera_feed.py
    │   └── signal_controller.py
    ├── data/                     # Sample datasets/logs
    ├── requirements.txt          # Dependencies
    └── README.md


# 🎯 How It Works
Input: Live video feed from CCTV cameras or sensor data (simulated).
Processing: Detect vehicles using OpenCV/YOLO and calculate lane-wise density.
Decision Engine: Use ML model to predict optimal signal timing.
Output: Send updated signal durations to traffic lights.
Monitoring: Admin dashboard displays live stats and allows manual override.
