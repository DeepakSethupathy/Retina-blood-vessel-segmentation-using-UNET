# Retina-blood-vessel-segmentation-using-UNET
Vessel segmentation from fundus images using UNET.

![image](https://user-images.githubusercontent.com/60769429/86891372-59ea6500-c11c-11ea-9b28-5fcc890486c0.png)

Semantic segmentation can be used to detect the vessels in fundus images. In semantic segmentation each pixel of an image is labelled either as blood vessel or background (0, 1). UNET is a deep learning architecture developed by Olaf Ronneberger et al for medical image segmentation. It consists of a contraction path and expansion path. The architecture is given above.

## Parameters

For the training of neural network DRIVE data is used.
It consists of 20 fundus images and the blood vessels labelled by ophthalmologist.
Random 48x48 patches are cropped from each image. 
Total of 2000 patches were extracted. 1600 patches were used for training and 400 for validation.

## Results 
