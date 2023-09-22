# Multi-Step-Deductive-Reasoning-Over-Natural-Language
This repository contains the code for the paper "Multi-Step Deductive Reasoning Over Natural Language: An Empirical Study on Out-of-Distribution Generalisation". This paper is the extention work from the poster [From Symbolic Logic Reasoning to Soft Reasoning: A Neural-Symbolic Paradigm](https://www.researchgate.net/publication/356695884_From_Symbolic_Logic_Reasoning_to_Soft_Reasoning_A_Neural-Symbolic_Paradigm). We add details for building the large-scale deeper multi-step reasoning dataset PARARULE-Plus and more experiments by adding the PARARULE-Plus in training. The goal is to build up an end-to-end neural based reasoning engine. The existing neural based models lack a reasoning engine, and they are not end-to-end training process. The repository also incorporates extra code for research as part of future work.

## Dataset
We use [PARARULE](https://allenai.org/data/ruletaker) from Allen AI institute. The dataset has been published on [Transformers as Soft Reasoners over Language](https://arxiv.org/abs/2002.05867), [CONCEPTRULES V1](https://drive.google.com/file/d/1lxoAvtcvqVCYiO8e3tENnrTQ1NNVtpjs/view?usp=sharing) and [CONCEPTRULES V2](https://drive.google.com/file/d/1lOCbW8bfZxj1RIzKDxn8xKg99XyYNj7z/view?usp=sharing) from [Tim Hartill](https://github.com/timhartill) and we published [PARARULE-Plus](https://github.com/Strong-AI-Lab/PARARULE-Plus) in this paper. You can download the data from the `dataset` folder. [PARARULE-Plus](https://github.com/Strong-AI-Lab/PARARULE-Plus) has also been collected by [LogiTorch](https://www.logitorch.ai/) which is a PyTorch-based library for logical reasoning on natural language. Furthermore, PARARULE-Plus has been merged by [OpenAI/Evals](https://github.com/openai/evals/pull/651) and collected by [ReasoningNLP](https://github.com/FreedomIntelligence/ReasoningNLP) and [Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers).

## Code
The main body of the code is following with my previous project [From Symbolic Logic Reasoning to Soft Reasoning: A Neural-Symbolic Paradigm](https://github.com/Strong-AI-Lab/A-Neural-Symbolic-Paradigm). We add more experiment analysis on CONCEPTRULES V1, CONCEPTRULE V2, and PARARULE-Plus. You can look and use the code in the `source code` folder.

If you want more details about this project, watch our [presentation recording](http://ilp.doc.ic.ac.uk/ijclr22_videos/NeSy%20Session%205%20-%20Thursday%2029th%20-%2014_40%20-%2015_50%20(BST)%20includes%20NeSy%20Invited%20Talk%20William%20Cohen.mp4).

 ## Citation
```
@inproceedings{bao2022multi,
  title={Multi-Step Deductive Reasoning Over Natural Language: An Empirical Study on Out-of-Distribution Generalisation},
  author={Qiming Bao and Alex Yuxuan Peng and Tim Hartill and Neset Tan and Zhenyun Deng and Michael Witbrock and Jiamou Liu},
  booktitle={Proceedings of the 16th International Workshop on Neural-Symbolic Learning and Reasoning as part of the 2nd International Joint Conference on Learning \& Reasoning (IJCLR 2022)},
  pages={202-217},
  month=sep,
  year={2022},
  address={Cumberland Lodge, Windsor Great Park, United Kingdom}
}
```
## Acknowledgement
 Thanks to the author of the [DeepLogic: Towards End-to-End Differentiable Logical Reasoning](https://github.com/nuric/deeplogic), for his advice and help in understanding and reproducing his work. This is of great help to me in completing this research and future research. Also Thanks [Tim Hartill](https://github.com/timhartill) who developed CONCEPTRULES V1 and CONCEPTRULES V2 datasets.
 
 Thanks to the help from [FacebookAI: fairseq](https://github.com/pytorch/fairseq) for my replication to the experiment result from [Transformers as Soft Reasoners over Language](https://arxiv.org/abs/2002.05867). Here is my replication notes [Finetuning RoBERTa on RACE tasks](https://github.com/14H034160212/fairseq/blob/master/examples/roberta/README.race.md) to the [Transformers as Soft Reasoners over Language](https://arxiv.org/abs/2002.05867).
 
 ## Other links
[DMN+] Dynamic Memory Networks for Visual and Textual Question Answering
https://arxiv.org/abs/1603.01417

[DMN] Ask Me Anything: Dynamic Memory Networks for Natural Language Processing 
https://arxiv.org/abs/1506.07285

[Hyperas] Bayesian optimization of automated hyperparameter tuning
https://github.com/maxpumperla/hyperas

[MemN2N] End-To-End Memory Networks
https://arxiv.org/abs/1503.08895

[MemN2N implementation on bAbI tasks with very nice interactive demo] End-To-End Memory Networks for Question Answering
https://github.com/14H034160212/MemN2N-babi-python

Memory Networks
https://arxiv.org/pdf/1410.3916.pdf
