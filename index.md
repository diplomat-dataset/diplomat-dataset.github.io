---
layout: article
lang: en
key: landing
full_width: false
comment: false
---


<div class="title">
Diplomat: A Dialogue Dataset for Situated PragMATic Reasoning <br>

<span class="info"> Anonymous Authors </span> <br>

<span class="info">NeurIPS 2023 Datasets and Benchmarks Track (Under Review) </span>
</div>

![](/assets/images/teaser.png)


Humans, as communicators, can understand the underlying meanings of figurative expressions and implicatures from dialogue utterances, which can be referred as a process of pragmatic reasoning.  Previous works commonly treat different implicit expressions, such as metaphor, sarcasm, as individual tasks. In this work, we introduce a new dataset, \dataset, aiming at a unified paradigm for pragmatic reasoning and situated conversational understanding. Our dataset is created using Amazon Meche, resulting in $4,177$ multi-turn dialogues. In company with the dataset, we propose three tasks: *Implication Identification and Reasoning*, *Conversational QA*, and *Zero-Shot Natural Language Inference* and benchmark them with state-of-the-art (SOTA) neural architectures. Experimental results demonstrate that: 1) \acp{llm} show poor performances in reasoning and identification. 2) Context understanding plays an important role in building benign huamn-machine interaction. 3) Current models defect on application of pragmatic reasoning. Hence, we call on more attention to improve the ability of context understanding as well as reasoning  capability.

## Punchline Dataset
The **Diplomat** dataset owns 4,177 data and covers a vocabulary with 48,900 words. More than that, human-annotated answers reach the amount of 6,494 and hold a vocabulary size of 20,000. Along with the dataset, we propose two tasks:  *Pragmatic Identification and Rationale* and *Conversational Question Answering*. The latter possesses 19,482 questions concerning the content of collected dialogues and the answers to the questions are written by humans. We benchmark those tasks with current SOTA models. Their performances are under our expectations. The best model achieves less than 0.70 accuracy score in the first task, and none of the models achieve more than 0.30 accuracy score for the second. Regarding the experimental results provided, the significance of pragmatic reasoning speaks for itself, therefore we hope to provide the community with a dataset for better studying the problem of pragmatic reasoning and give some insights into the current situation of generative language modeling.



## Paper

**Diplomat: A Dialogue Dataset for Situated PragMATic Reasoning** <br>
Anonymous Authors <br>
*NeurIPS 2023 Datasets and Benchmarks Track (Under Review)*

## Download

Our dataset is distributed under the [CC BY-NC-SA (Attribution-NonCommercial-ShareAlike)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. You can download our dataset from [Link here](link_here).


## Citation

```bibtex
@inproceedings{neurips2023punchline,
    title={Diplomat: A Dialogue Dataset for Situated PragMATic Reasoning},
    author={Anonymous Authors},
    booktitle={NeurIPS 2023 Datasets and Benchmarks Track (Under Review)},
    year={2023}
}
```

## References



## Contact

Please context [xxx@email.com](mailto: xxx@email.com) for questions about the Punchline dataset.
