# SSM-BERT

Predicting Software Functional Size Using Natural Language Processing: An Exploratory Case Study

## Installation

We provide a package file (``environment.yml``) to create a new environment (``ssm-bert``) using conda:

```bash
$ git clone https://github.com/smtnkc/ssm-bert.git
$ cd ssm-bert/
$ conda env create -f environment.yml
$ conda activate ssm-bert
```

## Running instructions:

1. Import a pre-trained BERT model:
  * ``BERT`` is generic model ([bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased))
  * ``BERT_SE`` is [Fávero's](https://github.com/elianedb/BERT_SE/) domain-adapted model ([BERT_SE](https://drive.google.com/drive/folders/1I9IBzZwbUCaRdMKZtwSc0IMdVDgW78v3?usp=sharing))
2. Add your dataset under ``data`` directory. Use `UserStory_1007.csv` as template.
3. Run train and test using ``ssm.ipynb`` notebook.