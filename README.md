# 🟧 Chemical-Pipelines-Corrosion-Detection-Model
Corrosion Detection Model for Chemical Pipelines using Digital Image Processing techniques. The project uses image-based analysis with Gabor filters and GLCM for texture feature extraction, along with a Streamlit-based interface for real-time prediction of corroded and normal pipeline images.

## 📌 Overview

Corrosion in pipelines is a major issue in industries as it affects safety and efficiency. It can lead to leakage, damage, and safety risks.
Traditional inspection methods are manual, time-consuming, and expensive. This project provides an automated way to detect corrosion from pipeline images using image processing techniques.

## ⚙️ Workflow

The system follows an image-based processing pipeline:
```
Input Image → Preprocessing → Feature Extraction → Classification → Output
```

## ⚙️ Methodology

The system follows an image-based workflow:

1. Input pipeline image
2. Image preprocessing (resize, rotation, flip)
3. Feature extraction using:
   - Gabor Filters (texture extraction)
   - GLCM (statistical features)
4. Classification of image as:
   - Corroded
   - Normal

## 🧠 Technologies Used

- Python
- OpenCV
- NumPy
- Streamlit
- PyTorch

## 📊 Dataset

- Initial dataset: ~120 images
- Expanded to ~1200 images using data augmentation
- Includes both corroded and normal pipeline images

## 🚀 Features

- Automatic corrosion detection
- Simple web interface using Streamlit
- Fast and easy to use
- Image-based analysis

## 🖥️ How to Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the app:
   ```
   python -m streamlit run webapp.py
   ```

## 📌 Output

The system predicts:

- "Corrosion Detected"
- "No Corrosion Detected"

## 📈 Future Improvements
- Real-time detection
- Larger dataset
- Improved accuracy
- IoT integration

## 📁 Project Structure
```
Chemical-Pipelines-Corrosion-Detection-Model/
├── Pipeline Corrosion Detection Final Dataset/
│   ├── train
│       ├── corroded/
│       └── normal/
│   └── test
│       ├── corroded/
│       └── normal/
├── webapp.py                      # Streamlit app
├── model/
│   └── Corrosion_Detection.pth 
├── notebook/
│   └── Pipeline_Corrosion_Detection_Model.ipynb
├── README.md
├── .gitignore
└── requirements.txt
The trained model (.pth) and dataset are not included due to size limitations.
```

## 👨‍💻 Author
**Dev Patel**

## 👨‍💻 Contribution
This project was fully developed independently, including dataset preparation, model implementation, and interface development.
