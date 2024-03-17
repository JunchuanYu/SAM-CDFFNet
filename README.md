
<font size='5'>**SAM-CDFFNet：SAM-based Cross-Dept Feature Fusion Net-work for Intelligent Identification of Landslides**</font>

Laidian Xi, [Junchuan Yu](https://github.com/JunchuanYu)☨, Daqing Ge, Yunxuan Pang, Ping Zhou, Changhong Hou, Yichuan Li, Yangyang Chen, Yuanbiao Dong

☨corresponding author


## To Do List
* **[2024.02.23]** Paper submission in review process.
* **[2023.03.17]** Dataset uploaded.
* **[ ]** Code under organization.
* **[ ]** Plan to upload code in the future.

## Dataset
The landslide datasets used in this study are all open source datasets, and the links to access the datasets and the literature are shown below
* Bijie Landlside Dataset: [Link](http://gpcv.whu.edu.cn/data/Bijie_pages.html),  [Paper](https://link.springer.com/article/10.1007/s10346-021-01694-6?fromPaywallRec=true).
* Landslide4Sense Dataset: [Link](https://github.com/iarai/Landslide4Sense-2022),  [Paper](https://ieeexplore.ieee.org/document/9944085).
* GVLM Dataset: [Link](https://github.com/zxk688/GVLM),  [Paper](https://www.sciencedirect.com/science/article/pii/S0924271623000242?dgcid=author).

## SAM-CDFFNet
![](https://pic3.zhimg.com/100/v2-ed1bcb87855feb9e4b8661eb503b07b2_r.jpg 'SAM-CDFFNet')
+ SAM-CDFFNet backbone from [SAM](https://github.com/facebookresearch/segment-anything), some code references [Attention UNet](https://github.com/EdgarLefevre/Attention_Unet_Pytorch), [HRNet](https://link.zhihu.com/?target=https%3A//github.com/HRNet), [Deeplabv3+](https://github.com/yassouali/pytorch_segmentation/blob/master/models/deeplabv3_plus.py). SAM-CDFFNet achieved the highest accuracy across three open-source remote sensing landslide datasets compared to other contrastive models.
+ The code is currently being organized and will be uploaded in the future. Thank you for your patience and stay tuned for updates!

## Acknowledgement
+ [SAM](https://github.com/facebookresearch/segment-anything).  SAM is the Segment Anything Model (SAM) proposed by Meta, which breaks through the boundaries of segmentation and greatly promotes the development of basic computer vision models.
+ [Attention UNet](https://github.com/EdgarLefevre/Attention_Unet_Pytorch). Attention mechanism enhances feature representation by focusing on informative regions during image segmentation.
+ [HRNet](https://link.zhihu.com/?target=https%3A//github.com/HRNet). High-Resolution Network maintains high-resolution feature maps throughout the network to capture fine details in images effectively.
+ [Deeplabv3+](https://github.com/yassouali/pytorch_segmentation/blob/master/models/deeplabv3_plus.py). DeepLabv3+ utilizes atrous spatial pyramid pooling and decoder module to achieve accurate semantic segmentation with multi-scale features.

If you're using SAM-CDFFNet in your research or applications, please cite using this BibTeX:

```bibtex
@article{xi2024rs,
  title={SAM-CDFFNet：SAM-based Cross-Dept Feature Fusion Net-work for Intelligent Identification of Landslides},
  author={Xi, Laidian and Yu, Junchuan and Ge,Daqing and Pang, Yunxuan and Zhou, and Ping and Hou, Changhong and Li, Yichuan and Chen, Yangyang and Dong, Yuanbiao },
  journal={},
  year={2024}
}
```