# 🧠 Depression Detection System

![Home Page Screenshot](DDS%20Image.jpeg)

A multi-modal emotion recognition project that integrates **text**, **audio**, and **video** analysis to detect emotional cues, potentially indicative of depression. This system applies Natural Language Processing, Speech Emotion Recognition, and Facial Expression Analysis using machine learning and deep learning models.

---

## 📌 Features

- 🔤 **Text Emotion Recognition** – uses NLP and sentiment analysis
- 🎙 **Speech Emotion Analysis** – classifies emotions from audio tone
- 🎥 **Facial Expression Detection** – interprets emotional states via video
- 🧠 Combines results from multiple modalities to strengthen detection accuracy

---

## 🧰 Tech Stack

| Domain        | Tools & Libraries                            |
|---------------|-----------------------------------------------|
| Language      | Python                                        |
| NLP           | NLTK, Scikit-learn, TextBlob, SpaCy (optional)|
| Audio         | LibROSA, pyaudio, TensorFlow/Keras            |
| Video         | dlib, OpenCV                                  |
| Web Framework | Flask                                         |
| Model Storage | HDF5, Pickle, JSON                            |

---

## 📁 Project Structure

```bash
depression-detection-system/
│
├── main.py                  # Main entry point
├── requirements.txt         # Required Python packages
├── library/                 # Core modules for emotion recognition
│   ├── speech_emotion_recognition.py
│   ├── text_emotion_recognition.py
│   └── video_emotion_recognition.py
├── Models/                  # Pretrained ML/DL models
├── templates/               # HTML files for web interface
├── static/                  # CSS, JS, images
├── README.md                # Project documentation
└── .gitignore               # Ignore unnecessary files
🚀 Getting Started
1. Clone the Repository
bash
Copy code
git clone https://github.com/zakelaskar/depression-detection-system.git
cd depression-detection-system
2. Install Dependencies
Make sure you have Python 3.8+ installed.

bash
Copy code
pip install -r requirements.txt
3. Run the App
bash
Copy code
python main.py
Then open http://localhost:5000 in your browser.

📊 Model Details
Audio Emotion Model: Trained using MFCC features + CNN/LSTM

Text Emotion Model: SVM classifier on preprocessed sentiment vectors

Video Model: Face landmarks extracted with dlib and classified via custom NN

Model files are stored in the /Models/ folder.

📦 Deployment Ideas (Optional)
Dockerize the app

Deploy to Heroku, Render, or AWS EC2

🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

📜 License
This project is licensed under the MIT License.
```

## 📬 Contact

**Zakir Elaskar**  
📧 [zelaskar@csuchico.edu](mailto:zelaskar@csuchico.edu) | [elaskarzakir@gmail.com](mailto:elaskarzakir@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/zakelaskar)


