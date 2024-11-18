# Project Name
> Melanoma Detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Problem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
  It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential 
  to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
  All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of 
  melanomas and moles, whose images are slightly dominant.


## Conclusions
- With basic CNN model, High training accuracy (92%), but poor validation accuracy (53%). Likely overfitting.
- With Data Augmentation & Dropout:Reduced training accuracy (56%) and lower validation accuracy (45%). Likely underfitting.
- Class Balance + Batch Normalization: High training accuracy (91%) but poor validation accuracy (50%) and very high loss. Model struggling to generalize.
- Class Balance + L2 Regularization (No Batch Norm): Improved validation accuracy (79%) with decent training accuracy (87%). Good balance.
- For 50 epochs, further improved validation accuracy (81%) and reduced loss. Model shows better generalization.


## Technologies Used
- tensorflow - 2.18.0
- keras - 3.6.0

## Acknowledgements

- I would like to express my gratitude to upGrad for providing the opportunity to work on this project as part of their AI and ML curriculum. This project has been 
  an excellent learning experience, allowing me to apply theoretical knowledge to a real-world problem.



## Contact
Created by [@Yasmin-NS] - feel free to contact me!

