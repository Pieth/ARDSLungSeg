# ARDSLungSeg
Deep Learning Lung Segmentation for mild, moderate and Severe ARDS lungs in computertomographic images

We programmed an artificial neural network based on the U-Net and trained with ~ 12000 CTs of the lungs. 
The trained model is able to segment the Lungs in the trained dataset to >95% fully automatically. The detection in the test set was ~ 85% accuracy. The intersection over union metric (Jacard Index) was used to determine the accuracy.
Since 85% accuracy is not yet good enough, we of course continue to work on improving the modified U-Net and training with more different pathologies. (e.g. COVID-19 lungs, COPD, pneumonia, etc.)

For the whole process, we used NI LabVIEW version 2019, NI Vision version 2019 and the Deep Learning Toolkit for LabVIEW, DeepLTK version 4.01 from Ngene (Yerevan 0033, Armenia)


The source code with a detailed description and some DICOM example CTs will be uploaded soon.
