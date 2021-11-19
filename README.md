# Food-101-Vision-Clasification

## Overview
Abstract. In this paper we address the problem of automatically recognizing
pictured dishes. To this end, we introduce a novel method to
mine discriminative parts using Random Forests (rf), which allows us
to mine for parts simultaneously for all classes and to share knowledge
among them. To improve efficiency of mining and classification, we only
consider patches that are aligned with image superpixels, which we call
components. To measure the performance of our rf component mining
for food recognition, we introduce a novel and challenging dataset of
101 food categories, with 101'000 images. With an average accuracy of
50.76%, our model outperforms alternative classification methods except
for cnn, including svm classification on Improved Fisher Vectors and
existing discriminative part-mining algorithms by 11.88% and 8.13%, respectively.
On the challenging mit-Indoor dataset, our method compares
nicely to other s-o-a component-based classification methods.

## my goal 
beating the accuracy that specified in the 'Overview' part using transfer learnin CNN model

this dataset paper and dataset can be find link : https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/
