# Chu Nom character - Style Classification
Classifying differently styled greyscale character images using neural networks with jupyter notebooks.

### Classification
The `MLP-Classifier.ipynb` notebook contains an implementation of a MLP, following a tutorial, to classify the MNIST dataset. This basic MLP was then expanded with a custom dataset, 
such that it can work with Chu Nom character images. This version of the MLP, as well as some poor prediction results (for a subset of styles), can be found in `MLP-StyleClassifier.ipynb`.  
To improve the accuracy of the style prediction, a CNN was implemented in `CNN-StyleClassifier.ipynb`, which was adapted from a tutorial for a CNN to classify the CIFAR-10 dataset.  
The generated MLP and CNN models are stored in `model.pt` and `model_cifar.pt` respectively.


### Other
The `Testing.ipynb` notebook was used to test, try out or hack together something to get immediate results (not necessairly related to style classification).
