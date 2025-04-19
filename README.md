🫀 AI-Powered Arrhythmia Detection and Electroanatomical Mapping
Welcome to the Hackfest25-15 project! This is a full-stack machine learning application that detects arrhythmia from intracardiac ECG signals and visualizes electroanatomical maps 🧠📈. The project leverages deep learning and medical signal processing to identify cardiac abnormalities and pinpoint their origin on the heart’s surface 🔍.

💡 Project Features
✨ Arrhythmia Detection
✨ ECG Preprocessing and Visualization
✨ Electroanatomical Mapping (EAM)
✨ Origin Estimation of Arrhythmic Events
✨ Streamlit Frontend for Easy Interaction
✨ Upload and Analyze Custom ECG Signals

🧰 Tech Stack
🐍 Python (NumPy, Matplotlib, TensorFlow, Scikit-learn)

🌐 Streamlit (Frontend UI)

🧠 Deep Learning (1D CNN for ECG classification)

📊 Electroanatomical mapping via activation maps
🚀 How to Run
📦 Clone the repo:

git clone https://github.com/hackfest-dev/Hackfest25-15.git cd Hackfest25-15

🧠 Setup environment:

pip install -r requirements.txt

🖥️ Run the frontend:

streamlit run streamlit/app.py

📤 Upload an ECG .npy file and view prediction + map

🧪 Sample Input
Format: A .npy file of shape (500, 12) representing 500 time steps for 12-lead ECG.

Output: "Normal" or "Arrhythmia" + Origin location from the activation map.

📸 Demo Preview
📈 Real-time visualization of ECG
🗺️ 1D to 2D electroanatomical mapping
✅ Arrhythmia classification with origin highlight
