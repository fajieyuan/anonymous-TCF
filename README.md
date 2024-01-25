# Probing the Performance Limits of Text Recommender Models Using LLMs: Discoveries and Perspectives

This repository is intended for anonymous review purposes. We have only provided the extra results for review. Upon acceptance, we will make all the data available for download. Additionally, we will provide the full code of the paper strictly for research purposes.

## More results on NDCG10

**Table: Accuracy (NDCG@10) comparison of IDCF and TCF using DSSM and SASRec. _FR_ represents using frozen LM, while _FT_  represents using fine-tuned LM.**
![ID vs TCF](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_IDvsLLM_NDCG.jpg)

**Table: Warm item recommendation (NDCG@10). 20 means items < 20 interactions are removed. TCF\textsubscript{175B} uses the pre-extracted features from the 175B LM. Only SASRec backbone is reported.**
![Warm item](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_PLM_warm_NDCG.jpg)

**Table: TCF's results (NDCG@10)  with renowned text encoders in the last 10 years. Text encoders are frozen and the SASRec backbone is used. Notable  advances in NLP benefit RS.**
![TCF_last10years](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/Table_LMcompare_NDCG.jpg)

**TCF’s performance (y-axis: NDCG@10(%)) with 9 text encoders of increasing size (x-axis). SASRec (upper three subfigures) and DSSM (bottom three subfigures**
![Scaling_up_ndcg](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/scaling_up_ndcg.jpg)

**TCF with retrained LM vs frozen LM (y-axis: NDCG@10(%)), where only the top two layers are retrained. The 175B LM is not retrained due to its ultra-high computational cost.**
![FtvsFz_ndcg](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/finetune_vs_freeze_ndcg.jpg)

## ChatGPT4Rec
The output by ChatGPT in the figure below indicates that ChatGPT fully understands the recommendation request. 
![Verify_ChatGPT4Rec](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_0-cropped.jpg)

We also show the prompts for ChatGPT on MIND, HM, and Bili respectively with the figures below.

**Example of Task 1 for MIND**
![Mind_ChatGPT4Rec1](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_MIND_4-cropped.jpg)
**Example of Task 2 for MIND**
![Mind_ChatGPT4Rec2](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_MIND_10-cropped.jpg)

**Example of Task 1 for HM**
![HM_ChatGPT4Rec1](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_HM_4-cropped.jpg)
**Example of Task 2 for HM**
![HM_ChatGPT4Rec2](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_HM_10-cropped.jpg)

**Example of Task 1 for Bili**
![Bili_ChatGPT4Rec1](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_Bili_4-cropped.jpg)
**Example of Task 2 for Bili**
![Bili_ChatGPT4Rec2](https://github.com/anonymous-TCF/anonymous-TCF/blob/main/Figures/ChatGPT4Rec_Bili_10-cropped.jpg)


