
# Traffic Light State Detection

![download](https://github.com/user-attachments/assets/1d08f3ff-7c36-44f1-b2f6-1c421013908d)


Developed by **Anderson Sales, Felipe Jun Hatsumura, and Igor Caetano** as part of the **INE410121** course at **UFSC**.

## 📌 Objective

This project aims to develop an application capable of automatically detecting the state (red, yellow, or green) of traffic lights in images using computer vision techniques and convolutional neural networks.

## 💡 Motivation

Cardiovascular diseases kill one Brazilian every 90 seconds, making it one of the leading causes of death. While this fact is not directly linked to traffic light detection, it inspired the use of **artificial intelligence techniques** in critical domains such as **healthcare** and **traffic**, where automatic and fast decision-making can also save lives.

## 👥 Target Audience

- Health and data science professionals
- Students and researchers in engineering, AI, and medicine
- Policy makers and analysts in public safety or mobility

## 📊 Datasets Used

1. **Heart Disease Dataset** (UCI Repository)  
   - [Dataset link](https://archive.ics.uci.edu/dataset/45/heart+disease)  
   - Multivariate, categorical, integer, and real data  
   - 303 instances and 13 features  
   - Requires preprocessing due to missing and inconsistent data  

2. **Traffic Light Detection Dataset** (Kaggle)  
   - [Dataset link](https://www.kaggle.com/datasets/wjybuqi/traffic-light-detection-dataset)

## 🛠️ Technologies and Algorithms

- **Faster R-CNN** ([PyTorch documentation](https://pytorch.org/vision/stable/_modules/torchvision/models/detection/faster_rcnn.html))
- **Retinex** for low-light image enhancement  
  - [Research article](https://www.researchgate.net/publication/323180489)  
  - [Implementation](https://santhalakshminarayana.github.io/blog/retinex-image-enhancement)
- **OpenCV** for image processing  
  - [Official documentation](https://docs.opencv.org/)
- **HoughCircles** for circle detection  
  - [Tutorial](https://medium.com/turing-talks/houghcircles-detec%C3%A7%C3%A3o-de-c%C3%ADrculos-em-imagens-com-opencv-e-python-2d229ad9d43b)

## 📁 Project Structure

```
├── data/                # Datasets
├── notebooks/           # Jupyter Notebooks for exploration
├── src/                 # Main source code
│   ├── preprocessing/   # Data preprocessing scripts
│   ├── models/          # Model implementations and training
│   └── utils/           # Utility functions
├── results/             # Generated outputs and plots
├── requirements.txt     # Project dependencies
└── README.md            # This file
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/andersonzambeli/visao_computacional.git
   cd visao_computacional
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the training and inference scripts in the `src/` folder.

## 📚 References

- [Project repository](https://github.com/andersonzambeli/visao_computacional)
- [Faster R-CNN - PyTorch](https://pytorch.org/vision/stable/_modules/torchvision/models/detection/faster_rcnn.html)
- [Retinex Enhancement Blog](https://santhalakshminarayana.github.io/blog/retinex-image-enhancement)
- [OpenCV Documentation](https://docs.opencv.org/)
- [HoughCircles with OpenCV](https://medium.com/turing-talks/houghcircles-detec%C3%A7%C3%A3o-de-c%C3%ADrculos-em-imagens-com-opencv-e-python-2d229ad9d43b)
