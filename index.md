---
feature_image: "https://i.postimg.cc/jqmzqzD7/titile-ocean.png"
layout: page
---


[![Ocean.png](https://i.postimg.cc/P5BkF2y2/ocean.jpg)](https://postimg.cc/v4Lj47pV)

{% include button.html text="Paper :book:" link="https://arxiv.org/abs/2006.10721" color="FF9900" %}{% include button.html text="Code" icon="github" link="https://github.com/researchmm/TracKit" color="#0366d6" %}{% include button.html text="Models :lollipop:" link="https://drive.google.com/drive/folders/1Gm0MkWwVJzaMepbgSMMNTpYTovEFphzF?usp=sharing" color="#FF6600" %}{% include button.html text="Results :paperclip:" link="https://drive.google.com/drive/folders/1oXmaHqubA21eoy6NMSs4emjIXcOW5C_v?usp=sharing" color="#CC00FF" %}{% include button.html text="Data :fuelpump:" link="https://drive.google.com/drive/folders/1ehjVhg6ewdWSWt709zd1TkjWF7UJlQlq?usp=sharing" color="#666666" %}

[![Title.png](https://i.postimg.cc/2yM7Ltrs/paper-title.png)](https://postimg.cc/D4QXtBW6)

### Abstract
Anchor-based Siamese trackers have achieved remarkable advancements in accuracy, yet the further improvement is restricted by the lagged tracking robustness. We find the underlying reason is that the regression network in anchor-based methods is only trained on the positive anchor boxes (i.e., IoU≥0.6). This mechanism makes it difficult to refine the anchors whose overlap with the target objects are small. In this paper, we propose a novel object-aware anchor-free network to address this issue. First, instead of refining the reference anchor boxes, we directly predict the position and scale of target objects in an anchor-free fashion. Since each pixel in groundtruth boxes is well trained, the tracker is capable of rectifying inexact predictions of target objects during inference. Second, we introduce a feature alignment module to learn an object-aware feature from predicted bounding boxes. The object-aware feature can further contribute to the classification of target objects and background. Moreover, we present a novel tracking framework based on the anchor-free model.  



### Demo
[![demo.gif](https://i.postimg.cc/yN8vDtRN/oceanplus.gif)](https://postimg.cc/68FdSHYs)


### Citation
```
@article{Ocean_2020,
  title={Ocean: Object-aware Anchor-free Tracking},
  author={Zhipeng Zhang, Houwen Peng, Jianlong Fu, Bing Li, Weiming Hu},
  journal={arXiv preprint arXiv:2006.10721},
  year={2020}
}
```


