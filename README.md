# LViT-Vision-Transformer-for-Lung-Cancer-Detection

Lung cancer is one of the leading causes of mortality for males and females worldwide. Machine learning plays a crucial role in the automated detection, segmentation, and computer aided diagnosis of malignant lesions. In our study, we trained a vision transformer model using computer tomography (CT) scans. To establish if cancer is malignant or benign, the results are then compared to lung cancer images. Pre-classifying CT images from the initial dataset were the first stage. Since the entire image cannot be processed for the training model, we employed segmentation to break the image up into patches. To process the image through the transformer encoder and keep the training process on schedule and adjust to the variance in the images, the image has been separated into patches. The transformer's output is now the MLP head. Using the vision transformer model, we achieved the best accuracy of 91.93% after extensive training with 100 epochs.

Link to Paper: 
https://ieeexplore.ieee.org/document/10085230
