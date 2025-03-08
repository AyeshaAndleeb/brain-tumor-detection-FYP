# Brain Tumor Detection Using Deep Learning

## 🚀 Project Overview
This project is part of my Final Year Project (FYP) and focuses on detecting brain tumors using deep learning techniques applied to MRI images. The application is built with Flask and uses a convolutional neural network (CNN) model to classify MRI images into four categories:
- **Pituitary Tumor**
- **Glioma Tumor**
- **Meningioma Tumor**
- **No Tumor**

The project aims to provide an intuitive web interface where users can upload MRI images and receive predictions along with confidence scores.

---

## 🌟 Key Features
- **Real-Time Prediction:** Upload MRI images to get instant predictions.
- **Confidence Score:** Displays the probability of the predicted class.
- **User-Friendly UI:** Simple and clean interface using HTML and Flask.
- **Image Visualization:** Shows uploaded image and prediction results.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS (Bootstrap)
- **Backend:** Flask (Python)
- **Modeling:** TensorFlow, Keras
- **Deployment:** Flask Development Server
- **Libraries:**
  - `Flask`: Web framework
  - `TensorFlow/Keras`: Deep learning model
  - `Pillow`: Image processing
  - `Numpy`: Numerical operations

---

## 📂 Project Structure
```
📦 Brain-Tumor-Detection
├─ models/                 # Pre-trained model (.h5 file)
├─ sample-mri-images/      # Sample images for testing
├─ templates/              # HTML templates (index.html)
├─ uploads/                # Folder for storing uploaded images
├─ venv/                   # Virtual environment
├─ main.py                 # Flask app
├─ requirements.txt        # Python dependencies
└─ README.md               # Project documentation
```

---

## ⚙️ Setup & Installation
1. **Clone the Repository:**
```sh
git clone https://github.com/AyeshaAndleeb/brain-tumor-detection-FYP.git
cd brain-tumor-detection-FYP
```

2. **Create a Virtual Environment:**
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies:**
```sh
pip install -r requirements.txt
```

4. **Run the Application:**
```sh
python main.py
```

5. **Access the App in Browser:**
Navigate to `http://localhost:5000`.

---

## 🚧 How to Use
1. Launch the web app.
2. Upload an MRI image through the provided interface.
3. View the prediction result and confidence score.

---

## 📈 Model Performance
- The model was trained on a comprehensive dataset of MRI images.
- Achieved high accuracy with robust performance on unseen data.

---

## 💡 Future Improvements
- Enhance the UI for better user experience.
- Integrate advanced preprocessing techniques for image enhancement.
- Deploy on a cloud platform for broader accessibility.

---

## 📝 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

---

## 🙌 Acknowledgements
- **Mentors:** Special thanks to my mentors for their guidance.
- **Dataset Source:** [Kaggle Brain MRI Images Dataset](https://www.kaggle.com)

---

## 📧 Contact
For any questions or suggestions, feel free to contact me via [LinkedIn](https://www.linkedin.com/in/ayeshaandleeb/) or open an issue on this repository.

---

Made with ❤️ by Ayesha Andleeb
