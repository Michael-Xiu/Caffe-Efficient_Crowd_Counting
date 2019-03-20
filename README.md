# Efficient Crowd Counting

These codes are implementations of the popular efficient crowd counting models on embedded systems and also the state-of-the-art networks that require high computing power and much memory for comparison. The codes are developed based on the Caffe framework suitable for deployment on embedded systems. We test the speed of these crowd counting models on ARMv8 and NVIDIA Jetson TX2.

## Model list
- <a name="MCNN"></a> **[MCNN]** Single-Image Crowd Counting via Multi-Column Convolutional Neural Network (**CVPR2016**) [[paper](https://pdfs.semanticscholar.org/7ca4/bcfb186958bafb1bb9512c40a9c54721c9fc.pdf)]

![](https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/MCNN.png)
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/MCNN.png" width="841" height="495" /></div>

MCNN contains three columns: **[MCNNL]**, **[MCNNM]**, **[MCNNS]**
