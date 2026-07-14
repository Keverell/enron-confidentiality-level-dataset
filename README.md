# Enron Confidentiality Level Dataset

A processed and annotated Enron email dataset for four-level confidentiality assessment, including offline training data and online continual learning data.

## Download

The datasets can be downloaded from the [GitHub Release page](https://github.com/zhangmengke0825/enron-confidentiality-level-dataset/releases/tag/dataset).

- [Download `offline_dataset.zip`](https://github.com/zhangmengke0825/enron-confidentiality-level-dataset/releases/download/dataset/offline_dataset.zip)
- [Download `online_dataset.zip`](https://github.com/zhangmengke0825/enron-confidentiality-level-dataset/releases/download/dataset/online_dataset.zip)

## Dataset Files

- `offline_dataset.zip`: Processed and annotated data used for offline model training, validation, and testing.
- `online_dataset.zip`: Chronologically organized data used for online continual learning and fixed evaluation.

The dataset uses four confidentiality levels: `ROUTINE`, `OPERATIONAL`, `SENSITIVE`, and `CRITICAL`.

The reviewer interaction signals included in the online dataset were generated through simulation and do not represent interaction records collected from real enterprise employees.

## Data Source

The email content was derived from the Enron Email Dataset and was processed, annotated, and reorganized for confidentiality level assessment.

## Citation

Citation information will be added after the associated paper is published.
