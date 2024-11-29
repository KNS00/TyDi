DISCLAIMER: The Notebooks in this repo are intended to complement the accompanying report by documenting results; they are structured for reproducibility rather than standalone readbility.

This project was created as part of the NLP course at DIKU 2023/2024. We perform several NLP tasks on the Answerable TyDi QA data set [1].

Each notebook corresponds to a section in the original problem description. The purpose of each notebook should be clear from the report. But overall,

* section 1 provides basic statistics on the TyDa data set in the languages Arabic, Bengali and Indonesian
* section 2 implements 3 different language models
* section 3 implements three different binary classifiers to predict whether a question is answerable or not
* section 4 implements two transformer based QAs and IOB-tagging
* section 5 implements binary classification and a sequence labeller
* section 6 implements logistics regression with the BPEmb tokenizer (one for each language) - then each model is trained on one language and tested on the two others.

[1] Jonathan H. Clark, Eunsol Choi, Michael Collins, Dan Garrette, Tom Kwiatkowski, Vitaly Nikolaev, and Jennimaria Palomaki. 2020. Tydi qa: A benchmark for information-seeking question answering in typologically diverse languages. Transactions of the Association for Computational Linguistics. Link: https://huggingface.co/datasets/copenlu/answerable_tydiqa. 
