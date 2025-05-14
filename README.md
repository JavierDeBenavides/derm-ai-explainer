# 🧠 derm-ai-explainer
Skin lesion classifier with explainable AI (Grad-CAM) using CNNs and ISIC dataset

## 🎯 Project Objectives

- Classify skin lesions (e.g., melanoma vs. benign) from dermoscopic images.
- Provide visual explanations for predictions using Grad-CAM.
- Deliver a simple, interactive interface for demonstration and testing.
- Promote responsible and interpretable AI in medical diagnostics.

## 🛠️ Tech Stack

- Python 3
- TensorFlow / Keras
- Grad-CAM
- Streamlit or Gradio (for the app interface)
- Matplotlib, NumPy, Pandas
- (Optional) Docker for deployment

## 📂 Project Structure

```bash
derm-ai-explainer/
├── data/                  # Dataset-related scripts or instructions
├── notebooks/             # Jupyter notebooks for EDA and experiments
├── model/                 # Model definitions and training scripts
├── app/                   # Streamlit or Gradio app
├── requirements.txt       # Dependencies
├── Dockerfile             # For deployment (optional)
└── README.md              # Project documentation
