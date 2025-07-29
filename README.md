# FireNet-Lite-Lightweight-Network-for-Fire-Detection  
A Specialized Lightweight Fire Detection Model for Real-Time IoT and Embedded Applications

This repository contains the implementation of **FireNet-Lite**, a highly efficient CNN-based model designed for real-time fire image classification using depthwise separable convolutions. With only **7,693 trainable parameters**, it is well-suited for deployment on resource-constrained devices like IoT surveillance systems and drones.

---

(Preprint of the research paper on this work will be available soon. Please consider citing this repository if you happen to use the code or model in your work.)

---

## Citation
@misc{ghous2024firenetlite,
title={FireNet-Lite: A Separable Convolutional Network for Ultra-Efficient Fire Image Classification},
author={Ali, Ghous and Ansari, Mohammad Samar and Ahmed, Muhammad and Yasir, Muhammad Sanad},
year={2024},
note={GitHub Repository: [https://github.com/ghous-ali/FireNet-Lite](https://github.com/ghous-ali/FireNet-Lite)}
}

---

In our paper, we used a training dataset accessed directly from Google Drive:
🔗 [Google Drive Fire Detection Dataset](https://drive.google.com/drive/folders/16n3vjADP-xO3Xcgm1t_dDOBcRH-07pck?usp=sharing)

for Testing 
🔗 [https://drive.google.com/drive/folders/1seop28o10RJANG4QCr10bYNHhvwBFInZ?usp=sharing](https://drive.google.com/drive/folders/1seop28o10RJANG4QCr10bYNHhvwBFInZ?usp=sharing)

All training was performed using this dataset, which contains labeled images and videos for fire and non-fire scenes. Testing was conducted on held-out samples from this dataset to ensure fair and unbiased evaluation across diverse fire scenarios.
---

The following is the link to our Kaggle dataset used for training and evaluation:  
🔗 https://www.kaggle.com/datasets/atulyakumar98/test-dataset

---

### Key Highlights
- ✅ Only 7,693 trainable parameters
- ✅ Accuracy: 93.00%
- ✅ Recall: 96.57%
- ✅ Precision: 91.21% 
- ✅ Optimized for edge and real-time applications

---

For details about the architecture, evaluation metrics, and deployment scenarios, please refer to the full notebook or our upcoming paper.

