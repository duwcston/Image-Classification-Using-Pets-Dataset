# Image-Classification-Using-Pets-Dataset
Using pre-trained ResNet50v2 model for multiclass image classification of Oxford-IIIT Pets dataset

## Dataset description

The Oxford-IIIT Pet Dataset is a 37 category pet dataset with roughly 200 images for each class created by the Visual Geometry Group at Oxford. The images have a large variations in scale, pose and lighting. All images have an associated ground truth annotation of breed, head ROI, and pixel level trimap segmentation. [[kaggle.com](https://www.robots.ox.ac.uk/~vgg/data/pets/)]

Original dataset was downloaded from [https://www.robots.ox.ac.uk/~vgg/data/pets/](https://www.robots.ox.ac.uk/~vgg/data/pets/).

## Project Structure
1: Import Libraries and Initial Setup <br />
2: Import Data <br />
3: Understanding the dataset <br />
4: Data Preparation: Image Resizing, Label One-hot Encoding, Image (Data) Augmentation, Batching and Prefetching <br />
5: Model Setup <br />
6: Model Training <br />
7: Model Evaluation <br />
8: Finetune Model <br />

## Model
- [[ResNet50V2](https://keras.io/api/applications/resnet/)]
- [[InceptionV3](https://keras.io/api/applications/inceptionv3/)]
- [[MobileNetV2](https://keras.io/api/applications/mobilenet/#mobilenetv2-function)]
