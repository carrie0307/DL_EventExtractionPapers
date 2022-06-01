Based on [BaptisteBlouin](https://github.com/BaptisteBlouin/EventExtractionPapers), I review papers about **Deep Learning based Event Extraction**, and annotate **keywords and Abbreviation of Models**. Besides, I categorized the papers as **Chinese Event Extraction, Open-domain Event Extraction, Event Data Generation, Cross-lingual Event Extraction, Few-Shot Event Extraction and Zero-Shot Event Extraction**, **Document-level EE**. 

Omissions and mistakes may exist in the review. Welcome to exchange and opinions!


* [Doc-Level EE](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Doc-EE.md)
* [Few-Shot and Zero Shot](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Few-Shot%20Zero-Shot%20EE.md)
* [Resolution](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Resolution.md)
* [Event Relateion EXtraction](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Event%20Relation%20Extraction.md)
* [Script Event Prediction](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Script%20Event%20Prediction.md)
* [Domain Adaption](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Domain%20Adaption.md)
* [Open-Domain EE](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Open%20Domain%20EE.md)
* [Joint Models about EE](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Joint%20Models%20about%20EE.md)
* [Multi-Lingual](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Multi%20Lingual%20EE.md)
* [Semi-supervised](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Semi-Supervised%20Weakly-Supervised%20EE.md)
* [New Dataset](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Dataset.md)
* [Data Generation](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Data%20Generation.md)
* [Chinese Event Extraction](https://github.com/carrie0307/DL_EventExtractionPapers/blob/master/Category/Chinese%20EE.md)


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

* IJCAI2020: **IJCAI2020 Knowledge Enhanced Event Causality Identification with Mention Masking Generalizations**
    * Authors: Jian Liu, Yubo Chen, Jun Zhao
    * url: [https://www.ijcai.org/Proceedings/2020/499](https://www.ijcai.org/Proceedings/2020/499)
    
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

* COLING2020: **KnowDis: Knowledge Enhanced Data Augmentation for Event Causality Detection via Distant Supervision**
    * Authors: Xinyu Zuo, Yubo Chen, Kang Liu, Jun Zhao
    * url: [https://www.aclweb.org/anthology/2020.coling-main.135/](https://www.aclweb.org/anthology/2020.coling-main.135/)

* COLING2020: Integrating External Event Knowledge for Script Learning
    * Authors: Shangwen Lv, Fuqing Zhu, Songlin Hu
    * url: [https://www.aclweb.org/anthology/2020.coling-main.27/]

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
    * url: [https://www2021.thewebconf.org/papers/taxonomy-aware-learning-for-few-shot-event-detection/](https://www2021.thewebconf.org/papers/taxonomy-aware-learning-for-few-shot-event-detection/)

* WWW2021: **Knowledge-Preserving Incremental Social Event Detection via Heterogeneous GNN**
    * Authors: Yuwei Cao, Hao Peng, Jia Wu, Yingtong Dou, Jianxin Li, Philip S. Yu
    * url: [https://www.researchgate.net/publication/348675695_Knowledge-Preserving_Incremental_Social_Event_Detection_via_Heterogeneous_GNNs](https://www.researchgate.net/publication/348675695_Knowledge-Preserving_Incremental_Social_Event_Detection_via_Heterogeneous_GNNs)

* WWW2021: **Multi-level Connection Enhanced Representation Learning for Script Event Prediction**
    * Authors: Lihong Wang, Juwei Yue, Shu Guo, Jiawei Sheng, Qianren Mao, Zhenyu Chen, Shenghai Zhong and Chen Li
    * Url: [https://www2021.thewebconf.org/papers/multi-level-connection-enhanced-representation-learning-for-script-event-prediction/](https://www2021.thewebconf.org/papers/multi-level-connection-enhanced-representation-learning-for-script-event-prediction/)

* IJCAI2021: **Discourse-Level Event Temporal Ordering with Uncertainty-Guided Graph Completion**
    * Authors: Jian Liu, Jinan Xu, Yufeng Chen, Yujie Zhang


* ACL2021: **Unleash GPT-2 Power for Event Detection**
    * Authors: Amir Pouran Ben Veyseh, Viet Lai, Franck Dernoncourt and Thien Huu Nguyen

* ACL2021: **OntoED: Low-resource Event Detection with Ontology Embedding**
    * Authors: Shumin Deng, Ningyu Zhang, Luoqiu Li, Chen Hui, Tou Huaixiao, Mosha Chen, Fei Huang and Huajun Chen
    * url: [https://arxiv.org/abs/2105.10922](https://arxiv.org/abs/2105.10922)

* ACL2021-Findings: **Few-Shot Event Detection with Prototypical Amortized Conditional Random Field**
    * Authors: Xin Cong, Shiyao Cui, Bowen Yu, Tingwen Liu, Wang Yubin and Bin Wang
    * url: [https://arxiv.org/abs/2012.02353](https://arxiv.org/abs/2012.02353)

* ACL2021: **Zero-shot Event Extraction via Transfer Learning: Challenges and Insights**
    * Authors: Qing Lyu, Hongming Zhang, Elior Sulem and Dan Roth


* ACL2021: **Text2Event: Controllable Sequence-to-Structure Generation for End-to-end Event Extraction**
    * Authors: Yaojie Lu, Hongyu Lin, Jin Xu, Xianpei Han, Jialong Tang, Annan Li, Le Sun, Meng Liao and Shaoyi Chen

* ACL2021: **CLEVE: Contrastive Pre-training for Event Extraction**
    * Authors: Ziqi Wang, Xiaozhi Wang, Xu Han, Yankai Lin, Lei Hou, Zhiyuan Liu, Peng Li, Juanzi Li and Jie Zhou

* ACL2021-Findings: **CasEE: A Joint Learning Framework with Cascade Decoding for Overlapping Event Extraction**
    * Authors: Jiawei Sheng, Shu Guo, Bowen Yu, Qian Li, Yiming Hei, Lihong Wang, Tingwen Liu and Hongbo Xu

* ACL2021: **Capturing Event Argument Interaction via A Bi-Directional Entity-Level Recurrent Decoder**
    * Authors: Xi Xiangyu, Wei Ye, Shikun Zhang, Quanxiu Wang, Huixing Jiang and Wei Wu

* ACL2021: **Trigger is Not Sufficient: Exploiting Frame-aware Knowledge for Implicit Event Argument Extractio**
    * Authors: Kaiwen Wei, Xian Sun, Zequn Zhang, Jingyuan Zhang, Guo Zhi and Li Jin


* ACL2021: **Document-level Event Extraction via Heterogeneous Graph-based Interaction Model with a Tracker**
    * Authors: Runxin Xu, Tianyu Liu, Lei Li and Baobao Chang

* ACL2021: **Document-level Event Extraction via Parallel Prediction Networks**
    * Authors: Hang Yang, Dianbo Sui, Yubo Chen, Kang Liu, Jun Zhao and Taifeng Wang

* ACL2021: **Document-Level Event Argument Extraction via Optimal Transport**
    * Authors: Amir Pouran Ben Veyseh, Minh Van Nguyen, Franck Dernoncourt, Bonan Min and Thien Huu Nguyen

* ACL2021: **MLBiNet: A Cross-Sentence Collective Event Detection Network**
    * Authors: Dongfang Lou, Zhilin Liao, Shumin Deng, Ningyu Zhang and Huajun Chen

* ACL2021: **Knowledge-Enriched Event Causality Identification via Latent Structure Induction Networks**
    * Authors: Pengfei Cao, Xinyu Zuo, Yubo Chen, Kang Liu, Jun Zhao, Yuguang Chen and Weihua Peng

* ACL2021: **LearnDA: Learnable Knowledge-Guided Data Augmentation for Event Causality Identification**
    * Authors: Xinyu Zuo, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao, Weihua Peng and Yuguang Chen

* ACL2021: **From Discourse to Narrative: Knowledge Projection for Event Relation Extraction**
    * Authors: Jialong Tang, Hongyu Lin, Meng Liao, Yaojie Lu, Xianpei Han, Le Sun, Weijian Xie and Jin Xu


* ACL2021: **Exploiting Document Structures and Cluster Consistencies for Event Coreference Resolution**
    * Authors: Hieu Minh Tran, Duy Phung and Thien Huu Nguyen

* ACL2021: **Don’t Let Discourse Confine Your Model: Sequence Perturbations for Improved Event Language Models**
    * Authors: Mahnaz Koupaee, Greg Durrett, Nathanael Chambers and Niranjan Balasubramanian

* ACL2021: **Conditional Generation of Temporally-ordered Event Sequences**
    * Authors: Shih-Ting Lin, Nathanael Chambers and Greg Durrett

* ACL2021: **ForecastQA: A Question Answering Challenge for Event Forecasting with Temporal Text Data**
    * Authors: Woojeong Jin, Rahul Khanna, Suji Kim, Dong-Ho Lee, Fred Morstatter, Aram Galstyan and Xiang Ren

* ACL2021: **Event Graph Knowledge Enhanced Explainable Causal Reasoning**
    * Authors: Li Du, Xiao Ding, Kai Xiong, Ting Liu and Bing Qin


* ACL2021: **Learning Event Graph Knowledge for Abductive Reasoning**
    * Authors: Li Du, Xiao Ding, Ting Liu and Bing Qin

* ACL2021: **The Possible, the Plausible, and the Desirable: Event-Based Modality Detection for Language Processing**
    * Authors: Valentina Pyatkin, Shoval Sadde, Aynat Rubinstein, Paul Portner and Reut Tsarfaty

* ACL2021-Findings: **Revisiting the Evaluation of End-to-end Event Extraction**
    * Authors: Shun Zheng, Wei Cao, Wei Xu, Jiang Bian
    * url: [https://aclanthology.org/2021.findings-acl.405.pdf](https://aclanthology.org/2021.findings-acl.405.pdf)

* EACL2021: **Adapting Event Extractors to Medical Data Bridging the Covariate Shift**
    * Authors: Aakanksha Naik, Jill Fain Lehman, Carolyn Rose
    * url: [https://www.aclweb.org/anthology/2021.eacl-main.258/](https://www.aclweb.org/anthology/2021.eacl-main.258/)

* EACL2021: **Fine-Grained Event Trigger Detection**
    * Authors: Duong Le, Thien Huu Nguyen
    * url: [https://www.aclweb.org/anthology/2021.eacl-main.237/](https://www.aclweb.org/anthology/2021.eacl-main.237/)

* EACL2021: **EACL2021 Probing into the Root A Dataset for Reason Extraction of Structural Events from Financial Documents**
    * Authors: Pei Chen, Kang Liu, Yubo Chen, Taifeng Wang, Jun Zhao
    * url: [https://www.aclweb.org/anthology/2021.eacl-main.175/](https://www.aclweb.org/anthology/2021.eacl-main.175/)

* Extracting Events and Their Relations from Texts A Survey on RecentResearch Progress and Challenges
    * Authors: KangLiu, YuboChen, JianLiu, XinyuZuo, JunZhaoa
    * url: [https://www.sciencedirect.com/science/article/pii/S266665102100005X](https://www.sciencedirect.com/science/article/pii/S266665102100005X)

* NAACL2021: **A Context-Dependent Gated Module for Incorporating Symbolic Semantics into Event Coreference Resolution**
    * Authors: Tuan Lai, Heng Ji, Trung Bui, Quan Hung Tran, Franck Dernoncourt, Walter Chang
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.274/](https://www.aclweb.org/anthology/2021.naacl-main.274/)

* NAACL2021: **Constrained Multi-Task Learning for Event Coreference Resolution**
    * Authors: Jing Lu, Vincent Ng
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.356/](https://www.aclweb.org/anthology/2021.naacl-main.356/)

* NAACL2021: **Document-Level Event Argument Extraction by Conditional Generation**
    * Authors: Sha Li, Heng Ji, Jiawei Han
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.69/](https://www.aclweb.org/anthology/2021.naacl-main.69/)

* NAACL2021: **Document-level Event Extraction with Efficient End-to-end Learning of Cross-Event Dependencies**
    * Authors: Kung-Hsiang Huang, Nanyun Peng
    * url: [https://www.aclweb.org/anthology/2021.nuse-1.4/](https://www.aclweb.org/anthology/2021.nuse-1.4/)

* NAACL2021: **Event Time Extraction and Propagation via Graph Attention Networks**
    * Authors: Haoyang Wen, Yanru Qu, Heng Ji, Qiang Ning, Jiawei Han, Avi Sil, Hanghang Tong, Dan Roth
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.6/](https://www.aclweb.org/anthology/2021.naacl-main.6/)

* NAACL2021: **Graph Convolutional Networks for Event Causality Identification with Rich Document-level Structures**
    * Authors: Minh Tran Phu, Thien Huu Nguyen
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.273/](https://www.aclweb.org/anthology/2021.naacl-main.273/)

* NAACL2021: **Modeling Event Plausibility with Consistent Conceptual Abstraction**
    * Authors: Ian Porada, Kaheer Suleman, Adam Trischler, Jackie Chi Kit Cheung
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.138/](https://www.aclweb.org/anthology/2021.naacl-main.138/)

* NAACL2021: **Temporal Reasoning on Implicit Events from Distant Supervision**
    * Authors: Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, Dan Roth
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.107/](https://www.aclweb.org/anthology/2021.naacl-main.107/)

* NAACL2021: **Time-Stamped Language Model Teaching Language Models to Understand the Flow of Events**
    * Authors: Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, Dan Roth
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.107/](https://www.aclweb.org/anthology/2021.naacl-main.107/)

* NAACL2021: **WEC Deriving a Large-scale Cross-document Event Coreference dataset from Wikipedia**
    * Authors: Alon Eirew, Arie Cattan, Ido Dagan
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.198/](https://www.aclweb.org/anthology/2021.naacl-main.198/)

* NAACL2021: Template Filling with Generative Transformers
    * Authors: Xinya Du, Alexander Rush, Claire Cardie
    * url: [https://aclanthology.org/2021.naacl-main.70/](https://aclanthology.org/2021.naacl-main.70/)

* CCL2021: **Towards Causal Explanation Detection with Pyramid Salient-Aware Network**
    * Authors: Xinyu Zuo, Yubo Chen, Kang Liu, Jun Zhao
    * url: [https://www.aclweb.org/anthology/2020.ccl-1.84/](https://www.aclweb.org/anthology/2020.ccl-1.84/)

* Information Sciences2021 **Document-level event causality identification via graph inference mechanism**
    * Authors: KunZhao, DonghongJi, FazhiHe, YijiangLiu, YafengRen
    * url: [https://www.sciencedirect.com/science/article/abs/pii/S002002552100116X](https://www.sciencedirect.com/science/article/abs/pii/S002002552100116X)

* CIKM2021: **Behind the Scenes: An Exploration of Trigger Biases Problem in Few-Shot Event Classification**
    * Authors: Peiyi Wang, Runxin Xu, Tianyu Liu, Damai Dai, Baobao Chang, Zhifang Sui 
    * url: [https://dl.acm.org/doi/10.1145/3459637.3482236](https://dl.acm.org/doi/10.1145/3459637.3482236)

* CIKM2021: **Understanding Event Predictions via Contextualized Multilevel Feature Learning**
    * Authors: Songgaojun Deng, Huzefa Rangwala, Yue Ning
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482309](https://dl.acm.org/doi/pdf/10.1145/3459637.3482309)

* CIKM2021: **Detection of Illicit Drug Trafficking Events on Instagram: A Deep Multimodal Multilabel Learning Approach**
    * Authors: Chuanbo Hu, Minglei Yin, Bin Liu, Xin Li, Yanfang Ye
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3481908](https://dl.acm.org/doi/pdf/10.1145/3459637.3481908)

* CIKM2021: **Uncertainty-Aware Self-Training for Semi-Supervised Event Temporal Relation Extraction**
    * Authors: Pengfei Cao, Xinyu Zuo, Yubo Chen, Kang Liu, Jun Zhao, Wei Bi
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482207](https://dl.acm.org/doi/pdf/10.1145/3459637.3482207)

* CIKM2021: **EasyFlinkCEP: Big Event Data Analytics for Everyone**
    * Authors:  Nikos Giatrakos, Eleni Kougioumtzi, Antonios Kontaxakis, Antonios Deligiannakis, Yannis Kotidis
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482094](https://dl.acm.org/doi/pdf/10.1145/3459637.3482094)


* CIKM2021: **Multi-Sentence Argument Linking via An Event-Aware Hierarchical Encoder**
    * Authors: Hang Yang, Yubo Chen, Kang Liu, Jun Zhao, Taifeng Wang
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482148](https://dl.acm.org/doi/pdf/10.1145/3459637.3482148)

* CIKM2021: **Multi-Task Self-Supervised Learning for Script Event Prediction**
    * Authors: Bo Zhou, Yubo Chen, Kang Liu, Jun Zhao, Jiexin Xu, Xiaojian Jiang
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482150](https://dl.acm.org/doi/pdf/10.1145/3459637.3482150)

* CIKM2021: **SeDyT: A General Framework for Multi-Step Event Forecasting via Sequence Modeling on Dynamic Entity Embeddings**
   * Authors: Hongkuan Zhou, James Orme-Rogers, Rajgopal Kannan, Viktor Prasanna
   * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482177](https://dl.acm.org/doi/pdf/10.1145/3459637.3482177)

* CIKM2021: **VidLife: A Dataset for Life Event Extraction from Videos**
    * Authors: VidLife: A Dataset for Life Event Extraction from Videos
    * url: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482022](https://dl.acm.org/doi/pdf/10.1145/3459637.3482022)

* EMNLP2021: **Enhanced Language Representation with Label Knowledge for Span Extraction**
   * Authors: Pan Yang, Xin Cong, Zhenyun Sun, Xingwu Liu
   * url: [https://aclanthology.org/2021.emnlp-main.379](https://aclanthology.org/2021.emnlp-main.379)

* EMNLP2021: **Integrating Deep Event-Level and Script-Level Information for Script Event Prediction**
    * Authors: Long Bai, Saiping Guan, Jiafeng Guo, Zixuan Li, Xiaolong Jin, Xueqi Cheng
    * url: [https://aclanthology.org/2021.emnlp-main.776.pdf](https://aclanthology.org/2021.emnlp-main.776.pdf)


* EMNLP2021: **Salience-Aware Event Chain Modeling for Narrative Understanding**
    * Authors: Xiyang Zhang, Muhao Chen, Jonathan May
    * url: [https://aclanthology.org/2021.emnlp-main.107.pdf](https://aclanthology.org/2021.emnlp-main.107.pdf)

* EMNLP2021: **Incorporating Circumstances into Narrative Event Prediction**
    * Authors: Shichao Wang, Xiangrui Cai, HongBin Wang, Xiaojie Yuan
    * url: [https://aclanthology.org/2021.findings-emnlp.416.pdf](https://aclanthology.org/2021.findings-emnlp.416.pdf)


* EMNLP2021: **Treasures Outside Contexts: Improving Event Detection via Global Statistics**
    * Authors: Rui Li, Wenlin Zhao, Cheng Yang, Sen Su
    * url: [https://aclanthology.org/2021.emnlp-main.206.pdf](https://aclanthology.org/2021.emnlp-main.206.pdf)

* EMNLP2021: **Lifelong Event Detection with Knowledge Transfer**
    * Authors: Pengfei Yu, Heng Ji, Prem Natarajan
    * url: [https://aclanthology.org/2021.emnlp-main.428.pdf](https://aclanthology.org/2021.emnlp-main.428.pdf)

* EMNLP2021: **Modeling Document-Level Context for Event Detection via Important Context Selection**
    * Authors: Amir Pouran Ben Veyseh, Minh Van Nguyen, Nghia Ngo Trung, Bonan Min, Thien Huu Nguyen
    * url: [https://aclanthology.org/2021.emnlp-main.439.pdf](https://aclanthology.org/2021.emnlp-main.439.pdf)

* EMNLP2021: **Honey or Poison? Solving the Trigger Curse in Few-shot Event Detection via Causal Intervention**
    * Authors: Jiawei Chen, Hongyu Lin, Xianpei Han, Le Sun
    * url: [https://aclanthology.org/2021.emnlp-main.637.pdf](https://aclanthology.org/2021.emnlp-main.637.pdf)

* EMNLP2021: **Learning Prototype Representations Across Few-Shot Tasks for Event Detection**
    * Authors: Viet Lai, Franck Dernoncourt, Thien Huu Nguyen
    * url: [https://aclanthology.org/2021.emnlp-main.427.pdf](https://aclanthology.org/2021.emnlp-main.427.pdf)

* EMNLP2021: **Self-Attention Graph Residual Convolutional Networks for Event Detection with dependency relations**
    * Authors: Anan Liu, Ning Xu, Haozhe Liu
    * url: [https://aclanthology.org/2021.findings-emnlp.28.pdf](https://aclanthology.org/2021.findings-emnlp.28.pdf)


* EMNLP2021: **Crosslingual Transfer Learning for Relation and Event Extraction via Word Category and Class Alignments**
    * Authors: Van Nguyen, Tuan Ngo Nguyen, Bonan Min, Thien Huu Nguyen
    * url: [https://aclanthology.org/2021.emnlp-main.440.pdf](https://aclanthology.org/2021.emnlp-main.440.pdf)

* EMNLP2021: **Machine Reading Comprehension as Data Augmentation: A Case Study on Implicit Event Argument Extraction**
    * Authors: Jian Liu, Yufeng Chen, Jinan Xu
    * url: [https://aclanthology.org/2021.emnlp-main.214.pdf](https://aclanthology.org/2021.emnlp-main.214.pdf)

* EMNLP2021: **ExcavatorCovid: Extracting Events and Relations from Text Corpora for Temporal and Causal Analysis for COVID-19**
    * Authors: Bonan Min, Benjamin Rozonoyer, Haoling Qiu, Alexander Zamanian, Nianwen Xue, Jessica MacBride
    * url: [https://aclanthology.org/2021.emnlp-demo.8.pdf](https://aclanthology.org/2021.emnlp-demo.8.pdf)

* EMNLP2021: **Joint Multimedia Event Extraction from Video and Article**
    * Authors: Brian Chen, Xudong Lin, Christopher Thomas, Manling Li, Shoya Yoshida, Lovish Chum, Heng Ji, Shih-Fu Chang
    * url: [https://aclanthology.org/2021.findings-emnlp.8.pdf](https://aclanthology.org/2021.findings-emnlp.8.pdf)


* EMNLP2021: **Exploring Sentence Community for Document-Level Event Extraction**
    * Authors: Yusheng Huang, Weijia Jia
    * url: [https://aclanthology.org/2021.findings-emnlp.32.pdf](https://aclanthology.org/2021.findings-emnlp.32.pdf)

* EMNLP2021: **Extracting Event Temporal Relations via Hyperbolic Geometry**
    * Authors: Xingwei Tan, Gabriele Pergola, Yulan He
    * url: [https://aclanthology.org/2021.emnlp-main.636.pdf](https://aclanthology.org/2021.emnlp-main.636.pdf)

* EMNLP2021: **ESTER: A Machine Reading Comprehension Dataset for Reasoning about Event Semantic Relations**
    * Authors: Rujun Han, I-Hung Hsu, Jiao Sun, Julia Baylon, Qiang Ning, Dan Roth, Nanyun Peng
    * url: [https://aclanthology.org/2021.emnlp-main.597.pdf](https://aclanthology.org/2021.emnlp-main.597.pdf)

* EMNLP2021: **ECONET: Effective Continual Pretraining of Language Models for Event Temporal Reasoning**
    * Authors: Rujun Han, Xiang Ren, Nanyun Peng
    * url: [https://aclanthology.org/2021.emnlp-main.436.pdf](https://aclanthology.org/2021.emnlp-main.436.pdf)

* EMNLP2021: **Utilizing Relative Event Time to Enhance Event-Event Temporal Relation Extraction**
    * Authors: Haoyang Wen, Heng Ji
    * url: [https://aclanthology.org/2021.emnlp-main.815.pdf](https://aclanthology.org/2021.emnlp-main.815.pdf)

* EMNLP2021: **Event Coreference Data (Almost) for Free: Mining Hyperlinks from Online News**
    * Authors: Michael Bugert | Iryna Gurevych
    * url: [https://aclanthology.org/2021.emnlp-main.38.pdf](https://aclanthology.org/2021.emnlp-main.38.pdf)

* EMNLP2021: **Conundrums in Event Coreference Resolution: Making Sense of the State of the Art**
    * Authors: Jing Lu, Vincent Ng
    * url: [https://aclanthology.org/2021.emnlp-main.103.pdf](https://aclanthology.org/2021.emnlp-main.103.pdf)

* EMNLP2021: **A Comprehensive Comparison of Word Embeddings in Event & Entity Coreference Resolution**
    * Authors: Judicael Poumay | Ashwin Ittoo
    * url: [https://aclanthology.org/2021.findings-emnlp.235.pdf](https://aclanthology.org/2021.findings-emnlp.235.pdf)

* EMNLP2021: **Corpus-based Open-Domain Event Type Induction**
    * Authors: Jiaming Shen, Yunyi Zhang, Heng Ji, Jiawei Han
    * url: [https://aclanthology.org/2021.emnlp-main.441.pdf](https://aclanthology.org/2021.emnlp-main.441.pdf)

* EMNLP2021: **The Future is not One-dimensional: Complex Event Schema Induction by Graph Modeling for Event Prediction**
    * Authors: Manling Li, Sha Li, Zhenhailong Wang, Lifu Huang, Kyunghyun Cho, Heng Ji, Jiawei Han, Clare Voss
    * url: [https://aclanthology.org/2021.emnlp-main.422.pdf](https://aclanthology.org/2021.emnlp-main.422.pdf)


* EMNLP2021: **Uncertain Local-to-Global Networks for Document-Level Event Factuality Identification**
    * Authors: Pengfei Cao, Yubo Chen, Yuqing Yang, Kang Liu, Jun Zhao
    * url: [https://aclanthology.org/2021.emnlp-main.207.pdf](https://aclanthology.org/2021.emnlp-main.207.pdf)

* EMNLP2021: **Learning Constraints and Descriptive Segmentation for Subevent Detection**
    * Authors: Haoyu Wang, Hongming Zhang, Muhao Chen, Dan Roth
    * url: [https://aclanthology.org/2021.emnlp-main.423.pdf](https://aclanthology.org/2021.emnlp-main.423.pdf)

## 2022

* AAAI2022: **A Graph Convolutional Network with Adaptive Graph Generation and Channel Selection for Event Detection**
    * Authors: Zhipeng Xie, Yumin Tu
    * [https://www.aaai.org/AAAI22Papers/AAAI-1594.XieZ.pdf](https://www.aaai.org/AAAI22Papers/AAAI-1594.XieZ.pdf)

* AAAI2022:  **Selecting Optimal Context Sentences for Event-Event Relation Extraction**
    * Authors: Hieu Man Duc Trong, Nghia Ngo Trung, Linh Van Ngo, Thien Huu Nguyen
    * url: [https://www.aaai.org/AAAI22Papers/AAAI-3912.ManH.pdf](https://www.aaai.org/AAAI22Papers/AAAI-3912.ManH.pdf)

* AAAI2022: **Language Model Priming for Cross-Lingual Event Extraction**
    * Authors: Steven Fincke, Shantanu Agarwal, Scott Miller, Elizabeth Boschee
    * url: [https://arxiv.org/abs/2109.12383](https://arxiv.org/abs/2109.12383)

* WWW2022: **EventBERT: A Pre-Trained Model for Event Correlation Reasoning**
    * Authors: Yucheng Zhou, Xiubo Geng, Tao Shen, Guodong Long and Daxin Jiang
    * url: [https://dl.acm.org/doi/10.1145/3485447.3511928](https://dl.acm.org/doi/10.1145/3485447.3511928)

* IJCAI2022: **Summary Markov Models for Event Sequences**
    * Debarun Bhattacharjya, Saurabh Sihag, Oktie Hassanzadeh, Liza Bialik
    * url: [https://arxiv.org/abs/2205.03375v1](https://arxiv.org/abs/2205.03375v1)

* IJCAI2022: **Document-level Event Factuality Identification via Reinforced Multi-Granularity Hierarchical Attention Networks**
    * Authors: Zhong Qian, Peifeng Li, Zhu Qiaoming, Guodong Zhou

* IJCAI2022: **Efficient Document-level Event Extraction via Pseudo-Trigger-aware Pruned Complete Graph**
    * Authors: Tong Zhu, Xiaoye Qu, Wenliang Chen, Zhefeng Wang, Baoxing Huai, Nicholas Yuan, Min Zhang
    * url: [https://arxiv.org/abs/2112.06013](https://arxiv.org/abs/2112.06013)

* IJCAI2022: **CUP: Curriculum Learning based Prompt Tuning for Implicit Event Argument Extraction**
    * Authors: Jiaju Lin, Qin Chen, Jie Zhou, Jian Jin, Liang He
    * url: [https://arxiv.org/abs/2205.00498v1](https://arxiv.org/abs/2205.00498v1)

* ICASSP2022: **Document-Level Event Extraction via Human-Like Reading Process**
    * Authors: Shiyao Cui, Xin Cong, Bowen Yu, Tingwen Liu, Yucheng Wang, Jinqiao Shi
    * url: [https://ieeexplore.ieee.org/document/9747721/](https://ieeexplore.ieee.org/document/9747721/)

* ICASSP2022: **Generating Disentangled Arguments with Prompts: A Simple Event Extraction Framework That Works**
    * Authors: Jinghui Si; Xutan Peng; Chen Li; Haotian Xu; Jianxin Li
    * url: [https://ieeexplore.ieee.org/abstract/document/9747160](https://ieeexplore.ieee.org/abstract/document/9747160)

* ICASSP2022: **A Knowledge/Data Enhanced Method for Joint Event and Temporal Relation Extraction**
    * Authors: Xiaobin Zhang; Liangjun Zang; Peng Cheng; Yuqi Wang; Songlin Hu
    * url: [https://ieeexplore.ieee.org/document/9746259](https://ieeexplore.ieee.org/document/9746259)

* SIGIR2022: CorED: Incorporating Type-level and Instance-level Correlations for Fine-grained Event Detection
    * Authors: Jiawei Sheng, Rui Sun, Shu Guo, Shiyao Cui, Jiangxia Cao, Lihong Wang, Tingwen Liu and Hongbo Xu

* SIGIR2022: **A Dual-Expert Framework for Event Argument Extraction**
    * Authors: Rui Li, Wenlin Zhao, Cheng Yang and Sen Su

* SIGIR2022: **What Makes The Story Forward? Inferring Commonsense Explanations as Prompts for Future Event Generation**
    * Authors: Li Lin, Yixin Cao, Lifu Huang, Shu'Ang Li, Xuming Hu, Lijie Wen and Jianmin Wang

* SIGIR2022: **Towards Event-level Causal Relation Identification**
    * Authors: Chuang Fan, Daoxing Liu, Libo Qin, Yue Zhang and Ruifeng Xu

* SIGIR2022: **Enhancing Event-Level Sentiment Analysis with Structured Arguments**
    * Authors: Qi Zhang, Jie Zhou, Qin Chen, Qingchun Bai and Liang He
    * url: [https://arxiv.org/abs/2205.15511v1](https://arxiv.org/abs/2205.15511v1)

* SIGIR2022: **Translation-Based Implicit Annotation Projection for Zero-Shot Cross-Lingual Event Argument Extraction**
    * Authors: Chenwei Lou, Jun Gao, Changlong Yu, Wei Wang, Huan Zhao, Weiwei Tu and Ruifeng Xu

* ACL2022: **ClarET: Pre-training a Correlation-Aware Context-To-Event Transformer for Event-Centric Generation and Classification**
    * Authors: Yucheng Zhou, Tao Shen, Xiubo Geng, Guodong Long, Daxin Jiang
    * url: [https://aclanthology.org/2022.acl-long.183/](https://aclanthology.org/2022.acl-long.183/)

* ACL2022: **Dynamic Prefix-Tuning for Generative Template-based Event Extraction**
    * Authors: Xiao Liu, Heyan Huang, Ge Shi, Bo Wang
    * url: [https://aclanthology.org/2022.acl-long.358](https://aclanthology.org/2022.acl-long.358)

* ACL2022: **Improving Event Representation via Simultaneous Weakly Supervised Contrastive Learning and Clustering**
    * Authors: Jun Gao, Wei Wang, Changlong Yu, Huan Zhao, Wilfred Ng, Ruifeng Xu
    * url: [https://aclanthology.org/2022.acl-long.216/](https://aclanthology.org/2022.acl-long.216/)

* ACL2022: **Legal Judgment Prediction via Event Extraction with Constraints**
    * Authors: Yi Feng, Chuanyi Li, Vincent Ng
    * url: [https://aclanthology.org/2022.acl-long.48/](https://aclanthology.org/2022.acl-long.48/)

* ACL2022: **Multilingual Generative Language Models for Zero-Shot Cross-Lingual Event Argument Extraction**
    * Authors: Kuan-Hao Huang, I-Hung Hsu, Prem Natarajan, Kai-Wei Chang, Nanyun Peng
    * url: [https://aclanthology.org/2022.acl-long.317.pdf](https://aclanthology.org/2022.acl-long.317.pdf)

* ACL2022: **Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction**
    * Authors: Yubo Ma, Zehao Wang, Yixin Cao, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao
    * url: [https://aclanthology.org/2022.acl-long.466](https://aclanthology.org/2022.acl-long.466)

* ACL2022: **Saliency as Evidence: Event Detection with Trigger Saliency Attribution**
    * Authors: Jian Liu, Yufeng Chen, Jinan Xu
    * url: [https://aclanthology.org/2022.acl-long.313/](https://aclanthology.org/2022.acl-long.313/)

* ACL2022: **Event-Event Relation Extraction using Probabilistic Box Embedding**
    * Authors:  EunJeong Hwang, Jay-Yoon Lee, Tianyi Yang, Dhruvesh Patel, Dongxu Zhang, Andrew McCallum
    * url: [https://aclanthology.org/2022.acl-short.26/](https://aclanthology.org/2022.acl-short.26/)

* ACL2022: **MMEKG: Multi-modal Event Knowledge Graph towards Universal Representation across Modalities**
    * Authors: Yubo Ma, Zehao Wang, Mukai Li, Yixin Cao, Meiqi Chen, Xinze Li, Wenqi Sun, Kunquan Deng, Kun Wang, Aixin Sun, Jing Shao
    * url: []

* ACL2022-findings: **A Graph Enhanced BERT Model for Event Prediction**
    * Authors: Li Du, Xiao Ding, Yue Zhang, ting liu, Bing Qin
    * url: [https://aclanthology.org/2022.findings-acl.206/](https://aclanthology.org/2022.findings-acl.206/)

* ACL2022-findings: **Document-Level Event Argument Extraction via Optimal Transport**
    * Authors:  Amir Pouran Ben Veyseh, Minh Van Nguyen, Franck Dernoncourt, Bonan Min, Thien Huu Nguyen
    * url: [https://aclanthology.org/2022.findings-acl.130/](https://aclanthology.org/2022.findings-acl.130/)

* ACL2022-findings: **ECO v1: Towards Event-Centric Opinion Mining**
    * Authors: Ruoxi Xu, Hongyu Lin, Meng Liao, Xianpei Han, Jin Xu, Wei Tan, Yingfei Sun, Le Sun
    * url: [https://aclanthology.org/2022.findings-acl.216/](https://aclanthology.org/2022.findings-acl.216/)


* ACL2022-findings: **Event Transition Planning for Open-ended Text Generation**
    * Authors:  Qintong Li, Piji Li, Wei Bi, Zhaochun Ren, Yuxuan Lai, Lingpeng Kong
    * url: [https://aclanthology.org/2022.findings-acl.269.pdf](https://aclanthology.org/2022.findings-acl.269.pdf)

* ACL2022-findings: **LEVEN: A Large-Scale Chinese Legal Event Detection Dataset**
    * Authors: Feng Yao, Chaojun Xiao, Xiaozhi Wang, Zhiyuan Liu, Lei Hou, Cunchao Tu, Juanzi Li, Yun Liu, Weixing Shen, Maosong Sun
    * url: [https://aclanthology.org/2022.findings-acl.17/](https://aclanthology.org/2022.findings-acl.17/)

* ACL2022-findings: **Query and Extract: Refining Event Extraction as Type-oriented Binary Decoding**
    * Authors: Sijia Wang, Mo Yu, Shiyu Chang, Lichao Sun, Lifu Huang
    * url: [https://arxiv.org/abs/2110.07476](https://arxiv.org/abs/2110.07476)

* ACL2022-findings: **Debiasing Event Understanding for Visual Commonsense Tasks**
    * Authors:  Minji Seo, YeonJoon Jung, Seungtaek Choi, seung-won hwang, Bei Liu
    * url: [https://aclanthology.org/2022.findings-acl.65](https://aclanthology.org/2022.findings-acl.65)

* NAACL2022: **Cross-Lingual Event Detection via Optimized Adversarial Training**
    * Authors: Luis Fernando Guzman-Nateras, Minh Van Nguyen, Thien Huu Nguyen

* NAACL2022: **A Two-Stream AMR-enhanced Model for Document-level Event Argument Extraction** 
    * Authors: Runxin Xu, Peiyi Wang, Tianyu Liu, Shuang Zeng, Baobao Chang, Zhifang Sui
    * url: [https://arxiv.org/abs/2205.00241](https://arxiv.org/abs/2205.00241)

* NAACL2022: **RAAT: Relation-Augmented Attention Transformer for Relation Modeling in Document-Level Event Extraction**
    * Authors: Yuan Liang, Zhuoxuan Jiang, di yin, Bo Ren

* NAACL2022: **Joint Extraction of Entities, Relations, and Events via Modeling Inter-Instance and Inter-Label Dependencies**
    * Authors: Minh Van Nguyen, Bonan Min, Franck Dernoncourt, Thien Huu Nguyen

* NAACL2022: **DocEE: A Large-Scale and Fine-grained Benchmark for Document-level Event Extraction**
    * Authors: MeiHan Tong, Bin Xu, Shuai Wang, Meihuan Han, Yixin Cao, Jiangqi Zhu, Siyu Chen, Lei Hou, Juanzi Li

* NAACL2022: **Contrastive Representation Learning for Cross-Document Coreference Resolution of Events and Entities**
    * Authors: Benjamin Hsu, Graham Horwood

* NAACL2022: **Document-Level Event Argument Extraction by Leveraging Redundant Information and Closed Boundary Loss**
    * Authors: Hanzhang Zhou, Kezhi Mao

* NAACL2022: MINION: a Large-Scale and Diverse Dataset for Multilingual Event Detection
    * Authors: Amir Pouran Ben Veyseh, Minh Van Nguyen, Franck Dernoncourt, Thien Huu Nguyen

* NAACL2022: Event Schema Induction with Double Graph Autoencoders
    * Authors: Xiaomeng Jin, Manling Li, Heng Ji


* NAACL2022: **DEGREE: A Data-Efficient Generation-Based Event Extraction Model**
    * Authors: I-Hung Hsu, Kuan-Hao Huang, Elizabeth Boschee, Scott Miller, Prem Natarajan, Kai-Wei Chang, Nanyun Peng
    * url: [https://github.com/PlusLabNLP/DEGREE](https://github.com/PlusLabNLP/DEGREE)

* NAACL2022-findings: **ScAN: Suicide Attempt and Ideation Events Dataset**
    * Authors: Bhanu Pratap Singh Rawat, Samuel Kovaly, Wilfred R. Pigeon, Hong Yu
    * url: [https://arxiv.org/abs/2205.07872](https://arxiv.org/abs/2205.07872)

* NAACL2022-findings: **Cross-document Misinformation Detection based on Event Graph Reasoning**
    * Authors: Xueqing Wu, Kung-Hsiang Huang, Yi Fung, Heng Ji

* NAACL2022-findings: **EA2E: Improving Consistency with Event Awareness for Document-Level Argument Extraction**
    * Authors: Qi Zeng, Qiusi Zhan, Heng Ji
    * url: [https://arxiv.org/abs/2205.14847v1](https://arxiv.org/abs/2205.14847v1)

* NAACL2022-findings: **Zero-Shot Event Detection Based on Ordered Contrastive Learning and Prompt-Based**
    * Authors: Senhui Zhang, Tao Ji, Wendi Ji, Xiaoling Wang
    * url: [https://github.com/KindRoach/NAACL-ZEOP](https://github.com/KindRoach/NAACL-ZEOP)

* NAACL2022-findings: **Textual Entailment for Event Argument Extraction: Zero- and Few-Shot with Multi-Source Learning**
    * Authors: Oscar Sainz, Itziar Gonzalez-Dios, Oier Lopez de Lacalle, Bonan Min, Eneko Agirre
    * url: [https://arxiv.org/abs/2205.01376](https://arxiv.org/abs/2205.01376)

* NAACL2022-findings: **Event Detection for Suicide Understanding**
    * Authors: Luis Fernando Guzman-Nateras, Viet Dac Lai, Amir Pouran Ben Veyseh, Franck Dernoncourt, Thien Huu Nguyen

* NAACL2022-findings: **Extracting Temporal Event Relation with Syntax-guided Graph Transformer**
    * Authors: SHUAICHENG ZHANG, Qiang Ning, Lifu Huang
    * url: [https://arxiv.org/abs/2104.09570v1](https://arxiv.org/abs/2104.09570v1)