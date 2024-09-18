## MNIST

The MNIST database (Modified National Institute of Standards and Technology database) is a cornerstone dataset in the fields of machine learning and computer vision, particularly for tasks involving handwritten digit recognition. Here's a comprehensive overview of MNIST and its significance:

## **1. Composition of the Dataset** ##
  -  Training Set: Contains 60,000 grayscale images of handwritten digits.
  -  Test Set: Contains 10,000 grayscale images for evaluating model performance.
  -  Source: Derived from two larger NIST databases:
  -  Special Database 1: Handwritten digits from high school students.
  -  Special Database 3: Handwritten digits from employees of the United States Census Bureau.
## **2. Image Specifications ** ##
  -  Resolution: Each image is 28x28 pixels.
  -  Color Depth: Grayscale, with pixel values ranging from 0 (background) to 255 (foreground).
  -  Size Normalization: Original NIST images, which are black and white (bilevel), are resized to fit within a 20x20 pixel box while maintaining the aspect ratio. This resizing introduces grayscale levels due to the anti-aliasing techniques employed.
  -  Centering: The images are centered in the 28x28 frame by calculating the center of mass of the pixel intensities and translating the image so that this center aligns with the center of the 28x28 grid. This ensures consistency in the positioning of digits across the dataset.
