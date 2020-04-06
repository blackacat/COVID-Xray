Overview
----
This repository is a PyTorch implementation of the paper "COVID-SCREENNET: AN AI POWERED POPULATION SCREENING OF COVID-19 CASES USING CHEST RADIOGRAPHY IMAGES".

Dataset
-----
The COVID cases are available [here](https://github.com/ieee8023/covid-chestxray-dataset).  
The normal and pneumonia cases are available [here](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge).


Transfer Learning
----
![](readme/transfer_learning.PNG)

Some Results
----
Longitudinal XCR images of a patient over the four time points.  
![](readme/one_patient.PNG)



Models
----
The model weights are available here.  
You can test your own image by:
```
python testing.py --image <X-ray path>
```

Thumbnail of generated heatmaps
-----
![](readme/heatmap.PNG)




Dependencies
-----
* Python 3.7
* Pytorch 0.4.0


