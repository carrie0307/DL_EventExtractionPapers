Based on [BaptisteBlouin](https://github.com/BaptisteBlouin/EventExtractionPapers), I review papers about **Deep Learning based Event Extraction**, and annotate **keywords and Abbreviation of Models**. Besides, I categorized the papers as **Chinese Event Extraction, Open-domain Event Extraction, Event Data Generation, Cross-lingual Event Extraction, Few-Shot Event Extraction and Zero-Shot Event Extraction**, **Document-level EE**. 

Omissions and mistakes may exist in the review. Welcome to exchange and opinions!

* [Chinese Event Extraction](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#chinese-event-detection)
* [Open-Domain EE](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#open-domain-event-extraction)
* [Event Data Generation](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#data-generation)
* [Multi-Lingual](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#multi-lingual)
* [FewShot & ZeroShot](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#few-shot--zero-shot)
* [Semi-supervised](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#semi-supervised)
* [Doc-Level EE](https://github.com/carrie0307/DL_EventExtractionPapers/tree/master#Doc-Level-EE)


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
    
* NAACL2016: **Joint extraction of events and entities within a document context**
    * Authors: Bishan Yang, Tom M. Mitchell
    * url: [https://www.aclweb.org/anthology/N16-1033/](https://www.aclweb.org/anthology/N16-1033/)
    
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
    * code: [https://github.com/yanghang111/DCFEE](https://github.com/yanghang111/DCFEE)
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

* AAAI2019: **One for All: Neural joint modeling of entities and events**
    * Author: Trung Minh Nguyen, Thien Huu Nguyen
    * url: [https://arxiv.org/abs/1812.00195](https://arxiv.org/abs/1812.00195)
    
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
    * code: [https://github.com/dolphin-zs/Doc2EDAG](https://github.com/dolphin-zs/Doc2EDAG)

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
* AAAI2020: **Extracting cybersecurity event information from text**
    * Author: Taneeya Satyapanich, Francis Ferraro, Tim Finin
    * url: [https://ebiquity.umbc.edu/_file_directory_/papers/943.pdf](https://ebiquity.umbc.edu/_file_directory_/papers/943.pdf)
    * code: [https://github.com/Ebiquity/CASIE](https://github.com/Ebiquity/CASIE)

* PAKDD2020: **Exploiting the Matching Information in the Support Set for Few Shot Event Classification**
    * Authors: Viet Lai, Franck Dernoncourt, Thien Huu Nguyen
    * url: [https://arxiv.org/abs/2002.05295](https://arxiv.org/abs/2002.05295)
    * Keywords: FewShot
    
* PAKDD2020: **Learning to Select Important Context Words for Event Detection**
    * Authors: Nghia Trung, NgoTuan Ngo, NguyenThien Huu Nguyen
    * url: [https://pakdd2020.org/download/conference_paper_slides/main-477.pdf](https://pakdd2020.org/download/conference_paper_slides/main-477.pdf)

* WSDM2020: **Meta-Learning with Dynamic-Memory-Based Prototypical Network for Few-Shot Event Detection**
    * Authors: Shumin Deng, Ningyu Zhang, Jiaojian Kang, Yichi Zhang, Wei Zhang, Huajun Chen
    * url: [https://arxiv.org/abs/1910.11621](https://arxiv.org/abs/1910.11621)
    * Code: [https://github.com/231sm/Low_Resource_KBP](https://github.com/231sm/Low_Resource_KBP)

* ACL2020: **Towards Open Domain Event Trigger Identification using Adversarial Domain Adaptation**
    * Authors: Aakanksha Naik, Carolyn Rose
    * url: [https://www.aclweb.org/anthology/2020.acl-main.681/](https://www.aclweb.org/anthology/2020.acl-main.681/)
    
* ACL2020: **Exploring Interpretability in Event Extraction: Multitask Learning of a Neural Event Classifier and an Explanation Decoder**
    * Authors: Zheng Tang, Gus Hahn-Powell, Mihai Surdeanu
    * url: [https://www.aclweb.org/anthology/2020.acl-srw.23/](https://www.aclweb.org/anthology/2020.acl-srw.23/)

* ACL2020: **Cross-media Structured Common Space for Multimedia Event Extraction**
    * Authors: Manling Li, Alireza Zareian, Qi Zeng, Spencer Whitehead, Di Lu, Heng Ji, Shih-Fu Chang
    * url: [https://arxiv.org/abs/2005.02472](https://arxiv.org/abs/2005.02472)

* ACL2020: **Discourse as a Function of Event: Profiling Discourse Structure in News Articles around the Main Event**
    * Authors: Prafulla Kumar Choubey and Aaron Lee and Ruihong Huang and Lu Wang
    * code: [https://github.com/prafulla77/Discourse_Profiling](https://github.com/prafulla77/Discourse_Profiling)

* ACL2020: **Document-Level Event Role Filler Extraction using Multi-Granularity Contextualized Encoding**
    * Authors: Xinya Du, Claire Cardie
    * url: [https://arxiv.org/abs/2005.06579](https://arxiv.org/abs/2005.06579)
    
* ACL2020: **Extensively Matching for Few-shot Learning Event Detection**
    * Authors: Viet Dac Lai, Franck Dernoncourt, Thien Huu Nguyen
    * url: https://www.aclweb.org/anthology/2020.nuse-1.5

* ACL2020: **Improving Event Detection via Open-domain Trigger Knowledge**
    * Authors: Meihan Tong, Bin Xu, Shuai Wang, Yixin Cao, Lei Hou, Juanzi Li and Jun Xie
    * url: [https://www.aclweb.org/anthology/2020.acl-main.522/](https://www.aclweb.org/anthology/2020.acl-main.522/)

* ACL2020: **A Two-Step Approach for Implicit Event Argument Detection**
    * Authors: Zhisong Zhang, Xiang Kong, Zhengzhong Liu, Xuezhe Ma and Eduard Hovy
    * url: [https://www.aclweb.org/anthology/2020.acl-main.667/](https://www.aclweb.org/anthology/2020.acl-main.667/)
    * code: [https://github.com/zzsfornlp/zmsp](https://github.com/zzsfornlp/zmsp)
    
* ACL2020: Multi-Sentence Argument Linking
    * Authors: Seth Ebner, Patrick Xia, Ryan Culkin, Kyle Rawlins, Benjamin Van DurmeA
    * url: [https://www.aclweb.org/anthology/2020.acl-main.718/](https://www.aclweb.org/anthology/2020.acl-main.718/)
    * code: [https://nlp.jhu.edu/rams/](https://nlp.jhu.edu/rams/)

* IJCAI2020: **A Unified Model for Financial Event Classification, Detection and Summarization**
     * Authors: Quanzhi Li, Qiong Zhang
     * url: [https://www.ijcai.org/Proceedings/2020/644](https://www.ijcai.org/Proceedings/2020/644)
     * 

* IJCAI2020: **F-HMTC: Detecting Financial Events for Investment Decisions Based on Neural Hierarchical Multi-Label Text Classification**
    * Authors: Xin Liang, Dawei Cheng, Fangzhou Yang, Yifeng Luo, Weining Qian, Aoying Zhou
    * url: [https://www.ijcai.org/Proceedings/2020/619](https://www.ijcai.org/Proceedings/2020/619)
    * code: [https://github.com/finint/F-HMTC](https://github.com/finint/F-HMTC)
    
* EMNLP2020: **MAVEN: A Massive General Domain Event Detection Dataset**
    * Authors: Xiaozhi Wang, Ziqi Wang, Xu Han, Wangyi Jiang, Rong Han, Zhiyuan Liu, Juanzi Li, Peng Li, Yankai Lin, Jie Zhou
    * url: [https://arxiv.org/abs/2004.13590]https://arxiv.org/abs/2004.13590
    * code: [https://github.com/THU-KEG/MAVEN-dataset](https://github.com/THU-KEG/MAVEN-dataset)

* EMNLP2020: **EMNLP2020 Joint Constrained Learning for Event-Event Relation Extraction**
    * Authors: Haoyu Wang, Muhao Chen, Hongming Zhang, Dan Roth
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.51.pdf](https://www.aclweb.org/anthology/2020.emnlp-main.51.pdf)
    * code: [https://github.com/CogComp/JointConstrainedLearning](https://github.com/CogComp/JointConstrainedLearning)

* EMNLP2020: **Analogous Process Structure Induction for Sub-event Sequence Prediction**
    * Authors: Hongming Zhang, Muhao Chen, Haoyu Wang, Yangqiu Song, Dan Roth
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.119/](https://www.aclweb.org/anthology/2020.emnlp-main.119/)
    
* EMNLP2020: **A Method for Building a Commonsense Inference Dataset based on Basic Events**
    * Authors: Kazumasa Omura, Daisuke Kawahara and Sadao Kurohashi
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.192](https://www.aclweb.org/anthology/2020.emnlp-main.192)

* EMNLP2020: **Affective Event Classification with Discourse-enhanced Self-training**
    * Authors: Yuan Zhuang, Tianyu Jiang and Ellen Riloff
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.452](https://www.aclweb.org/anthology/2020.emnlp-main.452)

* EMNLP2020: **Connecting the Dots: Event Graph Schema Induction with Path Language Modeling**
    * Authors: Manling Li, Qi Zeng, Ying Lin, Kyunghyun Cho, Heng Ji, Jonathan May, Nathanael Chambers and Clare Voss
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.50/](https://www.aclweb.org/anthology/2020.emnlp-main.50/)
    * code: [http://blender.cs.illinois.edu/software/pathlm/](http://blender.cs.illinois.edu/software/pathlm/)

* EMNLP2020: **Domain Knowledge Empowered Structured Neural Net for End-to-End Event Temporal Relation Extraction**
    * Authors: Rujun Han, Yichao Zhou and Nanyun Peng
    * url: [https://arxiv.org/abs/2009.07373](https://arxiv.org/abs/2009.07373)

* EMNLP2020: **Event Extraction as Machine Reading Comprehension**
    * Authors: Jian Liu, Yubo Chen, Kang Liu, Wei Bi and Xiaojiang Liu
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.128/](https://www.aclweb.org/anthology/2020.emnlp-main.128/)
    * code: [https://github.com/jianliu-ml/EEasMRC](https://github.com/jianliu-ml/EEasMRC)

* EMNLP2020: **Event Extraction by Answering (Almost) Natural Questions**
    * Authors: Xinya Du and Claire Cardie
    * url: [https://arxiv.org/abs/2004.13625](https://arxiv.org/abs/2004.13625)
    * code: [https://github.com/xinyadu/eeqa](https://github.com/xinyadu/eeqa)

* EMNLP2020: **Incremental Event Detection via Knowledge Consolidation Networks**
    * Authors: Pengfei Cao, Yubo Chen, Jun Zhao and Taifeng Wang
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.52](https://www.aclweb.org/anthology/2020.emnlp-main.52)
    * code: [https://github.com/CPF-NLPR/IncrementalED](https://github.com/CPF-NLPR/IncrementalED)

* EMNLP2020: **Weakly Supervised Subevent Knowledge Acquisition**
    * Authors: Wenlin Yao, Zeyu Dai, Maitreyi Ramaswamy, Bonan Min and Ruihong Huang
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.430](https://www.aclweb.org/anthology/2020.emnlp-main.430.pdf)
    * code: [https://github.com/wenlinyao/EMNLP20-SubeventAcquisition](https://github.com/wenlinyao/EMNLP20-SubeventAcquisition)

* EMNLP2020: **Event Detection: Gate Diversity and Syntactic Importance Scores for Graph Convolution Neural Networks**
    * Authors: Viet Dac Lai, Tuan Ngo Nguyen and Thien Huu Nguyen
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.435](https://www.aclweb.org/anthology/2020.emnlp-main.435)

* EMNLP2020: **Introducing a New Dataset for Event Detection in Cybersecurity Texts**
    * Authors: Hieu Man Duc Trong, Duc Trong Le, Amir Pouran Ben Veyseh, Thuat Nguyen and Thien Huu Nguyen
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.433](https://www.aclweb.org/anthology/2020.emnlp-main.433)

* EMNLP2020: **Semi-supervised New Event Type Induction and Event Detection**
    * Authors: Lifu Huang and Heng Ji
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.53](https://www.aclweb.org/anthology/2020.emnlp-main.53)
    * code: [https://github.com/wilburOne/SSVQVAE](https://github.com/wilburOne/SSVQVAE)

* EMNLP2020: **Severing the Edge Between Before and After: Neural Architectures for Temporal Ordering of Events**
    * Authors: Miguel Ballesteros, Rishita Anubhai, Shuai Wang, Nima Pourdamghani, Yogarshi Vyas, Jie Ma, Parminder Bhatia, Kathleen McKeown and Yaser Al-Onaizan
    * url: [https://www.aclweb.org/anthology/2020.emnlp-main.436](https://www.aclweb.org/anthology/2020.emnlp-main.436.pdf)
   
* EMNLP2020-Findings: **Edge-Enhanced Graph Convolution Networks for Event Detection with Syntactic Relation**
    * Authors: Shiyao Cui, Bowen Yu, Tingwen Liu, Zhenyu Zhang, Xuebin Wang and Jinqiao Shi
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.211](https://www.aclweb.org/anthology/2020.findings-emnlp.211.pdf)
    * code: [https://github.com/cuishiyao96/eegcned](https://github.com/cuishiyao96/eegcned)

* EMNLP2020-Findings: **Event Extraction as Multi-turn Question Answering**
    * Authors: Fayuan Li, Weihua Peng, Yuguang Chen, Quan Wang, Lu Pan, Yajuan Lyu and Yong Zhu
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.73/](https://www.aclweb.org/anthology/2020.findings-emnlp.73/)

* EMNLP2020-Findings: **How Does Context Matter? On the Robustness of Event Detection with Context-Selective Mask Generalization**
    * Authors: Jian Liu, Yubo Chen, Kang Liu, Yantao Jia and Zhicheng Sheng
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.229](https://www.aclweb.org/anthology/2020.findings-emnlp.229)

* EMNLP2020-Findings: **Graph Transformer Networks with Syntactic and Semantic Structures for Event Argument Extraction**
    * Authors: Amir Pouran Ben Veyseh, Tuan Ngo Nguyen and Thien Huu Nguyen
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.326](https://www.aclweb.org/anthology/2020.findings-emnlp.326)

* EMNLP2020-Findings: **Biomedical Event Extraction on Graph Edge-conditioned Attention Networks with Hierarchical Knowledge Graphs**
    * Authors: Kung-Hsiang Huang, Mu Yang and Nanyun Peng
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.114](https://www.aclweb.org/anthology/2020.findings-emnlp.114)
    * code: [https://github.com/PlusLabNLP/GEANet-BioMed-Event-Extraction](https://github.com/PlusLabNLP/GEANet-BioMed-Event-Extraction)

* EMNLP2020-Findings: **Resource-Enhanced Neural Model for Event Argument Extraction**
    * Authors: Jie Ma, Shuai Wang, Rishita Anubhai, Miguel Ballesteros and Yaser Al-Onaizan
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.318](https://www.aclweb.org/anthology/2020.findings-emnlp.318)

* EMNLP2020-Findings: **Learning to Classify Human Needs of Events from Category Definitions with Prototypical Instantiation**
    * Authors: Haibo Ding and Zhe Feng
    * url: [https://www.aclweb.org/anthology/2020.findings-emnlp.421](https://www.aclweb.org/anthology/2020.findings-emnlp.421)
    
* COLING2020: Hierarchical Chinese Legal event extraction via Pedal Attention Mechanism
    * Authors: Shirong Shen, Guilin Qi, Zhen Li, Sheng Bi, Lusheng Wang
    * url: [https://www.aclweb.org/anthology/2020.coling-main.9](https://www.aclweb.org/anthology/2020.coling-main.9)
    
* COLING2020: Is Killed More Significant than Fled? A Contextual Model for Salient Event Detection
    * Authors: Disha Jindal, Daniel Deutsch, Dan Roth
    * url: [https://www.aclweb.org/anthology/2020.coling-main.10/](https://www.aclweb.org/anthology/2020.coling-main.10/)
    * code: [https://github.com/CogComp/Salient-Event-Detection](https://github.com/CogComp/Salient-Event-Detection)
    
* COLING2020: Joint Event Extraction with Hierarchical Policy Network
    * Authors: Peixin Huang, Xiang Zhao, Ryuichi Takanobu, Zhen Tan, Weidong Xiao
    * url: [https://www.aclweb.org/anthology/2020.coling-main.239/](https://www.aclweb.org/anthology/2020.coling-main.239/)
    
* COLING2020: Modeling Event Salience in Narratives via Barthes’ Cardinal Functions
    * Authors: Takaki Otake, Sho Yokoi, Naoya Inoue, Ryo Takahashi, Tatsuki Kuribayashi, Kentaro Inui
    * url: [https://www.aclweb.org/anthology/2020.coling-main.160/](https://www.aclweb.org/anthology/2020.coling-main.160/)
    
* COLING2020: New Benchmark Corpus and Models for Fine-grained Event Classification: To BERT or not to BERT?
    * Authors: Jakub Piskorski, Jacek Haneczok, Guillaume Jacquet
    * url: [https://www.aclweb.org/anthology/2020.coling-main.584/](https://www.aclweb.org/anthology/2020.coling-main.584/)

* CCL2020: **A Novel Joint Framework for Multiple Chinese Events Extraction**
    * Author: Nuo xu, Haihua Xie and Dongyan Zhao
    * url: [https://www.aclweb.org/anthology/2020.ccl-1.88/](https://www.aclweb.org/anthology/2020.ccl-1.88/)

* arxiv2020: **Label Enhanced Event Detection with Heterogeneous Graph Attention Networks**
    * Authors: Shiyao Cui, Bowen Yu, Xin Cong, Tingwen Liu, Quangang Li, Jinqiao Shi
    * url: [https://arxiv.org/abs/2012.01878](https://arxiv.org/abs/2012.01878)

* arxiv2020: **Few-Shot Event Detection with Prototypical Amortized Conditional Random Field**
    * Authors: Xin Cong, Shiyao Cui, Bowen Yu, Tingwen Liu, Yubin Wang, Bin Wang
    * url: [https://arxiv.org/abs/2012.02353](https://arxiv.org/abs/2012.02353)

* arXiv2020: **Event Arguments Extraction via Dilate Gated Convolutional Neural Network with Enhanced Local Features**
    * Authors: Zhigang Kan, Linbo Qiao, Sen Yang, Feng Liu, Feng Huang
    * url: [https://arxiv.org/abs/2006.01854](https://arxiv.org/abs/2006.01854)
    
* arxiv2020: **Open-domain Event Extraction and Embedding for Natural Gas Market Prediction**
    * Authors: Chau, Minh Triet and Esteves, Diego and Lehmann, Jens
    * url: [https://arxiv.org/abs/1912.11334](https://arxiv.org/abs/1912.11334)

* arxiv2020: **Event Extraction as Definitation Comprehension**
    * Authors: Yunmo Chen, Tongfei Chen, Seth Ebner, Benjamin Van Durme
    * url: [https://arxiv.org/abs/1912.01586](https://arxiv.org/abs/1912.01586)
   
* arxiv2020: **Extracting COVID-19 Events from Twitter**
    * Authors: Shi Zong, Ashutosh Baheti, Wei Xu, Alan Ritter
    * url: [https://arxiv.org/abs/2006.02567](https://arxiv.org/abs/2006.02567)
    
* arxiv2020: **Improving Event Detection using Contextual Wrod and Sensence embeddings**
    * Authors: Mariano Maisonnave, Fernando Delbianco, Fernando Tohmé, Ana Maguitman, Evangelos Milios
    * url: [https://arxiv.org/abs/2007.01379](https://arxiv.org/abs/2007.01379)    
   
* arxiv2020: **Document-level Event-based Extraction Using Generative Template-filling Transformers**
    * Authors: Xinya Du, Alexander Rush, Claire Cardie
    * url: [https://arxiv.org/abs/2008.09249](https://arxiv.org/abs/2008.09249)
    
* arxiv: **Efficient End-to-end Learning of Cross-event Dependencies for Document-level Event Extraction**
    * Authors: Kung-Hsiang Huang, Nanyun Peng
    * url: [https://arxiv.org/abs/2010.12787](https://arxiv.org/abs/2010.12787)
    
* arxiv2020: **GATE Graph Attention Transformer Encoder for Cross-lingual Relation and Event Extraction**
    * Authors: Wasi Uddin Ahmad, Nanyun Peng, Kai-Wei Chang
    * url: [https://arxiv.org/abs/2010.03009](https://arxiv.org/abs/2010.03009)

* arxiv2020: **Improving Event Detection using Contextual Wrod and Sensence embeddings**
    * Authors: Mariano Maisonnave, Fernando Delbianco, Fernando Tohmé, Ana Maguitman, Evangelos Milios
    * url: [https://arxiv.org/abs/2007.01379](https://arxiv.org/abs/2007.01379)
    
* arxiv2020: **Temporal Random Indexing of Context Vectors Applied to Event Detection**
    * Authors: Yashank Singh, Niladri Chatterjee
    * url: [https://arxiv.org/abs/2008.12552](https://arxiv.org/abs/2008.12552)
    
* arxiv2020: **BERTering RAMS What and How Much does BERT Already Know About Event Arguments A Study on the RAMS Dataset**
    * Authors: Varun Gangal, Eduard Hovy
    * url: [https://arxiv.org/abs/2010.04098](https://arxiv.org/abs/2010.04098)

* arxiv2020: **End-to-End Neural Event Coreference Resolution**
    * Authors: Yaojie Lu, Hongyu Lin, Jialong Tang, Xianpei Han, Le Sun
    * url: [https://arxiv.org/abs/2009.08153](https://arxiv.org/abs/2009.08153)


## 2021

* AAAI2021: **What the Role Is vs. What Plays the Role: Semi-Supervised Event Argument Extraction via Dual Question Answering**
    * Authors: Yang Zhou, Yubo Chen , Jun Zhao, Yin Wu, Jiexin Xu and Jinlong Li
    * url: [https://www.aaai.org/AAAI21Papers/AAAI-2635.ZhouY.pdf](https://www.aaai.org/AAAI21Papers/AAAI-2635.ZhouY.pdf)

* AAAI2021: **Span-Based Event Coreference Resolution**
    * Authors: Jing Lu and Vincent Ng
    * url: [https://www.aaai.org/AAAI21Papers/AAAI-9086.LJ.pdf](https://www.aaai.org/AAAI21Papers/AAAI-9086.LJ.pdf)

* AAAI2021: **GATE: Graph Attention Transformer Encoder for Cross-Lingual Relationand Event Extraction**
    * Authors: Wasi Uddin Ahmad, Nanyun Peng, Kai-Wei Chang
    * url: [https://arxiv.org/abs/2010.03009](https://arxiv.org/abs/2010.03009)

* WWW2021: **Taxonomy-aware Learning for Few-shot Event Detection**
    * Authors: Jianming Zheng, Wanyu Chen, Wengqiang Lei and Honghui Chen

* WWW2021: **Knowledge-Preserving Incremental Social Event Detection via Heterogeneous GNN**
    * Authors: Yuwei Cao, Hao Peng, Jia Wu, Yingtong Dou, Jianxin Li, Philip S. Yu
    * url: [https://www.researchgate.net/publication/348675695_Knowledge-Preserving_Incremental_Social_Event_Detection_via_Heterogeneous_GNNs](https://www.researchgate.net/publication/348675695_Knowledge-Preserving_Incremental_Social_Event_Detection_via_Heterogeneous_GNNs)

* WWW2021: **Multi-level Connection Enhanced Representation Learning for Script Event Prediction**
    * Authors: Lihong Wang, Juwei Yue, Shu Guo, Jiawei Sheng, Qianren Mao, Zhenyu Chen, Shenghai Zhong and Chen Li

* WWW2021: **Learning Neural Point Processes with Latent Graphs**
    * Authors: Qiang Zhang, Aldo Lipani and Emine Yilmaz
    * url: [https://www.researchgate.net/publication/349380768_Learning_Neural_Point_Processes_with_Latent_Graphs](https://www.researchgate.net/publication/349380768_Learning_Neural_Point_Processes_with_Latent_Graphs)]
