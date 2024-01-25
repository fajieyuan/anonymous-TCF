# Probing the Performance Limits of Text Recommender Models Using LLMs: Discoveries and Perspectives

This repository is intended for anonymous review purposes. We have only provided the extra results for review. Upon acceptance, we will make all the data available for download. Additionally, we will provide the full code of the paper strictly for research purposes.

## More results on NDCG10

**Table: Accuracy (NDCG@10) comparison of IDCF and TCF using DSSM and SASRec. _FR_ represents using frozen LM, while _FT_  represents using fine-tuned LM.**
![ID vs TCF](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_IDvsLLM_NDCG.jpg)

**Table: Warm item recommendation (NDCG@10). 20 means items < 20 interactions are removed. TCF\textsubscript{175B} uses the pre-extracted features from the 175B LM. Only SASRec backbone is reported.**
![Warm item](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_PLM_warm_NDCG.jpg)

**TCF's results (NDCG@10)  with renowned text encoders in the last 10 years. Text encoders are frozen and the SASRec backbone is used. Notable  advances in NLP benefit RS.**
![Warm item](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_LMcompare_NDCG.jpg)
