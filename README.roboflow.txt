
Object-Bus-Dataset - v9 2024-03-23 10:49pm
==============================

This dataset was exported via roboflow.com on March 23, 2024 at 3:50 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 1224 images.
Bus-line-number-and-num-of-bus are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random shear of between -10° to +10° horizontally and -10° to +10° vertically
* Salt and pepper noise was applied to 1.51 percent of pixels


