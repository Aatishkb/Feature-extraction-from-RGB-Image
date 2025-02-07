# Feature Extraction from RGB Images
## Overview
- This project focuses on extracting meaningful features from RGB images. The process includes loading an image, converting it to a numerical format, and analyzing pixel intensity distributions across color channels. The extracted features can be used for various image processing and machine learning tasks.

## Features Extracted
- RGB Histogram Analysis
- Intensity vs. Frequency
- Intensity vs. Probability
- Histogram plots for individual color channels (Red, Green, Blue)
- Feature Extraction from Uniform Distributions

## Calculating mean, standard deviation, skewness, and kurtosis of pixel intensities within uniform bins
- Feature Extraction from Non-Uniform Distributions
- Probability distribution-based feature extraction
- Advanced statistical measurements (skewness, kurtosis)

## Steps Involved

- 1. Import Required Libraries
  - PIL, NumPy, Matplotlib, Scipy
    
- 2. Load and Convert Image
  - Open an RGB image and convert it into a NumPy array
    
- 3. Histogram Analysis
  - Generate histograms for each color channel
  
- 4. Compare frequency and probability distributions

- 5. Feature Extraction

- 6. Calculate statistical properties (mean, standard deviation, skewness, kurtosis)
     
- 7. Separate bins based on intensity and analyze their distributions

## Visualization
- Histograms to illustrate color intensity distributions
- Plots of probability distributions for each color channel
- Bar charts comparing uniform and non-uniform distributions

## Applications
- Image classification
- Texture analysis
- Medical image processing
- Object recognition

# Load image
image_path = "path/to/image.jpg"
img = Image.open(image_path)
img_array = np.array(img)

# Example: Compute mean intensity of red channel
mean_red = np.mean(img_array[:, :, 0])
print("Mean intensity of red channel:", mean_red)
Dependencies
Python 3.x
NumPy
Matplotlib
SciPy
PIL (Pillow)

## Conclusion
- This project provides a structured approach to extracting features from RGB images. By leveraging histogram analysis and statistical feature extraction, it enables a deeper understanding of image characteristics, useful for computer vision applications.

