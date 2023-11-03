# climate-science-fact-checking-system-using-BERT
A scientific statements fact-check and classification system

Three ipynb are provided.

(1) sb_rtv is for evidence retrieval, run it from top to bottom should download
base model, train with organized train dataset, and save the the mode config that
yields the highest f-score. Change predict to True to predict over test dataset.

(2) sb_cls is for evidence classification, run it from top to bottom should download
base model, train with organized train dataset, and save the the mode config that
yields the highest a-score. Change predict to True to predict over previous 
generated file.

(3) analyzer including data analyzing and graph plotting.

Packages used in this development:
Transformer pre-train models:
(1) bert-base-uncased
(2) bert-large-uncased
(3) roberta-base
(4) roberta-large
(5) distilbert-base-uncased