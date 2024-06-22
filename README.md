# Image-Processing-Techniques
A comprehensive suite of image processing techniques, encompassing essential morphological operations such as dilation, erosion, closing, and opening. Additionally, it includes advanced features like quality assessment and image comparison metrics such as Universal Quality Index (UQI), Quality Index (QI), and Percentage Fit Error (PFE).


# Morphological Operators:
## Dilation
Dilation is a morphological operation that adds pixels to the boundaries of objects in an image, increasing the size of foreground objects and filling in small holes.

![Dilation](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/55b0e57a-69cb-40e3-a4a3-5bf8f2242470)


## Erosion
Erosion is a morphological operation that removes pixels on the object boundaries, shrinking the size of foreground objects and eliminating small protrusions.

![Erosion](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/4f8320a7-c036-41de-8018-a532b3d7ce92)


## Opening 
Opening is a morphological operation that consists of an erosion followed by a dilation. It is useful in removing noise from the foreground of an image, as well as separating objects that are touching.

![Opening](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/863a45ce-91e4-4c66-9faf-802853ebcb9d)

## Closing
Closing is a morphological operation that consists of a dilation followed by an erosion. It is useful in closing small holes and gaps in the foreground, as well as smoothing the boundaries of objects.

![Closing](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/c954d9b2-a8b3-4039-a1ec-e432d2b2e188)

## Notes
- Structuring Element (B): It defines the neighborhood used for the operation. It can be of various shapes and sizes depending on the desired effect, here are some examples of Structuring Elements:
  
![Structuring Element](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/b5175162-c944-4fbc-8ed9-96d3cce33bf4)

- Binary Images (A): These are images with pixels that are either black (background) or white (foreground).
  
- These morphological operations are fundamental in preprocessing images for tasks such as segmentation, feature extraction, and noise reduction in digital image processing and computer vision applications.
  
# Quality Assessment and Image Comparison:

## Universal Quality Index
The Universal Quality Index (UQI) is a metric used to assess the similarity between a reference image and a fused image. It takes into account the mean, variance, and covariance of the images to compute a quality score.

![UQI](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/58c60b42-16fa-4327-a3b0-50868afae951)


## Quality Index
The Quality Index (QI) is another metric for image quality assessment, similar to UQI. It evaluates the similarity between a reference image and a fused image based on their statistical properties like mean, variance, and covariance.

![QI](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/7682cb5d-f437-4b6e-a00f-ea6791983bf4)


## Percentage Fit Error
The Percentage Fit Error (PFE) measures the difference between two grayscale images, typically a reference and a comparison image, by calculating the normalized difference in their norms.

![pfe](https://github.com/Khaledayman9/Image-Processing-Techniques/assets/105018459/7c77a22f-dd2f-42a8-9e1a-e2ac58614f23)

## Notes
- These metrics are commonly used in image fusion and comparison tasks to quantitatively assess the quality and similarity of images.
  
- The functions provided are Python implementations using libraries like NumPy and PIL (Pillow) for image processing and mathematical operations.

- These metrics help in objectively evaluating the performance of image fusion algorithms and comparing different image processing techniques based on their output quality.

## Technologies:
- Python
- Google Colab
