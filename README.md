# Morphological-Transformations
Apply morphological transformations (e.g., erosion, dilation) to an image using OpenCV
import cv2
import numpy as np

image = cv2.imread('input.jpg', 0)
kernel = np.ones((5, 5), np.uint8)

# Implement morphological transformations (e.g., erosion, dilation)

cv2.imwrite('morph_transformed.jpg', transformed_image)
