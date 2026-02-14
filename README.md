# RetinaMNIST_classification

### About dataset

MedMNIST is a standartized collection of medical images with miltiple size options.
 
Link to dataset: Data [<a href="https://doi.org/10.5281/zenodo.10519652">Zenodo</a>] Code [<a href="https://github.com/MedMNIST/MedMNIST">GitHub</a>] Preprint [<a href="https://arxiv.org/abs/2110.14795">arXiv</a>] Publication [<a href="https://doi.org/10.1038/s41597-022-01721-8">Nature Scientific Data'23 </a>]

RetinaMNIST is an ordinal regression task for 5 level grading of diabetic retinopathy severity.
Dataset contains 1600 fundus camera images, splitted into train=1080, val=120, and test=400 datapoints. 

RetinaMNIST+ dataset of size 224x224, 3 channels are used in this project.

### Supervised Classification

I tried to repeat baseline classification from original <a href="https://doi.org/10.1038/s41597-022-01721-8">publication<a>. ResNet18 pretrained on ImageNet was adopted with early stopping and learning rate scheduler. 

ACC of 0.59 and AUC of 82 were achieved on test set.


