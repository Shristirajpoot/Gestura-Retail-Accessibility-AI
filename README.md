# ✋ Gestura – Bridging Silence with AI 🤖  
> A real-time sign-language translator made with ❤️ using **Python, MediaPipe & OpenCV**

![GitHub Repo stars](https://img.shields.io/github/stars/Shristirajpoot/Gestura?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/Shristirajpoot/Gestura?color=brightgreen)
![Built with](https://img.shields.io/badge/Built%20with-Python%20%7C%20MediaPipe%20%7C%20OpenCV-blue)

---

## 🌟 Overview
**Gestura** is an AI-powered application that captures hand gestures via webcam, recognises American Sign Language (ASL) signs in real-time, and instantly converts them into text **and** speech. It leverages **MediaPipe** for landmark detection, a **Random Forest** model for classification, and Python’s text-to-speech engines to give voice to every gesture.

---

## 🎥 Demo Video  
📺 **Watch the full walkthrough:**  
[![Gestura – Demo](https://img.youtube.com/vi/sVI3OwGbkoI/0.jpg)](https://youtu.be/sVI3OwGbkoI)

> 🔗 *Click the image or [watch on YouTube](https://youtu.be/sVI3OwGbkoI)*
  

---

## 🎨 Features
- ✋ **Real-time sign detection** with webcam input  
- 🧠 **Landmark extraction & ML classification** (Random Forest)  
- 📝 **Instant text output** for each recognised sign  
- 🔊 **Text-to-speech synthesis** for audible translation  
- 🌗 **Light / Dark UI** (HTML + CSS front-end)  
- 🗂 **User dashboard** with profile, feedback & usage stats  
- 🎥 Built-in demo video and screenshots for quick preview  

---

## 📂 Project Structure
```plaintext
Gestura/
├── app.py                     # Flask / streamlit app runner
├── collect_imgs.py            # Script: capture images for dataset
├── create_dataset.py          # Build training data from captures
├── train_classifier.py        # Train Random Forest model
├── inference_classifier.py    # Real-time inference loop
├── requirements.txt           # Python dependencies
│
├── templates/                 # *.html pages (home, login, dashboard…)
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── contact.html
│   └── ...
│
├── static/
│   ├── main.css               # Global styles
│   ├── main.js                # Front-end logic
│   ├── images/                # Backgrounds, icons
│   └── hand-signs-of-the-ASL-Language.png
│
├── model.p                    # Trained Random Forest pickle
├── data.pickle                # Landmark encoder
├── demo (2).mp4               # Local demo video
└── README.md                  # You’re reading it!
```
| Account  | Home |
|-----------|------------|
| ![Home](./Screenshot%202025-01-28%20105641.png) | ![Login](./Screenshot%202025-01-30%20221835.png) |

| Login | About |
|----------|----------|
| ![Dashboard](./Screenshot%202025-01-30%20221905.png) | ![Feedback](./Screenshot%202025-01-30%20221937.png) |

| Feedback  |  Database |
|-------------|---------------|
| ![Camera](./Screenshot%202025-01-30%20222018.png) | ![Settings](./Screenshot%202025-01-30%20222513.png) |

| Camera Page |
|--------------|
| ![Profile](./Screenshot%202025-01-30%20224408.png) |

---

## 🚀 Getting Started

### 📦 Install Dependencies

```bash
git clone https://github.com/Shristirajpoot/Gestura.git
cd Gestura
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
pip install -r requirements.txt

▶️ Run the Application
bash
Copy
Edit
python app.py
```
Open http://localhost:5000 in your browser and allow webcam access.

## ✋ Supported Gestures
| ASL Sign   | Output           |
| ---------- | ---------------- |
| A, B, C... | Alphabet letters |
| Hello      | “Hello”          |
| Yes / No   | “Yes” / “No”     |
| Thank you  | “Thank you”      |
| Digits 0-9 | Numbers          |


## 🛠️ Built With
- 🐍 Python 3

- 🖼 MediaPipe – hand-landmark detection

- 📸 OpenCV – camera capture & image processing

- 🌲 Scikit-learn Random Forest – gesture classification

- 🔊 pyttsx3 / gTTS – text-to-speech

- 🌐 HTML + CSS + JS – front-end templates

## 👩‍💻 Author
### Shristi Rajpoot
- 📧 shristirajpoot369@gmail.com
- 🔗 GitHub @Shristirajpoot

## 📄 License
This project is licensed under the MIT License — feel free to use, modify & share with attribution.

### 🌟 If you find Gestura helpful, please ⭐ star the repo and spread the
