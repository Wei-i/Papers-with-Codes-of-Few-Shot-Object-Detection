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








## 目标检测框架

基于Detectron2的通用目标检测框架。目前已经成功整合了FCOS与YOLOF,代码和使用方法在：

https://git.woa.com/Application_Research_Center3/YTDetectron2

## 实验结果对比

### 主流方法效果对比

数据集情况：

政治实体39类训练集179138个目标框，验证集45048个框

目前较新的几个和多尺度有关的新检测方法实验对比：

| **Model**                          | **AP**    | **AP@small** | **AP@medium** | **AP@large** | **Time(ms)** | **THR** | **Recall** | **FAR** |
| ---------------------------------- | --------- | ------------ | ------------- | ------------ | ------------ | ------- | ---------- | ------- |
| **CenterNet**                      | 0.761     | 0.444        | 0.709         | 0.816        | 22           | 0.55    | 0.89       | 0.0013  |
| **FCOS**                           | 0.804     | 0.458        | 0.753         | 0.859        | 25           | -       | -          | -       |
| **YOLOF**                          | 0.801     | 0.455        | 0.736         | 0.864        | 27           | -       | -          | -       |
| **CenterNet2**                     | **0.826** | 0.444        | 0.773         | 0.887        | 28           | 0.85    | 0.9048     | 0.015   |
| **CenterNet2+HighFP**              | **0.817** | 0.444        | 0.773         | 0.887        | 28           | 0.88    | 0.9042     | 0.015   |
| **CenterNet2+FineTune10w(FP0.99)** | 0.802     | 0.408        | 0.737         | 0.869        | 28           | 0.85    | 0.8461     | 0.022   |

mAP指标结论：

1、4个方法对比，新的3个方法应用了多尺度改进均比CenterNet要好，mAP提升4%以上

2、从论文实验设置来看，YOLOF在训练策略上要求较为复杂，需要分几个阶段才能达到最优

3、CenterNet2在medium和large scale目标的提升更明显，能解决当前政治实体大尺度召回不好的问题。

业务指标结论：

1、黄色部分指标为政治实体业务测试集，数据分布：51861张，违规图5440，正常图46421

2、和算法结构变化有关，Centernet2召回能力较好，同等召回下误检是老模型的10倍并且阈值很高

3、分析代码发现CenterNet2对于0.85以上高置信度的FP不计算loss，在coco上有效，但不适合业务需求，调整后采用CenterNet2+HighFP进行finetune，效果不变，重新初始化训练中。

### 业务数据集上其他测试结果如下

| **序号** | **方法**                            | **FPS** | **AP** | **AP50** | **AP75** | **APs** | **APm** | **APl** |
| -------- | ----------------------------------- | ------- | ------ | -------- | -------- | ------- | ------- | ------- |
| 1        | FCOS-RT(ResNet50)                   | 57.8    | 78.782 | 92.213   | 85.819   | 42.995  | 73.5    | 84.814  |
| 2        | FCOS-RT(ResNet50)-Scale(832,512)    | 50      | 80.164 | 92.791   | 86.828   | 43.296  | 74.857  | 86.375  |
| 3        | FCOS-RT(ResNet50+BiFPN)             | 37.6    | 80.537 | 92.716   | 86.897   | 44.533  | 75.262  | 86.446  |
| 4        | FCOS-RT(DLA-34)                     | 52.6    | 80.498 | 93.226   | 87.233   | 45.714  | 74.769  | 86.882  |
| 5        | FCOS-RT(DLA-34+BiFPN)               | 40.2    | 80.434 | 92.569   | 86.883   | 45.830  | 75.346  | 85.917  |
| 6        | YOLOF(CSPDarknet53_9x)              | 37.7    | 79.383 | 93.774   | 87.352   | 43.343  | 73.837  | 85.249  |
| 7        | YOLOF(CSPDarknet53_stage2_3x)       | 37.6    | 80.856 | 93.931   | 87.502   | 46.323  | 74.503  | 87.453  |
| 8        | YOLOF(CSPDarknet53_stage2_3x_d)     | 37.6    | 81.221 | 93.515   | 88.047   | 47.948  | 75.173  | 87.639  |
| 9        | YOLOF(CSPDarknet53_stage2_3x_d_DC6) | 36.2    | 80.955 | 93.562   | 87.837   | 46.613  | 74.894  | 87.167  |

### 对应于上述不同序号算法里不同类别的测试结果如下

