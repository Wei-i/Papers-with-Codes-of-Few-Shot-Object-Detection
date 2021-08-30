# Papers-of-FSOD


## 1. Few Shot Object Detection Preliminaries
* K-shot N-way Object Detection
  - K means  the number of the objects for each class
  - N means the number of classes for few shot detection
* DataSet Split 
  - Base ClassSet 𝐶_𝑏 , Base Dataset 𝐷_𝑏 contains {(𝑥_𝑖, 𝑦_𝑖)} about abundant images and annotations
  - Novel ClassSet 𝐶_𝑛  , Novel Dataset 𝐷_𝑛 contains {(𝑥_𝑖, 𝑦_𝑖)} about few images and annotations
  - 𝐶_𝑏 ∩ 𝐶_𝑛=∅ , 𝐶_𝑏 ∪ 𝐶_𝑛=𝐶_𝑡𝑜𝑡𝑎𝑙 
  - COCO (Base : Novel = 60:20)、 PASCAL VOC (Base : Novel = 15:5)
* Training(Two phases)
  - Training on Base dataset
  - Fine-tuning on Novel and base dataset with few objects

* Method
  - Meta-Learning Based
  - Transfer-Learning Based

## 2. Recent work
###  2018

  - LSTD: A Low-Shot Transfer Detector for Object Detection (AAAI 2018) [Paper](https://arxiv.org/pdf/1803.01529.pdf)

### 2019
  - Few-shot Object Detection via Feature Reweighting (ICCV 2019) [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Kang_Few-Shot_Object_Detection_via_Feature_Reweighting_ICCV_2019_paper.html) [Code](https://github.com/bingykang/Fewshot_Detection)
  - Meta-Learning to Detect Rare Objects (ICCV 2019) [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Meta-Learning_to_Detect_Rare_Objects_ICCV_2019_paper.pdf) 
  - Meta R-CNN : Towards General Solver for Instance-level Low-shot Learning (ICCV 2019) [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Meta_R-CNN_Towards_General_Solver_for_Instance-Level_Low-Shot_Learning_ICCV_2019_paper.pdf) [Code](https://github.com/yanxp/MetaR-CNN)
  - RepMet: Representative-based metric learning for classification and few-shot object detection (CVPR 2020) [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karlinsky_RepMet_Representative-Based_Metric_Learning_for_Classification_and_Few-Shot_Object_Detection_CVPR_2019_paper.pdf) [Code]()
  
### 2020
  - Frustratingly Simple Few-Shot Object Detection (ICML 2020) [[Paper]]() [Code](https://github.com/ucbdrive/few-shot-object-detection)
  - Multi-Scale Positive Sample Refinement for Few-Shot Object Detection (CVPR 2020) [Paper]() [Code]()
  - Few-Shot Object Detection and Viewpoint Estimation for Objects in the Wild (ECCV 2020) [Paper]() [Code](https://github.com/YoungXIAO13/FewShotDetection)
  - Few-Shot Object Detection with Attention-RPN and Multi-Relation Detector (CVPR 2020) [Paper]() [Code]()
  - Context-Transformer: Tackling Object Confusion for Few-Shot Detection (AAAI 2020) [Paper]() [Code]()
  - Incremental Few-Shot Object Detection (CVPR 2020) [Paper]() [Code]()

### 2021
  - Meta-DETR: Few-Shot Object Detection via Unified Image-Level Meta-Learning (arxiv) [Paper]() [Code]()
  - Semantic Relation Reasoning for Shot-Stable Few-Shot Object Detection (CVPR 2021) [Paper]() [Code]()
  - Few-Shot Object Detection via Classification Refinement and Distractor Retreatment (CVPR 2021) [Paper]() [Code]()
  - Generalized Few-Shot Object Detection without Forgetting (CVPR 2021) [Paper]() [Code]()
  - FSCE: Few-Shot Object Detection via Contrastive Proposal Encoding (CVPR 2021) [Paper]() [Code]()
  - Dense Relation Distillation with Context-aware Aggregation for Few-Shot Object Detection (CVPR 2021) [Paper]() [Code]()
  - Hallucination Improves Few-Shot Object Detection (CVPR 2021) [Paper]() [Code]()
  - DeFRCN: Decoupled Faster R-CNN for Few-Shot Object Detection (CVPR 2021) [Paper](https://arxiv.org/pdf/2108.09017.pdf) [Code]()
