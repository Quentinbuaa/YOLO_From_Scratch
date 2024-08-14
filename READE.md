# YOLO_From_Scratch

## Introduction
In the repository, I provide the code to implement YOLO v1. YOLO is an object detection program based on maching learning. Since object detection is quite useful in our daily life, and YOLO has a rather impressive performance at this job, YOLO becomes famous among both industry and schools. As a teacher teaching computer vision, I need to introuce YOLO to students. Even though it is okay for me to just give them a big picture or just call the weights trained by others as illustration, I still want to go down to details. And this motivated me to write a yolo from scratch, so that I can learn and teach others better.

YOLO is built on the base of convolutional neural network. Neural network is nothing but an operation of matrix, or tensors (a high dimension of matrice, used to have more than three dimensions). Neural network can transform on matrix in a certain shape to another matrix with a new shape. YOLO is no exception. 

The input of YOLO is 3D tensor, in the shape of CxHxW, which is treated as an RGB colorful image by our human. The output of YOLO is also a 3D tensor, in the shape of SxSx(B*5J%$RT+C), which  


an image, represented with a tensor, such as CxHxW. The output matrix of YOLO is cubic tensor,
