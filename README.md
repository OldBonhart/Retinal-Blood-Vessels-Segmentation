## Retinal Blood Vessel Segmentation
---
### Motivation :
Automatic segmentation of medical images is an important step to extract useful information that can help doctors make a diagnosis. For example, it can be used to segment retinal vessels so that we can represent their structure and measure their width which in turn can help diagnose retinal diseases.

### Data
Available [here](https://hzfu.github.io/proj_deepvessel.html)

### Formulation of the problem:
Each pixel must be labeled “1” if it is part of a blood vessel in the image, and “0” if not.

### Solution:
[Retinal_Blood_Vessel_Segmentation.ipynb](https://github.com/OldBonhart/vessel_segmentation/blob/master/Retinal_Blood_Vessel_Segmentation.ipynb)[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1LTd4JT2TzLOM0pbgSXhhk6sQUUyM7vwf#scrollTo=0yAq9xteMY2l)<br>
This is a simple implementation neural net with architecture **UNet** on pytorch, as part of the extension for [**MedEyeService**](https://github.com/OldBonhart/MedEyeService).

### Results :
![alt](https://github.com/OldBonhart/vessel_segmentation/blob/master/reuslt.png)
