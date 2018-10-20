# pneumonia-localization


Not long ago, the machine learning group at Stanford University led by Adjunct Professor Andrew Ng released a paper on their computer vision algorithm which can detect and localize pneumonia for x-ray chest scans. Their algorithm outperformed the average practising radiologist at Stanford.Their algorithm achieved an accuracy of about 94%. Their project really inspired me so I decided to try it out. 

This project uses a pretrained VGG-16 neural network architecture to detect pneumonia in chest xray scans and  draw a heatmap to indicate areas the neural network used to classify it as an image containing pneumonia or not.
I used a training set consisting of almost 5300 images  of chest xray scans and validation set of almost 430 images. The algorithm achieved an accuracy of 97% on the training set and 88% percent on the validation set. There is a bit of high variance due to not having a large dataset. Link to dataset: https://www.kaggle.com/nielspace/chest-x-ray/data
Note!!
image labelled p-1-new-ai-can-diagnose-pneumonia-better-than-doctors.jpg wasn't my work
 
 update
!!!! 20/10/2018 !!!!
Changed model to vgg19 and that seemed to perform a little better than the vgg16 with accuracy of 89%. I also noticed that the network used the  inscription on the upper right of  some images to make predictions in addition to the areas necessary.
Demonstration can be seen in image labelled chest_abnormality.png
