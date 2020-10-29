# Preprocessed IXI Dataset

## IXI Dataset Description

IXI Dataset contains nearly 600 MR images from normal, healthy subjects.

### Acquisition protocol
- T1, T2, and PD-weighted images
- MRA images
- Diffusion-weighted images (15 directions)

### Scanning Location
- Hammersmith Hospital using a Philips 3T system
- Guy’s Hospital using a Philips 1.5T system
- Institute of Psychiatry using a GE 1.5T system

### Dataset Reference
The IXI dataset is available under the Creative Commons CC BY-SA 3.0 license. For more detailed information and download, please refer to [the official website of IXI project](https://brain-development.org/ixi-dataset/)

## Preprocessing
The T1 MRI data were used and preprocessed to generate normalised brain volume maps. The grey matter (GM) and white matter (WM) images were analyzed together.

### Steps

1. AC-PC Realignment
2. GM, WM Tissue Segmentation
3. Non-linear registration to MNI152 space
4. Normalization
5. Resampling
6. modulation
7. 4mm Smoothing

### Results
The result, normalized brain volume map, has shape of 121x145x121. Each voxel in the volume map represent regional volume of tissue.
 
### Software Environment
All images were pre-processed using [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) in the MATLAB R2018a environment. [DARTEL](http://www.neurometrika.org/node/34) which is one of the SPM extension was used for normalization, non-linear registeration, resampling, modulation and smoothing step.

### Preprocessing Reference
We followed the protocol from the paper ["Predicting brain age with deep learning from raw imaging data results in a reliable and heritable biomarker"](https://scholar.google.co.kr/scholar?hl=en&as_sdt=0%2C5&q=Predicting+brain+age+with+deep+learning+from+raw+imaging+data+results+in+a+reliable+and+heritable+biomarker&btnG=) by James H. Cole et al. For the very detailed preprocessing tutorial of Voxel-based Morphometry(VBM), see [here](https://www.fil.ion.ucl.ac.uk/~john/misc/VBMclass15.pdf)

## Download
Before we upload the preprocessed data to the Server of XAI Center, we can access to the dataset through this [temporary link](http://gofile.me/6Kggy/ZkPKhFdE5)

## Acknowledgement

<img src="http://xai.unist.ac.kr/static/img/logos/XAIC_logo.png" width="300" height="100">

### **Project Name**
> A machine learning and statistical inference framework for explainable artificial intelligence(의사결정 이유를 설명할 수 있는 인간 수준의 학습·추론 프레임워크 개발)

### **Managed by**
> Ministry of Science and ICT/XAIC

### **Participated Affiliation**
> UNIST, Korea Univ., Yonsei Univ., KAIST., AItrics

### **Web Site**
> <http://openXai.org>

### LICENSE
> This data is made available under the Creative [Commons CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/legalcode).
