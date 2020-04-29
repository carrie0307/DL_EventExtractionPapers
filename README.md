

Based on [BaptisteBlouin](https://github.com/BaptisteBlouin/EventExtractionPapers), I review papers about **Deep Learning based Event Extraction**, and annotate **keywords and Abbreviation of Models**. Besides, I categorized the papers as **Chinese Event Extraction, Open-domain Event Extraction, Event Data Generation, Cross-lingual Event Extraction, Few-Shot Event Extraction and Zero-Shot Event Extraction**. 

Omissions and mistakes may exist in the review. Welcome to exchange and opinions!

以[BaptisteBlouin](https://github.com/BaptisteBlouin/EventExtractionPapers) 的整理为参考，笔者结合平时自己在研究中的归纳，着重整理了自**2015年以来基于深度学习方法**的事件抽取与检测论文，并指出了每篇论文的**模型简称及核心关键词**等；同时又对**中文事件抽取、开放域事件抽取、事件数据生成、跨语言事件抽取、小样本事件抽取、零样本事件抽取**等类型的任务进行了单独分类的标注。

整理之中或存在疏漏与错误，欢迎大家交流与补充！

* [Chinese Event Extraction](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#chinese-event-detection)
* [Open-Domain EE](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#open-domain-event-extraction)
* [Event Data Generation](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#data-generation)
* [Multi-Lingual](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#multi-lingual)
* [FewShot & ZeroShot](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#few-shot--zero-shot)
* [https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#semi-supervised](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#semi-supervised)


## 2015
* ACL2015: **Event Extraction via Dynamic Multi-Pooling Convolutional Neural Networks**
    * Author: Chen, Yubo  and Xu, Liheng  and Liu, Kang  and Zeng, Daojian  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P15-1017](https://www.aclweb.org/anthology/P15-1017)
    * DataSet: [ACE2005](https://catalog.ldc.upenn.edu/LDC2006T06)
    * keywords: DMCNN, CNN, Dynamic Multi-Pooling

* ACL2015: **Event Detection and Domain Adaptation with Convolutional Neural Networks**
    * Author: Nguyen, Thien Huu  and Grishman, Ralph
    * url: [https://www.aclweb.org/anthology/P15-2060](https://www.aclweb.org/anthology/P15-2060)
    * code: [https://github.com/ThanhChinhBK/event_detector](https://github.com/ThanhChinhBK/event_detector)
    * DataSet: [ACE2005](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: CNN, Domain Adaption
    
## 2016
   
* ACL2016: **Event Nugget Detection with Forward-Backward Recurrent Neural Networks**
    * Author: Ghaeini, Reza  and Fern, Xiaoli  and Huang, Liang  and Tadepalli, Prasad
    * ur: [https://www.aclweb.org/anthology/P16-2060](https://www.aclweb.org/anthology/P16-2060)
    * DataSet: [ACE2005](https://catalog.ldc.upenn.edu/LDC2006T06), [Rich ERE](http://www.aclweb.org/old_anthology/W/W15/W15-0812.pdf)
    * Keywords: multi-words events, RNN

* ACL2016: **RBPB Regularization Based Pattern Balancing Method for Event Extraction**
    * Author: Sha, Lei  and Liu, Jing  and Lin, Chin-Yew  and Li, Sujian  and Chang, Baobao  and Sui, Zhifang
    * url: [https://www.aclweb.org/anthology/P16-1116](https://www.aclweb.org/anthology/P16-1116)
    * DataSet: [ACE2005](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Embedding & Pattern features, Regularization method

* ACL2016: **A Language-Independent Neural Network for Event Detection**
    * Author: Feng, Xiaocheng  and Huang, Lifu  and Tang, Duyu  and
Ji, Heng  and Qin, Bing  and Liu, Ting
    * url: [https://www.aclweb.org/anthology/P16-2011](https://www.aclweb.org/anthology/P16-2011)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), Spainish ERE Corpus
    * Keywords: Hybrid Neural Networks(RNN+CNN), multi-languages

* ACL2016: **Leveraging FrameNet to Improve Automatic Event Detection**
    * Author: Liu, Shulin  and Chen, Yubo  and He, Shizhu  and Liu, Kang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P16-1201](https://www.aclweb.org/anthology/P16-1201)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/liushulinle/events_in_framenet](https://github.com/liushulinle/events_in_framenet)
    * Keywords: [FrameNet](https://framenet.icsi.berkeley.edu/fndrupal/), Events automatically detected from FN

* EMNLP2016: **Modeling Skip-Grams for Event Detection with Convolutional Neural Networks**
    * Author: Nguyen, Thien Huu  and Grishman, Ralph
    * url: [https://www.aclweb.org/anthology/D16-1085](https://www.aclweb.org/anthology/D16-1085)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Non-consecutive kgrams, CNN

* COLING2016:**Leveraging Multilingual Training for Limited Resource Event Extraction**
    * Author: Hsi, Andrew  and Yang, Yiming  and Carbonell, Jaime  and Xu, Ruochen
    * url: [https://www.aclweb.org/anthology/C16-1114](https://www.aclweb.org/anthology/C16-1114)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Training on multiple languages using a combination of both language-dependent and language-independent features

* NAACL2016: **Joint Event Extraction via Recurrent Neural Networks**
    * Author: Nguyen, Thien Huu  and Cho, Kyunghyun  and Grishman, Ralph
    * url: [https://www.aclweb.org/anthology/N16-1034](https://www.aclweb.org/anthology/N16-1034)
    * DataSet:  [ACE2005](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: RNN, Joint Event Extraction
    
* CCL2016: **Event Extraction via Bidirectional Long Short-Term Memory Tensor Neural Network** 
   * Author: Chen, Yubo and Liu, Shulin and He, Shizhu and Liu, Kang and Zhao, Jun
   * url: [http://www.cips-cl.org/static/anthology/CCL-2016/CCL-16-081.pdf](http://www.cips-cl.org/static/anthology/CCL-2016/CCL-16-081.pdf)
   * DataSet:  [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
   * Keywords: Context-aware word representation, LSTM, Tensor layer

## 2017

* ACL2017: **Automatically Labeled Data Generation for Large Scale Event Extraction**
    * Author: Chen, Yubo  and   Liu, Shulin  and Zhang, Xiang  and
Liu, Kang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P17-1038](https://www.aclweb.org/anthology/P17-1038)
    * Code: [https://github.com/acl2017submission/event-data](https://github.com/acl2017submission/event-data)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Data Generation, Distant Supervision

* ACL2017: **Exploiting Argument Information to Improve Event Detection via Supervised Attention Mechanisms**
    * Author: Liu, Shulin  and Chen, Yubo  and Liu, Kang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P17-1164](https://www.aclweb.org/anthology/P17-1164)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Argument information, Supervised Attention


* IJCNLP2017: **Exploiting Document Level Information to Improve Event Detection via Recurrent Neural Networks**
    * Author: Duan, Shaoyang  and He, Ruifang  and Zhao, Wenli
    * url: [https://www.aclweb.org/anthology/I17-1036](https://www.aclweb.org/anthology/I17-1036)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: DLRNN, Document information, Cross-sentence clues

## 2018
* AAAI2018: **Scale up event extraction learning via automatic training data generation**
    * Authors: Zeng, Ying and Feng, Yansong and Ma, Rong and Wang, Zheng and Yan, Rui and Shi, Chongde and Zhao, Dongyan
    * url: [https://arxiv.org/pdf/1712.03665.pdf](
https://arxiv.org/pdf/1712.03665.pdf)
    * DataSet: Wikipedia article, 
    * Keywords: Data Generation, Distant Supervision

* AAAI2018: **Jointly Extraction Event Triggers and Arguments by Dependency-Bridge RNN and Tensor-Based Argument Iteraction**
    * Auhtor: Sha, Lei and Qian, Feng and Chang, Baobao and Sui, Zhifang
    * url: [http://shalei120.github.io/docs/sha2018Joint.pdf](http://shalei120.github.io/docs/sha2018Joint.pdf)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: dbRNN

* AAAI2018: **Graph convolutional networks with argument-aware pooling for event detection**
    * Author: Nguyen, Thien Huu and Grishman, Ralph
    * url: [http://ix.cs.uoregon.edu/~thien/pubs/graphConv.pdf](http://ix.cs.uoregon.edu/~thien/pubs/graphConv.pdf)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: GCN, Argument-aware Pooling

* AAAI2018: **Event detection via gated multilingual attention mechanism**
    * Author: Liu, Jian and Chen, Yubo and Liu, Kang and Zhao, Jun
    * url: [https://www.semanticscholar.org/paper/Event-Detection-via-Gated-Multilingual-Attention-Liu-Chen/e41984c1c89af71eb3700f5fd2a865eae95c6c8a](https://www.semanticscholar.org/paper/Event-Detection-via-Gated-Multilingual-Attention-Liu-Chen/e41984c1c89af71eb3700f5fd2a865eae95c6c8a)
    * DataSet:  [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Multilingual Attention
    
* ACL2018: **Document Embedding Enhanced Event Detection with Hierarchical and Supervised Attention**
    * Author: Zhao, Yue  and Jin, Xiaolong  and Wang, Yuanzhuo  and Cheng, Xueqi
    * url: [https://www.aclweb.org/anthology/P18-2066](https://www.aclweb.org/anthology/P18-2066)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Document Embedding, Hierarchicak and Supervised Attention

* ACL2018: **Self-regulation: Employing a Generative Adversarial Network to Improve Event Detection**
    * Author: Hong, Yu  and Zhou, Wenxuan  and Zhang, Jingli  and Zhou, Guodong  and Zhu, Qiaoming
    * url: [https://www.aclweb.org/anthology/P18-1048](https://www.aclweb.org/anthology/P18-1048)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), KBP2015
    * Keywords: GAN + ED

* ACL2018: **Nugget Proposal Networks for Chinese Event Detection**
    * Author: Lin, Hongyu and Lu, Yaojie and Han, Xianpei and Sun, Le
    * url: [https://www.aclweb.org/anthology/P18-1145.pdf](https://www.aclweb.org/anthology/P18-1145.pdf)
    * DataSet: [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), KBP2017 Corpus
    * Code: [https://github.com/sanmusunrise/NPNs](https://github.com/sanmusunrise/NPNs)

* ACL2018: **Zero-Shot Transfer Learning for Event Extraction**
    * Author: Lifu Huang, Heng Ji, Kyunghyun Cho, Ido Dagan, Sebastian Riedel, Clare R. Voss
    * url: [https://www.aclweb.org/anthology/P18-1201/](https://www.aclweb.org/anthology/P18-1201/)
    * Code:[https://github.com/wilburOne/ZeroShotEvent](https://github.com/wilburOne/ZeroShotEvent)
    * Keywords: Zero-Shot Transfer

* ACL2018: **DCFFE: A Document-level Chinese Financial Event Extraction System based on Automatically Labelled Training Data**
    * Author: Yang, Hang  and Chen, Yubo  and Liu, Kang  and Xiao, Yang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P18-4009](https://www.aclweb.org/anthology/P18-4009)
    * Keywords: Automatically Labelled, Chinese Financial EE
    
* **Joint Entity and Event Extraction with Generative Adversarial Imitation Learning**
    * Author: Tongtao Zhang and Heng Ji and Avirup Sil
    * url: [https://blender.cs.illinois.edu/paper/imitation2019.pdf](https://blender.cs.illinois.edu/paper/imitation2019.pdf)

* EMNLP2018: **Event Detection with Neural Networks A Rigorous Empirical Evaluation**
    * Author: Orr, Walker  and Tadepalli, Prasad  and Fern, Xiaoli
    * url: [https://www.aclweb.org/anthology/D18-1122](https://www.aclweb.org/anthology/D18-1122)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: DAG-GRU, Attention Mechnism

* EMNLP2018: **Exploiting Contextual Information via Dynamic Memory Network for Event Detection**
    * Author: Liu, Shaobo  and Cheng, Rui  and Yu, Xiaoming  and Cheng, Xueqi
    * url: [https://www.aclweb.org/anthology/D18-1127/](https://www.aclweb.org/anthology/D18-1127/)
    * Code: [https://github.com/AveryLiu/TD-DMN](https://github.com/AveryLiu/TD-DMN)
    * DataSet:  [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Contextual Information, Dynamic Memory Networks

* EMNLP2018: **Joint Multiple Event Extraction via Attention-based Graph Information Aggregration**
    * Author: Liu, Xiao  and Luo, Zhunchen  and Huang, Heyan
    * url: [https://www.aclweb.org/anthology/D18-1156](https://www.aclweb.org/anthology/D18-1156)
    * Code: [https://github.com/lx865712528/EMNLP2018-JMEE/](https://github.com/lx865712528/EMNLP2018-JMEE/)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: JMEE

* EMNLP2018: **Similar but not the Same Word Sense Disambiguation Improves Event Detection via Neural Representation Matching**
    * Author: Lu, Weiyi  and  Nguyen, Thien Huu
    * url: [https://www.aclweb.org/anthology/D18-1517/](https://www.aclweb.org/anthology/D18-1517/)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), [TAC2015](https://tac.nist.gov//2015/KBP/Event/index.html)
    * Keywords:  Word Sense Disambiguation

* EMNLP2018: **Collective Event Detection via a Hierarchical and Bias Tagging Networks with Gated Multi-level Attention Mechanisms**
    * Author: Chen, Yubo  and Yang, Hang  and Liu, Kang  and Zhao, Jun  and Jia, Yantao
    * url: [https://www.aclweb.org/anthology/D18-1158](https://www.aclweb.org/anthology/D18-1158)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/yubochen/NBTNGMA4ED/](https://github.com/yubochen/NBTNGMA4ED/)
    * Keywords: NBTNGMA4ED

* NAACL2018: **Semi-supervised event extraction with paraphrase clusters**
    * Author: Ferguson, James  and Lockard, Colin  and  Weld, Daniel  and Hajishirzi, Hannaneh
    * url: [https://www.aclweb.org/anthology/N18-2058/](https://www.aclweb.org/anthology/N18-2058/)
    * DataSet: [ACE2005 Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), [TAC2015](https://tac.nist.gov//2015/KBP/Event/index.html)
    * Keywords: Semi-supervised

* COLING2018: **Open-Domain Event Detection using Distant Supervision**
    * Author: Araki, Jun  and  Mitamura, Teruko
    * url: [https://www.aclweb.org/anthology/C18-1075/](https://www.aclweb.org/anthology/C18-1075/)
    * Code:[https://bitbucket.org/junaraki/coling2018-event](https://bitbucket.org/junaraki/coling2018-event)
    * Keywords: Open-Domain, Distant Supervision

## 2019
* AAAI2019: **Exploiting the Ground-Truth An Adversarial Imitation Based Knowledge Distiallation Approach for Event Detection**
    * Author: Liu, Jian and Chen, Yubo and Liu, Kang
    * url: [https://www.aaai.org/ojs/index.php/AAAI/article/view/4649/4527](https://www.aaai.org/ojs/index.php/AAAI/article/view/4649/4527)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Adversarial, Knowledge Distillation

* ACL2019: **Cost-Sensitive Regulation for Label Confustion-aware Event Detection**
    * Author: Lin, Hongyu  and Lu, Yaojie  and  Han, Xianpei  and Sun, Le
    * url: [https://www.aclweb.org/anthology/P19-1521](https://www.aclweb.org/anthology/P19-1521)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), [KBP2017](https://tac.nist.gov/2017/KBP/)
    * Code: [https://github.com/sanmusunrise/CSR](https://github.com/sanmusunrise/CSR)

* ACL2019: **Distilling Discrimination and Generalization Knowledge for Event Detection via Delta-Representation Learning**
    * Author: Lu, Yaojie  and Lin, Hongyu  and Han, Xianpei  and Sun, Le
    * url: [https://www.aclweb.org/anthology/P19-1429](https://www.aclweb.org/anthology/P19-1429)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), [KBP2017](https://tac.nist.gov/2017/KBP/)
    * Code: [https://github.com/luyaojie/delta-learning-for-ed](https://github.com/luyaojie/delta-learning-for-ed)

* ACL2019: **Exploring Pre-trained Language Models for Event Extraction and Geenration**
    * Author: Yang, Sen  and Feng, Dawei  and Qiao, Linbo  and Kan, Zhigang  and
    Li, Dongsheng
    * url: [https://www.aclweb.org/anthology/P19-1522](https://www.aclweb.org/anthology/P19-1522)
    * Keywords: PLMEE, BERT

* ACL2019: **Literary Event Detection**
    * Author: Matthew Sims, Jong Ho Park, David Bamman
    * url: [https://www.aclweb.org/anthology/P19-1353/](https://www.aclweb.org/anthology/P19-1353/)
    * Code: [https://github.com/dbamman/ACL2019-literary-events](https://github.com/dbamman/ACL2019-literary-events)

* ACL2019: **Open Domain Event Extraction Using Neural Latent Variable Models**
    * Author: Xiao Liu and Heyan Huang and Yue Zhang
    * url: [https://www.aclweb.org/anthology/P19-1276/](https://www.aclweb.org/anthology/P19-1276/)
    * Code: [https://github.com/lx865712528/ACL2019-ODEE](https://github.com/lx865712528/ACL2019-ODEE)

* ACL2019: **Rapid Customization for Event Extraction**
    * Author: Yee Seng Chan, Joshua Fasching, Haoling Qiu, Bonan Min
    * url: [https://www.aclweb.org/anthology/P19-3006/](https://www.aclweb.org/anthology/P19-3006/)
    * Code: [https://github.com/BBN-E/Rapid-customization-events-acl19](https://github.com/BBN-E/Rapid-customization-events-acl19)

* **Extending Event Detection to New Types with Learning from Keywords**
    * Author: Lai, Viet Dac  and Nguyen, Thien
    * url: [https://www.aclweb.org/anthology/D19-5532](https://www.aclweb.org/anthology/D19-5532)

* WWW2019: **Event Detection using Hierarchical Multi-Aspect Attention**
    * Author: Sneha Mehta, M. Raihanul Islam, Huzefa Rangwala, Naren Ramakrishnan
    * url: [https://dl.acm.org/doi/fullHtml/10.1145/3308558.3313659](https://dl.acm.org/doi/fullHtml/10.1145/3308558.3313659)
    * Code: [https://github.com/sumehta/FBMA](https://github.com/sumehta/FBMA)

* CONLL2019: **Exploiting the Entity Type Sequence to Benefit Event Detection**
    * Author: Yuze Ji, Youfang Lin, Jianwei Gao, Huaiyu Wan
    * url: [https://www.aclweb.org/anthology/K19-1057/](https://www.aclweb.org/anthology/K19-1057/)
    * Code: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)

* EMNLP2019: **A Search-based Neural Model for Biomedical Nested and Overlapping Event Detection**
    * Author: Kurt Junshean Espinosa, Makoto Miwa, Sophia Ananiadou
    * url: [https://www.aclweb.org/anthology/D19-1381/](https://www.aclweb.org/anthology/D19-1381/)
    * DataSet: BioNLP Cancer Genetics (CG) Shared Task 2013 

* EMNLP2019: **Cross-lingual Structure Transfer for Relation and Event Extraction**
    * Author: Ananya Subburathinam, Di Lu, Heng Ji, Jonathan May, Shih-Fu Chang, Avirup Sil, Clare Voss
    * url: [https://www.aclweb.org/anthology/D19-1030/](https://www.aclweb.org/anthology/D19-1030/)

* EMNLP2019: **Doc2EDAG: An End-to-End Document-level Framework for Chinese Financial Event Extraction**
    * Author: Shun Zheng, Wei Cao, Wei Xu, Jiang Bian
    * url: [https://www.aclweb.org/anthology/D19-1032/](https://www.aclweb.org/anthology/D19-1032/)

* EMNLP2019: **Entity, Relation, and Event Extraction with Contextualized Span Representations**
    * Author: David Wadden, Ulme Wennberg, Yi Luan, Hannaneh Hajishirzi
    * url: [https://www.aclweb.org/anthology/D19-1585](https://www.aclweb.org/anthology/D19-1585)
    * Code: [https://github.com/dwadden/dygiepp](https://github.com/dwadden/dygiepp)

* EMNLP2019: **Event Detection with Multi-Order Graph Convolution and Aggregated**
    * Author: Yan, Haoran  and Jin, Xiaolong  and Meng, Xiangbin  and Guo, Jiafeng  and Cheng, Xueqi
    * url: [https://www.aclweb.org/anthology/D19-1582](https://www.aclweb.org/anthology/D19-1582)
    * DataSet:  [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: MOGANED

* EMNLP2019: **Event Detection with Trigger-Aware Lattice Neural Network**
    * Author: Ning Ding, Ziran Li, Zhiyuan Liu, Haitao Zheng, Zibo Lin
    * url: [https://www.aclweb.org/anthology/D19-1033/](https://www.aclweb.org/anthology/D19-1033/)
    * DataSet:  [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/thunlp/TLNN](https://github.com/thunlp/TLNN)
    * Keywords: Trigger-Aware Lattice 

* EMNLP2019: **HMEAE: Hierarchical Modular Event Argument Extraction**
    * Author: Xiaozhi Wang, Ziqi Wang, Xu Han, Zhiyuan Liu, Juanzi Li, Peng Li, Maosong Sun, Jie Zhou, Xiang Ren
    * url: [https://www.aclweb.org/anthology/D19-1584/](https://www.aclweb.org/anthology/D19-1584/)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/thunlp/HMEAE](https://github.com/thunlp/HMEAE)

* EMNLP2019: **Joint Event and Temporal Relation Extraction with Shared Representations and Structured Prediction**
    * Author: Rujun Han, Qiang Ning, Nanyun Peng
    * url: [https://www.aclweb.org/anthology/D19-1041/](https://www.aclweb.org/anthology/D19-1041/)

* EMNLP2019: **Neural Cross-Lingual Event Detection with Minimal Parallel Resources**
    * Author: Jian Liu, Yubo Chen, Kang Liu, Jun Zhao
    * url: [https://www.aclweb.org/anthology/D19-1068/](https://www.aclweb.org/anthology/D19-1068/)
    * Keywords: Cross-Lingual Event Detection


* EMNLP2019: **Open Event Extraction from Online Text using a Generative Adversarial Network**
    * Author: Rui Wang, Deyu Zhou, Yulan He
    * url: [https://www.aclweb.org/anthology/D19-1027/](https://www.aclweb.org/anthology/D19-1027/)

* EMNLP2019: **Reporting the unreported: Event Extraction for Analyzing the Local Representation of Hate Crimes**
    * Author: Aida Mostafazadeh Davani etal.
    * url: [https://arxiv.org/pdf/1909.02126.pdf](https://arxiv.org/pdf/1909.02126.pdf)
    * Code: [https://github.com/aiida-/HateCrime](https://github.com/aiida-/HateCrime)

* IJCAI2019: **Extracting entities and events as a single task using a transition-based neural model**
    * Author: Zhang, Junchi and Qin, Yanxia and Zhang, Yue and Liu, Mengchi and Ji, Donghong
    * url: [https://www.ijcai.org/proceedings/2019/753](https://www.ijcai.org/proceedings/2019/753)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/zjcerwin/TransitionEvent](https://github.com/zjcerwin/TransitionEvent)

* IJCNLP2019: **A Hybrid Character Representatin for Chinese Event Detection**
    * Author: Xi Xiangyu ; Zhang Tong ; Ye Wei ; Zhang Jinglei ; Xie Rui ; Zhang Shikun
    * url: [https://ieeexplore.ieee.org/document/8851786](https://ieeexplore.ieee.org/document/8851786)
    * DataSet: [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)

* NAACL2019: **Adversarial Training for Weakly Supervised Event Detection**
    * Author: Xiaozhi Wang, Xu Han, Zhiyuan Liu, Maosong Sun, Peng Li
    * url: [https://www.aclweb.org/anthology/N19-1105/](https://www.aclweb.org/anthology/N19-1105/)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/LolaJing0822/Adversarial-Training-for-Weakly-Supervised-Event-Detection](https://github.com/LolaJing0822/Adversarial-Training-for-Weakly-Supervised-Event-Detection)

* NAACL2019: **Event Detection without Triggers**
    * Author: Shulin Liu, Yang Li, Feng Zhang, Tao Yang, Xinpeng Zhou
    * url: [https://www.aclweb.org/anthology/N19-1080/](https://www.aclweb.org/anthology/N19-1080/)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/liushulinle/event_detection_without_triggers](https://github.com/liushulinle/event_detection_without_triggers)

* NAACL2019: **Biomedical Event Extraction based on Knowledge-driven Tree-LSTM**
    * Author: Diya Li, Lifu Huang, Heng Ji, Jiawei Han
    * url: [https://www.aclweb.org/anthology/N19-1145/](https://www.aclweb.org/anthology/N19-1145/)
    * DataSet: Genia2011 dataset
    * Keywords: Knowledge-driven Tree-LSTM

* **A Survey of Event Extraction from Text**
    * Author: Wei Xiang, Bang Wang
    * url: [https://ieeexplore.ieee.org/document/8918013](https://ieeexplore.ieee.org/document/8918013)

* **Joint Event Extraction Based on Hierarchical Event Schemas From FrameNet**
    * Author: Wei Li , Dezhi Cheng, Lei He, Yuanzhuo Wang, Xiaolong Jin
    * url: [https://ieeexplore.ieee.org/document/8643786](https://ieeexplore.ieee.org/document/8643786)

## 2020
* PAKDD2020: **Exploiting the Matching Information in the Support Set for Few Shot Event Classification**
    * Authors: Viet Lai, Franck Dernoncourt, Thien Huu Nguyen
    * url: [https://arxiv.org/abs/2002.05295](https://arxiv.org/abs/2002.05295)
    * Keywords: FewShot

* WSDM2020: **Meta-Learning with Dynamic-Memory-Based Prototypical Network for Few-Shot Event Detection**
    * Authors: Shumin Deng, Ningyu Zhang, Jiaojian Kang, Yichi Zhang, Wei Zhang, Huajun Chen
    * url: [https://arxiv.org/abs/1910.11621](https://arxiv.org/abs/1910.11621)
    * Code: [https://github.com/231sm/Low_Resource_KBP](https://github.com/231sm/Low_Resource_KBP)

* arxiv2020: **Open-domain Event Extraction and Embedding for Natural Gas Market Prediction**
    * Authors: Chau, Minh Triet and Esteves, Diego and Lehmann, Jens
    * url: [https://arxiv.org/abs/1912.11334](https://arxiv.org/abs/1912.11334)

* arxiv2020: **Event Extraction as Definitation Comprehension**
    * Authors: Yunmo Chen, Tongfei Chen, Seth Ebner, Benjamin Van Durme
    * url: [https://arxiv.org/abs/1912.01586](https://arxiv.org/abs/1912.01586)

* arxiv2020: **Event Detection with Relation-Aware Graph Convolutional Neural Networks**
    * Authors: Shiyao Cui, Bowen Yu, Tingwen Liu, Zhenyu Zhang, Xuebin Wang, Jinqiao Shi
    * url: [https://arxiv.org/abs/2002.10757](https://arxiv.org/abs/2002.10757)
    * Code: to be updated

* arxiv2020: **MAVEN: A Massive General Domain Event Detection Dataset**
    * Authors: Xiaozhi Wang, Ziqi Wang, Xu Han, Wangyi Jiang, Rong Han, Zhiyuan Liu, Juanzi Li, Peng Li, Yankai Lin, Jie Zhou
    * url: [https://arxiv.org/abs/2004.13590]https://arxiv.org/abs/2004.13590
    
* arxiv2020: **Event Extraction by Answering (Almost) Natural Questions**
    * Authors:Xinya Du, Claire Cardie
    * url: [https://arxiv.org/abs/2004.13625](https://arxiv.org/abs/2004.13625)



    
## Chinese Event Detection
* NLPCC2016 : A convolution bilstm neural network model for chinese event extraction 中文事件抽取

* ACL2018: **Nugget Proposal Networks for Chinese Event Detection**
    * Author: Lin, Hongyu and Lu, Yaojie and Han, Xianpei and Sun, Le
    * url: [https://www.aclweb.org/anthology/P18-1145.pdf](https://www.aclweb.org/anthology/P18-1145.pdf)
    * DataSet: [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), KBP2017 Corpus
    * Code: [https://github.com/sanmusunrise/NPNs](https://github.com/sanmusunrise/NPNs)

* ACL2018: **DCFFE: A Document-level Chinese Financial Event Extraction System based on Automatically Labelled Training Data**
    * Author: Yang, Hang  and Chen, Yubo  and Liu, Kang  and Xiao, Yang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P18-4009](https://www.aclweb.org/anthology/P18-4009)
    * Keywords: Automatically Labelled, Chinese Financial EE

* EMNLP2019: **Doc2EDAG: An End-to-End Document-level Framework for Chinese Financial Event Extraction**
    * Author: Shun Zheng, Wei Cao, Wei Xu, Jiang Bian
    * url: [https://www.aclweb.org/anthology/D19-1032/](https://www.aclweb.org/anthology/D19-1032/)

* EMNLP2019: **Event Detection with Trigger-Aware Lattice Neural Network**
    * Author: Ning Ding, Ziran Li, Zhiyuan Liu, Haitao Zheng, Zibo Lin
    * url: [https://www.aclweb.org/anthology/D19-1033/](https://www.aclweb.org/anthology/D19-1033/)
    * DataSet:  [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/thunlp/TLNN](https://github.com/thunlp/TLNN)
    * Keywords: Trigger-Aware Lattice 

* IJCNLP2019: **A Hybrid Character Representatin for Chinese Event Detection**
    * Author: Xi Xiangyu ; Zhang Tong ; Ye Wei ; Zhang Jinglei ; Xie Rui ; Zhang Shikun
    * url: [https://ieeexplore.ieee.org/document/8851786](https://ieeexplore.ieee.org/document/8851786)
    * DataSet: [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)


* EMNLP2019: **Cross-lingual Structure Transfer for Relation and Event Extraction**
    * Author: Ananya Subburathinam, Di Lu, Heng Ji, Jonathan May, Shih-Fu Chang, Avirup Sil, Clare Voss
    * url: [https://www.aclweb.org/anthology/D19-1030/](https://www.aclweb.org/anthology/D19-1030/)


  
## Open Domain Event Extraction

* AACL2016: **Liberal Event Extraction and Event Schema Enduction**
    * Lifu Huang, Taylor Cassidy, Xiaocheng Feng, Heng Ji, Clare R. Voss, Jiawei Han, Avirup Sil
    * url: [https://www.aclweb.org/anthology/P16-1025/](https://www.aclweb.org/anthology/P16-1025/)

* NAACL2016: **Joint Learning Templates and Slots for Event Schema Induction**
    * Author: Lei Sha, Sujian Li, Baobao Chang, Zhifang Sui
    * url: [https://www.aclweb.org/anthology/N16-1049/](https://www.aclweb.org/anthology/N16-1049/)
    * Code: [https://github.com/shenglih/normalized_cut/tree/master](https://github.com/shenglih/normalized_cut/tree/master)

* AACL2015: **Generative Event Schema Induction with Entity Disambiguation**
    * Author: Kiem-Hieu Nguyen, Xavier Tannier, Olivier Ferret, Romaric Besançon
    * url: [https://www.aclweb.org/anthology/P15-1019/](https://www.aclweb.org/anthology/P15-1019/)

* COLING2018: **Open-Domain Event Detection using Distant Supervision**
    * Author: Araki, Jun  and  Mitamura, Teruko
    * url: [https://www.aclweb.org/anthology/C18-1075/](https://www.aclweb.org/anthology/C18-1075/)
    * Code:[https://bitbucket.org/junaraki/coling2018-event](https://bitbucket.org/junaraki/coling2018-event)
    * Keywords: Open-Domain, Distant Supervision

* ACL2019: **Open Domain Event Extraction Using Neural Latent Variable Models**
    * Author: Xiao Liu and Heyan Huang and Yue Zhang
    * url: [https://github.com/lx865712528/ACL2019-ODEE](https://github.com/lx865712528/ACL2019-ODEE)
    * Code: [https://github.com/lx865712528/ACL2019-ODEE](https://github.com/lx865712528/ACL2019-ODEE)

* EMNLP2019: **Reporting the unreported: Event Extraction for Analyzing the Local Representation of Hate Crimes**
    * Author: Aida Mostafazadeh Davani etal.
    * url: [https://arxiv.org/pdf/1909.02126.pdf](https://arxiv.org/pdf/1909.02126.pdf)
    * Code: [https://github.com/aiida-/HateCrime](https://github.com/aiida-/HateCrime)

* arxiv2020: **Open-domain Event Extraction and Embedding for Natural Gas Market Prediction**
    * Authors: Chau, Minh Triet and Esteves, Diego and Lehmann, Jens
    * url: [https://arxiv.org/abs/1912.11334](https://arxiv.org/abs/1912.11334)


## Data Generation
* ACL2016: **Leveraging FrameNet to Improve Automatic Event Detection**
    * Author: Liu, Shulin  and Chen, Yubo  and He, Shizhu  and Liu, Kang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P16-1201](https://www.aclweb.org/anthology/P16-1201)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Code: [https://github.com/liushulinle/events_in_framenet](https://github.com/liushulinle/events_in_framenet)
    * Keywords: [FrameNet](https://framenet.icsi.berkeley.edu/fndrupal/), Events automatically detected from FN

* ACL2017: **Automatically Labeled Data Generation for Large Scale Event Extraction**
    * Author: Chen, Yubo  and   Liu, Shulin  and Zhang, Xiang  and
Liu, Kang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P17-1038](https://www.aclweb.org/anthology/P17-1038)
    * Code: [https://github.com/acl2017submission/event-data](https://github.com/acl2017submission/event-data)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Data Generation, Distant Supervision

* ACL2019: **Exploring Pre-trained Language Models for Event Extraction and Geenration**
    * Author: Yang, Sen  and Feng, Dawei  and Qiao, Linbo  and Kan, Zhigang  and
    Li, Dongsheng
    * url: [https://www.aclweb.org/anthology/P19-1522](https://www.aclweb.org/anthology/P19-1522)
    * Keywords: PLMEE, BERT

* **Extending Event Detection to New Types with Learning from Keywords**
    * Author: Lai, Viet Dac  and Nguyen, Thien
    * url: [https://www.aclweb.org/anthology/D19-5532](https://www.aclweb.org/anthology/D19-5532)

* EMNLP2019: **Open Event Extraction from Online Text using a Generative Adversarial Network**
    * Author: Rui Wang, Deyu Zhou, Yulan He
    * url: [https://www.aclweb.org/anthology/D19-1027/](https://www.aclweb.org/anthology/D19-1027/)

* EMNLP2019: **Reporting the unreported: Event Extraction for Analyzing the Local Representation of Hate Crimes**
    * Author: Aida Mostafazadeh Davani etal.
    * url: [https://arxiv.org/pdf/1909.02126.pdf](https://arxiv.org/pdf/1909.02126.pdf)
    * Code: [https://github.com/aiida-/HateCrime](https://github.com/aiida-/HateCrime)

* arxiv2020: **MAVEN: A Massive General Domain Event Detection Dataset**
    * Authors: Xiaozhi Wang, Ziqi Wang, Xu Han, Wangyi Jiang, Rong Han, Zhiyuan Liu, Juanzi Li, Peng Li, Yankai Lin, Jie Zhou
    * url: [https://arxiv.org/abs/2004.13590]https://arxiv.org/abs/2004.13590

## Multi-lingual
* ACL2016: **A Language-Independent Neural Network for Event Detection**
    * Author: Feng, Xiaocheng  and Huang, Lifu  and Tang, Duyu  and
Ji, Heng  and Qin, Bing  and Liu, Ting
    * url: [https://www.aclweb.org/anthology/P16-2011](https://www.aclweb.org/anthology/P16-2011)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), Spainish ERE Corpus
    * Keywords: Hybrid Neural Networks(RNN+CNN), multi-languages

* COLING2016:**Leveraging Multilingual Training for Limited Resource Event Extraction**
    * Author: Hsi, Andrew  and Yang, Yiming  and Carbonell, Jaime  and Xu, Ruochen
    * url: [https://www.aclweb.org/anthology/C16-1114](https://www.aclweb.org/anthology/C16-1114)
    * DataSet: [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Training on multiple languages using a combination of both language-dependent and language-independent features

* AAAI2018: **Event detection via gated multilingual attention mechanism**
    * Author: Liu, Jian and Chen, Yubo and Liu, Kang and Zhao, Jun
    * url: [https://www.semanticscholar.org/paper/Event-Detection-via-Gated-Multilingual-Attention-Liu-Chen/e41984c1c89af71eb3700f5fd2a865eae95c6c8a](https://www.semanticscholar.org/paper/Event-Detection-via-Gated-Multilingual-Attention-Liu-Chen/e41984c1c89af71eb3700f5fd2a865eae95c6c8a)
    * DataSet:  [ACE2005 English Corpus](https://catalog.ldc.upenn.edu/LDC2006T06)
    * Keywords: Multilingual Attention

* EMNLP2019: **Cross-lingual Structure Transfer for Relation and Event Extraction**
    * Author: Ananya Subburathinam, Di Lu, Heng Ji, Jonathan May, Shih-Fu Chang, Avirup Sil, Clare Voss
    * url: [https://www.aclweb.org/anthology/D19-1030/](https://www.aclweb.org/anthology/D19-1030/)

* EMNLP2019: **Neural Cross-Lingual Event Detection with Minimal Parallel Resources**
    * Author: Jian Liu, Yubo Chen, Kang Liu, Jun Zhao
    * url: [https://www.aclweb.org/anthology/D19-1068/](https://www.aclweb.org/anthology/D19-1068/)
    * Keywords: Cross-Lingual Event Detection


## Few-Shot & Zero-Shot
* ACL2018: **Zero-Shot Transfer Learning for Event Extraction**
    * Author: 
    * url: [https://www.aclweb.org/anthology/P18-1201/](https://www.aclweb.org/anthology/P18-1201/)
    * Code:[https://github.com/wilburOne/ZeroShotEvent](https://github.com/wilburOne/ZeroShotEvent)
    * Keywords: Zero-Shot Transfer

* PAKDD2020: **Exploiting the Matching Information in the Support Set for Few Shot Event Classification**
    * Authors: Viet Lai, Franck Dernoncourt, Thien Huu Nguyen
    * url: [https://arxiv.org/abs/2002.05295](https://arxiv.org/abs/2002.05295)
    * Keywords: FewShot

* WSDM2020: **Meta-Learning with Dynamic-Memory-Based Prototypical Network for Few-Shot Event Detection**
    * Authors: Shumin Deng, Ningyu Zhang, Jiaojian Kang, Yichi Zhang, Wei Zhang, Huajun Chen
    * url: [https://arxiv.org/abs/1910.11621](https://arxiv.org/abs/1910.11621)
    * Code: [https://github.com/231sm/Low_Resource_KBP](https://github.com/231sm/Low_Resource_KBP)



## Semi-Supervised
* NAACL2018: **Semi-supervised event extraction with paraphrase clusters**
    * Author: Ferguson, James  and Lockard, Colin  and  Weld, Daniel  and Hajishirzi, Hannaneh
    * url: [https://www.aclweb.org/anthology/N18-2058/](https://www.aclweb.org/anthology/N18-2058/)
    * DataSet: [ACE2005 Chinese Corpus](https://catalog.ldc.upenn.edu/LDC2006T06), [TAC2015](https://tac.nist.gov//2015/KBP/Event/index.html)
    * Keywords: Semi-supervised

