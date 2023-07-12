## Datasets
※No details on paper contents 

### Keywords
1. [Fake News/Misinformation](#fake-news-/-misinformation-datasets)
2. [Others (Ideology, Propaganda, etc.)](#others)

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

## Fake News / Misinformation Datasets

#### FakeNewsNet: A data repository with news content, social context and spatialtemporal information for studying fake news on social media

[[Paper]](https://arxiv.org/pdf/1809.01286.pdf)
[[Dataset]](https://github.com/KaiDMML/FakeNewsNet)

<details>
<summary>citation</summary>
- Kai Shu, Deepak Mahudeswaran, Suhang Wang, Dongwon Lee, and Huan Liu, "FakeNewsNet: A data repository with news content, social context and spatialtemporal information for studying fake news on social media," arXiv preprint arXiv:1809.01286, 2018.
</details>  
<details>
<summary>summary</summary>
- Famous Twitter dataset. Need to collect information on news articles, but some articles are lost and cannot be collected. It includes propagations before 2015, when quote retweeting was not implemented, so propagations after 2015 also include only non-quote retweets. Pytorch-Geometric provides UPFD dataset constructed using this dataset.
</details>  

#### FibVID: Comprehensive fake news diffusion dataset during the COVID-19 period

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0736585321001271)
[[Dataset]](https://github.com/merry555/FibVID)

<details>
<summary>citation</summary>
- Jisu Kim, Jihwan Aum, SangEun Lee, Yeonju Jang, Eunil Park, and Daejin Choi, "FibVID: Comprehensive fake news diffusion dataset during the COVID-19 period," Telematics and Informatics, vol.64, p.101688, 2021.
</details>  
<details>
<summary>summary</summary>
- Twitter dataset provided for training and testing propagation-based methods. Only including quotes.
</details>  


### Covid-19 Datasets for Multimodal Fake News Detection
<details>
<summary>click to check</summary>

#### ReCOVery: A multimodal repository for COVID-19 news credibility research

[[Paper]](https://dl.acm.org/doi/10.1145/3340531.3412880)
[[Dataset]](https://github.com/apurvamulay/ReCOVery)

<details>
<summary>citation</summary>
- Xinyi Zhou, Apurva Mulay, Emilio Ferrara, and Reza Zafarani, "ReCOVery: A multimodal repository for COVID-19 news credibility research," Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM '20), pp.3205–3212, 2020.
</details>  
<details>
<summary>summary</summary>
- Reliable / Unreliable (according to Media Bias / Fact Check)
</details>  

#### MMCoVaR: Multimodal COVID-19 vaccine focused data repository for fake news detection and a baseline architecture for classification

[[Paper]](https://dl.acm.org/doi/10.1145/3487351.3488346)
[[Dataset]](https://github.com/InfintyLab/MMCoVaR)

<details>
<summary>citation</summary>
- Mingxuan Chen, Xinqiao Chu, and K. P. Subbalakshmi, "MMCoVaR: Multimodal COVID-19 vaccine focused data repository for fake news detection and a baseline architecture for classification," Proceedings of the 2021 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM '21), pp.31–38, 2021.
</details>  
<details>
<summary>summary</summary>
- An extended dataset of Covid-19 misinformation dataset such as ReCOVery. Data types included in previous datasets are all-in-one in this. They also perform stance detection.
</details>  


#### The COVMis-Stance dataset: Stance detection on Twitter for COVID-19 misinformation

[[Paper]](https://arxiv.org/pdf/2204.02000.pdf)
[[Dataset]](https://github.com/yanfangh/covid-rumor-stance)

<details>
<summary>citation</summary>
- Yanfang Hou, Peter van der Putten, and Suzan Verberne, "The COVMis-Stance dataset: Stance detection on Twitter for COVID-19 misinformation," arXiv preprint arXiv:2204.02000, 2022.
</details>  
<details>
<summary>summary</summary>
- Specific to stance detection (Favor / Against / Neither). MMCoVaR precedes this? 
</details>  

</details>


## Others

#### Truth Social dataset

[[Paper]](https://ojs.aaai.org/index.php/ICWSM/article/view/22211)
[[Dataset]](https://zenodo.org/record/7522646)

<details>
<summary>citation</summary>
- Patrick Gerard, Nicholas Botzer, and Tim Weninger, "Truth Social dataset," Proceedings of the International AAAI Conference on Web and Social Media, vol.17, no.1, pp.1034-1040, 2023.
</details>  
<details>
<summary>summary</summary>
- First dataset to cover Truth Social. Propagations can be constructed?
</details>  


#### TIMME: Twitter ideology-detection via multi-task multi-relational embedding

[[Paper]](https://dl.acm.org/doi/10.1145/3394486.3403275)
[[Dataset]](https://github.com/PatriciaXiao/TIMME/tree/master/data)

<details>
<summary>citation</summary>
- Zhiping Xiao, Weiping Song, Haoyan Xu, Zhicheng Ren, and Yizhou Sun, "TIMME: Twitter ideology-detection via multi-task multi-relational embedding," Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, pp.2258–2268, 2020.
</details>  
<details>
<summary>summary</summary>
- Provide a dataset to construct a heterogeneous graph consisting of follows, favorites, replies, mentions, and retweets, and further attempted to detect ideology (Democrat/Republican) in a model using GNN
</details>  

#### Identifying ideologues: A global dataset on political leaders, 1945–2020

[[Paper]](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/identifying-ideologues-a-global-dataset-on-political-leaders-19452020/75E5853F10DB42AF0AB7895C0066D76B)
[[Dataset]](https://github.com/bastianherre/global-leader-ideologies)

<details>
<summary>citation</summary>
- Bastian Herre, "Identifying ideologues: A global dataset on political leaders, 1945–2020," British Journal of Political Science, vol.53, issue 2, pp.740–748, 2023.
</details>  
<details>
<summary>summary</summary>
- Analyze the ideology (leftist, centrist, rightist and non-ideological) of chief executives in OECD countries
</details>  


#### An information retrieval approach to building datasets for hate speech detection

[[Paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/hash/e00da03b685a0dd18fb6a08af0923de0-Abstract-round2.html)
[[Dataset]](https://github.com/mdmustafizurrahman/An-Information-Retrieval-Approach-to-Building-Datasets-for-Hate-Speech-Detection)

<details>
<summary>citation</summary>
- Md Mustafizur Rahman, Dinesh Balakrishnan, Dhiraj Murthy, Mucahid Kutlu, and Matt Lease, "An information retrieval approach to building datasets for hate speech detection," Proceedings of the Neural Information Processing Systems Track on Datasets and Benchmarks, vol.1, 2021.
</details>  
<details>
<summary>summary</summary>
- Hate (including hate words) / non-Hate. Maybe it'll help with how to annotate hate speech detection in the future.
</details>  


#### Exploring polarization of users behavior on Twitter during the 2019 South American protests -> Linguistic and news-sharing polarization during the 2019 South American protests

[[Paper]](https://arxiv.org/pdf/2104.05611.pdf)

-summary: The latter is unavailable for research.  


#### Learning to adapt domain shifts of moral values via instance weighting

[[Paper]](https://arxiv.org/pdf/2104.05611.pdf)
<details>
<summary>citation</summary>
- Xiaolei Huang, Alexandra Wormley, and Adam Cohen, "Learning to adapt domain shifts of moral values via instance weighting," Proceedings of the 33rd ACM Conference on Hypertext and Social Media (HT '22), pp.121–131, 2022.
</details>  
-summary: よく分からん．Perhaps you should research another paper for a definition of "Moral values".

