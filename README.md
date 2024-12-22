In this project, various NLP tasks are conducted on the Answerable TyDi QA dataset [1]. Originally developed as part of a group project for an NLP course at DIKU in 2023, it has since then been expanded and refined.

To reproduce the results, clone the project and run:

  docker build -t tydi_qa .

followed by:

  docker-compose up

Each notebook corresponds to a section in the original problem description.

* section 1 provides basic statistics on the Tydi QA data set
* section 2 implements two language models
* section 3 implements three binary classifiers to predict whether a question is answerable or not
* sections 4, 5 and 6 are not part of the public repository 

[1] Jonathan H. Clark, Eunsol Choi, Michael Collins, Dan Garrette, Tom Kwiatkowski, Vitaly Nikolaev, and Jennimaria Palomaki. 2020. Tydi qa: A benchmark for information-seeking question answering in typologically diverse languages. Transactions of the Association for Computational Linguistics. Link: https://huggingface.co/datasets/copenlu/answerable_tydiqa.
