## Graph Representation Learning

### Keywords
- [Graph Transformer](#graph-transformer)
- [Graph Structure Learning](#graph-structure-learning)
- [Structure-aware GNN](#structure-aware-gnn)
- [Multimodal Machine Learning](#multimodal-machine-learning)
- [Temporal Graph Learning](#temporal-graph-learning)

---

[//]: # (### Title &#40;Conference or Journal&#41;)

[//]: # ()
[//]: # ([[Paper]]&#40;&#41;)

[//]: # ([[Code]]&#40;&#41;)

[//]: # ([[bibtex]]&#40;&#41;)

[//]: # ()
[//]: # (<details><summary>citation</summary><div>)
[//]: # (<details><summary>summary</summary><div>)

[//]: # (  )
[//]: # (    )

[//]: # (- 調査中
)

[//]: # (    )

[//]: # (  </div></details>  
  )

[//]: # (  ```)

[//]: # (  調査中)

[//]: # (  ```)

[//]: # (- Keywords : `keyword`)

## Graph Transformer

#### Transformer for graphs: An overview from architecture perspective
[[Paper]](https://arxiv.org/pdf/2202.08455.pdf)
<details>
<summary>citation</summary>
- Erxue Min, Runfa Chen, Yatao Bian, Tingyang Xu, Kangfei Zhao, Wenbing Huang, Peilin Zhao, Junzhou Huang, Sophia Ananiadou, and Yu Rong, "Transformer for graphs: An overview from architecture perspective," arXiv preprint arXiv:2202.08455, 2022.
</details>
<details>
<summary>summary</summary>
- Research suitable tasks for each Graph Transformer
</details>  

#### Attending to graph transformers
[[Paper]](https://arxiv.org/pdf/2302.04181.pdf)
[[Code]](https://github.com/luis-mueller/probing-graph-transformers)
<details>
<summary>citation</summary>
- Luis Müller, Mikhail Galkin, Christopher Morris, and Ladislav Rampášek, "Attending to Graph Transformers," arXiv preprint arXiv:2302.04181, 2023.
</details>
<details>
<summary>summary</summary>
- Validating mitigation of over-smoothing
</details>  

## Graph Structure Learning

#### A survey on graph structure learning: Progress and opportunities
[[Paper]](https://arxiv.org/pdf/2103.03036.pdf)

<details>
<summary>citation</summary>
- Yanqiao Zhu, Weizhi Xu, Jinghao Zhang, Yuanqi Du, Jieyu Zhang, Qiang Liu, Carl Yang, and Shu Wu, "A survey on graph structure learning: Progress and opportunities," arXiv preprint arXiv:2103.03036, 2021.
</details>
<details>
<summary>summary</summary>
- Outline methods for obtaining fine-grained structural information.
</details>  

## Structure-aware GNN

#### Structure-aware transformer for graph representation learning
[[Paper]](https://proceedings.mlr.press/v162/chen22r.html)
[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/PNP)

<details>
<summary>citation</summary>
- Dexiong Chen, Leslie O’Bray, and Karsten Borgwardt, "Structure-Aware Transformer for Graph Representation Learning," Proceedings of the 39th International Conference on Machine Learning, vol.162 pp.3469-3489, 2022. 
</details>
<details>
<summary>summary</summary>
- Transformer does not consider structure (ignores edges), so structural information extracted by GNN is used for positional encoding.
</details>  

## Multimodal Machine Learning

#### Multimodal Machine Learning: A Survey and Taxonomy

[[Paper]](https://ieeexplore.ieee.org/document/8269806)
[[日本語概要もあります]](https://serenard.hatenablog.com/entry/2019/09/26/164727)

<details>
<summary>citation</summary>
- Tadas Baltrusaitis, Chaitanya Ahuja, and Louis-Philippe Morency, "Multimodal machine learning: A survey and taxonomy," IEEE Transactions on Pattern Analysis and Machine Intelligence, vol.41, issue 2, pp.423–443, 2019. 
</details>
<details>
<summary>summary</summary>
- Fundamental approach to utilizing multiple features (I mainly read the Fusion section.)
</details>


## Temporal Graph Learning

- Discrete Time Dynamic Graph


- Continuous Time Dynamic Graph

#### Inductive representation learning on temporal graphs (TGAT)

[[Paper]](https://openreview.net/forum?id=rJeW1yHYwH)
[[Code]](https://github.com/StatsDLMathsRecomSys/Inductive-representation-learning-on-temporal-graphs)

<details>
<summary>citation</summary>
- Da Xu, Chuanwei Ruan, Evren Korpeoglu, Sushant Kumar, and Kannan Achan, "Inductive representation learning on temporal graphs," International Conference on Learning Representations (ICLR), 2020. 
</details>
<details>
<summary>summary</summary>
- Estimates graph evolution by learning subgraphs starting from added/changed nodes using attentions.
</details>  

#### Temporal graph networks for deep learning on dynamic graphs (TGN)

[[Paper]](https://openreview.net/forum?id=rJeW1yHYwH)
[[Code]](https://github.com/twitter-research/tgn)
※ Pytorch-Geometricでも実装できそうだが難しそう
<details>
<summary>citation</summary>
- Emanuele Rossi, Ben Chamberlain, Fabrizio Frasca, Davide Eynard, Federico Monti, and Michael Bronstein, "Temporal graph networks for deep learning on dynamic graphs," Proceedings of the 37th International Conference on Machine Learning (ICML), 2020.
</details>
<details>
<summary>summary</summary>
- Introducing memory into TGAT to capture more global graph evolution
</details>  

[Other Papers:](https://github.com/S-K-KU/references/blob/main/papers/others_with_no_details/Temporal_Learning.md)  
