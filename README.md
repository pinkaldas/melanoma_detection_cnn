# Project Name
Melanoma Detection using CNN


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model was underfitting using basic CNN architecture
- Modifying the CNN architecture does not help in underfitting due to class imbalance
- Modified the existing CNN after class rebalancing and got accuracy of about 85%
- Used VGG-16 for feature extraction only: The model got overfitted.
- Used VGG-16 with Fine Tuning: The validation accuracy jumps to 91% 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas, numpy, matplotlib, seaborn
- library - tensorflow, keras
- library - VGG-16

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@pinkaldas] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->