# Image Colorization Using Deep Learning

This repository contains an implementation of an image colorization system using deep learning techniques. The model converts grayscale images to colored images using state-of-the-art neural networks.

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/aanandmrh222/Image-Colorization.git
cd image-colorization

# Install required packages
pip install -r requirements.txt

# Run colorization on a single image
python colorize.py --image "image path"
python colorize.py --image images/img.jpg
```

## 📋 Requirements

```
torch>=1.9.0
torchvision>=0.10.0
numpy>=1.19.5
opencv-python>=4.5.3
PIL>=8.3.1
matplotlib>=3.4.3
```


## 📋 Download the model files: 

```
1. colorization_deploy_v2.prototxt:    https://github.com/richzhang/colorization/tree/caffe/colorization/models
2. pts_in_hull.npy:        https://github.com/richzhang/colorization/blob/caffe/colorization/resources/pts_in_hull.npy
3. colorization_release_v2.caffemodel: https://www.dropbox.com/s/dx0qvhhp5hbcx7z/colorization_release_v2.caffemodel?dl=1
```


## ✨ Results

Before | After
:-------------------------:|:-------------------------:
![Grayscale]![a1](https://github.com/user-attachments/assets/c9f4d4ec-de83-4c19-8a5c-83946b902a18) | ![Colorized]![a2](https://github.com/user-attachments/assets/95208f16-d755-4861-8adc-eedb3017f614)
![Grayscale]![a3](https://github.com/user-attachments/assets/75a0f49b-3181-4b17-83e2-d71eaad11dbc) | ![Colorized]![a4](https://github.com/user-attachments/assets/ac2faff9-99e3-4583-a764-2b2d5e6ab548)
