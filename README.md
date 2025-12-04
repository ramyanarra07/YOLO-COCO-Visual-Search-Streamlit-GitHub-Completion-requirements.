# YOLO-COCO-Visual-Search-Streamlit-GitHub-Completion-requirements.# YOLOv11 Image Search using Streamlit

##  Project Title
**YOLOv11-Based Image Search and Object Detection Web Application**

## NAME : NARRA RAMYA
## REG NO :212223040128
Project: YOLOv11 Image Search and Object Detection using Streamlit

---

## Abstract / Introduction
This project demonstrates an end-to-end **object detection and image search system** using the **YOLOv11 model** and **Streamlit**.  
The application allows users to upload or browse images, and automatically detects multiple objects within them using the **COCO 2017 dataset** categories.

The project was implemented locally in **VS Code** using a **Conda environment**, ensuring reproducibility and smooth deployment. It aims to combine the power of deep learning and interactive web deployment through Streamlit.

---

##  Dataset & YOLO Model Details (COCO)
- **Dataset:** COCO (Common Objects in Context) 2017 validation subset  
- **Model Used:** `yolo11m.pt` (YOLOv11 medium pre-trained model)  
- **Framework:** PyTorch for model inference  
- **Number of Classes:** 80 COCO object classes  
- **Input Source:** Local image files stored or uploaded by users

YOLOv11 is a high-performance object detection model capable of real-time detection with high accuracy. It was selected for this project due to its balance between inference speed and precision.

---

## Environment Setup
All development and testing were performed locally on **Windows 11** using **VS Code** and **Anaconda**.

### Tools Used:
- Visual Studio Code (VS Code)
- Anaconda (Conda environment)
- Python 3.11
- Streamlit (for web interface)
- PyTorch (for YOLO inference)

### Required Files:
- `app.py` — main Streamlit application  
- `src/` — contains supporting scripts (`inference.py`, `config.py`, `utils.py`)  
- `requirements.txt` — all dependencies  
- `yolo11m.pt` — pretrained YOLOv11 model weights  
- `Screenshots/` — folder with execution and output screenshots  

---

## CPU Installation Steps
(For users without GPU support)

```bash
# Step 1: Create and activate Conda environment
conda create -n yolov11 python=3.11 -y
conda activate yolov11

# Step 2: Navigate to the project directory
cd C:\Users\admin\Downloads\Yolov11_Image_search\Yolov11_Image_search

# Step 3: Install all dependencies
pip install -r requirements.txt
```
## How to Run in VS Code using Conda

Follow these steps carefully:

# Activate Conda environment
conda activate yolov11

# Move into project folder
cd C:\Users\admin\Downloads\Yolov11_Image_search\Yolov11_Image_search

# Run Streamlit web app
python -m streamlit run app.py

After running, Streamlit will display a message like:
You can now view your Streamlit app in your browser.
Local URL: http://localhost:8501

## How to Deploy using Streamlit

Once the environment is set up, deploy the project locally by running:

streamlit run app.py


This launches the YOLOv11 web UI, where users can upload images and view object detection results instantly.

## Output Screenshots (UI + Detection + Terminal)

<img width="894" height="460" alt="image" src="https://github.com/user-attachments/assets/c0dc49bf-8c8b-43fd-8936-bb31454db46f" />

<img width="919" height="526" alt="image" src="https://github.com/user-attachments/assets/8538f4b5-2e2d-4723-b77c-f3c74e2991b2" />

<img width="759" height="712" alt="image" src="https://github.com/user-attachments/assets/90cf6b36-8dba-429b-b2af-19ff6b0ef683" />



## Enhancements / Innovations Added

Added image metadata search to quickly locate images by category or filename.

Included efficient preprocessing pipeline for faster inference.

Integrated Streamlit UI customization for better user experience.

Improved model loading and GPU compatibility handling.

## Results & Conclusion

The YOLOv11 Image Search system successfully detects multiple objects in images with high precision.
By integrating Streamlit, the model’s output becomes interactive and user-friendly.

This project demonstrates how deep learning models can be seamlessly deployed for end-user interaction using minimal resources.

## Key Results:

Real-time object detection with YOLOv11m

Smooth and interactive Streamlit web interface

Fully deployable on CPU-based systems

Modular code for easy extension and reuse
```
📂 Project Structure
Yolov11_Image_search/
 ┣ app.py
 ┣ requirements.txt
 ┣ src/
 ┃ ┣ config.py
 ┃ ┣ inference.py
 ┃ ┗ utils.py
 ┣ processed/
 ┣ yolo11m.pt
 ┣ Screenshots/
 ┗ README.md
```
