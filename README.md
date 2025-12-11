# This-repository-includes-the-project-of-lightweight-networks-CrackSeg-GWD
CrackSeg-GWD: Automatic lightweight networks for Multi-Material Bridge Crack Segmentation
Datasets used on this study:

1. The SteelCrack dataset [33] is a widely used benchmark for steel crack detection and segmentation. It contains images collected from structural health monitoring projects, including inspections of the Nanjing Second Yangtze River Bridge and the Humen Bridge. The dataset features cracks with diverse characteristics, such as variations in length, width, and color, and captures scenes under different environmental and background conditions. Some images also include handwritten markings made by field inspectors, providing a realistic representation of practical inspection scenarios. The dataset is divided into 3,300 training images, 525 validation images, and 530 test images, offering a well-balanced split for deep learning–based segmentation studies. "Z. He, W. Chen, J. Zhang, Y.H. Wang, Crack segmentation on steel structures using boundary guidance model, Autom Constr 162 (2024). https://doi.org/10.1016/j.autcon.2024.105354."
SteelCrack dataset :https://github.com/hzlbbfrog/Civil-dataset. 

2. The YCD dataset contains images of two main types of surface defects: road cracks and concrete wall cracks. Variations in camera distance and angle result in cracks of different scales, from fine hairlines to large visible fractures. The dataset includes 776 images, split into 622 for training and 154 for testing. All images were resized to 512 × 512, matching the preprocessing used for other datasets such as DeepCrack537. Figure 7 shows sample images that reflect the dataset’s diversity in crack types and scales. "X. Yang, H. Li, Y. Yu, X. Luo, T. Huang, X. Yang, Automatic Pixel-Level Crack Detection and Measurement Using Fully Convolutional Network, Computer-Aided Civil and Infrastructure Engineering 33 (2018). https://doi.org/10.1111/mice.12412."
YCD dataset : 
Concrete Crack Segmentation Dataset: The concrete dataset comprises a total of 3,616 images, each sized 4032 by 33024 pixels. Among these, 1,744 images, along with their corresponding ground truth, were derived. This subset includes 458 high-resolution images of concrete surfaces captured at Middle East Technical University

Ozgenel dataset:https://data.mendeley.com/datasets/jwsn7tfbrp/1

DeepCrack dataset comprises 537 images with a resolution of 544 x 384 pixels, accompanied by ground truth images at the pixel level.

DeepCrack dataset:https://github.com/yhlleo/DeepCrack

Crack500 dataset consists of 1896 training images and 1124 testing images, all at a resolution of 640 × 360 pixels. Notably, Crack500 offers a diverse range of crack shapes and widths, presenting significant challenges for crack segmentation tasks.

Crack500 dataset: https://github.com/fyangneil/pavement-crack-detection
