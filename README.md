# alzheimer-mri-classification
MRI-based classification of Alzheimer's disease stages (CN, MCI, AD) using deep learning.

This project focuses on the classification of Alzheimer's disease stages using 3D brain MRI data and deep learning.

The objective is to automatically classify patients into three clinical categories:
- Cognitively Normal (CN)
- Mild Cognitive Impairment (MCI)
- Alzheimer's Disease (AD)

A 3D Convolutional Neural Network (CNN) is trained on preprocessed MRI volumes to learn spatial patterns associated with disease progression.

## links to the database
https://adni.loni.usc.edu/data-samples/adni-data/neuroimaging/mri/mri-image-data-sets/
For this project, I used 3T scan data, choosing ADNI1: Complete 3Y 3T for greater precision, as the collection was carried out over a longer period of time.
Once on the site, just follow the steps outlined to access the data and download it. Make sure you have enough memory, of course.

## Methodology
- Loading and matching MRI (NIfTI) files with clinical metadata
- Preprocessing and normalization of 3D brain images
- Construction of a custom PyTorch dataset
- Training of a 3D CNN model
- Evaluation using classification accuracy

## Technologies
- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- NiBabel
- SciPy

## Execution Time
Due to the size of MRI volumes and the use of 3D convolutional networks, training and preprocessing may take several hours depending on hardware resources.

## Notes
This project was developed for educational and research purposes and is not intended for clinical use.
