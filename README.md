# Multi_Sense_Embedding_Surve (Under construction)
Please commit a related paper for a good survey and discuss (I don't have a plan to publish a survey paper).

# Training
## Survey
- [From Word to Sense Embeddings: A Survey on Vector Representations of Meaning](https://arxiv.org/abs/1805.04032), 2018.
- [Word Embeddings: A Survey](https://arxiv.org/pdf/1901.09069.pdf), 2019.

## Supervised (including Knowledge Based)
### Concept Hierarchy (e.g. WORDNET, BabelNet)
#### Post Edit
- [Retrofitting Word Vectors to Semantic Lexicons](https://aclanthology.org/N15-1184/), 2015.
- [De-Conflated Semantic Representations](https://aclanthology.org/D16-1174/), 2016.
- [GenSense: A Generalized Sense Retrofitting Model](https://aclanthology.org/C18-1141/), 2018.

#### with Word Sense Disambiguation
- [Multi-sense embeddings through a word sense disambiguation process Author links open overlay panel](https://www.sciencedirect.com/science/article/pii/S0957417419304269), 2019.

### Wikipedia
- [Sense-aware Semantic Analysis: A Multi-prototype Word Representation Model using Wikipedia](https://clgiles.ist.psu.edu/pubs/AAAI2015-sense-aware.pdf), 2015.

## Un-Supervised (From Corpora Only)
### Parametric
- [Multi-prototype vector-space models of word meaning](https://aclanthology.org/N10-1013.pdf), 2010.
- [Improving Word Representations via Global Contextand Multiple Word Prototypes](https://aclanthology.org/P12-1092.pdf), 2012.
- [K-Embeddings: Learning Conceptual Embeddings for Words using Context](https://aclanthology.org/N16-1151/), 2016.
- [Multimodal Word Distributions](https://aclanthology.org/P17-1151/), 2017.

#### with Latent Dirichlet Allocation
- [A Mixture Model for Learning Multi-Sense Word Embeddings](https://aclanthology.org/S17-1015.pdf), 2017.
- [Word2Sense: Sparse Interpretable Word Embeddings](https://aclanthology.org/P19-1570/), 2020.

### Non-Parametric (unperfectly, without parametic 'k' about a number of sense which words have)
- [Efficient Non-parametric Estimation of Multiple Embeddings per Word in Vector Space](https://aclanthology.org/D14-1113/), 2014.
  - CODE [original github](https://github.com/yauhen-info/NP-MSSG) and [reimplement?](https://github.com/jackee777/MSSG)
- [Multi Sense Embeddings from Topic Models](https://aclanthology.org/W19-7405/), 2019.
##### non-english
- [Modified multi-sense skip-gram using weighted context and x-means 가중 문맥벡터와 X-means 방법을 이용한 변형 다의어스킵그램](https://www.koreascience.or.kr/article/JAKO202123157173814.page), 2021.

### Non-Parametric (perfectly)
- [Do Multi-Sense Embeddings Improve Natural Language Understanding?](https://aclanthology.org/D15-1200/), 2015.

### Others
#### with Part-of-Speech
- [sense2vec - A Fast and Accurate Method for Word Sense Disambiguation In Neural Word Embeddings](https://arxiv.org/abs/1511.06388), 2015.


#### with Word Sense Disambiguation


## Introduction
For Japanese, [言語処理における分散表現学習のフロンティア](https://jsai.ixsq.nii.ac.jp/ej/index.php?action=pages_view_main&active_action=repository_action_common_download&item_id=2107&item_no=1&attribute_id=22&file_no=1&page_id=13&block_id=23), 2016.

# Evaluation (Including For Word Embedding)
## Survey
- [A Survey of Word Embeddings Evaluation Methods](https://arxiv.org/abs/1801.09536), 2018.
## Semantic Similairy Survey
- [An overview of word and sense similarity](https://www.cambridge.org/core/journals/natural-language-engineering/article/an-overview-of-word-and-sense-similarity/8516094B74E1B1A32EE64226B6E7C298), 2019.
- [Evolution of Semantic Similarity—A Survey](https://dl.acm.org/doi/pdf/10.1145/3440755?casa_token=uE-8vRWrfIUAAAAA:q80LvP7BBWBbiFON5Wcd9CXohiz043_CSFNtfWdM3B7z5r3I8T3ok03uBmmVx32jER6d-SVfVvN5), 2020.
## Intrinsic (Word Only)
### Word Analogy
ACL page https://aclweb.org/aclwiki/Analogy_(State_of_the_art).

### Word Similarity
ACL page https://aclweb.org/aclwiki/Similarity_(State_of_the_art).
#### RelatedNess
- [SemEval-2017 Task 2: Multilingual and Cross-lingual Semantic Word Similarity](https://aclanthology.org/S17-2002/)
  - [Sense identification data: A dataset for lexical semantics (SemEval-2017 Task 2 + with BabelNet ID)](https://www.sciencedirect.com/science/article/pii/S2352340920311616), 2020.
  - [Novel metrics for computing semantic similarity with sense embeddings](https://www.sciencedirect.com/science/article/abs/pii/S0950705120305025), 2020.
- [MSD-1030: A Well-built Multi-Sense Evaluation Dataset for Sense Representation Models](https://aclanthology.org/2020.lrec-1.711/), 2020.
#### Similarity
- [SimLex-999: Evaluating Semantic Models With (Genuine) Similarity Estimation](https://aclanthology.org/J15-4004/), 2015.
- [Multi-SimLex: A Large-Scale Evaluation of Multilingual and Crosslingual Lexical Semantic Similarity](https://direct.mit.edu/coli/article/46/4/847/97326/Multi-SimLex-A-Large-Scale-Evaluation-of), 2020.

## Intrinsic & Extrinsic (With Sentence, Slightly related paper is categorized to Application Use)
### Similarity
- SCWS [Improving Word Representations via Global Contextand Multiple Word Prototypes](https://aclanthology.org/P12-1092.pdf), 2012. # dupliates
- [SemEval-2020 Task 3: Graded Word Similarity in Context](https://aclanthology.org/2020.semeval-1.3.pdf), 2020.
 
### Binary Sense Detection (similar to Word Sense Disambiguation)
- [WiC: the Word-in-Context Dataset for Evaluating Context-Sensitive Meaning Representations](https://aclanthology.org/N19-1128/), 2019.
- [XL-WiC: A Multilingual Benchmark for Evaluating Semantic Contextualization](https://aclanthology.org/2020.emnlp-main.584/), 2020.
- [SemEval-2021 Task 2: Multilingual and Cross-lingual Word-in-Context Disambiguation (MCL-WiC)](https://aclanthology.org/2021.semeval-1.3/), 2021.
- [WiC-TSV: An Evaluation Benchmark for Target Sense Verification of Words in Context](https://aclanthology.org/2021.eacl-main.140/), 2021.

# Related Works
## Word Embedding
### Survey
- [Word Representation](https://link.springer.com/chapter/10.1007/978-981-15-5573-2_2), 2020.
### Training
- [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781), 2013.
- [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/abs/1310.4546), 2013.
- [GloVe: Global Vectors for Word Representation](https://aclanthology.org/D14-1162/), 2014.
- [Word Representations via Gaussian Embedding](https://arxiv.org/abs/1412.6623), 2014.
- [Poincaré Embeddings for Learning Hierarchical Representations](https://papers.nips.cc/paper/2017/hash/59dfa2df42d9e3d41f5b02bfc32229dd-Abstract.html), 2017.
- [Enriching Word Vectors with Subword Information](https://aclanthology.org/Q17-1010/), 2017.

## Contextual Word Embedding
survey page https://github.com/tomohideshibata/BERT-related-papers.
- [Deep Contextualized Word Representations](https://aclanthology.org/N18-1202/), 2018.
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423/), 2019.

## Contextual Sense Embedding
- []

## Word Sense Disambiguation
### Survey
- [Recent Trends in Word Sense Disambiguation: A Survey](https://helda.helsinki.fi/bitstream/handle/10138/333318/0593.pdf?sequence=1), 2021.
### Supervised

### Knowledge Based
#### Vector Based
- [Language Modelling Makes Sense: Propagating Representations through WordNet for Full-Coverage Word Sense Disambiguation](https://aclanthology.org/P19-1569.pdf), 2019. 

### Un-Supervised

## Word Semantic Change Detection
- [SemEval-2020 Task 1:Unsupervised Lexical Semantic Change Detection](https://aclanthology.org/2020.semeval-1.1.pdf), 2020.
- [Analysing Lexical Semantic Change with Contextualised Word Representations](https://aclanthology.org/2020.acl-main.365/), 2020.

## Dynamic Word Embedding

## Application Use
- [Contextualized Word Representations for Multi-Sense Embedding](https://aclanthology.org/Y18-1004.pdf), 2018.
  - [多義語分散表現の文脈化](https://www.jstage.jst.go.jp/article/jnlp/26/4/26_689/_article/-char/ja/), 2019.

## Annotated Corpus
- [SemCor](https://www.kaggle.com/nltkdata/semcor-corpus)

## Embedding Propery
- [Unsupervised Word Polysemy Quantification with Multiresolution Grids of Contextual Embeddings](https://arxiv.org/abs/2003.10224), 2020.
- [単語埋め込みによる論理演算](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/A6-3.pdf), 2021.
- [A Cluster-based Approach for Improving Isotropy in Contextual Embedding Space](https://aclanthology.org/2021.acl-short.73/), 2021.

### Brain and Language
- [Not all ambiguous words are created equal: An EEG investigation of homonymy and polysemy](https://www.sciencedirect.com/science/article/abs/pii/S0093934X12001125), 2012.

# Open Lexical DataBase
- [BabelNet: The automatic construction, evaluation and application of a wide-coverage multilingual semantic network](http://wwwusers.di.uniroma1.it/~navigli/pubs/AIJ_2012_Navigli_Ponzetto.pdf), 2012.
- [ConceptNet 5.5: An Open Multilingual Graph of General Knowledge](https://arxiv.org/pdf/1612.03975.pdf), 2016.
