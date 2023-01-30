# breast-cancer-image-segmentation-attention-unet
Breast cancer is one of the most common causes of death among women worldwide. Early detection helps in reducing the number of early deaths. The data reviews the medical images of breast cancer using ultrasound scan. Breast Ultrasound Dataset is categorized into three classes  :
  normal, benign, and malignant images. Breast ultrasound images can produce great results in classification, detection, and segmentation of breast cancer when combined with machine learning.

The data collected at baseline include breast ultrasound images among women in ages between 25 and 75 years old. This data was collected in 2018. The number of patients is 600 female patients. The dataset consists of 780 images with an average image size of 500*500 pixels. The images are in PNG format. The ground truth images are presented with original images. The images are categorized into three classes, which are normal, benign, and malignant.

Approach

AttentionUNet/UNet is the best know model for Multi-Class Segmentation, thats why we will be creating a Attention UNet Model.
As the image Dataset is old, please do not use it for any new medical operations.
All the images are of 500 X 500 pixels, Kaggle RAM wil not be enough so we will be resizing the Image to 256 X 256 pixels.
Model Architecture

The Model will consist of a Encoder Block, Decoder Block and a Attention Gate.
