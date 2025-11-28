# Attention-based-unet-for-segmentation

The goal of this project was to run the **U-Net model with and without the attention gate** to compare its influence on the **segmentation of medical images**.

The dataset consisted of **20 T2-weighted MRI images + masks**, with **5 classes to segment**: background, liver, left kidney, right kidney, and spleen.

The results highlight the superior performance of the model with the attention gate, achieving Dice scores around or above 0.6 for each of the classes. Even though some classes were more frequent than others, a balance was maintained throughout the training. Additional improvements are suggested in the slides.

Below are some of the results observed.

![Results obtained with the U-Net](https://github.com/Emanuelle-p/Attention-based-unet-for-segmentation/blob/main/unet.png)

![Results obtained with the U-Net with attention gate](https://github.com/Emanuelle-p/Attention-based-unet-for-segmentation/blob/main/unet_with_attention_gate.png)
