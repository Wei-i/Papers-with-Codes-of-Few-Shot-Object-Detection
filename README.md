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








# youtu_audit_element_det
There is a implementation for youtu-senosr-detection on Pytorch(政治实体检测).
This module is based on [CenterNet](http://arxiv.org/abs/1904.07850) which is a bottom-up and anchor-free object detection method.
Up to now, our mudule supports for a total of 93 categories detection.
   

## Main results
### categories-id

|  id  |            category_name            |
| :--: | :---------------------------------: |
|  1   |           "国旗(ZZ003)",            |
|  2   |           "国徽(ZZ004)",            |
|  3   |           "党旗(ZZ001)",            |
|  4   |           "党徽(ZZ002)",            |
|  5   |          "人民币(ZZ016)",           |
|  6   |           "军旗(ZZ005)",            |
|  7   |           "军徽(ZZ006)",            |
|  8   |          "旭日旗(ZZ015)",           |
|  9   |    "含有中国全貌的地图(ZZ017)",     |
|  10  |           "纳粹(ZZ014)",            |
|  11  |         "疆独旗帜(ZZ013)",          |
|  12  |        "雪山狮子旗(ZZ012)",         |
|  13  |         "WTC台湾旗(ZZ010)",         |
|  14  |       "港英政府徽章(ZZ011)",        |
|  15  |        "国民党党徽(ZZ009)",         |
|  16  |       "香港区旗区徽(ZZ007)",        |
|  17  |       "澳门区旗区徽(ZZ008)",        |
|  18  |         "ISIS旗帜(ZZ018)",          |
|  19  |        "法轮功标志(ZZ019)",         |
|  20  |         "蒙独旗帜(ZZ020)",          |
|  21  |          "新唐人(ZZ021)",           |
|  22  |       "无上师电视台(ZZ022)",        |
|  23  |        "SOH希望之声(ZZ023)",        |
|  24  |         "希望之声(ZZ024)",          |
|  25  |           "警徽(ZZ025)",            |
|  26  |          "明镜网(ZZ026)",           |
|  27  |          "大纪元(ZZ027)",           |
|  28  |         "苹果日报(ZZ028)",          |
|  29  |         "美国之音(ZZ029)",          |
|  30  |         "阿波罗网(ZZ030)",          |
|  31  |       "自由亚洲电台(ZZ031)",        |
|  32  |          "看中国(ZZ032)",           |
|  33  |         "多维新闻(ZZ033)",          |
|  34  |       "多维视频对话(ZZ034)",        |
|  35  |         "自由时报(ZZ035)",          |
|  36  |        "解放军臂章(ZZ036)",         |
|  37  |         "警察臂章(ZZ037)",          |
|  38  |        "新中国联邦(ZZ038)",         |
|  39  |       "中华民国国旗(ZZ039)",        |
|  40  |          "统一教(ZZ040)",           |
|  41  |          "全能神(ZZ041)",           |
|  42  |           "神韵(ZZ042)",            |
|  43  |         "纪念六四(ZZ043)",          |
|  44  |      "天安门母亲运动(ZZ044)",       |
|  45  |          "自由64(ZZ045)",           |
|  46  |        "蓝地黄虎旗(ZZ046)",         |
|  47  |          "日月旗(ZZ047)",           |
|  48  |          "同心旗(ZZ048)",           |
|  49  |          "藏青会(ZZ049)",           |
|  50  |         "西藏国徽(ZZ050)",          |
|  51  |        "伊斯兰国徽(ZZ051)",         |
|  52  |  "共青团团徽(GongQingTuanEmblem)",  |
|  53  |   "共青团团旗(GongQingTuanFlag)",   |
|  54  |  "少先队队徽(ShaoXianDuiEmblem)",   |
|  55  |   "少先队队旗(ShaoXianDuiFlag)",    |
|  56  |     "俄罗斯国旗(RussianFlag)",      |
|  57  |      "加拿大国旗(CanadaFlag)",      |
|  58  |       "印度国旗(IndiaFlag)",        |
|  59  |  "印度尼西亚国旗(IndonesiaFlag)",   |
|  60  | "巴基斯坦伊斯兰国旗(PakistanFlag)", |
|  61  |       "巴西国旗(BrazilFlag)",       |
|  62  |      "德国国旗(GermanyFlag)",       |
|  63  |    "新加坡国旗(SingaporeFlag)",     |
|  64  |       "日本国旗(JapanFlag)",        |
|  65  |     "朝鲜国旗(NorthKoreaFlag)",     |
|  66  |       "法国国旗(FrenchFlag)",       |
|  67  |      "泰国国旗(ThailandFlag)",      |
|  68  |      "美国国旗(AmericaFlag)",       |
|  69  |   "菲律宾国旗(PhilippinesFlag)",    |
|  70  |     "蒙古国国旗(MongoliaFlag)",     |
|  71  |      "越南国旗(VietnamFlag)",       |
|  72  |     "韩国国旗(SouthKoreaFlag)",     |
|  73  |     "时代力量(ShiDaiLiLiang)",      |
|  74  |         "三K党(KKKEmblem)",         |
|  75  |     "灰狼徽章(HuiLangEmblem)",      |
|  76  |         "万维TV(WanWeiTV)",         |
|  77  | "德国十字勋章(NaziShiZiXunZhang)",  |
|  78  |       "纳粹国徽(NaziGuoHui)",       |
|  79  |   "建党100周年纪念标识(CPC100)",    |
|  80  |       "港支联(GangZhiLian)",        |
|  81  |        "64纪念馆(64Museum)",        |
|  82  |      "自由西藏学生运动(SFT)",       |
|  83  |    "中国人权(ZhongGuoRenQuan)",     |
|  84  |    "恐怖组织(TerroristGroups)",     |
|  85  |     "胡赛运动(HouthiMovement)",     |
|  86  |              "6432nd",              |
|  87  |  "908台湾国运动旗帜(908TaiwanQi)",  |
|  88  |      "台字翠青旗(CuiQingQi)",       |
|  89  | "台湾独立建国联盟旗(TaiwanDuLiQi)", |
|  90  |     "台湾独立玉山旗(YuShanQi)",     |
|  91  |  "台湾独立鲸鱼旗(TaiwanJingYuQi)",  |
|  92  |      "民进党党旗(TWDPPFlag)",       |
|  93  |         "台湾双十庆典2021",         |

### Object Detection on Zhengzhi validation
| **模型/测试集**               | 38 classes(only_55c=False) | **86classes + 0301badcase** | **86classes + 0301badcase + dang** | **86-classes-qitadanghui-all-0805** | **86-classes-qitadanghui-add only** | **111_classes_0907** |
| ----------------------------- | -------------------------- | --------------------------- | ---------------------------------- | ----------------------------------- | ----------------------------------- | -------------------- |
| **之前的模型：**              |                            |                             |                                    |                                     |                                     |                      |
| DRN_ZZ0618_C86_E180           | 0.9158                     | 0.9131                      | 0.8882                             | /                                   | /                                   |                      |
| **0805的模型：**              |                            |                             |                                    |                                     |                                     |                      |
| DRN_ZZ0806_C86_E70.pth        | 0.9055                     | 0.9275                      | 0.9236                             | 0.9238                              | 0.9279                              |                      |
| DRN_ZZ0806_C86_E160.pth       | 0.9085                     | 0.9315                      | 0.9277                             | 0.9279                              | 0.9310                              |                      |
| DRN_ZZ0806_C86_E180.pth       | 0.9039                     | 0.9280                      | 0.9241                             | 0.9243                              | 0.9294                              |                      |
| DRN_ZZ0806_C86_E200.pth       | 0.9094                     | 0.9318                      | 0.9279                             | 0.9281                              | 0.9340                              |                      |
|                               |                            |                             |                                    |                                     |                                     |                      |
| **0901的模型：**              |                            |                             |                                    |                                     |                                     |                      |
| DRN_ZZ0907_C111_E140.pth      | /                          | /                           | /                                  | 0.9264                              | /                                   | 0.9082               |
| DRN_ZZ0907_C111_E190.pth      | /                          | /                           | /                                  | 0.9298                              | /                                   | 0.9163               |
|                               |                            |                             |                                    |                                     |                                     |                      |
| **0922的模型**：              |                            |                             |                                    |                                     |                                     |                      |
| DRN_ZZ0922_C93_E180_32gpu.pth | /                          | /                           | /                                  | 0.9289                              | /                                   | 0.9279               |
| DRN_ZZ0922_C93_E200_32gpu.pth | /                          | /                           | /                                  | 0.9316                              | /                                   | 0.9306               |
| DRN_ZZ0922_C93_E180_16gpu.pth | /                          | /                           | /                                  | 0.9356                              | /                                   | 0.9353               |
| DRN_ZZ0922_C93_E200_16gpu.pth | /                          | /                           | /                                  | 0.9317                              | /                                   | 0.9314               |
|                               |                            |                             |                                    |                                     |                                     |                      |
|                               |                            |                             |                                    |                                     |                                     |                      |


### Train

```pyhon
rpf-jcli run rpf.yaml
```



|  id  |            category_name            |
| :--: | :---------------------------------: |
|  1   |           "国旗(ZZ003)",            |
|  2   |           "国徽(ZZ004)",            |
|  3   |           "党旗(ZZ001)",            |
|  4   |           "党徽(ZZ002)",            |

|  id  |  category_name   |
| :--: | :--------------: |
|  1   |  "国旗(ZZ003)",  |
|  2   |  "国徽(ZZ004)",  |
|  3   |  "党旗(ZZ001)",  |
|  4   |  "党徽(ZZ002)",  |
|  5   | "人民币(ZZ016)", |
|  6   |  "军旗(ZZ005)",  |