| **类别**            | **1**      | **2**      | **3**      | **4**      | **5**      | **6**  | **7**      | **8**      | **9**      |
| ------------------- | ---------- | ---------- | ---------- | ---------- | ---------- | ------ | ---------- | ---------- | ---------- |
| 国旗(ZZ003)         | 73.542     | 74.963     | 75.685     | 76.130     | 75.849     | 74.861 | 76.046     | **76.207** | 75.873     |
| 国徽(ZZ004)         | 78.937     | 80.445     | 81.277     | 81.396     | 80.903     | 80.861 | 82.373     | **82.582** | 82.272     |
| 党旗(ZZ001)         | 79.44      | 78.751     | **81.322** | 79.081     | 81.154     | 77.9   | 80.497     | 79.121     | 79.460     |
| 党徽(ZZ002)         | 74.077     | 75.711     | **77.151** | 76.673     | 77.013     | 76.331 | 76.454     | 76.267     | 76.285     |
| 人民币(ZZ016)       | 75.458     | 76.282     | 76.718     | 76.397     | 76.860     | 76.373 | 77.873     | 77.944     | **78.047** |
| 军旗(ZZ005)         | 79.588     | 82.223     | 83.588     | 82.722     | 82.533     | 83.202 | **84.657** | 84.110     | 83.534     |
| 军徽(ZZ006)         | 77.22      | 78.422     | 79.220     | 79.678     | 79.663     | 79.535 | **91.096** | 81.434     | 80.988     |
| 旭日旗(ZZ015)       | 78.032     | 80.991     | 83.129     | 81.545     | 82.709     | 81.949 | **84.203** | 83.331     | 83.890     |
| 中国全貌地图(ZZ017) | 95.181     | 96.224     | 96.481     | 96.272     | 96.456     | 95.991 | **96.621** | 96.317     | 96.564     |
| 纳粹(ZZ014)         | 64.475     | 57.285     | 67.376     | 68.204     | 67.689     | 68.501 | 69.420     | 69.694     | **69.851** |
| 疆独旗帜(ZZ013)     | 70.852     | 71.531     | 72.657     | 70.796     | **73.670** | 71.151 | 70.329     | 73.143     | 73.071     |
| 雪山狮子旗(ZZ012)   | 55.261     | 57.152     | 56.909     | **59.135** | 58.006     | 57.144 | 57.981     | 57.424     | 57.359     |
| WTC台湾旗(ZZ010)    | 70.503     | 71.579     | 70.212     | 70.968     | 69.298     | 70.598 | 71.609     | **71.938** | 71.707     |
| 港英政府徽章(ZZ011) | 68.756     | 73.590     | 74.750     | 71.606     | 74.525     | 72.903 | **76.049** | 72.665     | 72.769     |
| 国民党党徽(ZZ009)   | 71.918     | 74.310     | 74.179     | 74.849     | 74.474     | 75.825 | 75.146     | 76.860     | **77.006** |
| 香港区旗区徽(ZZ007) | 75.546     | 76.899     | 76.820     | 77.633     | 76.939     | 46.84  | 78.364     | **78.695** | 78.348     |
| 澳门区旗区徽(ZZ008) | 83.03      | 83.286     | 84.204     | 83.014     | 83.798     | 82.586 | 83.231     | **84.392** | 83.801     |
| ISIS旗帜(ZZ018)     | 72.236     | 74.436     | 76.749     | 75.604     | 76.051     | 74.941 | **78.763** | 76.453     | 77.379     |
| 法轮功标志(ZZ019)   | 82.958     | 84.226     | 82.784     | 83.112     | 82.749     | 81.539 | 83.275     | 83.842     | **84.736** |
| 蒙独旗帜(ZZ020)     | 80.853     | **85.250** | 83.497     | 83.667     | 83.257     | 82.616 | 83.332     | 84.736     | 83.784     |
| 新唐人(ZZ021)       | 89.385     | 90.634     | 90.105     | 90.512     | 90.148     | 89.577 | 90.232     | **91.000** | 90.693     |
| 无上师电视台(ZZ022) | 93.118     | 93.538     | 93.663     | 93.409     | **93.900** | 89.481 | 93.023     | 93.376     | 93.507     |
| SOH希望之声(ZZ023)  | 91.813     | **92.195** | 91.951     | 91.649     | 91.925     | 88.688 | 91.196     | 90.714     | 90.627     |
| 望之声(ZZ024)       | 72.556     | **77.742** | 75.482     | 75.165     | 76.142     | 68.714 | 71.261     | 75.251     | 71.060     |
| 警徽(ZZ025)         | 74.833     | 76.739     | 78.094     | 77.559     | 77.976     | 80.670 | 81.689     | **81.881** | 81.781     |
| 明镜网(ZZ026)       | 90.967     | 91.742     | 92.078     | 92.986     | **93.020** | 89.827 | 91.413     | 92.991     | 92.747     |
| 大纪元(ZZ027)       | 89.7       | 90.191     | 91.432     | **91.639** | 91.493     | 88.785 | 91.264     | 90.904     | 91.285     |
| 苹果日报(ZZ028)     | 46.216     | 43.385     | 46.398     | 46.198     | 46.980     | 50.806 | 48.665     | **53.644** | 52.284     |
| 美国之音(ZZ029)     | 84.331     | 86.613     | 86.547     | **88.244** | 86.209     | 83.865 | 86.846     | 87.125     | 87.165     |
| 阿波罗网(ZZ030)     | **95.817** | 95.141     | 95.444     | 94.641     | 95.186     | 92.742 | 95.076     | 95.467     | 95.399     |
| 自由亚洲电台(ZZ031) | 91.1       | 91.522     | 91.838     | **91.981** | 91.506     | 88.788 | 89.426     | 90.149     | 89.644     |
| 看中国(ZZ032)       | 95.822     | 96.633     | 96.822     | 96.429     | **96.856** | 92.832 | 95.557     | 95.534     | 94.195     |
| 多维新闻(ZZ033)     | 89.515     | 89.141     | 89.595     | 89.456     | 89.548     | 88.097 | 89.466     | 89.696     | **90.028** |
| 多维视频对话(ZZ034) | 94.282     | **94.910** | 94.840     | 94.183     | 94.423     | 91.105 | 94.041     | 93.932     | 94.324     |
| 自由时报(ZZ035)     | 90.567     | 91.149     | 91.343     | 91.378     | 91.246     | 89.936 | 91.951     | **92.416** | 92.182     |
| 解放军臂章(ZZ036)   | 73.626     | 75.586     | 75.074     | 75.421     | 74.674     | 75.848 | 77.238     | **77.990** | 77.374     |
| 警察臂章(ZZ037)     | 79.501     | 81.292     | 80.319     | 81.393     | 79.006     | 79.290 | 80.721     | **82.360** | 80.354     |
| 新中国联邦(ZZ038)   | 66.684     | 68.704     | 68.520     | **70.309** | 66.895     | 67.834 | 69.354     | 68.430     | 68.714     |
| 中华民国国旗(ZZ039) | 54.79      | 55.975     | 56.696     | **58.369** | 56.183     | 57.408 | 57.649     | 57.702     | 57.169     |

