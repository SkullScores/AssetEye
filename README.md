# AssetEye 🔍

**AssetEye** is an AI-powered infrastructure inspection system that uses drone imagery and deep learning to detect, segment, and analyze critical components and defects across power lines, bridges, solar farms, and more.

---

## 💡 What It Does
- Performs object detection and instance segmentation on ultra-high-res drone images
- Identifies components like insulators, U-bolts, arching horns, and more
- Uses semi-supervised learning with pseudo-labeling to reduce manual annotation
- Processes tiled image patches for scalable training on large datasets

---

## 🧠 Tech Stack
- Python & OpenCV
- Detectron2 (Mask R-CNN, Faster R-CNN)
- CVAT for annotations
- PyTorch & torchvision
- COCO format for training/evaluation

---

## 📁 Project Structure (planned)
AssetEye/
├── data/ # Raw and processed images
├── annotations/ # CVAT, COCO-format labels
├── detector/ # Model code using Detectron2
├── scripts/ # Preprocessing, tiling, training
├── notebooks/ # Visualizations, analysis
├── results/ # Outputs & metrics
├── README.md
├── requirements.txt
└── .gitignore

---

## 🚀 Getting Started
```bash
git clone https://github.com/yourusername/AssetEye.git
cd AssetEye
pip install -r requirements.txt
