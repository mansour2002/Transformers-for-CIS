# Transformers for Cancer Instance Segmentation
SegFormer, a Transformer-Based Model, for Cell Nuclei Instance Segmentation on PanNuke Dataset Using PyTorch


Overview
------------
SegFormer leverages transformers, a powerful neural network architecture, to achieve high accuracy in segmenting images. This project focuses on applying SegFormer to the task of segmenting individual cell nuclei within microscopy images. The PanNuke dataset provides a collection of labeled images for training and evaluating the model. It is designed to work with the PanNuke extension dataset which includes nearly 200,000 nuclei across various cancer types. The notebook contains detailed Pytorch code for applying deep learning models to perform nuanced segmentation tasks that are crucial for advancing computational pathology.

[SegFormer paper](https://arxiv.org/abs/2105.15203)


Dataset
------------
[Link](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke)


Tversky Loss
------------
The Tversky loss is a differentiable loss function designed for image segmentation tasks. It addresses limitations of other metrics like Jaccard similarity (IoU loss) by incorporating a weighting factor to penalize both false positives and false negatives. This can be particularly useful in imbalanced datasets where one class (e.g., background pixels) might dominate.


Results
------------
These figures show some representative input images and corresponding ground truths and predicted images:

![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%201.png?raw=true)


![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%202.png?raw=true)


![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%203.png?raw=true)


![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%204.png?raw=true)


![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%205.png?raw=true)


![Sample](https://github.com/mansour2002/Transformers-for-CIS/blob/main/Figures/Segmentation%206.png?raw=true)




