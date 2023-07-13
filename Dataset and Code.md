---
title: Datasets and Code
---

## Datasets
<div align="center">
<img src="/assets/Dataset.png" />

</div>
<p style="text-align:justify">We compare our methods with other approaches
on five public datasets including <a href="https://linqs.org/datasets/#cora">Cora</a>, CiteSeer , Reddit ,
Amazon, and Pubmed. Detailed statistics are presented
in Table 1 where the last column refers to the number of node
classes. To conduct edge-level and graph-level tasks, we sample
edges and subgraphs from the original data where the label of an
edge is decided by its two endpoints and the subgraph label follows
the majority of the subgraph nodes. For example, if nodes have 3
different classes, say 𝑐1, 𝑐2, 𝑐3, then edge-level tasks contain at least
6 categories (𝑐1, 𝑐2, 𝑐3, 𝑐1𝑐2, 𝑐1𝑐3, 𝑐2𝑐3). We also evaluate additional
graph classification and link prediction on more specialized datasets
where the graph label and the link label are inborn and not related
to any node </p>

## Code
We have sent our codes to github ,click <a href="https://github.com/sheldonresearch/ProG">here</a> to check.
