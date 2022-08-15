# What's On My Skin: Skin Cancer Detector
<p align="center">
  <img 
    width="540"
    height="710"
    src="https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/ss/x1.jpg"
  >
</p>

## Background and Aim 🏹
Skin cancer is considered as one of the most dangerous types of cancers and there is a drastic increase in the rate of deaths due to lack of knowledge on the symptoms and their prevention. Thus, early detection at premature stage is necessary so that one can prevent the spreading of cancer. Skin cancer is further divided into various types out of which the most hazardous ones are Melanoma, Basal cell carcinoma, Squamous cell carcinoma etc.In the color images of skin, there is a high similarity between different skin lesion like Melanoma and Nevus, which increase the difficulty of the detection and diagnosis. A reliable automated system for skin lesion classification is essential for early detection to save effort, time and human life.This project is about detection and classification of various types of skin cancer using deep learning and image processing tools.



## Tools Used 🧰
- **Python**
- **Fastai**
- **Tensorflow**
- **Gradio**
- **Numpy, Matplotlib, Seaborn**

## Dataset and Categories of Skin Cancers :
- ### Dataset: [Cancer MNSIT HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- ### Categories of Cancer and other Skin Disorder Used:
   - Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
   - basal cell carcinoma (bcc)
   - benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), 
   - dermatofibroma (df)
   - melanoma (mel) 
   - melanocytic nevi (nv) 
   - vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc)

## Notebooks Made 📚🧑🏻‍💻

1. ### [Version 1 ( Tensorflow Based CNN Model)](https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/tree/main/V1(Tensorflow))
- #### Accuracy - 82 %
- #### Architecture(Self-Made Convolutional Neural Network):
<p align="center">
  <img 
    width="400"
    height="1500"
    src="https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/V1(Tensorflow)/model.png"
  >
</p>



2. ### [Version 2 ( Fastai Based Resnet Transfer Learning Model)](https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/tree/main/V2%20Fastai)
- #### Accuracy - 96 %
- #### Architecture( Resnet Architecture):
<p align="center">
  <img 
    width="400"
    height="650"
    src="https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/ss/rs1.png"
  >
</p>


* ##### A simplified view of Resnet 34:

![ss](https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/ss/ss22.png)

## Final Application
- The app was being made using Gradio Framework can be replicated through running this [Version2 Notebook](https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/V2%20Fastai/V2%20Fastai.ipynb).

![ss](https://github.com/AdiNarendra98/WhatsonmySkin-SkinCancerDetector/blob/main/ss/ss1.png)



