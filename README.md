# Canny Edge Detection

The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images. It was developed by John F. Canny in 1986. Canny also produced a computational theory of edge detection explaining why the technique works.

## Process of Canny Edge Detection Algorithm

The Process of Canny edge detection algorithm can be broken down to 5 different steps:

1) Apply Gaussian filter to smooth the image in order to remove the noise
2) Find the intensity gradients of the image
3) Apply non-maximum suppression to get rid of spurious response to edge detection
4) Apply double threshold to determine potential edges
5) Track edge by hysteresis: Finalize the detection of edges by suppressing all the other edges that are weak and not connected to strong edges.
