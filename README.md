## Survey/Overview papers/documents should read on Machine Reading Comprehension
- Danqi Chen: **Neural Reading Comprehension and Beyond**. PhD thesis, Stanford University, 2018, [link](https://github.com/danqi/thesis).
- Boyu Qiu et al., **A Survey on Neural Machine Reading Comprehension**, arXiv, 2019, [link](https://arxiv.org/pdf/1906.03824.pdf).
- Xin Zhang et al., **Machine Reading Comprehension: a Literature Review**, arXiv, 2019, [link](https://arxiv.org/pdf/1907.01686.pdf).
- Shanshan Liu et al., **Neural Machine Reading Comprehension: Methods and Trends**, arXiv, 2019, [link](https://arxiv.org/pdf/1907.01118.pdf).


## Evaluation papers
- Saku Sugawara et al., **Evaluation Metrics for Machine Reading Comprehension: Prerequisite Skills and Readability**, ACL, 2017, [link](https://www.aclweb.org/anthology/P17-1075.pdf).


## Basic Papers/Models

**Noted**

- KBMRC: Knowledge-based Machine Reading Comprehension
  * Details: https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers/wiki/Knowledge-based-MRC 
- OPQA: Open-domain Question Answering
- UQ: Unanswerable Questions
  * Details: https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers/wiki/Unanswerable-Questions
- Multi-Passage MRC: Multi-Passage Machine Reading Comprehension
  * Details: https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers/wiki/Multi-Passage-MRC
- CQA: Conversational Question Answering
  * Details: https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers/wiki/CQA

| Year | Title | Model| Conference | Author/Team | Datasets | Misc                                                                  | Paper, Source Code |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 2015 | Teaching Machines to Read and Comprehend | Attentive Reader | NIPS | Google DeepMind, University of Oxford | CNN and Daily Mail |  | [paper](https://papers.nips.cc/paper/5945-teaching-machines-to-read-and-comprehend.pdf), code |
| 2016 | Text Understanding with the Attention Sum Reader Network | Attention Sum Reader | ACL | IBM Watson | Children’s Book Test, CNN and Daily Mail |  | [paper](https://www.aclweb.org/anthology/P16-1086), [code](https://github.com/rkadlec/asreader) |
| 2016 | Long Short-Term Memory-Networks for Machine Reading | Memory Networks | EMNLP | University of Edinburgh |  |  | [paper](https://www.aclweb.org/anthology/D16-1053.pdf), [code] |
| 2016 | A Thorough Examination of the CNN/Daily Mail Reading Comprehension Task |  | ACL | Danqi Chen et al., |  |  | [paper](https://www.aclweb.org/anthology/P16-1223.pdf), [code] |
| 2016 | Multi-Perspective Context Matching for Machine Comprehension | Multi-Perspective Context Matching | Arxiv | IBM Watson Research |  |  | [paper](https://arxiv.org/pdf/1612.04211.pdf), [code] |
| 2017 | Bi-directional Attention Flow for Machine Comprehension | BiDAF | ICLR | University of Washington, Allen Institute | SQuAD 1.1 |  | [paper](https://arxiv.org/pdf/1611.01603.pdf), [code](https://github.com/allenai/bi-att-flow) |
| 2017 | Machine Comprehension Using Match-LSTM and Answer Pointer | Match-LSTM | ICLR | Singapore Management University | SQuAD 1.1 |  | [paper](https://arxiv.org/pdf/1608.07905.pdf), [code](https://github.com/shuohangwang/SeqMatchSeq) |
| 2017 | Attention-over-Attention Neural Networks for Reading Comprehension | Attention-over-Attention Reader | ACL | Yiming Cui et al., |  |  | [paper](https://www.aclweb.org/anthology/P17-1055.pdf), [code]|
| 2017 | R-Net: Machine Reading Comprehension with Self-Matching Networks | R-Net | Technical Report | Microsoft Research Asia  | SQuAD 1.1, MS-MARCO |  | [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf), [code](https://github.com/HKUST-KnowComp/R-Net) |
| 2017 | Reading Wikipedia to Answer Open-Domain Questions | DrQA | ACL | Danqi Chen et al.,  | Wikipedia, SQuAD 1.1, CuratedTREC, WebQuestions, WikiMovies | OPQA, Multi-Passage MRC | [paper](https://www.aclweb.org/anthology/P17-1171), [code](https://github.com/facebookresearch/DrQA) |
| 2017 | Gated-Attention Readers for Text Comprehension | Gated-attention Reader | ACL | CMU  | CNN and Daily Mail, Children’s Book Test, Who Did What |  | [paper](https://arxiv.org/pdf/1606.01549.pdf), [code](https://github.com/bdhingra/ga-reader) |
| 2017 | DCN+: Mixed Objective and Deep Residual CoAttention for Question Answering |  | Arxiv | Salesforce Research |  |  | [paper](https://arxiv.org/pdf/1711.00106.pdf), [code] |
| 2017 | Dynamic CoAttention Networks for Question Answering | Dynamic coattention networks | ICLR | Salesforce Research |  |  | [paper](https://arxiv.org/pdf/1611.01604.pdf), [code] |
| 2018 | QANET: Combining local Convolution with global Self-Attention for Reading Comprehension | QANet | ICLR | CMU, Google Brain  | SQuAD 1.1 |  | [paper](https://openreview.net/pdf?id=B14TlG-RW), [code](https://github.com/google-research/google-research/tree/master/qanet) |
| 2019 | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | BERT | NAACL | Google AI Language  | GLUE, SQuAD 1.1, SQuAD 2.0, SWAG |  | [paper](https://www.aclweb.org/anthology/N19-1423), [code](https://github.com/google-research/bert) |
|  |  |  |  |  |  |  | [paper]() |



## Datasets
- Following Danqi Chen, we have four answer types: Cloze test, Multiple choice, Span extraction and Free answering.

| Year | Dataset | Task | Size | Source | Web/Paper | Answer type                                                                  | Misc | Similar datasets |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|1999|DeepRead| RC | 60 development and 60 test? | news stories|[paper](https://dl.acm.org/citation.cfm?id=1034678.1034731)| Free answering |  |  |
|2013|QA4MRE| RC | | various articles |[paper](https://www.cs.cmu.edu/~hovy/papers/13CLEF-QA4MRE.pdf)| Multiple choice |  | |
|2013|MCTest| RC | 500 stories + 2k questions | fictional stories |[paper](http://aclweb.org/anthology/D13-1020)| Multiple choice | open-domain  |  |
|2015|CNN and Daily Mail| RC | 93k + 220k articles| CNN + Daily Mail |[paper](https://cs.nyu.edu/~kcho/DMQA/)| Cloze test |  |  |
|2015|bAbI| RC | | classic text adventure game |[web](https://research.fb.com/downloads/babi/)| Free answering | 20 tasks |  |
|2015|Children's Book Test| RC | 108 children's books | |[web](https://research.fb.com/downloads/babi/)| Cloze test |  | |
|2016|LAMBADA||||[paper](http://clic.cimec.unitn.it/lambada/)| Cloze test |  | |
|2016|Who-did-What||||[paper](https://tticnlp.github.io/who_did_what/)| Cloze test |  | |
|2016|MS MARCO||||[web](http://www.msmarco.org/dataset.aspx)| Free answering |  |  |
|2016|NewsQA||||[paper](https://datasets.maluuba.com/NewsQA)| Span extraction |  |  |
|2016|SQuAD 1.1| RC | 87k training + 10k development | Wikipedia |[paper](https://rajpurkar.github.io/SQuAD-explorer/)| Span extraction |  | NewsQA |
|2017|TriviaQA||||[paper](http://nlp.cs.washington.edu/triviaqa/)| Span extraction | | |
|2017|RACE||||[paper](http://www.cs.cmu.edu/~glai1/data/race/)| Multiple choice |  | |
|2017|SQA||||[paper](https://people.cs.umass.edu/~miyyer/pubs/2017_acl_dynsp.pdf)|  |  | |
|2017|NarrativeQA||||[paper](https://github.com/deepmind/narrativeqa)| Free answering |  |  |
|2017|SearchQA||||[paper](https://arxiv.org/pdf/1704.05179.pdf)| Free answering |  | |
|2017|WikiSuggest||||[paper](https://aclweb.org/anthology/D15-1237)|  |  | |
|2018|MultiRC| RC | 6k+ questions | various articles | [web](https://cogcomp.seas.upenn.edu/multirc/), [paper](https://www.aclweb.org/anthology/N18-1023)| Multiple choice  | multiple sentence reasoning | MCTest |
|2018|CQA||||[paper](http://aclweb.org/anthology/N18-1059)|  |  | |
|2018|SQuAD 2.0| RC | 150k | Wikipedia |[paper](https://rajpurkar.github.io/SQuAD-explorer/)| Span extraction | no answer: 50k | NewsQA |
|2018| CoQA | RC | 127k | various articles |[paper](https://stanfordnlp.github.io/coqa/)| Free answering | conversational questions | QuAC |
|2018| Quac | RC | 100k | Wikipedia |[paper](http://quac.ai/)| Span extraction | conversational questions | CoQA |
|2018| HotpotQA | RC | 113k | Wikipedia |[web](https://hotpotqa.github.io/), [paper](https://arxiv.org/pdf/1809.09600.pdf)| Span extraction | multi-hop reasoning | QAngaroo |
| 2018 | RecipeQA | RC | 36k | various |  |  | multimodal comprehension |  |
| 2018 | CLOTH | RC | 99k | English exams |  | Cloze test |  | RACE |
| 2018 | DuoRC | RC | 186k | movie plot |  | Span extraction |  | NarrativeQA  |
| 2018 | CliCR | RC | 100k | clinical case text |  | Cloze test |  |  |
| 2018 | FEVER |  |  |  |  |  |  | |
| 2018 | ProPara | RC | 2k | procedural text |  |  |  | bAbI, SCoNE |
| 2018 | ARC | RC | 8k | science exam |  |  | easy 5197, challenge 2590 | |
| 2018 | DuReader |  |  |  |  | Free answering |  |  |
| 2013 | WebQuestions | QA |  |  |  | |  |  |
| 2015 | CuratedTREC | QA |  |  |  | |  |  |
| 2016 | WikiMovies | QA |  |  |  | |  |  |
| 2018 | OpenBookQA | QA | 6k | science facts |  | Multiple choice  | external knowledge | ARC |
| 2018 | SWAG | QA | 113k | video caption |  | Multiple choice | situational commonsense reasoning |  |
|2018|CSQA| QA |200k dialogs, 1.6M turns ||[paper](https://arxiv.org/pdf/1801.10314.pdf)|  |  |  |

## Knowledge Bases/Knowledge Sources
- Wikipedia
- Freebase
- DBPedia

## Question Answering Systems
- IBM's DeepQA
- QuASE
- Microsoft's AskMSR
- YodaQA
- DrQA


## New Papers from EMNLP 2019 about MRC
- Minghao Hu, Yuxing Peng, Zhen Huang and Dongsheng Li, **A Multi-Type Multi-Span Network for Reading Comprehension that Requires Discrete Reasoning**, [link](https://arxiv.org/pdf/1908.05514.pdf).
- Huazheng Wang, Zhe Gan, Xiaodong Liu, Jingjing Liu, Jianfeng Gao and Hongning Wang, **Adversarial Domain Adaptation for Machine Reading Comprehension**, [link?]().
- Yimin Jing, Deyi Xiong and Zhen Yan, **BiPaR: A Bilingual Parallel Dataset for Multilingual and Cross-lingual Reading Comprehension on Novels**, [link?]().
- Lifu Huang, Ronan Le Bras, Chandra Bhagavatula and Yejin Choi, **Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning**, [link?]().
- Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang and Guoping Hu, **Cross-Lingual Machine Reading Comprehension**, [link?]().
- Todor Mihaylov and Anette Frank, **Discourse-Aware Semantic Self-Attention for Narrative Reading Comprehension**, [link?]().
- Kyungjae Lee, Sunghyun Park, Hojae Han, Jinyoung Yeo, Seung-won Hwang and Juho Lee, **Learning with Limited Data for Multilingual Reading Comprehension**, [link?]().
- Qiu Ran, Yankai Lin, Peng Li, Jie Zhou and Zhiyuan Liu, **NumNet: Machine Reading Comprehension with Numerical Reasoning**, [link?]().
- Yiming Cui, Ting Liu, Wanxiang Che, Li Xiao, Zhipeng Chen, Wentao Ma, Shijin Wang and Guoping Hu, **A Span-Extraction Dataset for Chinese Machine Reading Comprehension**, [link?]().
- Daniel Andor, Luheng He, Kenton Lee and Emily Pitler, **Giving BERT a Calculator: Finding Operations and Arguments with Reading Comprehension**, [link?]().
- Delai Qiu, Yuanzhe Zhang, Xinwei Feng, Xiangwen Liao, Wenbin Jiang, Yajuan Lyu, Kang Liu and Jun Zhao, **Machine Reading Comprehension Using Structural Knowledge Graph-aware Network**, [link?]().
- Pradeep Dasigi, Nelson F. Liu, Ana Marasovic, Noah A. Smith and Matt Gardner, **Quoref: A Reading Comprehension Dataset with Questions Requiring Coreferential Reasoning**, [link?]().
- Tsung-Yuan Hsu, Chi-Liang Liu and Hung-yi Lee, **Zero-shot Reading Comprehension by Cross-lingual Transfer Learning with Multi-lingual Language Representation Model**, [link?]().



## New Papers from ACL 2019 about MRC
- Yimeng Zhuang and Huadong Wang, **Token-level Dynamic Self-Attention Network for Multi-Passage Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1218).
- Chao Wang and Hui Jiang, **Explicit Utilization of General Knowledge in Machine Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1219).
- Kyosuke Nishida et al., **Multi-style Generative Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1220).
- Minghao Hu, Yuxing Peng, Zhen Huang and Dongsheng Li, **Retrieve, Read, Rerank: Towards End-to-End Multi-Document Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1221).
- Ming Ding et al., **Cognitive Graph for Multi-Hop Reading Comprehension at Scale**, [link](https://www.aclweb.org/anthology/P19-1259).
- Ming Tu et al., **Multi-hop reading comprehension across multiple documents by reasoning over heterogeneous graphs**, [link](https://www.aclweb.org/anthology/P19-1260).
- An Yang et al., **Enhancing Pre-Trained Language Representations with Rich Knowledge for Machine Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1226).
- Alon Talmor and Jonathan Berant, **MultiQA: An Empirical Investigation of Generalization and Transfer in Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1485).
- Yichen Jiang el at., **Explore, Propose, and Assemble: An Interpretable Model for Multi-Hop Reading Comprehension**, [link](https://arxiv.org/pdf/1906.05210.pdf).
- Yi Tay et al., **Simple and Effective Curriculum Pointer-Generator Networks for Reading Comprehension over Long Narratives**, [link](https://www.aclweb.org/anthology/P19-1486).
- Sewon Min et al., **Multi-hop Reading Comprehension through Question Decomposition and Rescoring**, [link](https://www.aclweb.org/anthology/P19-1613).
- Souvik Kundu et al., **Exploiting Explicit Paths for Multi-hop Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1263).
- Haichao Zhu et al., **Learning to Ask Unanswerable Questions for Machine Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1415).
- Xuanyu Zhang, **MC^2: Multi-perspective Convolutional Cube for Conversational Machine Reading Comprehension**, [link](https://www.aclweb.org/anthology/P19-1622).
- Diana Galvan, **Active Reading Comprehension: A dataset for learning the Question-Answer Relationship strategy**, [link](https://www.aclweb.org/anthology/P19-2014).


## Thanks to these repositories:
- https://github.com/penzant/nlu_datasets_2018
- https://github.com/seriousmac/awesome-qa




