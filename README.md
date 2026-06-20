# 🧠 Human Face Identification App

A Streamlit-based Computer Vision application that detects human faces in uploaded images using OpenCV's Haar Cascade Classifier.

The application provides an interactive interface where users can upload images, adjust detection parameters, and visualize detected faces in real time.

---

## 🌟 Features

✅ Human Face Detection

✅ Interactive Streamlit Dashboard

✅ Adjustable Detection Parameters

✅ Image Upload Support

✅ Face Highlighting with Bounding Boxes

✅ Real-Time Detection Results

✅ Face Count Display

---

## 🛠️ Technology Stack

| Category             | Technologies            |
| -------------------- | ----------------------- |
| Programming Language | Python                  |
| Web Interface        | Streamlit               |
| Computer Vision      | OpenCV                  |
| Image Processing     | NumPy, Pillow           |
| Face Detection       | Haar Cascade Classifier |

---

## 📂 Project Structure

```text
human-face-identification-app/
│
├── app.py
├── requirements.txt
└── README.md
```

---


## 📸 Application Output

### Uploaded Image

<img width="933" height="807" alt="Screenshot 2026-06-18 222309" src="https://github.com/user-attachments/assets/53a8cd7f-6290-42df-b074-70cb4b2d3eff" />


### Face Detection Result

<img width="1062" height="787" alt="Screenshot 2026-06-18 222340" src="https://github.com/user-attachments/assets/9b8d7df5-3ae8-4e5d-9336-92f1d4fa131c" />


---

## ⚙️ How It Works

### Step 1

Upload an image (JPG, JPEG, or PNG).

### Step 2

The image is converted to grayscale for processing.

### Step 3

OpenCV Haar Cascade detects human faces.

### Step 4

Detected faces are highlighted with bounding boxes.

### Step 5

The total number of detected faces is displayed.

---

## ✨ Detection Controls

Users can adjust:

* Scale Factor
* Minimum Neighbors

These parameters help fine-tune face detection accuracy.

---


##  Installation

### Clone Repository

```bash
git clone https://github.com/RohithaKavala/human-face-identification-app.git
```

### Navigate to Project

```bash
cd human-face-identification-app
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 🔮 Future Improvements

* Real-Time Webcam Face Detection
* Face Recognition using Deep Learning
* Emotion Detection
* Face Mask Detection
* Multi-Person Analysis

---

## 👩‍💻 Author

**Rohitha Kavala**


---

## ⭐ Support

If you found this project useful, consider giving it a Star ⭐ on GitHub.
