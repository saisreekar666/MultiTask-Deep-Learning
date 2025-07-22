# 🧠 Multi-Task Deep Learning System: GAN, Object Detection, Captioning & RL Agent

This project showcases a comprehensive AI pipeline combining:
- 🎨 **GANs for image generation**
- 🕵️‍♂️ **Faster R-CNN for object detection**
- 📝 **BLIP for image captioning**


## 📌 Project Overview

This notebook implements an advanced multi-model deep learning architecture featuring both vision and control modules:

### 🔷 Vision AI (Image)
- **GAN**: Generates synthetic images based on noise.
- **Faster R-CNN**: Detects and classifies objects in real images.
- **BLIP**: Generates meaningful image captions using transformer-based multimodal learning.
---

## 📊 Performance Highlights

| Module              | Metric        | Result            |
|---------------------|---------------|-------------------|
| Object Detection    | mAP           | **0.76**          |
| Captioning Quality  | Qualitative   | Human-like captions

---

## 🧩 Tech Stack

- **TensorFlow / PyTorch** (as per task)
- **OpenCV**, **Matplotlib**, **Seaborn** for visualization
- **Transformers** (for BLIP)
- **CUDA** (GPU recommended)

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/multitask-deep-learning.git
cd multitask-deep-learning
pip install -r requirements.txt
jupyter notebook Final_Project_DL.ipynb

