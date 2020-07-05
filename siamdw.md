---
title: SiamDW
feature_image: "https://i.postimg.cc/d1FRncyv/siamdw.png"
aside: true
---

[![SiamDW.png](https://i.postimg.cc/9XJPPSF5/siamdw-overview.jpg)](https://postimg.cc/NL2rBdHp)

{% include button.html text="Paper :book:" link="http://openaccess.thecvf.com/content_CVPR_2019/html/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.html" color="FF9900" %}{% include button.html text="Code" icon="github" link="https://github.com/researchmm/SiamDW" color="#0366d6" %}{% include button.html text="Models :lollipop:" link="https://drive.google.com/drive/folders/19dBWxOqZnvM0FsgXGzH2Y7Bg7wgYMEoO" color="#FF6600" %}{% include button.html text="Results :paperclip:" link="https://drive.google.com/file/d/1rTC2XKJ2bznVjtXW-UAzeUGc7QizeLP9/view?usp=sharing" color="#CC00FF" %}{% include button.html text="Data :fuelpump:" link="https://drive.google.com/drive/folders/1ehjVhg6ewdWSWt709zd1TkjWF7UJlQlq?usp=sharing" color="#666666" %}

[![Title.png](https://i.postimg.cc/2yM7Ltrs/paper-title.png)](https://postimg.cc/D4QXtBW6)

### Abstract
Siamese networks have drawn great attention in visual tracking because of their balanced accuracy and speed. However, the backbone networks used in Siamese trackers are relatively shallow, such as AlexNet, which does not fully take advantage of the capability of modern deep neural networks. In this paper, we investigate how to leverage deeper and wider convolutional neural networks to enhance tracking robustness and accuracy. We observe that direct replacement of backbones with existing powerful architectures, such as ResNet and Inception, does not bring improvements. The main reasons are that 1) large increases in the receptive field of neurons lead to reduced feature discriminability and localization precision; and 2) the network padding for convolutions induces a positional bias in learning. To address these issues, we propose new residual modules to eliminate the negative impact of padding, and further design new architectures using these modules with controlled receptive field size and network stride. The designed architectures are lightweight and guarantee real-time tracking speed when applied to SiamFC and SiamRPN.


### Demo
[![demo.gif](https://github.com/researchmm/SiamDW/demo/vis.gif)](https://github.com/researchmm/SiamDW/demo/vis.gif)


### Citation
```
@InProceedings{SiamDW_2019_CVPR,
author = {Zhang, Zhipeng and Peng, Houwen},
title = {Deeper and Wider Siamese Networks for Real-Time Visual Tracking},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2019}
} 
```
