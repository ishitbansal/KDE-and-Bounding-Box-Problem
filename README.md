# Kernel-Density-Estimation

Done as part of the course SMAI/Monsoon23

Implemented Kernel Density Estimation (KDE). It includes the following functions

- allows selection from the following kernels: box, gaussian, triangular
- fit data
- select appropriate bandwidth using the pseudo-likelihood method
- evaluate the density given an input x
- visualize the data and the estimated pdf. For this, assumed that the function will be used only when input dataset is 1-D or 2-D.

### Bounding Box Problem

The primary objective of the bounding box problem is to accurately define the boundaries of these entities while maintaining their spatial relationships within the document layout. This often requires determining optimal thresholds for horizontal and vertical distances between bounding boxes, ensuring that connections are established within paragraphs while preserving the structural integrity of paragraphs and columns. 

Using the KDE implemented, estimated the appropriate horizontal and vertical thresholds to apply to the distances between the boxes, that boxes within the same paragraphs are connected and there are no connections to boxes in other paragraphs.

Visualized the density estimated and thresholded document for each of the hyperparameter settings per image.
