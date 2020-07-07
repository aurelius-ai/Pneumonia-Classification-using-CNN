# Pneumonia-Classification-using-CNN
The project is about diagnosing pneumonia from XRay images of lungs of a person using Convolutional Neural Network 
Pneumonia is a very common disease. It can be either: 
* Bacterial pneumonia 
* Viral Pneumonia 
* Mycoplasma pneumonia 
* Fungal pneumonia. 
This dataset I have useed consists pneumonia samples belonging to the first two classes. 
The dataset consists of only very few samples and that too unbalanced. The aim of this kernel is to develop a robust deep learning model from scratch on this limited amount of data. We all know that deep learning models are data hungry but if you know how things work, you can build good models even with a limited amount of data.

For the sake of keeping it real I havent used data augumentation in this workbook. The reason being simple is that in real life we cant augument from Xray images. X-ray scans are only taken in a specific orientation, and variations such as flips and rotations will not exist in real X-ray images.
