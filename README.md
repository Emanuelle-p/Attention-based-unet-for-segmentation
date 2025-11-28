# Attention-based-unet-for-segmentation

This goal of this project was to run the **U-Net model with and without the attention gate** to compare its influence in the **segmentation of medical images**.

The dataset consisted of **20 T2 MRI images + mask** and **5 classes to segment**: background, liver, left kidney, right kidney and spleen.

The results highlight the better performance of the model with the attention gate, with dice scores higher than 0.5 for each one of the classes. Some improvements are also suggested in the slides.
