# 🏥 DICOM Viewer – Medical Image Visualization Tool
[![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)](https://python.org)

<p align="center">
<img src="https://raw.githubusercontent.com/abdullah-gamil05/ImageBasedAnatomy_Tasks/main/task5_Dicom_Viewer/results/gui.png" alt="GUI Overview" width="700">
</p>

## 🔬 Overview
The DICOM Viewer is designed to handle complex medical imaging data with support for multiple visualization modes. Whether you're working with single 2D slices, multi-slice datasets, or full 3D volumes, this application provides the tools needed for comprehensive medical image analysis.

**Project Timeline**: December 2024
**Institution**: Cairo University - Faculty of Engineering
**Course**: Intro to Imaging and Image-Based Anatomy

## ✨ Features

### 🖼️ Comprehensive Image Display

- **2D Visualization**: Sequential slice display with video playback capabilities
- **M2D (Multi-slice 2D)**: Tile-based arrangement and video rendering for multi-slice analysis
- **3D Visualization**: Volumetric tile display for comprehensive 3D exploration

### 🛠️ Interactive Analysis Tools

- **Real-time Adjustments**: Dynamic zoom, pan, brightness, and contrast controls
- **Precision Navigation**: Frame-by-frame navigation for detailed analysis
- **Multi-modal Support**: Optimized viewing for different imaging modalities

#### 🔍 Advanced DICOM Features

- **Metadata Explorer**: Comprehensive DICOM tag search and display
- **Patient Information**: Detailed study, series, and image metadata review
- **Data Anonymization**: Secure patient data removal for research and sharing
- **Tag Search**: Quick lookup of specific DICOM attributes

### 🔒 Privacy & Security

- **HIPAA Compliance**: Built-in anonymization features
- **Secure Processing**: Patient data protection during analysis
- **Research Ready**: Anonymized exports for academic use

---
## 🛠️ Tech Stack

- **Language**: Python 3.7+
- **GUI Framework**: Tkinter
- **Image Processing**:
  - pydicom - DICOM file handling
  - Pillow (PIL) - Image manipulation
  - NumPy - Numerical computations
- **Visualization**: Custom rendering engine

  ## 📂 Project Structure
```bash
 dicom-medical-viewer/
├── requirements.txt        # Python dependencies
├── data/
│   ├── input/             # Sample DICOM files
│   └── output/            
├── src/
│   ├── main_viewer.py 
│   └── 3d_tiles_viewer.py   
└── README.md             # This file
   ```
## 📦 Installation
### Prerequisites
Ensure you have Python 3.7 or higher installed on your system.

### Setup Instructions

#### 1. Clone the repository
 ```bash
   git clone https://github.com/3bdullah-Gamil/dicom-medical-viewer.git
cd dicom-medical-viewer
   ```

#### 2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

#### 3. Run the application
```bash
  python main.py
- Python 3.7+
   ```

## 🚀 Usage
### etting Started

#### 1. Launch the Application
```bash
  python main.py
   ```

#### 2. Load DICOM Files
- Click "Load DICOM" button
- Browse and select (`.dcm`) files
- The application will automatically detect the image type (2D/M2D/3D)

#### 2. Explore Your Data

- Use interactive controls for zoom, pan, and contrast adjustment
- Navigate through slices using the built-in controls
- Access metadata through the tag search feature


## 📁 Supported Formats
### Input Formats

- **File Extension**: (`.dcm`) (DICOM files)
- **Imaging Modalities**:
  - CT (Computed Tomography)
  - MRI (Magnetic Resonance Imaging)
  - Other DICOM-compliant modalities

### Output Capabilities

- **Visualizations**: Video sequences, tiled displays
- **Anonymized Files**: Securely processed DICOM files
- **Metadata Exports**: Comprehensive tag information

  
## 📸 Example Visualizations

### 2D Sequential Slice Display

<img src="https://raw.githubusercontent.com/abdullah-gamil05/ImageBasedAnatomy_Tasks/main/task5_Dicom_Viewer/results/image1.png" alt="2D Slices" width="600">

### M2D Tile Arrangement

<img src="https://raw.githubusercontent.com/abdullah-gamil05/ImageBasedAnatomy_Tasks/main/task5_Dicom_Viewer/results/m2d_cine.gif" alt="M2D Cine" width="600">

### 3D Volume Tiles

<img src="https://raw.githubusercontent.com/abdullah-gamil05/ImageBasedAnatomy_Tasks/main/task5_Dicom_Viewer/results/3d_tiles_view.png" alt="M2D Tiles" width="600">


## 🔮 Future Enhancements
- GPU-accelerated rendering for faster performance.
- AI-driven segmentation for automated region-of-interest detection.
- Web-based deployment for remote access.

## 👥 Team Members
- **Abdullah Gamil**
- **Mohamed Badawy**
- **Rowaida Mohamed**
- **Yomna Sabry**



## References
1. RadiAnt DICOM Viewer: [https://www.radiantviewer.com](https://www.radiantviewer.com)
2. MicroDicom Viewer: [https://www.microdicom.com](https://www.microdicom.com)
3. PyDicom Documentation: [https://pydicom.github.io](https://pydicom.github.io)

---

