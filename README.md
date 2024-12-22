This project was created as part of the NLP course at DIKU 2023/2024. We perform several NLP tasks on the Answerable TyDi QA dataset [1].

To reproduce the results, clone the project and run:

  docker build -t tydi_qa .

followed by:

  docker-compose up

The project report was the original submission. Since then,the code has been restructured and changed to improve its clarity and organization.

Each notebook corresponds to a section in the original problem description. However, in the code, the tasks are performed on the English language for clarity. 

* section 1 provides basic statistics on the TyDa data set in the languages Arabic, Bengali and Indonesian
* section 2 implements 3 different language models
* section 3 implements three different binary classifiers to predict whether a question is answerable or not
* section 4 implements two transformer based QAs and IOB-tagging
* section 5 implements binary classification and a sequence labeller
* section 6 implements logistics regression with the BPEmb tokenizer (one for each language) - then each model is trained on one language and tested on the two others.


[1] Jonathan H. Clark, Eunsol Choi, Michael Collins, Dan Garrette, Tom Kwiatkowski, Vitaly Nikolaev, and Jennimaria Palomaki. 2020. Tydi qa: A benchmark for information-seeking question answering in typologically diverse languages. Transactions of the Association for Computational Linguistics. Link: https://huggingface.co/datasets/copenlu/answerable_tydiqa. 
