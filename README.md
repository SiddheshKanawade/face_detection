# face_detection

In this project, we use the PCA(Principal Component Analysis) method to recognize various faces.

## Table of contents
* [Problem Statement](#problem-statement)
* [Background](#background)
* [Dataset](#dataset)
* [Technologies](#technologies)
* [Files and Folders](#files-and-folders)
* [Future Extensions](#future-extensions)

## Problem Statement
Design a real-time face recognition system using eigenfaces.

## Background
The primary role in conveying identity and emotion in human interactions is of
the face. The human brain has remarkable abilities to recognize, differentiate
and remember faces. Even with potential hindrances such as ageing, lighting conditions, expressions, the ability to recognize faces is still astounding. Computational models of face recognition, in particular, are interesting because they can contribute not only to theoretical insights but also to practical applications. Criminal identification, security systems, image and film processing, are all aspects where such technology is utilitarian. Even the ability to merely detect faces, let alone recognizing them, can be very practical.

## Dataset
[AT&T Database of Faces](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces/download?datasetVersionNumber=2).

## Technologies
The project uses Python >= 3.8
Instructions to use:
1. Setup the python environment into local system
2. If using `Jupyter Notebook`, then install the requirements.txt
3. Use [official python documentation](https://docs.python.org/3.9/) in case if you face any error.
Other technologies used
* Google Colab / Jupyter Notebook
* Pillow
* Matplotlib
* Numpy

## Files and Folders
`20110199_Assignment2.ipynb`: The main file containing the code.<br>
`Image_dataset`: The database of faces extracted.<br>
`requirements.txt`: The dependencies for the code. They have to be preinstalled.<br>
`20110199_Assignment2.pdf`: The understanding of the algorithm and results of the project.

## Future Extensions
The project can be extended by able to detect the new image if it comes repeatedly. This can be done by storing the new image in the pool of eigen faces(eigen space).
