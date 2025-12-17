# CNN-Based Retinal Image Denoising

This project explores neural network–based denoising for biomedical imaging using retinal fundus images from the DRIVE dataset.

A convolutional neural network (CNN) is trained to remove synthetic Gaussian noise from clean images. Performance is compared against classical Gaussian filtering using PSNR and SSIM metrics.

The results demonstrate that CNNs preserve structural details more effectively than traditional filters, motivating interest in more advanced probabilistic denoising approaches.

## Methods
- Dataset: DRIVE retinal fundus images
- Noise model: additive Gaussian noise
- Model: shallow convolutional neural network
- Evaluation: PSNR, SSIM, visual comparison

## Results
![Comparison](figures/comparison.png)
