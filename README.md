# LLM4IR-Survey
This is the repo for the survey of LLM4IR.

## Paper List

### Query Rewriter

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2303.07678.pdf)\] 
2. **QUILL: Query Intent with Large Language Models using Retrieval Augmentation and Multi-stage Distillation**, _Srinivasan et al._, EMNLP 2022 (Industry). \[[Paper](https://aclanthology.org/2022.emnlp-industry.50.pdf)\]
3. **Generative and Pseudo-Relevant Feedback for Sparse, Dense and Learned Sparse Retrieval**, _Mackie et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2305.07477.pdf)]
4. **Generative Relevance Feedback with Large Language Models**, _Mackie et al._, SIGIR 2023 (short paper). \[[Paper](https://arxiv.org/pdf/2304.13157.pdf)\]
5. **GRM: Generative Relevance Modeling Using Relevance-Aware Sample Estimation for Document Retrieval**, _Mackie et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2306.09938.pdf)]
6. **Knowledge Refinement via Interaction Between Search Engines and Large Language Models**, _Feng et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2305.07402.pdf)]
7. **LARGE LANGUAGE MODELS ARE STRONG ZERO-SHOT RETRIEVER**, _Shen et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2304.14233.pdf)]
8. **Large Language Models Know Your Contextual Search Intent: A Prompting Framework for Conversational Search**, _Mao et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2303.06573.pdf)]
9. **Precise Zero-Shot Dense Retrieval without Relevance Labels**, _Gao et al._, ACL 2023.  \[[Paper](https://aclanthology.org/2023.acl-long.99.pdf)]
10. **Query Expansion by Prompting Large Language Models**, _Jagerman et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2305.03653.pdf)]
11. **Query Rewriting for Retrieval-Augmented Large Language Models**, _Ma et al._, arXiv 2023.  \[[Paper](https://arxiv.org/pdf/2305.14283.pdf)]

### Retriever
#### LLM for Producing Search Data
1. **InPars: Data Augmentation for Information Retrieval using Large Language Models**, _Bonifacio et al._, arXiv 2022. \[[Paper](https://arxiv.org/pdf/2202.05144.pdf)\]
2. **InPars-v2: Large Language Models as Efficient Dataset Generators for Information Retrieval**, _Jeronymo et al._, arXiv 2023. \[[Paper](https://arxiv.org/abs/2301.01820)\]
3. **Promptagator: Few-shot Dense Retrieval From 8 Examples**, _Dai et al._, ICLR 2023. \[[Paper](https://arxiv.org/pdf/2209.11755.pdf)\]
4. **AugTriever: Unsupervised Dense Retrieval by Scalable Data Augmentation**, _Meng et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2212.08841.pdf)\]
5. **UDAPDR: Unsupervised Domain Adaptation via LLM Prompting and Distillation of Rerankers**, _Saad-Falco et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2303.00807.pdf)\]
6. **Soft Prompt Tuning for Augmenting Dense Retrieval with Large Language Models**, _Peng et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2307.08303.pdf)\]
7. **Questions are all you need to train a dense passage retriever**, _Sachan et al._, ACL 2023. \[[Paper](https://aclanthology.org/2023.tacl-1.35.pdf)\]


#### LLM for Enhancing Retriever
1. **Text and Code Embeddings by Contrastive Pre-Training**, _Neelakantan et al._, arXiv 2022. \[[Paper](https://cdn.openai.com/papers/Text_and_Code_Embeddings_by_Contrastive_Pre_Training.pdf)\]
2. **Large dual encoders are generalizable retrievers**, _Ni et al._, ACL 2022. \[[Paper](https://aclanthology.org/2022.emnlp-main.669.pdf)\]
3. **Task-aware retrieval with instructions**, _Asai et al._, ACL 2023 (Findings). \[[Paper](https://aclanthology.org/2023.findings-acl.225.pdf)\]
4. **Transformer memory as a differentiable search index**, _Tay et al._, NeurIPS 2022. \[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/892840a6123b5ec99ebaab8be1530fba-Paper-Conference.pdf)\]
5. **Large Language Models are Built-in Autoregressive Search Engines**, _Ziems et al._, ACL 2023 (Findings). \[[Paper](https://aclanthology.org/2023.findings-acl.167.pdf)\]

### Re-ranker

#### Fine-tuning LLMs for Re-ranking
1. **Document Ranking with a Pretrained Sequence-to-Sequence Model**, _Nogueira et al._, EMNLP 2020 (Findings). \[[Paper](https://aclanthology.org/2020.findings-emnlp.63.pdf)\]
2. **Text-to-Text Multi-view Learning for Passage Re-ranking**, _Ju et al._, SIGIR 2021 (Short Paper). \[[Paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3463048)\] 
3. **The Expando-Mono-Duo Design Pattern for Text Ranking with Pretrained Sequence-to-Sequence Models**, _Pradeep et al._, arXiv 2021. \[[Paper](https://arxiv.org/pdf/2101.05667.pdf)\] 
4. **RankT5: Fine-Tuning T5 for Text Ranking with Ranking Losses**, _Zhuang et al._, SIGIR 2023 (Short Paper). \[[Paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3592047)\] 

#### Prompting LLMs for Re-ranking
1. **Holistic Evaluation of Language Models**, _Liang et al._, arXiv 2022. \[[Paper](https://arxiv.org/pdf/2211.09110.pdf)\] 
2. **Improving Passage Retrieval with Zero-Shot Question Generation**, _Sachan et al._, EMNLP 2022. \[[Paper](https://aclanthology.org/2022.emnlp-main.249.pdf)\] 
3. **Discrete Prompt Optimization via Constrained Generation for Zero-shot Re-ranker**, _Cho et al._, ACL 2023 (Findings). \[[Paper](https://aclanthology.org/2023.findings-acl.61.pdf)\] 
4. **Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent**, _Sun et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2304.09542.pdf)\] 
5. **Zero-Shot Listwise Document Reranking with a Large Language Model**, _Ma et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2305.02156.pdf)\] 
6. **Large Language Models are Effective Text Rankers with Pairwise Ranking Prompting**, _Qin et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2306.17563.pdf)\] 

#### Utilizing LLMs for Re-ranking Data Augmentation
1. **ExaRanker: Explanation-Augmented Neural Ranker**, _Ferraretto et al._, SIGIR 2023 (Short Paper). \[[Paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3592067)\]
2. **InPars-Light: Cost-Effective Unsupervised Training of Efficient Rankers**, _Boytsov et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2301.02998.pdf)\]
3. **Generating Synthetic Documents for Cross-Encoder Re-Rankers**, _Askari et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2305.02320.pdf)\]
4. **Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent**, _Sun et al._, arXiv 2023. \[[Paper](https://arxiv.org/pdf/2304.09542.pdf)\]

### Reader