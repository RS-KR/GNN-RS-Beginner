# GNN-RS-Beginner
> 넓고 얕게 GNN 기반 추천 훑어보기
<br>

**Keword**: Why GNN?, Survey, GCN, CF, Inductive Learning, Web-Scale, Graph Attention, Knowledge Graph


<details>
<summary><strong>Table of Contents</strong></summary>

- [Schedule](#schedule)
  * [1. OT + Understanding Convolutions on Graphs](#1-ot--understanding-convolutions-on-graphs)
  * [2. Why GNN for RS? &amp; Survey](#2-why-gnn-for-rs--survey)
  * [3. Neural Graph Collaborative Filtering](#3-neural-graph-collaborative-filtering)
  * [4. LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation](#4-lightgcn-simplifying-and-powering-graph-convolution-network-for-recommendation)
  * [5. Inductive Representation Learning on Large Graphs](#5-inductive-representation-learning-on-large-graphs)
  * [6. Graph Convolutional Neural Networks for Web-Scale Recommender Systems](#6-graph-convolutional-neural-networks-for-web-scale-recommender-systems)
  * [7. Graph Attention Networks](#7-graph-attention-networks)
  * [8. KGAT: Knowledge Graph Attention Network for Recommendation](#8-kgat-knowledge-graph-attention-network-for-recommendation)
  * [9~10. Selected Paper or Hands-on Session](#910-selected-paper-or-hands-on-session)
* [Furthermore](#furthermore)
</details>
<details>
<summary><strong>진행방식</strong></summary>
 
- Resource를 각자 보고 옵니다. 1, 2주차를 제외하고는 논문은 읽고 오지 않아도 됩니다.
- 사전에 질문이나 이야기해볼 거리를 Issue에 남깁니다.
- 전체적으로 이해가 안 갈 경우 사전에 신청받아 자세한 설명을 하는 시간을 갖습니다.
- 진행 시간은 1시간을 기본으로 합니다.
- 4주차, 8주차에는 참고할만한 영상이 없습니다. 지원자를 받아 발표 영상을 사전에 만듭니다.
- 9~10주차에는 
  - 2주차에 본 Survey에 소개된 분야에서 관심 있는 주제를 지원자를 받아 발표하거나
  - *[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)*, *[TensorFlow GNN](https://github.com/tensorflow/gnn)*, *[DEEP GRAPH LIBRARY](https://www.dgl.ai)* 핸즈온 세션을 진행합니다.

- 진행에 대한 구성원의 의견을 적극적으로 반영합니다.

</details>

<br>

# Schedule

### 1. OT + Understanding Convolutions on Graphs

- [Link](https://distill.pub/2021/understanding-gnns/)
- [토론 내용](https://github.com/RS-KR/GNN-RS-Beginner/labels/understanding-gnns)

<br>

### 2. Why GNN for RS? & Survey

- Learning and Reasoning on Graph for Recommendation
  - [PDF](https://next-nus.github.io/slides/tuto-cikm2019-public.pdf?fbclid=IwAR2hkJIQBsav5KalKqLQ3oBiIXfvbJ5-h5zxsydeHxjGQ5mvxxF_WuV-jNw)
  - Part1 까지

- Graph Neural Networks for Recommender Systems: Challenges, Methods, and Directions
  - [Paper](https://arxiv.org/abs/2109.12843), [Github](https://github.com/tsinghua-fib-lab/GNN-Recommender-Systems?fbclid=IwAR0e-32RP3Tx2SxpZJUM5FMNfO1NGE-sW4inVPfM1Q5nGCEiSOU2MJL0vfw#Recommendation-Stages)
  - Part 3까지

<br>

### 3. Neural Graph Collaborative Filtering

- [Paper](https://arxiv.org/abs/1905.08108), 인용수 555이상, SIGIR'19
- [video](https://www.youtube.com/watch?v=ce0LrvVblCU), [slide](https://www.slideshare.net/taeseonryu/neural-graph-collaborative-filtering-paper-review?qid=de05d94d-a9ab-4565-b21e-19ce6937f028&v=&b=&from_search=9)
- Code: [torch](https://github.com/RUCAIBox/RecBole/blob/master/recbole/model/general_recommender/ngcf.py)

<br>

### 4. LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation

- [Paper](https://arxiv.org/abs/2002.02126), 인용수 313이상, SIGIR'20
- [Resource](https://www.youtube.com/watch?v=5Wy-DL6tdkU&list=PLk2rTgnuPEyL80AjiSbCZLkivdUBWEMRV), [Slide](https://www.slideshare.net/ceradam/paperreview-lightgcn-simplifying-and-powering-graph-convolution-network-for-recommendation)
- Code: [torch](https://github.com/RUCAIBox/RecBole/blob/master/recbole/model/general_recommender/lightgcn.py)
- 추가자료
  - UltraGCN: Ultra Simplification of Graph Convolutional Networks for Recommendation

<br>

### 5. Inductive Representation Learning on Large Graphs

- GraphSAGE: Graph SAmpling and aggreGatE

- [Paper](https://arxiv.org/abs/1706.02216)
- [Resource](https://www.youtube.com/watch?v=rGn3bmoxnJU)

<br>

### 6. Graph Convolutional Neural Networks for Web-Scale Recommender Systems

- PinSage

- [Paper](https://arxiv.org/abs/1806.01973)

- [Resource](https://www.youtube.com/watch?v=qTfeWt95EmQ)

<br>

### 7. Graph Attention Networks

- GAT

- [Paper](https://arxiv.org/abs/1710.10903)
- [Resource](https://www.youtube.com/watch?v=shdNuppfClU)

<br>

### 8. KGAT: Knowledge Graph Attention Network for Recommendation

- [Paper](https://arxiv.org/abs/1905.07854)
- Resource: None

<br>

### 9~10. Selected Paper or Hands-on Session

- 투표!

<br>

# Furthermore

### Semi-Supervised Classification with Graph Convolutional Networks

- [Paper](https://openreview.net/forum?id=SJU4ayYgl)

- [Resource](https://www.youtube.com/watch?v=F-JPKccMP7k)
