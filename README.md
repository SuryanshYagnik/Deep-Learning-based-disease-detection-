**Identification of Corn Leaf Disease Using Deep Learning**

The rapid identification and early prevention of crop diseases play a pivotal role in enhancing agricultural productivity. This paper presents an innovative approach leveraging deep Convolutional Neural Network (CNN) models to effectively identify and diagnose plant diseases based on leaf images. Given the remarkable success of CNNs in machine vision, our implemented models demonstrate promising accuracy in disease identification.

The evaluation of model performance involves tuning various parameters, including batch size, dropout rates, and the number of epochs. Notably, our models, namely CNN, VGG16, ResNet50, and AlexNet, achieved impressive disease-classification accuracy rates of 95.56%, 90.25%, 92.18%, and 93.30%, respectively. These results surpass the performance of traditional handcrafted-feature-based approaches.

The findings underscore the potential of deep CNN models to significantly enhance the efficiency of disease identification, offering promising prospects for real-time implementation in agricultural systems. This research contributes to the advancement of precision agriculture by providing accurate and timely disease diagnosis, thereby supporting sustainable crop management practices.

## Setup

Clone the repo, submodules and install the required packages.

```
git clonehttps: //github.com/SuryanshYagnik/Deep-Learning-based-disease-detection.git
cd Deep-Learning-based-disease-detection
conda create -n DL_Model python=3.10
conda activate DL_Model
pip install -r requirements.txt
source setup.sh
```

## Training

We provide training scripts under `training_scripts/`. Try them out from the top-level directory of this repository.

## Evaluation

Evaluation codes are put in evaluation/ directory. Most of our evaluations follow existing high-incluence open-source repos. Please refer to each sub-directory for the corresponding detailed README and running script.
