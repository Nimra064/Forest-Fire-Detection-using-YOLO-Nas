# Forest Fire Detection using YOLO Nas
Forest fires are one of the most destructive natural disasters, causing severe damage to ecosystems, wildlife, and human life. This project presents an automated Forest Fire Detection System using the powerful YOLO-NAS (You Only Look Once - Neural Architecture Search) model for real-time fire detection.

The system leverages deep learning and computer vision techniques to accurately identify fire in images or video streams, enabling early detection and rapid response. <br>
![images](https://github.com/Nimra064/Forest-Fire-Detection-using-YOLO-Nas/assets/71897920/3f3a96d6-cab1-459e-bac6-2d45b6688c29)

---
## 🚀 Features
- 🔍 Real-time fire detection using YOLO-NAS  
- 📸 Supports image and video input  
- ⚡ Fast and efficient inference  
- 🧠 Deep learning-based object detection  
- 📊 Bounding box visualization with confidence scores  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Framework:** PyTorch  
- **Model:** YOLO-NAS  
- **Libraries:**
  - OpenCV  
  - NumPy  
  - Matplotlib  
  - SuperGradients  

---

## 📂 Project Structure
```bash
Forest-Fire-Detection-using-YOLO-Nas/
│
├── dataset/ # Dataset for training/testing
├── models/ # Saved trained models
├── notebooks/ # Jupyter notebooks
├── utils/ # Helper functions
├── train.py # Model training script
├── detect.py # Fire detection script
├── requirements.txt # Dependencies
└── README.md # Documentation
```
## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Nimra064/Forest-Fire-Detection-using-YOLO-Nas.git
cd Forest-Fire-Detection-using-YOLO-Nas
2️⃣ Create Virtual Environment (Optional)
python -m venv venv

Activate environment:

Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
▶️ Usage
🔹 Train the Model
python train.py
🔹 Run Detection
python detect.py --source path/to/image_or_video
📊 Model Details

YOLO-NAS is an advanced object detection model built using Neural Architecture Search (NAS). It provides:

Improved accuracy
Faster inference
Efficient deployment performance
📸 Output
Fire regions detected with bounding boxes
Confidence scores displayed for predictions
🎯 Applications
🌲 Forest monitoring
🚒 Fire early warning systems
🛰️ Drone & satellite surveillance
🏭 Industrial fire detection
📈 Future Improvements
Real-time webcam integration
Web app deployment
Enhanced dataset for better accuracy
Alert & notification system
🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

📄 License

This project is open-source and available under the MIT License.
