# Four Tile Image Classification
Image classification is one of the most interesting studies in computer vision. The main aim of this project is to classify images among multiple classes using deep learning algorithms such as Convolutional neural networks (CNNs) and ResNet-50. 

In this project, the image dataset named CIFARTile presented by CVPR-NAS is used. Each of CIFARTile image consists with four images from CIFAR10 and its own label. The label is an integer value from 0 to 3 and related to the number of unique classes. To be specific, it is calculated by subtracting one from the total number of unique classes. For example, the image shown below includes two birds, one automobile and one airplane so the number of unique classes is three. Therefore, the label is 2 which is subtracted one from three. More details on the dataset can be found on the page https://github.com/RobGeada/cvpr-nas-datasets .

<p align="center">
  <img src="https://user-images.githubusercontent.com/82886152/218500687-4acedd61-f643-448b-8604-9fc534ddc39c.png">
</p>

To improve model's performance, preprocessing - such as normalisation, scaling, one-hot encoding and data augmentaion -, and hyper-parameter tuning and early-stopping methods are conducted. Additionally, assessment is implemented by the accuracy & loss graph and confusion matrix.

The details can be found in the report uploaded in the repository.
