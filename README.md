# DS201 / Deep Learning

## About

* This is a college course project about Diacritic restoration problem in Vietnamese text using Deep learning based models.
* Techniques applied:
> * Word tokenizations
> * Models: RNN-LSTM, GRU, Bidirectional RNN approach
> * Metric: Bleu-score and accuracy

## Table of contents

> * [DS200.L21 / Big data](#ds202--data-science-thesis-1)
* [About](#about)
* [Table of contents](#table-of-contents)
* [Data source](#data-source)
* [Data preprocessing](#data-preprocessing)
* [Code](#code)
* [Report](#report)
* [References](#references)
* [For citation](#for-citation)

## Data source

* <a href="https://github.com/duyvuleo/VNTC" target="_blank">A Large-scale Vietnamese News Text Classification Corpus</a>
* This dataset was used in the following paper:

`A Comparative Study on Vietnamese Text Classification Methods
Cong Duy Vu Hoang, Dien Dinh, Le Nguyen Nguyen, Quoc Hung Ngo. In Proceedings of IEEE International Conference on Research, Innovation and Vision for the Future (RIVF 2007) (long), 2007.
`

## Data preprocessing

* The source data is split into single sentences giving a dataset of 500,000 data points.

## Code

* Feature extraction and models training (and so on) in this repo are implemented in Google Colab.
* All codes are organized in `name.ipynb` files.

## Report

* <a href="https://github.com/githubbinh/DS201-Deeplearning/blob/main/report.pdf" target="_blank">Report</a>
* <a href="https://github.com/githubbinh/DS201-Deeplearning/blob/main/vn_report.pdf" target="_blank">Report (Vietnamese version)</a>

## References

* All references are cited in the report file.

## For citation

```
@INPROCEEDINGS{9530818,
author={Tran, Quang-Linh and Lam, Gia-Huy and Duong, Van-Binh and Do, Trong-Hop},
booktitle={2021 IEEE International Conference on Communication, Networks and Satellite (COMNETSAT)},
title={A Study on Diacritic Restoration Problem in Vietnamese Text using Deep Learning based Models},
year={2021},  volume={},  number={},  pages={306-310},  doi={10.1109/COMNETSAT53002.2021.9530818}}
```
