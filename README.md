# 🧠 Brain Tumor Segmentation using U-Net

## 📌 Overview
This project implements a deep learning-based approach for brain tumor segmentation from MRI images using the U-Net architecture. The model performs pixel-wise classification to accurately detect tumor regions and support medical image analysis.

## 🧠 Model Architecture
- U-Net (Encoder-Decoder CNN)
- Skip connections to preserve spatial information
- Designed for biomedical image segmentation tasks

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib

## 📂 Dataset
- Brain MRI images dataset
- Preprocessed (resizing, normalization)
- Used for supervised segmentation tasks

⚠️ Dataset is not included due to size limitations.

## 📥 Download Resources
- Model Weights: https://drive.google.com/file/d/1ET2f3fyCAHLiYQOQAHxTlEOHCE142gx3/view?usp=drive_link
- Dataset: https://drive.google.com/file/d/1hd2eA5NsJl6x8uWgaJIsbjKOtGfVdpEu/view?usp=drive_link

After downloading, place them like this:

project/
│
├── code.ipynb
├── weights/
├── data/

## 🚀 How to Run
1. Download dataset and model weights  
2. Place them in the correct folders  
3. Run the notebook using Jupyter Notebook or Google Colab  

## 🧪 Training & Results
- Trained a U-Net model for pixel-wise tumor segmentation  
- Processed MRI images for tumor vs healthy tissue classification  
- Improved performance through preprocessing and normalization  
- Achieved consistent segmentation results on validation samples  

## 📊 Evaluation Metrics
- Dice Coefficient  
- Intersection over Union (IoU)  
- Pixel Accuracy  

## ⚡ Key Features
- Automatic tumor segmentation  
- High spatial accuracy using U-Net skip connections  
- End-to-end deep learning pipeline  
- Applicable to real-world medical imaging problems  

## 🔮 Future Work
- Improve accuracy using larger datasets  
- Apply data augmentation techniques  
- Extend to 3D segmentation (3D U-Net)  

## 👨‍💻 Author
- Karam Khziem
