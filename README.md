# Prostate-Gland-Segmentation-Based-on-Deep-Learning-in-T2-Weighted-MRI
Three individually trained densenet201 architectures ensembled to build a fully automated method for prostate segmentation in
3D T2-weighted MRI volumes. Keras library has been used. Read REPORT.pdf for more detailed technical description of the project.

This project is licensed under the terms of the MIT license.

## Attached files
In ./Attachments/ subfolder (please read the report -REPORT.pdf-  before for a better understanding of attachments' description):
* s01_pre-processing for training.ipynb: script performing the pre-processing of the images;
* s02_training script.ipynb: script implementing the training of the individual networks
* s03_testing script.ipynb: script loading the trained models, ensemobling them, predicting the segmentation masks and computing the performances of the model on the dataset partitions.
