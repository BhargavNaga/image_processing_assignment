# Digital Image Processing

## Problem Statement 1

### Objective
The objective of this task is to determine the quality of a degraded face image compared to its original without utilizing built-in functions like PSNR (Peak Signal-to-Noise Ratio). The degradation process involves:

1. **Blur the Image:**
   - Utilize a blurring filter to degrade the image. This simulates the effect of capturing images in less than ideal conditions or with a low-quality camera.

2. **Add Gaussian Noise:**
   - Introduce Gaussian noise to the blurred image. Gaussian noise is a random noise that follows a Gaussian distribution. This noise addition mimics real-world scenarios where images may be corrupted during transmission or storage.

3. **Compress and Decompress Using JPEG 2000:**
   - Compress the image using the JPEG 2000 standard, which is commonly used for image compression. 
   - Then decompress the compressed image to a degree of 70% - 80% to further degrade the image quality.

