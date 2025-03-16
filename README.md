# 🤳 Automatic Selfie Capturing using Python  

This is a Python-based project that automatically captures a selfie using your system's webcam. It uses **OpenCV** for real-time face detection and image capturing, making the process seamless and user-friendly.  

## 🚀 Features  

✅ **Automatic Face Detection** using Haar Cascade Classifier.  
✅ **Hands-free Selfie Capture** when a face is detected.  
✅ **Countdown Timer** before capturing to allow adjustments.  
✅ **Saves Captured Image** with a timestamped filename.  
✅ **Real-time Video Feed** with live detection feedback.  

## 🛠️ Technologies Used  

- **Python 3.x**  
- **OpenCV** (cv2)  
- **Datetime** (for timestamping images)  
- **OS** (optional, for handling file paths)  

## 📸 Demo  

![WhatsApp Image 2025-03-09 at 13 08 24_f46bc288](https://github.com/user-attachments/assets/c65c65d0-82d1-4486-8f1f-2c17d24810fe)
 

## 🔧 Installation & Setup  

### 1. Clone the Repository  

```bash
git clone https://github.com/your-username/automatic-selfie-capturing.git
```  

### 2. Navigate to the Project Directory  

```bash
cd automatic-selfie-capturing
```  

### 3. Install Required Packages  

```bash
pip install opencv-python
```  

### 4. Run the Script  

```bash
python selfie_capture.py
```  

## 💻 How It Works  

1. The webcam starts and displays a real-time video feed.  
2. The system detects a face using Haar Cascade.  
3. Once detected, a countdown starts (default 3 seconds).  
4. A selfie is captured automatically and saved in the local directory.  

## 📂 Folder Structure  

```
automatic-selfie-capturing/
│── haarcascade_frontalface_default.xml   # Haar Cascade file for face detection
│── selfie_capture.py                    # Main Python script
│── captured_images/                     # Folder where selfies will be saved
└── README.md                            # Project documentation
```  

## 📝 Usage Notes  

- Make sure your webcam is connected and working.  
- You can adjust the countdown timer and save path inside the `selfie_capture.py` file.  

## 🌟 Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature-name`.  
3. Commit your changes: `git commit -m "Add some feature"`.  
4. Push to your branch: `git push origin feature-name`.  
5. Submit a pull request.  

## 📄 License  

This project is licensed under the **MIT License** — feel free to use and modify.  

## 📬 Contact  

For queries or feedback:  
🔗 **GitHub:** [Rachana-Hegde](https://github.com/Rachana-Hegde)  
