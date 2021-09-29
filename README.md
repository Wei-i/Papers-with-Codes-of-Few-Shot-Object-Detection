# Papers-with-Codes of Few-Shot Object Detection 


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
  ![image](https://user-images.githubusercontent.com/47490392/131458670-89e7e75e-433a-4aea-8b23-a01ee85a1b54.png)

  - Transfer-Learning Based
  ![image](https://user-images.githubusercontent.com/47490392/131458759-824a1385-a276-4e99-be93-4d0d73cf5885.png)


## 2. Recent work
###  2018

  - LSTD: A Low-Shot Transfer Detector for Object Detection (AAAI 2018) [[Paper]](https://arxiv.org/pdf/1803.01529.pdf)

### 2019
  - Few-shot Object Detection via Feature Reweighting (ICCV 2019) [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kang_Few-Shot_Object_Detection_via_Feature_Reweighting_ICCV_2019_paper.pdf) [[Code]](https://github.com/bingykang/Fewshot_Detection)
  - Meta-Learning to Detect Rare Objects (ICCV 2019) [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Meta-Learning_to_Detect_Rare_Objects_ICCV_2019_paper.pdf) 
  - Meta R-CNN : Towards General Solver for Instance-level Low-shot Learning (ICCV 2019) [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Meta_R-CNN_Towards_General_Solver_for_Instance-Level_Low-Shot_Learning_ICCV_2019_paper.pdf) [[Code]](https://github.com/yanxp/MetaR-CNN)
  - RepMet: Representative-based metric learning for classification and few-shot object detection (CVPR 2020) [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karlinsky_RepMet_Representative-Based_Metric_Learning_for_Classification_and_Few-Shot_Object_Detection_CVPR_2019_paper.pdf) [[Code]](https://github.com/jshtok/RepMet)
  
### 2020
  - Frustratingly Simple Few-Shot Object Detection (ICML 2020) [[Paper]](https://arxiv.org/pdf/2003.06957.pdf) [[Code]](https://github.com/ucbdrive/few-shot-object-detection)
  - Multi-Scale Positive Sample Refinement for Few-Shot Object Detection (ECCV 2020) [[Paper]](https://arxiv.org/pdf/2007.09384.pdf) [[Code]](https://github.com/jiaxi-wu/MPSR)
  - Few-Shot Object Detection and Viewpoint Estimation for Objects in the Wild (ECCV 2020) [[Paper]](https://arxiv.org/pdf/2007.12107.pdf) [[Code]](https://github.com/YoungXIAO13/FewShotDetection)
  - Few-Shot Object Detection with Attention-RPN and Multi-Relation Detector (CVPR 2020) [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Few-Shot_Object_Detection_With_Attention-RPN_and_Multi-Relation_Detector_CVPR_2020_paper.pdf) [[Code]](https://github.com/fanq15/FewX)
  - Context-Transformer: Tackling Object Confusion for Few-Shot Detection (AAAI 2020) [[Paper]](https://arxiv.org/pdf/2003.07304.pdf) [[Code]](https://github.com/Ze-Yang/Context-Transformer)
  - Incremental Few-Shot Object Detection (CVPR 2020) [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Perez-Rua_Incremental_Few-Shot_Object_Detection_CVPR_2020_paper.pdf)

### 2021
  - Meta-DETR: Few-Shot Object Detection via Unified Image-Level Meta-Learning (arxiv) [[Paper]](http://arxiv.org/abs/2103.11731) [[Code]](https://github.com/ZhangGongjie/Meta-DETR)
  - Semantic Relation Reasoning for Shot-Stable Few-Shot Object Detection (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Semantic_Relation_Reasoning_for_Shot-Stable_Few-Shot_Object_Detection_CVPR_2021_paper.pdf)
  - Few-Shot Object Detection via Classification Refinement and Distractor Retreatment (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Few-Shot_Object_Detection_via_Classification_Refinement_and_Distractor_Retreatment_CVPR_2021_paper.pdf) 
  - Generalized Few-Shot Object Detection without Forgetting (CVPR 2021) [[Paper]](https://github.com/Megvii-BaseDetection/GFSD) [[Code]](https://arxiv.org/pdf/2105.09491.pdf)
  - FSCE: Few-Shot Object Detection via Contrastive Proposal Encoding (CVPR 2021) [[Paper]](https://arxiv.org/pdf/2103.05950.pdf) [[Code]](https://github.com/MegviiDetection/FSCE)
  - Dense Relation Distillation with Context-aware Aggregation for Few-Shot Object Detection (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Dense_Relation_Distillation_With_Context-Aware_Aggregation_for_Few-Shot_Object_Detection_CVPR_2021_paper.pdf) [[Code]](https://github.com/hzhupku/DCNet)
  - Hallucination Improves Few-Shot Object Detection (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Hallucination_Improves_Few-Shot_Object_Detection_CVPR_2021_paper.pdf) [[Code]](https://github.com/pppplin/HallucFsDet)
  - DeFRCN: Decoupled Faster R-CNN for Few-Shot Object Detection (ICCV 2021) [[Paper]](https://arxiv.org/pdf/2108.09017.pdf) [[Code]](https://github.com/er-muyue/DeFRCN)