### 整库的测试

| **方法**                            | **THR** | **Recall** | **FAR** | **THR** | **Recall** | **FAR** |
| ----------------------------------- | ------- | ---------- | ------- | ------- | ---------- | ------- |
| CenterNet                           |         |            |         | 0.55    | 0.89       | 0.0013  |
| FCOS-RT(ResNet50)                   | 0.7     | 0.9015     | 0.007   | 0.85    | 0.6671     | 0.0014  |
| FCOS-RT(ResNet50)-Scale(832,512)    | 0.74    | 0.8972     | 0.007   | 0.85    | 0.6824     | 0.0015  |
| FCOS-RT(ResNet50+BiFPN)             | 0.75    | 0.9006     | 0.017   | 0.89    | 0.4713     | 0.0012  |
| FCOS-RT(DLA-34)                     | 0.73    | 0.9        | 0.021   | 0.9     | 0.3471     | 0.0015  |
| FCOS-RT(DLA-34+BiFPN)               | 0.76    | 0.8983     | 0.018   | 0.9     | 0.4557     | 0.0013  |
| YOLOF(CSPDarknet53_9x)              | 0.49    | 0.9011     | 0.008   | 0.7     | 0.8009     | 0.0012  |
| YOLOF(CSPDarknet53_stage2_3x)       | 0.46    | 0.9        | 0.012   | 0.68    | 0.7741     | 0.0013  |
| YOLOF(CSPDarknet53_stage2_3x_d)     | 0.47    | 0.9007     | 0.008   | 0.69    | 0.7926     | 0.0014  |
| YOLOF(CSPDarknet53_stage2_3x_d_DC6) | 0.47    | 0.9        | 0.009   | 0.69    | 0.8009     | 0.0015  |



