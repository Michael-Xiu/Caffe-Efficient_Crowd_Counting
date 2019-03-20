# Efficient Crowd Counting

These codes are implementations of the popular efficient crowd counting models on embedded systems and also the state-of-the-art networks that require high computing power and much memory for comparison. The codes are developed based on the Caffe framework suitable for deployment on embedded systems. We test the speed of these crowd counting models on ARMv8 and NVIDIA Jetson TX2.

## Model list
- <a name="FCN"></a> **[FCN]** Fully Convolutional Crowd Counting On Highly Congested Scenes (**VISAPP2017**) [[paper](https://arxiv.org/abs/1612.00220)] 
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/FCN.png" width="450" height="436" /></div>
  
- <a name="MCNN"></a> **[MCNN]** Single-Image Crowd Counting via Multi-Column Convolutional Neural Network (**CVPR2016**) [[paper](https://pdfs.semanticscholar.org/7ca4/bcfb186958bafb1bb9512c40a9c54721c9fc.pdf)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/MCNN.png" width="600" height="353" /></div>
MCNN contains three columns: **[MCNN_L]**, **[MCNN_M]**, **[MCNN_S]**

- <a name="Zhang"></a> **[Zhang]** Cross-scene Crowd Counting via Deep Convolutional Neural Networks (**CVPR2015**) [[paper](https://www.ee.cuhk.edu.hk/~xgwang/papers/zhangLWYcvpr15.pdf)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/Zhang.png" width="600" height="308" /></div>

- <a name="Sindagi"></a> **[Sindagi]** CNN-based Cascaded Multi-task Learning of High-level Prior and Density Estimation for Crowd Counting (**AVSS2017**) [[paper](https://arxiv.org/abs/1707.09605)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/Sindagi.png" width="600" height="329" /></div>

- <a name="Switch-CNN"></a> **[Switch-CNN]** Switching Convolutional Neural Network for Crowd Counting (**CVPR2017**) [[paper](https://arxiv.org/abs/1708.00199)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/SwitchCNN.png" width="600" height="541" /></div>

- <a name="CPCNN"></a> **[CPCNN]** Generating High-Quality Crowd Density Maps using Contextual Pyramid CNNs (**ICCV2017**) [[paper](https://arxiv.org/abs/1708.00953)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/CPCNN.png" width="528" height="219" /></div>

- <a name="ACSCP"></a> **[ACSCP]**  Crowd Counting via Adversarial Cross-Scale Consistency Pursuit  (**CVPR2018**) [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shen_Crowd_Counting_via_CVPR_2018_paper.pdf)]
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/ACSCP.png" width="600" height="358" /></div>


## Result
.<div align=center><img src="https://github.com/Michael-Xiu/Caffe-Efficient_Crowd_counting/raw/master/model/result.png" width="600" height="282" /></div>





