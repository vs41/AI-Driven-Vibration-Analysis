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





📉 Compressive Sensing for Image Compression & Reconstruction:
Compressive Sensing (CS) is an advanced technique that allows the reconstruction of signals or images from fewer samples than traditional methods require. It leverages the idea that many natural signals are sparse or compressible in some domain (like DCT or wavelet), allowing significant data reduction with minimal quality loss.

🧠 How It Works:
Compression (Sensing): Acquire a small number of linear measurements from the original image.

Reconstruction: Use optimization (e.g., Basis Pursuit, L1 minimization) to recover the full image from those few measurements.

This project demonstrates CS applied to images, showing how well the image can be reconstructed even after aggressive compression.

![11](https://github.com/user-attachments/assets/12be767d-359b-4932-88bf-415336f9ab5a)
![22](https://github.com/user-attachments/assets/cf4b829c-6e1c-4ca3-a4da-03610e8f9dcc)



🔬  Validation with Experimental Data


![23](https://github.com/user-attachments/assets/4eaba35e-0e8a-4735-b723-99c692eb4d19)

Displacement vs. Time for the Cantilever Beam

The orange graph represents the experimental displacement data recorded using an accelerometer. The measurement is taken at a point located 250 mm from the fixed base of the cantilever beam.

The blue graph represents the algorithmically computed displacement at the same location using the proposed method.

Both graphs exhibit a similar trend, demonstrating good agreement between experimental and predicted results. The observed error in displacement magnitude is approximately 1% to 2%, indicating strong accuracy of the algorithm.

➡️ Conclusion:
The displacement predicted by the algorithm closely matches the experimental data, validating the reliability and accuracy of the proposed method.

By using Sobel operator method for cantilever beam:







