### Survey/Overview papers/documents should read in Machine Reading Comprehension
- Danqi Chen: Neural Reading Comprehension and Beyond. PhD thesis, Stanford University, 2018, [link](https://github.com/danqi/thesis).
- Boyu Qiu et al., A Survey on Neural Machine Reading Comprehension, arXiv, 2019, [link](https://arxiv.org/pdf/1906.03824.pdf).
- Shanshan Liu et al., Neural Machine Reading Comprehension: Methods and Trends, arXiv, 2019, [link](https://arxiv.org/pdf/1907.01118.pdf).


### Papers/Models
| Year | Title | Model| Conference | Author/Team | Datasets | Link                                                                  | Source Code |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 2015 | Teaching Machines to Read and Comprehend |  | NIPS | Google DeepMind, University of Oxford | CNN and Daily Mail | [paper](https://papers.nips.cc/paper/5945-teaching-machines-to-read-and-comprehend.pdf) | code |
| 2016 | Text Understanding with the Attention Sum Reader Network |  | ACL | IBM Watson | Children’s Book Test, CNN and Daily Mail | [paper](https://www.aclweb.org/anthology/P16-1086) | [code](https://github.com/rkadlec/asreader) |
| 2016 | Key-Value Memory Networks for Directly Reading Documents |  | EMNLP | Facebook AI Research, CMU | WikiMovies, WikiQA  | [paper](https://aclweb.org/anthology/D16-1147) | [code](https://github.com/facebook/MemNN/tree/master/KVmemnn) |
| 2017 | Bi-directional Attention Flow for Machine Comprehension | BiDAF | ICLR | University of Washington, Allen Institute | SQuAD 1.1 | [paper](https://arxiv.org/pdf/1611.01603.pdf) | [code](https://github.com/allenai/bi-att-flow) |
| 2017 | Machine Comprehension Using Match-LSTM and Answer Pointer |  | ICLR | Singapore Management University | SQuAD 1.1 | [paper](https://arxiv.org/pdf/1608.07905.pdf) | [code](https://github.com/shuohangwang/SeqMatchSeq) |
| 2017 | R-Net: Machine Reading Comprehension with Self-Matching Networks | R-Net | Technical Report | Microsoft Research Asia  | SQuAD 1.1, MS-MARCO | [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf) | [code](https://github.com/HKUST-KnowComp/R-Net) |
| 2017 | Reading Wikipedia to Answer Open-Domain Questions | DrQA | ACL | Danqi Chen et al.,  | SQuAD 1.1, CuratedTREC, WebQuestions, WikiMovies | [paper](https://www.aclweb.org/anthology/P17-1171) | [code](https://github.com/facebookresearch/DrQA) |
| 2017 | Gated-Attention Readers for Text Comprehension |  | ACL | CMU  | CNN and Daily Mail, Children’s Book Test, Who Did What | [paper](https://arxiv.org/pdf/1606.01549.pdf) | [code](https://github.com/bdhingra/ga-reader) |
| 2018 | QANET: Combining local Convolution with global Self-Attention for Reading Comprehension | QANet | ICLR | CMU, Google Brain  | SQuAD 1.1 | [paper](https://openreview.net/pdf?id=B14TlG-RW) | [code](https://github.com/google-research/google-research/tree/master/qanet) |
| 2019 | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | BERT | NAACL | Google AI Language  | GLUE, SQuAD 1.1, SQuAD 2.0, SWAG | [paper](https://www.aclweb.org/anthology/N19-1423) | [code](https://github.com/google-research/bert) |



### Datasets
- Following Danqi Chen, we have four answer types: Cloze test, Multiple choice, Span extraction and Free answering.

| Year | Dataset | Task | Size | Source | Web/Paper | Answer type                                                                  | Misc | Similar datasets |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|1999|DeepRead| RC | 60 development and 60 test? | news stories|[paper](https://dl.acm.org/citation.cfm?id=1034678.1034731)| Free answering |  |  |
|2013|QA4MRE|?|?|?|[paper](https://www.cs.cmu.edu/~hovy/papers/13CLEF-QA4MRE.pdf)|  |  | |
|2013|MCTest||||[paper](http://aclweb.org/anthology/D13-1020)| Multiple choice |  |  |
|2015|CNN and Daily Mail||||[paper](https://cs.nyu.edu/~kcho/DMQA/)| Cloze test |  |  |
|2015|bAbI||||[web](https://research.fb.com/downloads/babi/)| Free answering |  |  |
|2015|Children's Book Test||||[web](https://research.fb.com/downloads/babi/)| Cloze test |  | |
|2016|LAMBADA||||[paper](http://clic.cimec.unitn.it/lambada/)| Cloze test |  | |
|2016|Who-did-What||||[paper](https://tticnlp.github.io/who_did_what/)| Cloze test |  | |
|2016|MS MARCO||||[web](http://www.msmarco.org/dataset.aspx)| Free answering |  |  |
|2016|NewsQA||||[paper](https://datasets.maluuba.com/NewsQA)| Span extraction |  |  |
|2016|SQuAD 1.1| RC |  | Wikipedia |[paper](https://rajpurkar.github.io/SQuAD-explorer/)| Span extraction |  | NewsQA |
|2017|TriviaQA||||[paper](http://nlp.cs.washington.edu/triviaqa/)| Span extraction | | |
|2017|RACE||||[paper](http://www.cs.cmu.edu/~glai1/data/race/)| Multiple choice |  | |
|2017|SQA||||[paper](https://people.cs.umass.edu/~miyyer/pubs/2017_acl_dynsp.pdf)|  |  | |
|2017|NarrativeQA||||[paper](https://github.com/deepmind/narrativeqa)| Free answering |  |  |
|2017|SearchQA||||[paper](https://arxiv.org/pdf/1704.05179.pdf)| Free answering |  | |
|2017|WikiSuggest||||[paper](https://aclweb.org/anthology/D15-1237)|  |  | |
|2018|MultiRC| RC | 6k+ questions | various articles | [web](https://cogcomp.seas.upenn.edu/multirc/), [paper](https://www.aclweb.org/anthology/N18-1023)| Multiple choice  | multiple sentence reasoning | MCTest |
|2018|CSQA| QA |200k dialogs, 1.6M turns ||[paper](https://arxiv.org/pdf/1801.10314.pdf)|  |  |  |
|2018|CQA||||[paper](http://aclweb.org/anthology/N18-1059)|  |  | |
|2018|SQuAD 2.0| RC | 150k | Wikipedia |[paper](https://rajpurkar.github.io/SQuAD-explorer/)| Span extraction | no answer: 50k | NewsQA |
|2018| CoQA | RC | 127k | various articles |[paper](https://stanfordnlp.github.io/coqa/)| Free answering | conversational questions | QuAC |
|2018| Quac | RC | 100k | Wikipedia |[paper](http://quac.ai/)| Span extraction | conversational questions | CoQA |
|2018| HotpotQA | RC | 113k | Wikipedia |[web](https://hotpotqa.github.io/), [paper](https://arxiv.org/pdf/1809.09600.pdf)| Span extraction | multi-hop reasoning | QAngaroo |
| 2018 | SWAG | QA | 113k | video caption |  | Multiple choice | situational commonsense reasoning |  |
| 2018 | OpenBookQA | QA | 6k | science facts |  | Multiple choice  | external knowledge | ARC |
| 2018 | RecipeQA | RC | 36k | various |  |  | multimodal comprehension |  |
| 2018 | CLOTH | RC | 99k | English exams |  | Cloze test |  | RACE |
| 2018 | DuoRC | RC | 186k | movie plot |  | Span extraction |  | NarrativeQA  |
| 2018 | CliCR | RC | 100k | clinical case text |  | Cloze test |  |  |
| 2018 | FEVER |  |  |  |  |  |  | |
| 2018 | ProPara | RC | 2k | procedural text |  |  |  | bAbI, SCoNE |
| 2018 | ARC | RC | 8k | science exam |  |  | easy 5197, challenge 2590 | |
| 2018 | DuReader |  |  |  |  | Free answering |  |  |


# Thanks to these repositories:
- https://github.com/penzant/nlu_datasets_2018
- https://github.com/seriousmac/awesome-qa




