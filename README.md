# Cross-lingual toxicity classifier

## Research question
Сan English data improve detection of toxicity in Russian?

## Methodology
Train a classifier on English and Russian data using cross-lingual model and compare with classifiers trained only on Russian.

## Cross-lingual model
XLM-RoBERTa.
- https://arxiv.org/pdf/1911.02116.pdf
- https://huggingface.co/transformers/model_doc/xlmroberta.html.

## Data
#### Russian
- https://www.kaggle.com/alexandersemiletov/toxic-russian-comments
- https://www.kaggle.com/blackmoon/russian-language-toxic-comments

#### English
- https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

## Conclusion
Check the project report (*report.pdf*) for results of experiments.
