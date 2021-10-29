# Multi_Sense_Embedding_Surve (Under construction)
Please commit a related paper for a good survey and discuss (I don't have a plan to publish a survey paper).

# Training
## Survey
- [From Word to Sense Embeddings: A Survey on Vector Representations of Meaning](https://arxiv.org/abs/1805.04032), 2018.
- [Word Embeddings: A Survey](https://arxiv.org/pdf/1901.09069.pdf), 2019.

## Use Open Lexical DataBase
### Concept Hierarchy (e.g. WORDNET, BabelNet)
#### Post Edit
- [Retrofitting Word Vectors to Semantic Lexicons](https://aclanthology.org/N15-1184/), 2015.
- [De-Conflated Semantic Representations](https://aclanthology.org/D16-1174/), 2016.
- [GenSense: A Generalized Sense Retrofitting Model](https://aclanthology.org/C18-1141/), 2018.
#### with Word Sense Disambiguation
- [Multi-sense embeddings through a word sense disambiguation process
Author links open overlay panel](https://www.sciencedirect.com/science/article/pii/S0957417419304269), 2019.

## From Corpora Only
### Parametric

### Non-Parametric (without parametic 'k' about a number of sense which words have)
#### k-means
- [Efficient Non-parametric Estimation of Multiple Embeddings per Word in Vector Space](https://aclanthology.org/D14-1113/), 2014.
  - CODE [original github](https://github.com/yauhen-info/NP-MSSG) and [reimplement?](https://github.com/jackee777/MSSG)
### Others
#### with Part-of-Speech
- [sense2vec - A Fast and Accurate Method for Word Sense Disambiguation In Neural Word Embeddings](https://arxiv.org/abs/1511.06388), 2015.
#### with Latent Dirichlet Allocation
#### with Word Sense Disambiguation


## Introduction
For Japanese, [言語処理における分散表現学習のフロンティア](https://jsai.ixsq.nii.ac.jp/ej/index.php?action=pages_view_main&active_action=repository_action_common_download&item_id=2107&item_no=1&attribute_id=22&file_no=1&page_id=13&block_id=23), 2016.

# Evaluation (Including For Word Embedding)
## Survey
- [A Survey of Word Embeddings Evaluation Methods](https://arxiv.org/abs/1801.09536), 2018.
## Intrinsic (Word Only)
### Word Analogy
ACL page https://aclweb.org/aclwiki/Analogy_(State_of_the_art).

### Word Similarity
ACL page https://aclweb.org/aclwiki/Similarity_(State_of_the_art).
- [MSD-1030: A Well-built Multi-Sense Evaluation Dataset for Sense Representation Models](https://aclanthology.org/2020.lrec-1.711/)
#### RelatedNess
#### Similarity

## Intrinsic & Extrinsic (With Sentence, Slightly related paper is categorized to Application Use)
### Similarity
### Binary Sense Detection
- [WiC: the Word-in-Context Dataset for Evaluating Context-Sensitive Meaning Representations](https://aclanthology.org/N19-1128/), 2019.
- [XL-WiC: A Multilingual Benchmark for Evaluating Semantic Contextualization](https://aclanthology.org/2020.emnlp-main.584/)
- []
# Related Works
## Word Embedding
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

## Word Sense Disambiguation

## Word Semantic Change Detection
- [Analysing Lexical Semantic Change with Contextualised Word Representations](https://aclanthology.org/2020.acl-main.365/), 2020.
### Dynamic Word Embedding

## Application Use
- [多義語分散表現の文脈化](https://www.jstage.jst.go.jp/article/jnlp/26/4/26_689/_article/-char/ja/), 2019.

## Annotated Corpus
- [SemCor](https://www.kaggle.com/nltkdata/semcor-corpus)

## Embedding Propery
- [Unsupervised Word Polysemy Quantification with Multiresolution Grids of Contextual Embeddings](https://arxiv.org/abs/2003.10224), 2020.
- [単語埋め込みによる論理演算](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/A6-3.pdf), 2021.
