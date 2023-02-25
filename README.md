# Skin Cancer Classifier (Pytorch)

Dataset used - [Kaggle Link](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## About Dataset

Dataset contains 7470 unique neoplasm photos from 7 types of cancers - 

1. Melanocytic nevi
2. Melanoma
3. Benign keratosis-like lesions
4. Basal cell carcinoma
5. Actinic keratoses
6. Vascular lesions
7. Dermatofibroma

## Training 

The model chosen was densenet 121 model pre-trained with Imagenet dataset. The model was trained for 15 epochs with Nvidia V100 GPU.

## Result Metrics

<img width="517" alt="Screen Shot 2023-02-25 at 4 41 18 AM" src="https://user-images.githubusercontent.com/55760893/221354964-11959249-ba74-4597-ad03-b352dddb6e57.png">

