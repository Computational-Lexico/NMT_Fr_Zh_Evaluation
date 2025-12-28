# Evaluation of Neural Machine Translation (French–Chinese)

This repository contains code and sample data for evaluating neural machine
translation systems on a French–Chinese medical corpus.

The study compares a fine-tuned mBART model with Google Translate and ChatGPT,
using both automatic metrics (BLEU, METEOR, chrF, TER, BERTScore)
and human evaluation following the MQM human annotations.

## Contents

- `Evaluation_of_MT_ MQM .ipynb`: main notebook (TMX parsing, alignment, evaluation)
- `requirements.txt`: Python dependencies
- `data/`: sample data for demonstration purposes

## Data

Due to licensing and ethical constraints, the full corpus (OPUS TICO-19)
is not redistributed.
Only a small sample of sentence pairs is provided to illustrate the pipeline.

## Reproducibility

The notebook can be run in Google Colab or locally with Python 3.9+.

## Author

Chen Lian 陈恋 （LLL, University of Orléans / CRLAO – CNRS / INALCO)
