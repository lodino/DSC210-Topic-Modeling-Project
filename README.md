# DSC210-Topic-Modeling-Project
### Course: DSC 210 Numerical Linear Algebra
### Instructor: Prof. Lily Weng

Codebase for Topic Modeling Project (DSC210 24 Fall)

<img width="50%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image5.png">

**Experiments for 20NewsGroup**: [https://colab.research.google.com/drive/1LfOxd-RU9siWoN3biaAvLOjfWcgr_vow?usp=sharing](https://colab.research.google.com/drive/1LfOxd-RU9siWoN3biaAvLOjfWcgr_vow?usp=sharing).

**Experiments for AGNews**: [https://colab.research.google.com/drive/1LfOxd-RU9siWoN3biaAvLOjfWcgr_vow?usp=sharing](https://colab.research.google.com/drive/1aUIYthRoOkT_3fqb-n0x9AHw7x6T86_5?usp=sharing).

**Instruction for Results Reproduction**: We advise the grader to run all the experiments on **Google Colab** with the basic CPU setting (no need for GPU). Running all the cells within the two notebooks following the sequence of codes in the two notebooks will give all the results we obtained. Note that experiments on AGNews, especially LDA and UMAP visualization, might take around 10-20 minutes each. We also included the copies of the above notebooks in this repository. Before running on the local, please run `python3 -m pip install -r requirements.txt` to install dependencies. 

Our experiments build upon the following implementations:
- [https://www.kaggle.com/code/sumantindurkhya/topic-modeling-on-20-newsgroup-data-lsa-and-lda](https://www.kaggle.com/code/sumantindurkhya/topic-modeling-on-20-newsgroup-data-lsa-and-lda).
- [https://github.com/silviatti/topic-model-diversity/blob/master/diversity_metrics.py](https://github.com/silviatti/topic-model-diversity/blob/master/diversity_metrics.py).
- [https://github.com/yashskhandelwal/latent_semantic_analysis](https://github.com/yashskhandelwal/latent_semantic_analysis).

We acknowledge and thank the authors for making their work publicly available.


## Results:
  
### The results on dataset [20Newsgroups](https://www.kaggle.com/datasets/crawford/20-newsgroups) :

Results of three metrics for three methods: 

<img width="40%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image8.png">

Top 5 Topics and Top 5 Words for NMF, LSA, and LDA:

<img width="50%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image11.png">

2-D visualization of the document-topic matrices:

<img width="90%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image6.png">

### The results on dataset [AGNews](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset) :

Results of three metrics for three methods: 

<img width="40%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image9.png">

Top 4 Topics and Top 5 Words for NMF, LSA, and LDA:

<img width="50%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image10.png">

2-D visualization of the document-topic matrices:

<img width="90%" src="https://github.com/lodino/DSC210-Topic-Modeling-Project/blob/main/images/image7.png">
