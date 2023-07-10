---
title: All in One —— Multi-Task Prompting for GNN
feature_text: |
  ## ProG
  We propose a multi-task prompting approach for graph models, which enables the smooth integration of NLP's prompting concept into graph tasks. 
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "Allinone is  a multi-task prompting approach for graph models, which enables the smooth integration of NLP's prompting concept into graph tasks. "
---

Allinone is  a multi-task prompting approach for graph models, which enables the smooth integration of NLP's prompting concept into graph tasks. 

{% include button.html text="Fork it" icon="github" link="https://anonymous.4open.science/r/mpg" color="#0366d6" %} {% include button.html text="Buy me a coffee ☕️" link="https://buymeacoffee.com/daviddarnes#support" color="#f68140" %} {% include button.html text="Tweet it" icon="twitter" link="https://twitter.com/intent/tweet/?url=https://alembic.darn.es&text=Alembic%20-%20A%20Jekyll%20boilerplate%20theme&via=DavidDarnes" color="#0d94e7" %} {% include button.html text="Install Alembic ⚗️" link="https://github.com/daviddarnes/alembic#installation" %}
## Abstract
Recently, “pre-training and fine-tuning” has been adopted as a standard workflow for many graph tasks since it can take general graph
knowledge to relieve the lack of graph annotations from each application. However, graph tasks with node level, edge level, and
graph level are far diversified, making the pre-training pretext often
incompatible with these multiple tasks. This gap may even cause a
“negative transfer” to the specific application, leading to poor results.
Inspired by the prompt learning in natural language processing
(NLP), which has presented significant effectiveness in leveraging
prior knowledge for various NLP tasks, we study the prompting
topic for graphs with the motivation of filling the gap between pre-trained models and various graph tasks. In this paper, we propose a
novel multi-task prompting method for graph models. Specifically,
we first unify the format of graph prompts and language prompts
with the prompt token, token structure, and inserting pattern. In
this way, the prompting idea from NLP can be seamlessly introduced to the graph area. Then, to further narrow the gap between
various graph tasks and state-of-the-art pre-training strategies, we
further study the task space of various graph applications and re-formulate downstream problems to the graph-level task. Afterward,
we introduce meta-learning to efficiently learn a better initialization for the multi-task prompt of graphs so that our prompting
framework can be more reliable and general for different tasks. We
conduct extensive experiments, results from which demonstrate
the superiority of our method.
## Contributions

- We unify the prompt format in the language area and graph area, and further propose an effective graph prompt for multi-task settings
- We propose an effective way to reformulate node-level and edge-level tasks to graph-level tasks, which can further match many pre-training pretexts
- We introduce the meta-learning technique to our graph prompting study so that we can learn a reliable prompt for improving the multi-task performance
- We carefully analyze why our method works and confirm the effectiveness of our method via extensive experiments

## Conclusion
In this paper, we study the multi-task problem of graph prompts
with few-shot settings. We propose a novel method to reformulate
different-level tasks to unified ones and further design an effective
prompt graph with a meta-learning technique. We extensively evaluate the performance of our method. Experiments demonstrate the
effectiveness of our framework.
## Acknowledgements
This research is supported in part by project #MMT-p2-23 of the
Shun Hing Institute of Advanced Engineering, The Chinese University of Hong Kong, by grants from the Research Grant Council of
the Hong Kong Special Administrative Region, China (No. CUHK
14217622), NSFC (No. 61972087, No. 62206067, No. U1936205, No.
62172300, No. 62202336), Guangzhou-HKUST(GZ) Joint Funding
Scheme (No. 2023A03J0673), National Key R&D Program of China
(No. 2022YFB3104300, No. 2021YFC3300300), the Fundamental Research Funds for the Central Universities (No. ZD-21-202101), and
Open Research Projects of Zhejiang Lab (No. 2021KH0AB04). The
first author, Dr. Xiangguo Sun, in particular, wants to thank
his parents for their kind support during his tough period.
