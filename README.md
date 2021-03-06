# Sarcasm detection Using Commonsense 

Implementation for the paper "__*[Does Commonsense help in detecting Sarcasm?](https://arxiv.org/abs/2109.08588)*__", published at [Insights from Negative Results in NLP](https://insights-workshop.github.io/2021/cfp/) workshop, EMNLP 2021.

Authors: [Somnath Basu Roy Chowdhury](https://www.cs.unc.edu/~somnath/) and [Snigdha Chaturvedi](https://sites.google.com/site/snigdhac/)

## Pre-requisites

```
# create a clean conda env
conda create -n commonsense-sarcasm python==3.8 
source activate commonsense-sarcasm

pip install -r requirements.txt
```

Install COMET (trained on ATOMIC) package using the instructions provided in the following repository - [https://github.com/vered1986/comet-commonsense](https://github.com/vered1986/comet-commonsense).

## Steps:

1. Generate the data using the CreateDataset python notebook
2. Change in the config and dataset name in Baseline notebook to run and save the baseline model.
3. Run the commonsense infused model in the GCNModel notebook

## Citation

```
@inproceedings{basu-roy-chowdhury-chaturvedi-2021-commonsense,
    title = "Does Commonsense help in detecting Sarcasm?",
    author = "Basu Roy Chowdhury, Somnath  and
      Chaturvedi, Snigdha",
    booktitle = "Proceedings of the Second Workshop on Insights from Negative Results in NLP",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.insights-1.2",
    doi = "10.18653/v1/2021.insights-1.2",
}
```