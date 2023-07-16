---
layout: article
lang: en
key: landing
full_width: false
comment: false
---


<div class="title">
DiPlomat: A Dialogue Dataset for Situated Pragmatic Reasoning <br>

<span class="info"> Anonymous Authors </span> <br>

<span class="info">NeurIPS 2023 Datasets and Benchmarks Track (Under Review) </span>
</div>

<br>

![](/assets/images/teaser.png)

<br>

Pragmatic reasoning plays a pivotal role in deciphering implicit meanings that frequently arise in real-life conversations and is essential for the development of communicative social agents. In this paper, we introduce a novel challenge, **DiPlomat**, aiming at benchmarking machines’ capabilities on pragmatic reasoning and situated conversational understanding. Compared with previous works that treat different figurative expressions (e.g. metaphor, sarcasm) as individual tasks, **DiPlomat** provides a cohesive framework towards general pragmatic understanding. Our dataset is created through the utilization of Amazon Mechanical Turk ( AMT ), resulting in a total of 4, 177 multi-turn dialogues. In conjunction with the dataset, we propose two tasks, Pragmatic Identification and Reasoning (PIR) and Conversational Question Answering (CQA). Experimental results with state-of-the-art (SOTA) neural architectures reveal several significant findings: 1) large language models (LLMs) exhibit poor performance in tackling this subjective domain; 2) comprehensive comprehension of context emerges as a critical factor for establishing benign human-machine interactions; 3) current models defect in the application of pragmatic reasoning. As a result, we call on more attention to improve the ability of context understanding, reasoning, and implied meaning modeling.


## Diplomat Dataset
The **Diplomat** dataset owns 4,177 data and covers a vocabulary of 48,900 words. More than that, human-annotated answers reach an amount of 6,494, hold a vocabulary size of 20,000, and cover 5 types of reasoning. Along with the dataset, we propose two tasks:  Pragmatic Identification and Reasoning (PIR) and Conversational Question Answering. The latter possesses 19,482 questions concerning the content of collected dialogues and the answers to the questions are written by humans. We benchmark those tasks with current SOTA models. Their performances are under our expectations. The best model achieves less than a 0.70 accuracy score in the first task, and none of the models achieve more than a 0.30 accuracy score for the second. Regarding the experimental results provided, the significance of pragmatic reasoning speaks for itself, therefore we hope to provide the community with a dataset for better studying the problem of pragmatic reasoning and give some insights into the current situation of generative language modeling.

<p align="center">
<img src="/assets/images/punchline_example.png" width="800"/>
</p>

## Tasks
We propose 2 tasks: Pragmatic Identification and Reasoning (PIR) and Conversational Question Answering (CQA). <be>

<div align="center">
|**TASK** | **Centered Ability**| **Brief Description**|
|   ---     |   ---     | --- | 
|     PIR    | *Pragmatic Awareness, Pragmatic Reasoning*           | Using pragmatic turns, and give a reason. |
| CQA | *Pragmatic Awareness, Pragmatic Reasoning, Application* | Answer a question which is design for the pragmatic turn.|
</div>

## Paper


**[DiPlomat: A Dialogue Dataset for Situated Pragmatic Reasoning](https://arxiv.org/abs/2306.09030)** (Paper link)<br>
Anonymous Authors <br>
*NeurIPS 2023 Datasets and Benchmarks Track (Under Review)*

## Download

Our dataset is distributed under the [CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. You can download our dataset from [Link here](https://drive.google.com/drive/folders/1Z33-6pXay9R-zRXJcFNtxaZMjTv9Zfs9?usp=share_link).

The following code is recommended to use for loading the dataset, while the [Huggingface transformers package](https://anaconda.org/conda-forge/transformers) is needed.
```python
from datasets import load_from_disk
dataset = load_from_disk(f"{dataset_directory_name}")
```


## Citation

```bibtex
@inproceedings{neurips2023diplomat,
    title={DiPlomat: A Dialogue Dataset for Situated Pragmatic Reasoning},
    author={Anonymous Authors},
    booktitle={NeurIPS 2023 Datasets and Benchmarks Track (Under Review)},
    year={2023}
}
```

## References



## Contact

Please context [lihengli@stu.pku.edu.cn](mailto: 2000017754@stu.pku.edu.cn) for questions about the Diplomat dataset.
