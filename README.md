# GenText-Forensics

GenText-Forensics is a lightweight multimodal document forgery detection system for detecting and explaining manipulation in text-rich document images.

## Main Features

- Authentic vs. forged document classification
- Suspicious-region visualization
- OCR text extraction
- Basic forensic explanation
- Lightweight training pipeline
- Google Colab training support
- Laptop-friendly inference

## Dataset

The project uses a selected subset of the RealText-V2 dataset.

Large dataset files are intentionally excluded from GitHub and should be stored in Google Drive or another suitable storage location.

## Planned Pipeline

Document Image  
↓  
Image Preprocessing  
↓  
Lightweight CNN  
↓  
Authentic / Forged Classification  
↓  
Grad-CAM  
↓  
OCR  
↓  
Forensic Explanation  

## Technology Stack

- Python
- PyTorch
- torchvision
- OpenCV
- Hugging Face
- Grad-CAM
- OCR
- Streamlit
- Google Colab

## Project Structure

```text
GenText-Forensics/
├── data/
├── notebooks/
├── src/
├── models/
├── outputs/
├── app/
├── README.md
├── requirements.txt
├── config.yaml
└── .gitignore
```

## Development Stages

1. Dataset exploration
2. Dataset preprocessing
3. Authentic/forged classification
4. Model evaluation
5. Grad-CAM visualization
6. OCR integration
7. Forensic explanation generation
8. Streamlit application
