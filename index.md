---
layout: article
lang: en
key: landing
full_width: false
comment: false
---


<div class="title">
DiploMAT: A Dialogue Dataset for Situated PragMATic Reasoning <br>

<span class="info"> Anonymous Authors </span> <br>

<span class="info">NeurIPS 2023 Datasets and Benchmarks Track (Under Review) </span>
</div>

<br>

![](/assets/images/teaser.png)

<br>

Pragmatic reasoning aims at resolving implicit meanings that commonly occur in real-life and is crucial for building communicative social agents.
We introduce a new benchmark, **Diplomat**, aiming at a unified paradigm for pragmatic reasoning and situated conversational understanding.  Compared with previous works that treat different figurative expressions (*e.g.*, metaphor, sarcasm) as individual tasks, **Diplomat** provides a unified understanding towards general pragmatic understanding. Our dataset is created using Amazon Mechanical Turk (AMT), resulting in 4,177 multi-turn dialogues. In company with the dataset, we propose two tasks: Pragmatic Identification and Reasoning and Conversational Question Answering. Experimental results with state-of-the-art (SOTA) neural architectures demonstrate that: 1) Large language models (LLMs) show poor performances in this subjective topic. 2) Context understanding is a crucial factor in building benign human-machine interaction. 3) Current models defect in the application of pragmatic reasoning. As a result, we call on more attention to improve the ability of context understanding, reasoning and implied meaning modeling.


## Diplomat Dataset
The **Diplomat** dataset owns 4,177 data and covers a vocabulary with 48,900 words. More than that, human-annotated answers reach the amount of 6,494 and hold a vocabulary size of 20,000. Along with the dataset, we propose two tasks:  Pragmatic Identification and Reasoning (PIR) and Conversational Question Answering. The latter possesses 19,482 questions concerning the content of collected dialogues and the answers to the questions are written by humans. We benchmark those tasks with current SOTA models. Their performances are under our expectations. The best model achieves less than 0.70 accuracy score in the first task, and none of the models achieve more than 0.30 accuracy score for the second. Regarding the experimental results provided, the significance of pragmatic reasoning speaks for itself, therefore we hope to provide the community with a dataset for better studying the problem of pragmatic reasoning and give some insights into the current situation of generative language modeling.


## Paper


**Diplomat: A Dialogue Dataset for Situated PragMATic Reasoning** <br>
Anonymous Authors <br>
*NeurIPS 2023 Datasets and Benchmarks Track (Under Review)*

## Download

Our dataset is distributed under the [CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. You can download our dataset from [Link here](https://drive.google.com/drive/folders/1Z33-6pXay9R-zRXJcFNtxaZMjTv9Zfs9?usp=share_link).

The following code is recommended to use for loading the dataset
'''
from datasets import load_from_disk
dataset = load_from_disk(f"{dataset_directory_name}")
'''


## Citation

```bibtex
@inproceedings{neurips2023diplomat,
    title={Diplo{MAT}: A Dataset for Situated Conversational Prag{MAT}ic Reasoning},
    author={Anonymous Authors},
    booktitle={NeurIPS 2023 Datasets and Benchmarks Track (Under Review)},
    year={2023}
}
```

## References



## Contact

Please context [2000017754@stu.pku.edu.cn](mailto: 2000017754@stu.pku.edu.cn) for questions about the Diplomat dataset.
