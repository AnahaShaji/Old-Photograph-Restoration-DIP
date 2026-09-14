# Old Photograph Restoration Using Image Enhancement and Blur Reduction

## Project Overview

Old photographs can suffer from blur, loss of sharpness, poor contrast, and other forms of degradation. This project uses Digital Image Processing techniques to improve the quality of vintage photographs.

Different restoration and enhancement techniques are applied and compared to identify the most effective method.

## Objectives

- Improve the visual quality of degraded vintage photographs.
- Reduce the effect of blur using image processing techniques.
- Apply different restoration and enhancement methods.
- Compare the performance of different techniques.
- Evaluate the results using MSE, PSNR, and SSIM.

## Dataset

The project uses the **Vintage Photo Restoration Clean and Damaged Image** dataset from Kaggle.

- Total images: 200
- Clean images: 146
- Damaged images: 54
- Image format: JPG
- Images used for main experiment: 10 clean images

The clean images were used as reference images. Gaussian blur was applied to simulate image degradation for quantitative evaluation.

## Techniques Used

- Gaussian Blur
- Median Filtering
- Laplacian Sharpening
- Unsharp Masking
- High-Boost Filtering
- Histogram Equalization
- CLAHE
- Combined Image Restoration

## Evaluation

The restoration methods were evaluated using:

- **MSE (Mean Squared Error)**
- **PSNR (Peak Signal-to-Noise Ratio)**
- **SSIM (Structural Similarity Index)**

The average results across 10 images showed that **Unsharp Masking** achieved the best overall performance.

### Best Result

- MSE: **154.32**
- PSNR: **27.83 dB**
- SSIM: **0.7990**

## Tools and Libraries

- Python
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Scikit-image
- KaggleHub

## Project Structure

```text
Old-Photograph-Restoration-DIP/
│
├── DIP_Old_Photograph_Restoration_Using_Image_Enhancement_and_Blur_Reduction.ipynb
├── README.md
├── requirements.txt
├── images/
├── screenshots/
└── report/
```
## Conclusion

The project demonstrates how Digital Image Processing techniques can be used to improve the sharpness and visual quality of degraded vintage photographs. Among the tested methods, Unsharp Masking provided the best overall performance for the selected images.

## Author

**Anaha Shaji**

BCA

Marian College, Kuttikkanam
