# Paper-List
List of deep learning papers, including CV (Computer Vision), NLP (Natural language processing), Multimodal and other research directions.


# 多模态

### 多模态对话

|paper|源码|收录|简介|个人笔记|
|:-:|:-:|:-:|:-:|:-:|
|[Learning to Respond with Stickers: A Framework of Unifying Multi-Modality in Multi-Turn Dialog](https://arxiv.org/abs/2003.04679)|[code](https://github.com/gsh199449/stickerchat)|WWW 2020|open-domain; 检索式; 可回复出表情包|-|
|[Towards Expressive Communication with Internet Memes: A New Multimodal Conversation Dataset and Benchmark](https://arxiv.org/abs/2109.01839)|[code](https://github.com/lizekang/DSTC10-MOD)|-|open-domain; 检索式; 可回复出表情包|-|
|[Multimodal Dialogue Response Generation](https://aclanthology.org/2022.acl-long.204/)|[code](https://aclanthology.org/2022.acl-long.204/)|ACL 2022|**Divter**; open-domain; 生成式; 可生成图像|[笔记](https://friedrichor.github.io/Paper-List/Multimodal/多模态对话/Multimodal%20Dialogue%20Response%20Generation.html)|

### 多模态情感分析

|paper|源码|收录|简介|个人笔记|
|:-:|:-:|:-:|:-:|:-:|
| [Few-Shot Multi-Modal Sentiment Analysis with Prompt-Based Vision-Aware Language Modeling](https://ieeexplore.ieee.org/document/9859654) |        [code](https://github.com/yynj98/PVLM)         |      ICME 2022      |           **PVLM**; Few-shot; Prompt           |    -     |
| [Unified Multi-modal Pre-training for Few-shot Sentiment Analysis with Prompt-based Learning]() |       [code](https://github.com/yynj98/UP-MPF)        | ACM Multimedia 2022 |                **UP-MPF**; Few-shot; Prompt                |    -     |
| [Multimodal Sentiment Detection Based on Multi-channel Graph Neural Networks](https://aclanthology.org/2021.acl-long.28/) |   [code](https://github.com/YangXiaocui1215/MGNNS)    |   ACL/IJCNLP 2021   |                 **MGNNS**; GNN                 |    -     |
| [Image-Text Multimodal Emotion Classification via Multi-View Attentional Network](https://ieeexplore.ieee.org/document/9246699) |    [code](https://github.com/YangXiaocui1215/MVAN)    |      IEEE 2021      |                    **MVAN**                    |    -     |
| [Few-shot Multimodal Sentiment Analysis based on Multimodal Probabilistic Fusion Prompts](https://arxiv.org/abs/2211.06607) | [code](https://github.com/YangXiaocui1215/MultiPoint) |        2022         | **MultiPoint**; Few-shot; Probabilistic Fusion |    -     |

### 视频领域

|paper|源码|收录|简介|个人笔记|网上讲解|
|:-:|:-:|:-:|:-:|:-:|:-:|
|[Two-Stream Convolutional Networks for Action Recognition in Videos](https://proceedings.neurips.cc/paper/2014/hash/00ec53c4682d36f5c4359f4ae7bd7ba1-Abstract.html)|  -   | NIPS 2014 |               视频领域中应用深度学习的开山之作               | [笔记](https://friedrichor.github.io/Paper-List/Multimodal/视频领域/Two-Stream%20Convolutional%20Networks%20for%20Action%20Recognition%20in%20Videos.html) |[视频](https://www.bilibili.com/video/BV1mq4y1x7RU/)|
|[VideoBERT: A Joint Model for Video and Language Representation Learning](https://ieeexplore.ieee.org/document/9009570)|-|ICCV 2019|对动作分类任务直接进行 zero-shot 推理时，就能与先前的有监督训练好的 S3D 取得差不多的效果|[笔记](https://friedrichor.github.io/Paper-List/Multimodal/视频领域/VideoBERT：A%20Joint%20Model%20for%20Video%20and%20Language%20Representation%20Learning.html)||


# NLP


# CV

### 图像分类


|paper|源码| 收录 |简介|个人笔记|网上讲解|
|:-:|:-:|:-:|:-:|:-:|:-:|
|[An Image Is Worth 16x16 Words: Transformers For Image Recognition At Scale](https://arxiv.org/abs/2010.11929)|[code](https://github.com/google-research/vision_transformer)|ICLR 2021|**Vision Transformer**|[笔记](https://friedrichor.github.io/Paper-List/CV/经典模型/Vision%20Transformer.html)|[博客](https://blog.csdn.net/qq_37541097/article/details/118242600)；[视频](https://www.bilibili.com/video/BV1Jh411Y7WQ/)；[视频(代码)](https://www.bilibili.com/video/BV1AL411W7dT/)|
|[Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)|[code](https://github.com/microsoft/Swin-Transformer)|ICCV 2021|**Swin Transformer**|-|[博客](https://blog.csdn.net/qq_37541097/article/details/121119988)；[视频](https://www.bilibili.com/video/BV1pL4y1v7jC/)；[视频(代码)](https://www.bilibili.com/video/BV1yg411K7Yc/)|
|[A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545)|[code](https://github.com/facebookresearch/ConvNeXt)|CVPR 2022|**ConvNeXt**|-|[博客](https://blog.csdn.net/qq_37541097/article/details/122556545)；[视频](https://www.bilibili.com/video/BV1SS4y157fu/)；[视频(代码)](https://www.bilibili.com/video/BV14S4y1L791/)|


### 目标检测

|paper|源码|收录|简介|个人笔记|网上讲解|
|:-:|:-:|:-:|:-:|:-:|:-:|
| [Rich feature hierarchies for accurate object detection and semantic segmentation](https://arxiv.org/abs/1311.2524) |                         -                          | CVPR 2014 |    **R-CNN**     | [笔记](https://friedrichor.github.io/Paper-List/CV/目标检测/R-CNN.html) | [视频](https://www.bilibili.com/video/BV1af4y1m7iL?p=1) |
|        [Fast R-CNN](https://arxiv.org/abs/1504.08083)        |  [code](https://github.com/rbgirshick/fast-rcnn)   | ICCV 2015 |  **Fast R-CNN**  | [笔记](https://friedrichor.github.io/Paper-List/CV/目标检测/Fast%20R-CNN.html) | [视频](https://www.bilibili.com/video/BV1af4y1m7iL?p=2) |
| [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://proceedings.neurips.cc/paper/2015/hash/14bfa6bb14875e45bba028a21ed38046-Abstract.html) | [code](https://github.com/ShaoqingRen/faster_rcnn) | NIPS 2015 | **Faster R-CNN** | [笔记](https://friedrichor.github.io/Paper-List/CV/目标检测/Faster%20R-CNN.html) | [视频](https://www.bilibili.com/video/BV1af4y1m7iL?p=3) |


