# knee-MRI-injury-detection- detection of knee injuries in MRI exams

This repository contains an implementation of a convolutional neural network (ELNet) that classifies specific knee injuries (Meniscus,Abnormal,Acl) from MRI exams.

MRNet is a the knee MRI dataset provided by Stanford.

It's splitted in training set (1130 cases), validation set (120 cases) and test set (120 cases)
we don't have access to the test set.

Each case, in both train and valid folder, has 3 MRI scans taken from different planes: sagittal, coronal and axial.
The 3 MRI scans of a given patient don't necessarily have the same number of slices.

Between different cases (or patients) and for a given plane, MRI scans don't necessarily have the same number of slices either.

out of 1130  
in Abnormal 
913 cases are positive
217 negative

in Acl
208 positive case
922 negative

in Meniscus
397 positive cases
733 negative 

https://github.com/Iffat9/knee-MRI-injury-detection-app next part.

For the detail explantion of this project you can have a look at the video:
https://drive.google.com/file/d/1_QHE1nMp-gCUjwo6KHvgNgTQPDEtBbZ3/view?usp=sharing


 

