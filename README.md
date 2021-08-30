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

  - LSTD: A Low-Shot Transfer Detector for Object Detection (AAAI 2018)

### 2019
  - Few-shot Object Detection via Feature Reweighting (ICCV 2019)
  - Meta-Learning to Detect Rare Objects (ICCV 2019)
  - Meta R-CNN : Towards General Solver for Instance-level Low-shot Learning (ICCV 2019)
  - RepMet: Representative-based metric learning for classification and few-shot object detection (CVPR 2020)
  
### 2020
  - Frustratingly Simple Few-Shot Object Detection (ICML 2020)
  - Multi-Scale Positive Sample Refinement for Few-Shot Object Detection (CVPR 2020)
  - Few-Shot Object Detection and Viewpoint Estimation for Objects in the Wild (ECCV 2020)
  - Few-Shot Object Detection with Attention-RPN and Multi-Relation Detector (CVPR 2020)
  - Context-Transformer: Tackling Object Confusion for Few-Shot Detection (AAAI 2020)
  - Incremental Few-Shot Object Detection (CVPR 2020)

### 2021
  - Meta-DETR: Few-Shot Object Detection via Unified Image-Level Meta-Learning (arxiv)
  - Semantic Relation Reasoning for Shot-Stable Few-Shot Object Detection (CVPR 2021)
  - Few-Shot Object Detection via Classification Refinement and Distractor Retreatment (CVPR 2021)
  - Generalized Few-Shot Object Detection without Forgetting (CVPR 2021)
  - FSCE: Few-Shot Object Detection via Contrastive Proposal Encoding (CVPR 2021)
  - Dense Relation Distillation with Context-aware Aggregation for Few-Shot Object Detection (CVPR 2021)
  - Hallucination Improves Few-Shot Object Detection (CVPR 2021)
  - DeFRCN: Decoupled Faster R-CNN for Few-Shot Object Detection (CVPR 2021)
