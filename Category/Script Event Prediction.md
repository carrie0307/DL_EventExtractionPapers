## Script Event Prediction

### Survey

* A survey of script learning [[paper]](https://link.springer.com/article/10.1631/FITEE.2000347)

### Early Researches

* ACL2008: 
Unsupervised Learning of Narrative Event Chains [[paper]](https://www.aclweb.org/anthology/P08-1090/)

* EACL2012: 
Skip n-grams and Ranking Functions for Predicting Script Events [[paper]](https://aclanthology.org/E12-1034/)

* EACL2014: 
Statistical Script Learning with Multi-Argument Events [[paper]](https://aclanthology.org/E14-1024/)

### Event-pair based

* AAAI2016: 
What Happens Next? Event Prediction Using a Compositional Neural Network Model [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/10344)[[code]](https://mark.granroth-wilding.co.uk/papers/what_happens_next/)

* EMNLP2017: 
Integrating Order Information and Event Relation for Script Event Prediction [[paper]](https://aclanthology.org/D17-1006/)  [[code]](https://github.com/wangzq870305/event_chain)

* AAAI2018: Event Representations with Tensor-Based Compositions[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11932/11791) [[code]](https://github.com/stonybrooknlp/event-tensors)
(i) a sentence similarity task, (ii) a new hard similarity task, and (iii) an event prediction task (two variants of the narrative cloze)
Transitive Sentence Similarity, Hard Similarity Task, MCNC, Generating Event Schemas (Nearest Neighbor Schema Generation)

### Event-chain based

#### Event-segment based
* AAAI2019: 
SAM-Net: Integrating event-level and chain-level attentions to predict what happens next [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4655)


#### Event-chain based

* WWW2021: Multi-level Connection Enhanced Representation Learning for Script Event Prediction [[paper]](https://dl.acm.org/doi/10.1145/3442381.3449894)

* IJIS: What happens next? Combining enhanced multilevel script learning and dual fusion strategies for script event prediction [[paper]](https://onlinelibrary.wiley.com/doi/10.1002/int.23025?af=R)[[code]](https://github.com/xianhuaxizi/EMDF-Net)


### Event-graph based

* IJCAI2018: 
Constructing Narrative Event Evolutionary Graph for Script Event Prediction [[paper]](https://www.ijcai.org/Proceedings/2018/0584) [[code]](https://github.com/eecrazy/ConstructingNEEG_IJCAI_2018)

* COLING2020: 
Heterogeneous Graph Neural Networks to Predict What Happen Next [[paper]](https://aclanthology.org/2020.coling-main.29.pdf)

* ACL2022-findings: A Graph Enhanced BERT Model for Event Prediction [[paper]](https://aclanthology.org/2022.findings-acl.206.pdf)[[code]](https://github.com/sjcfr/GraphBert)




### External knowledge Enhanced

* AAAI2018: 
FEEL: Featured Event Embedding Learning [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11936)


#### Discourse Relation

* ACL2019: Multi-Relational Script Learning for Discourse Relations [[paper]](https://aclanthology.org/P19-1413/) [[code]](https://github.com/doug919/multi_relational_script_learning)

* EMNLP2020: Weakly-Supervised Modeling of Contextualized Event Embedding for Discourse Relations[[paper]](https://aclanthology.org/2020.findings-emnlp.446/)[[code]](https://github.com/doug919/narrative_graph_emnlp2020)

#### KB enhanced

* EMNLP2019: 
Event Representation Learning Enhanced with External Commonsense Knowledge [[paper]](https://aclanthology.org/D19-1495/)[[code]](https://github.com/MagiaSN/CommonsenseERL_EMNLP_2019)
    * [EventMind](http://aclweb.org/anthology/P18-1043)
    * [ATOMIC](https://dl.acm.org/doi/abs/10.1609/aaai.v33i01.33013027)

* COLING2020: 
Integrating External Event Knowledge for Script Learning [[paper]](https://aclanthology.org/2020.coling-main.27.pdf)
    * [ASER](https://dl.acm.org/doi/10.1145/3366423.3380107)

#### Original texts enhanced

* EMNLP2021-Findings: Incorporating Circumstances into Narrative Event Prediction [[paper]](https://aclanthology.org/2021.findings-emnlp.416/) [[code]](https://github.com/Shichao-Wang/CircEvent)

* EMNLP2021: 
Integrating Deep Event-Level and Script-Level Information for Script Event Prediction [[paper]](https://aclanthology.org/2021.emnlp-main.777/) [[code]](https://github.com/waltbai/MCPredictor)

* AAAI2023: 
Rich Event Modeling for Script Event Prediction [[paper]](https://arxiv.org/abs/2212.08287)


#### Multi-task
* SIGIR2020: Incorporating Scenario Knowledge into a Unified Fine-tuning Architecture for Event Representation [[paper]](https://doi.org/10.1145/3397271.3401173)

* CIKM2021: Multi-Task Self-Supervised Learning for Script Event Prediction [[paper]](https://doi.org/10.1145/3459637.3482150)


#### Others
* AAAI2021:Multimodal Event Representation Learning in Heterogeneous [[paper]](https://www.aaai.org/AAAI21Papers/AAAI-6544.ZhangL.pdf)


### Related Evaulation Tasks

####  Multiple Choice Narrative Cloze (MCNC)
* Task Goal: Aim to predict the subsequent event of a given event chain from a candidate event list.
* Download from [IJCAI2018-SGNN](https://github.com/eecrazy/ConstructingNEEG_IJCAI_2018)
* Most papers about script-learning evaluation their methods via MCNC task.

####  Multiple-Choice Narrative Sequences (MCNS)

* MCNS turns MCNC into a sequence prediction problem by creating multiple-choice questions for each step, except the start event.
* Download from xxx
* Related papers: [[AAAI2018-FEEL]](https://ojs.aaai.org/index.php/AAAI/article/view/11936), [[COLING2020-HeterEvent]](https://aclanthology.org/2020.coling-main.29.pdf), [[EventTransE]](https://aclanthology.org/P19-1413/)


#### Multiple-Choice Narrative Explanation (MCNE)
* MCNE provides an additional clue, the end event, to MCNS. The inference model has to connect the start and end by explaining things happened in between.

* Download from xxx
* Related papers: [[AAAI2018-FEEL]](https://ojs.aaai.org/index.php/AAAI/article/view/11936), [[COLING2020-HeterEvent]](https://aclanthology.org/2020.coling-main.29.pdf), [[EventTransE]](https://aclanthology.org/P19-1413/)

####  Coherent Multiple Choice Narrative Cloze (CMCNC)
* A cleaned version of MCNC dataset.
* Download from [[AAAI2018-TBC]](https://github.com/StonyBrookNLP/event-tensors/tree/master/data)
* Related paper: [[AAAI2018-TBC]](https://ojs.aaai.org/index.php/AAAI/article/view/11932/11791)


#### Story Cloze Test (SCT)
* The SCT task requires models to select the correct ending from two candidates given a story context. Compared with MCNC which focuses on **abstract events**, the stories in SCT are **concrete events and with much more details**. 

* Download from [[HuggingFace]](https://huggingface.co/datasets/story_cloze#:~:text=Dataset%20Summary,to%20a%20four%2Dsentence%20story.)
* Related paper: [[ACL2022-GraphBERT]](https://aclanthology.org/2022.findings-acl.206.pdf)


#### Hard Similar Task
* The goal of this task is that similar events should be close to each other in the same vector space, while dissimilar events should be far away with each other.
* Downlad from [[EMNLP2019-Ding et al.]](https://github.com/MagiaSN/CommonsenseERL_EMNLP_2019/tree/master/data)
* Related papers: [[AAAI2018-TBC]](https://ojs.aaai.org/index.php/AAAI/article/view/11932/11791), [[EMNLP2019-Ding et al.]](https://aclanthology.org/D19-1495/), [[AAAI21-MERL]](https://www.aaai.org/AAAI21Papers/AAAI-6544.ZhangL.pdf)


#### Transitive Sentence Similarity
* The task aims to measure the similarity between event pair.
* Download from [[EMNLP2019-Ding et al.]](https://github.com/MagiaSN/CommonsenseERL_EMNLP_2019/tree/master/data)
* Related papers: [[AAAI2018-TBC]](https://ojs.aaai.org/index.php/AAAI/article/view/11932/11791), [[EMNLP2019-Ding et al.]](https://aclanthology.org/D19-1495/), [[AAAI21-MERL]](https://www.aaai.org/AAAI21Papers/AAAI-6544.ZhangL.pdf)


#### Nearest Neighbor Schema Generation
* The task takes as input a **single seed event** and produces the schema based on this event.
* Download from [[AAAI2018-TBC]](https://github.com/StonyBrookNLP/event-tensors/tree/master/data)
* Related papers:  [[AAAI2018-TBC]](https://ojs.aaai.org/index.php/AAAI/article/view/11932/11791)

#### Multimodal Event Similarity
* The task extends the Hard Similar Dataset to multimodal with the same procedure as described earlier for the hard similarity events dataset, resulting in 690 event triples paired with 6,900 event images.
* The dataset is not public yes, but [the paper](https://www.aaai.org/AAAI21Papers/AAAI-6544.ZhangL.pdf) details the construction of the dataset.


#### Cross-modal Event Retrieval
* In this task, a randomly selected image as a query and aim to retrieve the bestmatched event triple out of a randomly-constructed event triple set.
* The dataset is not public yes, but [the paper](https://www.aaai.org/AAAI21Papers/AAAI-6544.ZhangL.pdf) details the construction of the dataset.
