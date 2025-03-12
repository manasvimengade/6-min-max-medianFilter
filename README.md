# 6-min-max-medianFilter
The Mean-Median-Max Filter combines three filtering techniques: mean filtering (for noise smoothing), median filtering (to remove impulse noise), and max filtering (to preserve bright pixels). This hybrid approach reduces various types of noise while maintaining important image features like edges and highlights.

Mean Filter: A linear filter that replaces a pixel with the average of its neighbors, used for Gaussian noise reduction, but it blurs edges.
Median Filter: A non-linear filter that replaces a pixel with the median of its neighbors, effective for salt-and-pepper noise removal while preserving edges.
Max Filter: A non-linear filter that replaces a pixel with the maximum value in the neighborhood, useful for enhancing bright regions and morphological operations.
