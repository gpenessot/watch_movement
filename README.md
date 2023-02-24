# watch_movement
---
There are 3 notebooks:
- `app_PyTorch.ipynb`: this notebook is a POC of watch movement image classifier. The model is based on ResNet152 with [fastai](https://www.fast.ai/) library (PyTorch). This beta version model can be tested here : https://huggingface.co/spaces/gpenessot/watch_movement_detector
- `app_TensorFlow.ipynb`: this notebooks is a classification model based on VGG16. The aim of this notebook is to explore model results by extracting features map and Grad-CAM. All utilities developed to plot features map and Grad-CAM will be integrated in a specific library. 
- `app_TensorFlow_EfficientNetB7`: A test to fine-tune EfficientNetB7 model. I have to add more samples to my dataset in order to get better performance.

