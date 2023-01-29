# A simple CNN for Multiple Sclerosis (MS) diagnosis using Magnetic resonance imaging (MRI). (Under Construction)
### Info ℹ️
For my final master's thesis, I developed and implemented a simple convolutional neural network to help facilitate, accelerate and improve the complex process of diagnosing the disease.

Early diagnosis of the disease can help to control the disease in its earliest stages, extending patients' expectancy and quality of life.

### Dataset 📝
For the development of this model, the following open access [dataset](https://www.kaggle.com/datasets/buraktaci/multiple-sclerosis) obtained from the Kaggle platform was used.

The dataset contains a total of 3427 MRI images of the brain, in two different views (Axial and Sagittal) and distributed as follows:
+ 1002 Axial view control images
+ 1014 sagittal view control images
+ 650 Axial view MS images
+ 761 Sagittal view MS images

Or, in other words:
+ 1411 MS images
+ 2016 control images

Three different models were implemented:
1. Model with all images
2. Model with axial view images
3. Model with the sagittal view images

### Results ✅
Results produced by the model were as follows:
1. Model with all images - 97% accuracy
2. Model with the axial view images - 98% accuracy
3. Model with sagittal view images - 98% accuracy

**Detailed model results can be found at the end of the Jupyter Notebook files.**

### Versions 🛠 
For the development of the project, the free version of Google Colab was used, so the computational power greatly limited the training phase of the model. They were also used for the design of the CNN PyTorch and torchvision.
Python
```
Python 3.7.13
```
Pytorch
```
1.12.1+cu113
```

### Endnotes ✍🏻
This information is only a part of the work done, if you need more information please do not hesitate to contact me.
