# Image-denoising

Satellite Image Denoising using OpenCV
This project demonstrates the use of image denoising techniques to improve the quality of satellite images using Python and OpenCV.
Satellite images often contain noise due to atmospheric interference, sensor errors, or transmission disturbances. Denoising helps improve visual clarity and is essential for accurate interpretation and downstream tasks like object detection and classification.

# Image Denoising using Multiple Filtering Techniques

This project explores and compares various image denoising techniques applied to satellite images in `.rad` and `.png` formats. Both grayscale and RGB color images were denoised using traditional and advanced filtering methods.


# Denoising Techniques Implemented

1. Gaussian Filtering
   - Smooths the image but may blur edges.

2. Median Filtering
   - Effective for salt-and-pepper noise.
   
3. Bilateral Filtering
   - Edge-preserving and smooths based on pixel similarity.

4. Non-Local Means (NLM)
   - Advanced method using self-similarity of patches.
   - Achieved best PSNR scores across images.

5. Channel-wise Denoising (RGB)
   - Applied filters separately on R, G, and B channels for color image enhancement.
     
# Evaluation Metric:
PSNR (Peak Signal-to-Noise Ratio) was used to measure denoising effectiveness.
- Higher PSNR indicates better quality restoration.

