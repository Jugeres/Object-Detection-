# 🚀 Computer Vision Labs with PyTorch, FastAPI & InsightFace

Kumpulan project Computer Vision yang dibuat menggunakan **PyTorch**,
**TorchVision**, **FastAPI**, **Tkinter**, dan **InsightFace**.

## 📌 Projects

### Lab 1 --- Faster R-CNN Object Detection

-   Training Faster R-CNN
-   Deteksi **Person** dan **Bicycle**
-   Fine-tuning model pretrained
-   Model saving (.pth)

### Lab 2 --- FastAPI Detection Service

-   REST API `/detect`
-   JSON response
-   Load trained model
-   CORS support

### Lab 2 GUI Client

-   Upload image
-   Drag & Drop
-   Bounding box visualization

### Face Recognition

-   Face Detection
-   Face Embedding
-   Webcam Recognition
-   Threshold Evaluation
-   TAR & FAR

## 🛠 Tech Stack

-   Python
-   PyTorch
-   TorchVision
-   FastAPI
-   Uvicorn
-   InsightFace
-   OpenCV
-   NumPy
-   Pillow
-   Matplotlib

## 📂 Repository Structure

``` text
.
├── Lab1_FasterRCNN_VOC.ipynb
├── lab2_fastapi_backend.py
├── lab2_gui_client.py
├── recognize.py
├── known_faces/
├── test_images/
└── README.md
```

## ⚙️ Installation

``` bash
pip install torch torchvision fastapi uvicorn insightface onnxruntime opencv-python pillow matplotlib requests
```

## 🚀 Run

Backend

``` bash
uvicorn lab2_fastapi_backend:app --reload --port 8000
```

GUI

``` bash
python lab2_gui_client.py
```

Face Recognition

``` bash
python recognize.py
```

## 👨‍💻 Author

**Afzal Raza S.**\
Informatics Student - Universitas Muhammadiyah Surabaya

⭐ If you like this project, give it a star on GitHub!
