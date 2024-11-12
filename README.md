# Accident Detection System 🚨

An AI-powered accident detection system developed using PyTorch to monitor traffic and detect accidents in real-time. The system sends alert notifications to nearby emergency services, including ambulances, police stations, and other first responders, to ensure swift assistance at the scene.

Features
* Real-Time Accident Detection: Leverages computer vision and deep learning models to identify accidents in traffic.
* Instant Alerts: Sends automatic notifications to nearby emergency services when an accident is detected.
* High Accuracy: Built with state-of-the-art PyTorch models, ensuring reliable accident detection.
* Scalable & Flexible: Easily integrates with different video feeds and sensor data sources.


# Installation
```
git clone https://github.com/navaneethsanil/Accident-Detection.git
cd Accident-Detection

python -m venv env
source env/scripts/activate

pip install -r requirements.txt
```

Then run the accident_detection.ipynb file. You can see the demo by executing the Gradio Demo section

**Note**: In the main.ipynb file, you can bypass the training step. Instead, you can load the pre-trained model
