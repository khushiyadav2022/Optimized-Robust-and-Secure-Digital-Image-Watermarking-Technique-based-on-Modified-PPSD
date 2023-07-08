# Optimized-Robust-and-Secure-Digital-Image-Watermarking-Technique-based-on-Modified-PPSD
Robust and Secure Digital Image Watermarking Technique

[Paper](https://github.com/khushiyadav2022/Optimized-Robust-and-Secure-Digital-Image-Watermarking-Technique-based-on-Modified-PPSD/blob/0f37ba4d359694edb6206dd317f7d6f1ffa61ab9/purkh%20paper.pdf)

In my M.Tech thesis, I developed an advanced method for digital image watermarking called "Optimized, Robust, and Secure Digital Image Watermarking Technique based on Modified Periodic and Smooth Decomposition" (PPSD). This technique combines the principles of Periodic and Smooth Decomposition (PPSD), Discrete Wavelet Transform (DWT), and Singular Value Decomposition (SVD) to achieve improved results.

The process begins by decomposing the host and watermark images into smooth and periodic components. The smooth component is further decomposed into frequency sub-bands using 2nd level DWT. Next, the watermark singular matrix is combined with the singular matrix of the transformed image through SVD. To obtain the watermarked image, the inverse of DWT is applied.

By employing this proposed technique, several key parameters were enhanced. The Peak Signal-to-Noise Ratio (PSNR) increased to 92.9075, while the Structural Similarity Index Measure (SSIM) for the watermarked image reached 0.8039, and the SSIM for the extracted watermark was 0.9924. Additionally, the Normalized Cross-Correlation (NCC) value was measured at 0.9929. These results demonstrate that the proposed technique is both imperceptible and robust against various types of attacks.

During the development, we encountered a false positive problem when using SVD. However, we successfully addressed this issue by incorporating a digital signature. The digital signature provides authentication prior to the extraction of the watermark image, ensuring the reliability and integrity of the watermarking process.

<h1 align="center">Embedding procedure</h1>

![image](https://github.com/khushiyadav2022/Optimized-Robust-and-Secure-Digital-Image-Watermarking-Technique-based-on-Modified-PPSD/assets/108923908/575b0321-a51d-48bf-ad5e-b380c4f441f9)


<h1 align="center">Extracting procedure</h1>

![image](https://github.com/khushiyadav2022/Optimized-Robust-and-Secure-Digital-Image-Watermarking-Technique-based-on-Modified-PPSD/assets/108923908/3d0d3f21-9de1-4360-9c01-1852e57f9d9a)


In my M.Tech thesis, I developed an advanced method for digital image watermarking called "Optimized, Robust, and Secure Digital Image Watermarking Technique based on Modified Periodic and Smooth Decomposition" (PPSD). This technique combines the principles of Periodic and Smooth Decomposition (PPSD), Discrete Wavelet Transform (DWT), and Singular Value Decomposition (SVD) to achieve improved results.

The process begins by decomposing the host and watermark images into smooth and periodic components. The smooth component is further decomposed into frequency sub-bands using 2nd level DWT. Next, the watermark singular matrix is combined with the singular matrix of the transformed image through SVD. To obtain the watermarked image, the inverse of DWT is applied.

By employing this proposed technique, several key parameters were enhanced. The Peak Signal-to-Noise Ratio (PSNR) increased to 92.9075, while the Structural Similarity Index Measure (SSIM) for the watermarked image reached 0.8039, and the SSIM for the extracted watermark was 0.9924. Additionally, the Normalized Cross-Correlation (NCC) value was measured at 0.9929. These results demonstrate that the proposed technique is both imperceptible and robust against various types of attacks.

During the development, we encountered a false positive problem when using SVD. However, we successfully addressed this issue by incorporating a digital signature. The digital signature provides authentication prior to the extraction of the watermark image, ensuring the reliability and integrity of the watermarking process.





