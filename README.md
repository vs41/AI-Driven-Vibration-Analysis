# AI-Driven-Vibration-Analysis

 🧹 Image Denoising: Self-Guided vs Gaussian Filter
This project demonstrates two methods for reducing noise in images:

🔹 Gaussian Filter
A traditional, widely used linear filter that smooths the image by averaging pixel values with a Gaussian kernel. It's effective for general noise reduction but may blur edges.

🔹 Self-Guided Filter
An edge-preserving filter that adapts based on local image structures. It maintains sharper details and edges while still reducing noise, offering better performance in many visual applications compared to standard methods.

🖼️ Results
Below are comparison results showing the effect of both filters on the same noisy image:

📌 Original Image vs Gaussian Filter Vs Self-Guided Filter

![images](https://github.com/user-attachments/assets/f1bc8abf-5cae-4ba3-82ce-1d57a22f6350)
![denoised_image_Gaussian](https://github.com/user-attachments/assets/417ca467-147a-40a6-86e7-7441b5a6323e)
![denoised_image_self](https://github.com/user-attachments/assets/6da8721f-14f0-4cef-8d84-dede1d69b992)



📉 Compressive Sensing for Image Compression & Reconstruction
Compressive Sensing (CS) is an advanced technique that allows the reconstruction of signals or images from fewer samples than traditional methods require. It leverages the idea that many natural signals are sparse or compressible in some domain (like DCT or wavelet), allowing significant data reduction with minimal quality loss.

🧠 How It Works:
Compression (Sensing): Acquire a small number of linear measurements from the original image.

Reconstruction: Use optimization (e.g., Basis Pursuit, L1 minimization) to recover the full image from those few measurements.

This project demonstrates CS applied to images, showing how well the image can be reconstructed even after aggressive compression.

![11](https://github.com/user-attachments/assets/12be767d-359b-4932-88bf-415336f9ab5a)
![22](https://github.com/user-attachments/assets/cf4b829c-6e1c-4ca3-a4da-03610e8f9dcc)







