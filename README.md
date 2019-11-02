# Datasets of Computer Vision

发现了一个NB的网址，可以搜CV数据集：https://www.visualdata.io/



## 中文简介

### 人脸数据集

- [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)：人脸数据集，包含来自10177个不同个体的202599张原始人脸和对齐操作过的人脸数据，每个人脸包括40个attribute二分类标注和5个landmark标注，可用于人脸属性识别、人脸检测、关键点定位、人脸编辑、人脸生成等任务。
- CelebA-HQ：从原式CelebA数据集中选取了一定数量制作成的高清人脸数据集，来自[Progressive Growing of GANs](https://arxiv.org/abs/1710.10196)，与原CelebA包含的数据类型相同。
- [CelebAMask-HQ](https://www.ctolib.com/switchablenorms-CelebAMask-HQ.html)：高清人脸数据集，除了CelebA-HQ的属性外，还带有Semantic Segmentation标注
- [FFHQ](https://ruby.ctolib.com/NVlabs-ffhq-dataset.html)：高清人脸数据集，来自StyleGAN，包括7万张带标注的1024分辨率的PNG图片，已经进行了对齐和裁剪处理。

### 场景数据集

- [Places2](http://places2.csail.mit.edu/)：场景数据集，400个类别，超过1千万张图片，
- [CityScapes](https://www.cityscapes-dataset.com/)：场景数据集。50个不同城市的街景照片，5000张精细标注，20000张粗略标注

### 物体分割数据集

- [COCO](http://cocodataset.org/)：包含33w张已标注图片的大规模标注数据集，包括150w个物体，80个类别的20w标注信息，以及25w个标注了关键点的人物照片，用于场景物体检测、物体分割、图片配文（caption）任务。

- [Object365](https://www.objects365.org/overview.html)：包含60w张图片365类物体1000w实例的bbox标注，来自旷视
- 



## Detail in English

- **COCO** is a large-scale object detection, segmentation, and captioning dataset. COCO has several features:
  - Object segmentation
  - Recognition in context
  - Superpixel stuff segmentation
  - 330K images (>200K labeled)
  - 1.5 million object instances
  - 80 object categories
  - 91 stuff categories
  - 5 captions per image
  - 250,000 people with keypoints
- **Objects365** is a brand new dataset, designed to spur object detection research with a focus on diverse objects in the Wild.
  - 365 categories
  - 600k images
  - 10 million bounding boxes