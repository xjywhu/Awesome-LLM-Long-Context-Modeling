# Large Language Model Based Long Context Modeling Papers and Blogs
<!--
[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/Xnhyacinth/Awesome-LLM-Long_Context_Modeling) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) -->
<div align="center">
 <p align="center">
 
   <a href="#1-Survey-Papers">📝 Papers</a> 
 
 </p>
</div>
<div align="center">

<!-- ![Build](https://img.shields.io/appveyor/build/gruntjs/grunt) -->
[![LICENSE](https://img.shields.io/github/license/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/Xnhyacinth/Long_Text_Modeling_Papers?color=blue)](https://github.com/Xnhyacinth/Long_Text_Modeling_Papers/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/Xnhyacinth/Long_Text_Modeling_Papers/pulls)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

This repo includes papers and blogs about Efficient Transformers, Length Extrapolation, Long Term Memory, Retrieval Augmented Generation(RAG), and Evaluation for Long Context Modeling.

🔥 Must-read papers for LLM-based Long Context Modeling.

Thanks for all the great contributors on GitHub!🔥⚡🔥

### Contents

* [1. Survey Papers](#1-Survey-Papers)
* [2. Efficient Transformers](#2-Efficient-Transformers)
  * [2.1 Sparse Transformers](#21-Sparse-Transformers)
  * [2.2 Linear Transformers](#22-Linear-Transformers)
  * [2.3 Hierarchical Transformers](#23-Hierarchical-Transformers)
* [3. Recurrent Transformers](#3-Recurrent-Transformers)
* [4. State Space Models](#4-State-Space-Models)
* [5. Length Extrapolation](#5-Length-Extrapolation)    🔥RoPE🔥
* [6. Long Term Memory](#6-Long-Term-Memory)
* [7. RAG](#7-RAG)
* [8. Compress](#8-Compress)
* [9. Benchmark and Evaluation](#9-Benchmark-and-Evaluation)
* [10. Blogs](#10-Blogs)
* [Acknowledgements](#acknowledgements)

# 📢 News

- **[2024.02.15]**
    - Paper: [Long-form evaluation of model editing](https://arxiv.org/abs/2402.09394)
    - Paper: [Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens](https://arxiv.org/abs/2401.17377)

- **[2024.02.01]**
    - Paper: [LOCOST: State-Space Models for Long Document Abstractive Summarization](https://arxiv.org/abs/2401.17919)
    - Paper: [Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens](https://arxiv.org/abs/2401.17377)

- **[2024.01.30]**
    - Paper: [Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation](https://arxiv.org/abs/2401.16421)
    - Paper: [LongFin: A Multimodal Document Understanding Model for Long Financial Domain Documents](https://arxiv.org/abs/2401.15050)
    - Paper: [PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models](https://arxiv.org/abs/2401.15042)
    - Paper: [LongHealth: A Question Answering Benchmark with Long Clinical Documents](https://arxiv.org/abs/2401.14490)
    - Paper: [MambaByte: Token-free Selective State Space Model](https://arxiv.org/abs/2401.13660)

- **[2024.01.26]**
    - Paper: [Commonsense-augmented Memory Construction and Management in Long-term Conversations via Context-aware Persona Refinement](https://arxiv.org/abs/2401.14215)

- **[2024.01.25]**
    - Paper: [With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation](https://arxiv.org/abs/2401.11504)

- **[2024.01.17]**
    - Paper: [The What, Why, and How of Context Length Extension Techniques in Large Language Models -- A Detailed Survey](https://arxiv.org/abs/2401.07872)
    - Paper: [Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization](https://arxiv.org/abs/2401.07793)
    - Paper: [Extending LLMs' Context Window with 100 Samples](https://arxiv.org/abs/2401.07004)
    - Paper: [E^2-LLM: Efficient and Extreme Length Extension of Large Language Models](https://arxiv.org/abs/2401.06951)
    - Paper: [DocFinQA: A Long-Context Financial Reasoning Dataset](https://arxiv.org/abs/2401.06915)

- **[2024.01.11]**
    - Paper: [Attendre: Wait To Attend By Retrieval With Evicted Queries in Memory-Based Transformers for Long Context Processing](https://arxiv.org/abs/2401.04881)
    - Paper: [Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models](https://arxiv.org/abs/2401.04695)
    - Paper: [The Impact of Reasoning Step Length on Large Language Models](https://arxiv.org/abs/2401.04925v1)
 
---

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## 1. Survey Papers

1. [**Efficient Transformers: A Survey.**](https://arxiv.org/abs/2009.06732) *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler.* Arxiv 2022.

2. [**A Survey on Long Text Modeling with Transformers.**](https://arxiv.org/abs/2302.14502) *Zican Dong, Tianyi Tang, Lunyi Li, Wayne Xin Zhao.* Arxiv 2023.

3. [**Neural Natural Language Processing for Long Texts: A Survey of the State-of-the-Art.**](https://arxiv.org/abs/2305.16259) *Dimitrios Tsirmpas, Ioannis Gkionis, Ioannis Mademlis, Georgios Papadopoulos.* Arxiv 2023.

4. [**Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey.**](https://arxiv.org/abs/2311.12351) *Yunpeng Huang, Jingwei Xu, Zixu Jiang, Junyu Lai, Zenan Li, Yuan Yao, Taolue Chen, Lijuan Yang, Zhou Xin, Xiaoxing Ma.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Strivin0311/long-llms-learning)](https://github.com/Strivin0311/long-llms-learning)

5. [**Length Extrapolation of Transformers: A Survey from the Perspective of Position Encoding.**](https://arxiv.org/abs/2312.17044) *Liang Zhao, Xiaocheng Feng, Xiachong Feng, Bing Qin, Ting Liu.* Arxiv 2024.

6. [**The What, Why, and How of Context Length Extension Techniques in Large Language Models -- A Detailed Survey.**](https://arxiv.org/abs/2401.07872) *Saurav Pawar, S.M Towhidul Islam Tonmoy, S M Mehedi Zaman, Vinija Jain, Aman Chadha, Amitava Das.* Arxiv 2024.

## 2. Efficient Transformers

### 2.1 Sparse Transformers

1. [**Generating Long Sequences with Sparse Transformers.**](https://arxiv.org/abs/1904.10509) *Rewon Child, Scott Gray, Alec Radford, Ilya Sutskever.* Arxiv 2019.

2. [**Blockwise selfattention for long document understanding.**](https://aclanthology.org/2020.findings-emnlp.232/) *Jiezhong Qiu, Hao Ma, Omer Levy, Wen-tau Yih, Sinong Wang, Jie Tang.* EMNLP 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xptree/BlockBERT)](https://github.com/xptree/BlockBERT)

3. [**Longformer: The Long-Document Transformer.**](https://arxiv.org/abs/2004.05150) *Iz Beltagy, Matthew E. Peters, Arman Cohan.* Arxiv 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/allenai/longformer)](https://github.com/allenai/longformer)

4. [**ETC: Encoding Long and Structured Inputs in Transformers.**](https://aclanthology.org/2020.emnlp-main.19/) *Joshua Ainslie, Santiago Ontanon, Chris Alberti, Vaclav Cvicek, Zachary Fisher, Philip Pham, Anirudh Ravula, Sumit Sanghai, Qifan Wang, Li Yang.* EMNLP 2020.

5. [**Big Bird: Transformers for Longer Sequences.**](https://papers.nips.cc/paper/2020/hash/c8512d142a2d849725f31a9a7a361ab9-Abstract.html) *Manzil Zaheer, Guru Guruganesh, Kumar Avinava Dubey, Joshua Ainslie, Chris Alberti, Santiago Ontanon, Philip Pham, Anirudh Ravula, Qifan Wang, Li Yang, Amr Ahmed.* NeurIPS 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/bigbird)](https://github.com/google-research/bigbird)

6. [**Reformer: The efficient transformer.**](https://arxiv.org/abs/2001.04451)  *Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya.* ICLR 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/reformer-pytorch)](https://github.com/lucidrains/reformer-pytorch)

7. [**Sparse Sinkhorn Attention.**](https://arxiv.org/abs/2002.11296) *Yi Tay, Dara Bahri, Liu Yang, Donald Metzler, Da-Cheng Juan.* ICML 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/sinkhorn-transformer)](https://github.com/lucidrains/sinkhorn-transformer)

8. [**Sparse and continuous attention mechanisms.**](https://arxiv.org/abs/2006.07214) *André F. T. Martins, António Farinhas, Marcos Treviso, Vlad Niculae, Pedro M. Q. Aguiar, Mário A. T. Figueiredo.* NIPS 2020. 

9. [**Efficient Content-Based Sparse Attention with Routing Transformers.**](https://aclanthology.org/2021.tacl-1.4/) *Aurko Roy, Mohammad Saffar, Ashish Vaswani, David Grangier.* TACL 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/routing-transformer)](https://github.com/lucidrains/routing-transformer)

10. [**LongT5: Efficient text-to-text transformer for long sequences.**](https://aclanthology.org/2022.findings-naacl.55/) *Mandy Guo, Joshua Ainslie, David Uthus, Santiago Ontanon, Jianmo Ni, Yun-Hsuan Sung, Yinfei Yang.* NAACL 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/longt5)](https://github.com/google-research/longt5)

11. [**Efficient Long-Text Understanding with Short-Text Models.**](https://aclanthology.org/2023.tacl-1.17/) *Maor Ivgi, Uri Shaham, Jonathan Berant.* TACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Mivg/SLED)](https://github.com/Mivg/SLED)

12. [**Parallel Context Windows for Large Language Models.**](https://aclanthology.org/2023.acl-long.352/) *Nir Ratner, Yoav Levine, Yonatan Belinkov, Ori Ram, Inbal Magar, Omri Abend, Ehud Karpas, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AI21Labs/Parallel-Context-Windows)](https://github.com/AI21Labs/Parallel-Context-Windows)

13. [**Unlimiformer: Long-Range Transformers with Unlimited Length Input.**](https://arxiv.org/abs/2305.01625) *Amanda Bertsch, Uri Alon, Graham Neubig, Matthew R. Gormley.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/unlimiformer)](https://github.com/abertsch72/unlimiformer)

14. [**Landmark Attention: Random-Access Infinite Context Length for Transformers.**](https://arxiv.org/abs/2305.16300) *Amirkeivan Mohtashami, Martin Jaggi* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/epfml/landmark-attention)](https://github.com/epfml/landmark-attention)

15. [**LONGNET: Scaling Transformers to 1,000,000,000 Tokens.**](https://arxiv.org/abs/2307.02486) *Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang, Nanning Zheng, Furu Wei.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LongNet)](https://github.com/kyegomez/LongNet)

16. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

17. [**Blockwise Parallel Transformer for Long Context Large Models.**](https://arxiv.org/abs/2305.19370) *Hao Liu, Pieter Abbeel.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/Blockwise-Parallel-Transformer)](https://github.com/lhao499/llm_large_context)

18. [**MEGABYTE: Predicting Million-byte Sequences with Multiscale Transformers.**](https://arxiv.org/abs/2305.07185) *Lili Yu, Dániel Simig, Colin Flaherty, Armen Aghajanyan, Luke Zettlemoyer, Mike Lewis.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/MEGABYTE-pytorch)](https://github.com/lucidrains/MEGABYTE-pytorch)

19. [**Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.**](https://arxiv.org/abs/2305.15805) *Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann.* Arxiv 2023. 

20. [**Long-range Language Modeling with Self-retrieval.**](https://arxiv.org/abs/2306.13421) *Ohad Rubin, Jonathan Berant.* Arxiv 2023. 

21. [**Max-Margin Token Selection in Attention Mechanism.**](https://arxiv.org/abs/2306.13596) *Davoud Ataee Tarzanagh, Yingcong Li, Xuechen Zhang, Samet Oymak.* Arxiv 2023. 

22. [**Chunk, Align, Select: A Simple Long-sequence Processing Method for Transformers.**](https://arxiv.org/abs/2308.13191) *Jiawen Xie, Pengyu Cheng, Xiao Liang, Yong Dai, Nan Du.* Arxiv 2023. 

23. [**Sparse Token Transformer with Attention Back Tracking.**](https://openreview.net/forum?id=VV0hSE8AxCw) *Heejun Lee, Minki Kang, Youngwan Lee, Sung Ju Hwang.* ICLR 2023. 

24. [**Empower Your Model with Longer and Better Context Comprehension.**](https://arxiv.org/pdf/2307.13365v2.pdf) *YiFei Gao, Lei Wang, Jun Fang, Longhua Hu, Jun Cheng.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yileijin/attention-transition)](https://github.com/yileijin/attention-transition)

25. [**Ring Attention with Blockwise Transformers for Near-Infinite Context.**](https://arxiv.org/pdf/2310.01889v1.pdf) *Hao Liu, Matei Zaharia, Pieter Abbeel.* Arxiv 2023.

26. [**Efficient Streaming Language Models with Attention Sinks.**](https://arxiv.org/pdf/2309.17453.pdf) *Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/streaming-llm)](https://github.com/mit-han-lab/streaming-llm)

27. [**HyperAttention: Long-context Attention in Near-Linear Time.**](https://arxiv.org/abs/2310.05869) *Insu Han, Rajesh Jayaram, Amin Karbasi, Vahab Mirrokni, David P. Woodruff, Amir Zandieh.* Arxiv 2023.

28. [**Fovea Transformer: Efficient Long-Context Modeling with Structured Fine-to-Coarse Attention.**](https://arxiv.org/pdf/2311.07102v1.pdf) *Ziwei He,Jian Yuan,Le Zhou,Jingwen Leng,Bo Jiang.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZiweiHe/Fovea-Transformer)](https://github.com/ZiweiHe/Fovea-Transformer)

### 2.2 Linear Transformers

1. [**Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention.**](https://arxiv.org/abs/2006.16236) *Angelos Katharopoulos, Apoorv Vyas, Nikolaos Pappas, François Fleuret.* ICML 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/idiap/fast-transformers)](https://github.com/idiap/fast-transformers)

2. [**Learning Fast Algorithms for Linear Transforms Using Butterfly Factorizations.**](https://arxiv.org/abs/1903.05895) *Tri Dao, Albert Gu, Matthew Eichhorn, Atri Rudra, Christopher Ré.* Arxiv 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/butterfly)](https://github.com/HazyResearch/butterfly)

3. [**Masked language modeling for proteins via linearly scalable long-context transformers.**](https://arxiv.org/abs/2006.03555) *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020. 

4. [**Rethinking attention with performers.**](https://arxiv.org/abs/2009.14794) *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/performer-pytorch)](https://github.com/lucidrains/performer-pytorch)

5. [**Linformer: Self-attention with linear complexity.**](https://arxiv.org/abs/2006.04768) *Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/linear-attention-transformer)](https://github.com/lucidrains/linear-attention-transformer)

6. [**Random Feature Attention.**](https://arxiv.org/abs/2103.02143) *Hao Peng, Nikolaos Pappas, Dani Yogatama, Roy Schwartz, Noah A. Smith, Lingpeng Kong.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Noahs-ARK/RFA)](https://github.com/Noahs-ARK/RFA)

7. [**Luna: Linear unified nested attention.**](https://arxiv.org/abs/2106.01540) *Xuezhe Ma, Xiang Kong, Sinong Wang, Chunting Zhou, Jonathan May, Hao Ma, Luke Zettlemoyer.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sooftware/luna-transformer)](https://github.com/sooftware/luna-transformer)

8. [**Fnet: Mixing tokens with fourier transforms.**](https://arxiv.org/abs/2105.03824) *James Lee-Thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jaketae/fnet)](https://github.com/jaketae/fnet)

9. [**Gated Linear Attention Transformers with Hardware-Efficient Training.**](https://arxiv.org/abs/2312.06635v2) *Songlin Yang, Bailin Wang, Yikang Shen, Rameswar Panda, Yoon Kim.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/berlino/gated_linear_attention)](https://github.com/berlino/gated_linear_attention)

### 2.3 Hierarchical Transformers

1. [**Neural Legal Judgment Prediction in English.**](https://aclanthology.org/P19-1424.pdf) *Ilias Chalkidis, Ion Androutsopoulos, Nikolaos Aletras.* ACL 2019. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/PolarisRisingWar/pytorch_ljp)](https://github.com/PolarisRisingWar/pytorch_ljp)

2. [**Hierarchical Neural Network Approaches for Long Document Classification.**](https://arxiv.org/abs/2201.06774) *Snehal Khandve, Vedangi Wagh, Apurva Wani, Isha Joshi, Raviraj Joshi.* ICML 2022. 

3. [**Hi-transformer: Hierarchical interactive transformer for efficient and effective long document modeling.**](https://arxiv.org/abs/2106.01040) *Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang.* ACL-IJCNLP 2021 

4. [**Erniesparse: Learning hierarchical efficient transformer through regularized self-attention.**](https://arxiv.org/abs/2203.12276) *Yang Liu, Jiaxiang Liu, Li Chen, Yuxiang Lu, Shikun Feng, Zhida Feng, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* Arxiv 2022.

## 3. Recurrent Transformers

1. [**Transformer-XL: Attentive language models beyond a fixed-length context.**](https://arxiv.org/abs/1901.02860) *Zihang Dai, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov.* ACL 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kimiyoung/transformer-xl)](https://github.com/kimiyoung/transformer-xl)

2. [**Compressive Transformers for Long-Range Sequence Modelling.**](https://arxiv.org/abs/1911.05507) *Jack W. Rae, Anna Potapenko, Siddhant M. Jayakumar, Timothy P. Lillicrap.* Arxiv 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/compressive-transformer-pytorch)](https://github.com/lucidrains/compressive-transformer-pytorch)

3. [**Memformer: The memory-augmented transformer.**](https://arxiv.org/abs/2010.06891) *Qingyang Wu, Zhenzhong Lan, Kun Qian, Jing Gu, Alborz Geramifard, Zhou Yu.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memformer)](https://github.com/lucidrains/memformer)

4. [**ERNIE-Doc: A Retrospective Long-Document Modeling Transformer.**](https://aclanthology.org/2021.acl-long.227/) *SiYu Ding, Junyuan Shang, Shuohuan Wang, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* ACL-IJCNLP 2021. 

5. [**Memorizing Transformers.**](https://arxiv.org/abs/2203.08913) *Yuhuai Wu, Markus N. Rabe, DeLesley Hutchins, Christian Szegedy.* Arxiv 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memorizing-transformers-pytorch)](https://github.com/lucidrains/memorizing-transformers-pytorch)

6. [**Recurrent Attention Networks for Long-text Modeling.**](https://aclanthology.org/2023.findings-acl.188/) *Xianming Li, Zongxi Li, Xiaotian Luo, Haoran Xie, Xing Lee, Yingbin Zhao, Fu Lee Wang, Qing Li.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/4ai/ran)](https://github.com/4ai/ran)

7. [**RWKV: Reinventing RNNs for the Transformer Era.**](https://arxiv.org/abs/2305.13048) *Bo Peng, Eric Alcaide, Quentin Anthony, Alon Albalak, Samuel Arcadinho, Huanqi Cao, Xin Cheng, Michael Chung, Matteo Grella, Kranthi Kiran GV, Xuzheng He, Haowen Hou, Przemyslaw Kazienko, Jan Kocon, Jiaming Kong, Bartlomiej Koptyra, Hayden Lau, Krishna Sri Ipsit Mantri, Ferdinand Mom, Atsushi Saito, Xiangru Tang, Bolun Wang, Johan S. Wind, Stansilaw Wozniak, Ruichong Zhang, Zhenyuan Zhang, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/BlinkDL/RWKV-LM)](https://github.com/BlinkDL/RWKV-LM)

8. [**Segmented Recurrent Transformer: An Efficient Sequence-to-Sequence Model.**](https://arxiv.org/abs/2305.16340) *Yinghan Long, Sayeed Shafayet Chowdhury, Kaushik Roy.* Arxiv 2023. 

9. [**Scaling Transformer to 1M tokens and beyond with RMT.**](https://arxiv.org/abs/2304.11062) *Aydar Bulatov, Yuri Kuratov, Mikhail S. Burtsev.* Arxiv 2023. 

10. [**Block-Recurrent Transformers.**](https://arxiv.org/abs/2203.07852) *DeLesley Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/block-recurrent-transformer-pytorch)](https://github.com/lucidrains/block-recurrent-transformer-pytorch)

11. [**TRAMS: Training-free Memory Selection for Long-range Language Modeling.**](https://arxiv.org/abs/2310.15494) *Haofei Yu, Cunxiang Wang, Yue Zhang, Wei Bi.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lwaekfjlk/TRAMS)](https://github.com/lwaekfjlk/TRAMS)

## 4. State Space Models

1. [**Mamba: Linear-Time Sequence Modeling with Selective State Spaces.**](https://arxiv.org/abs/2312.00752) *Albert Gu, Tri Dao.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/state-spaces/mamba)](https://github.com/state-spaces/mamba)

2. [**MoE-Mamba: Efficient Selective State Space Models with Mixture of Experts.**](https://arxiv.org/abs/2401.04081) *Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur.* Arxiv 2024.

3. [**MambaByte: Token-free Selective State Space Model.**](https://arxiv.org/abs/2401.13660) *Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush.* Arxiv 2024.

4. [**LOCOST: State-Space Models for Long Document Abstractive Summarization.**](https://arxiv.org/abs/2401.17919) *Florian Le Bronnec, Song Duong, Mathieu Ravaut, Alexandre Allauzen, Nancy F. Chen, Vincent Guigue, Alberto Lumbreras, Laure Soulier, Patrick Gallinari.* Arxiv 2024.

## 5. Length Extrapolation

1. [**RoFormer: Enhanced Transformer with Rotary Position Embedding.**](https://arxiv.org/abs/2104.09864) *Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZhuiyiTechnology/roformer)](https://github.com/ZhuiyiTechnology/roformer)

2. [**Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation.**](https://arxiv.org/abs/2108.12409) *Ofir Press, Noah A. Smith, Mike Lewis.* ICLR 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases)](https://github.com/ofirpress/attention_with_linear_biases)

3. [**KERPLE: Kernelized Relative Positional Embedding for Length Extrapolation.**](https://arxiv.org/abs/2205.09921) *Ta-Chung Chi, Ting-Han Fan, Peter J. Ramadge, Alexander I. Rudnicky.* Arxiv 2022. 

4. [**Dissecting Transformer Length Extrapolation via the Lens of Receptive Field Analysis.**](https://aclanthology.org/2023.acl-long.756/) *Ta-Chung Chi, Ting-Han Fan, Alexander I. Rudnicky, Peter J. Ramadge.* ACL 2023. 

5. [**A Length-Extrapolatable Transformer.**](https://aclanthology.org/2023.acl-long.816/) *Yutao Sun, Li Dong, Barun Patra, Shuming Ma, Shaohan Huang, Alon Benhaim, Vishrav Chaudhary, Xia Song, Furu Wei.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sunyt32/torchscale)](https://github.com/sunyt32/torchscale)

6. [**Randomized Positional Encodings Boost Length Generalization of Transformers.**](https://aclanthology.org/2023.acl-short.161/) *Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/randomized_positional_encodings)](https://github.com/google-deepmind/randomized_positional_encodings)

7. [**The Impact of Positional Encoding on Length Generalization in Transformers.**](https://arxiv.org/abs/2305.19466) *Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/McGill-NLP/length-generalization)](https://github.com/McGill-NLP/length-generalization)

8. [**Focused Transformer: Contrastive Training for Context Scaling.**](https://arxiv.org/abs/2307.03170) *Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/CStanKonrad/long_llama)](https://github.com/CStanKonrad/long_llama)

9. [**Extending Context Window of Large Language Models via Positional Interpolation.**](https://arxiv.org/abs/2306.15595) *Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian.* Arxiv 2023. 

10. [**Exploring Transformer Extrapolation.**](https://arxiv.org/abs/2307.10156) *Zhen Qin, Yiran Zhong, Hui Deng.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/Rpe)](https://github.com/OpenNLPLab/Rpe)

11. [**LM-Infinite: Simple On-the-Fly Length Generalization for Large Language Models.**](https://arxiv.org/pdf/2308.16137.pdf) *Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LM-Infinite)](https://github.com/kyegomez/LM-Infinite)

12. [**YaRN: Efficient Context Window Extension of Large Language Models.**](https://arxiv.org/abs/2309.00071) *Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jquesnelle/yarn)](https://github.com/jquesnelle/yarn)

13. [**PoSE: Efficient Context Window Extension of LLMs via Positional Skip-wise Training.**](https://arxiv.org/abs/2309.10400) *Dawei Zhu,Nan Yang,Liang Wang,Yifan Song,Wenhao Wu,Furu Wei,Sujian Li.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/PoSE)](https://github.com/dwzhu-pku/PoSE)

14. [**LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models.**](https://arxiv.org/abs/2309.12307) *Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han, Jiaya Jia.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/LongLoRA)](https://github.com/dvlab-research/LongLoRA)

15. [**Scaling Laws of RoPE-based Extrapolation.**](https://arxiv.org/abs/2310.05209) *Xiaoran Liu, Hang Yan, Shuo Zhang, Chenxin An, Xipeng Qiu, Dahua Lin.* Arxiv 2023.

16. [**Attention Alignment and Flexible Positional Embeddings Improve Transformer Length Extrapolation.**](https://arxiv.org/pdf/2311.00684v1.pdf) *Ta-Chung Chi,Ting-Han Fan,Alexander I. Rudnicky.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chijames/Attention-Alignment-Transformer-Length-Extrapolation)](https://github.com/chijames/Attention-Alignment-Transformer-Length-Extrapolation)

17. [**CoCA: Fusing position embedding with Collinear Constrained Attention for fine-tuning free context window extending.**](https://arxiv.org/abs/2309.08646) *Shiyi Zhu, Jing Ye, Wei Jiang, Qi Zhang, Yifan Wu, Jianguo Li.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/codefuse-ai/Collinear-Constrained-Attention)](https://github.com/codefuse-ai/Collinear-Constrained-Attention)

18. [**Structured Packing in LLM Training Improves Long Context Utilization.**](https://arxiv.org/abs/2312.17296) *Konrad Staniszewski, Szymon Tworkowski, Sebastian Jaszczur, Henryk Michalewski, Łukasz Kuciński, Piotr Miłoś.* Arxiv 2024.

19. [**LLM Maybe LongLM: Self-Extend LLM Context Window Without Tuning.**](https://arxiv.org/abs/2401.01325v1) *Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Zirui Liu, Chia-Yuan Chang, Huiyuan Chen, Xia Hu.* Arxiv 2024.

20. [**Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache.**](https://arxiv.org/abs/2401.02669) *Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li, Zhigang Ji, Yong Li, Wei Lin.* Arxiv 2024.

21. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

22. [**Extending LLMs' Context Window with 100 Samples.**](https://arxiv.org/abs/2401.07004) *Yikai Zhang, Junlong Li, Pengfei Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/Entropy-ABF)](https://github.com/GAIR-NLP/Entropy-ABF)

23. [**E^2-LLM: Efficient and Extreme Length Extension of Large Language Models.**](https://arxiv.org/abs/2401.06951) *Jiaheng Liu, Zhiqi Bai, Yuanxing Zhang, Chenchen Zhang, Yu Zhang, Ge Zhang, Jiakai Wang, Haoran Que, Yukang Chen, Wenbo Su, Tiezheng Ge, Jie Fu, Wenhu Chen, Bo Zheng.* Arxiv 2024.

24. [**With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation.**](https://arxiv.org/abs/2401.11504) *Y. Wang, D. Ma, D. Cai.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TemporaryLoRA/Temp-LoRA)](https://github.com/TemporaryLoRA/Temp-LoRA)

25. [**Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation.**](https://arxiv.org/abs/2401.16421) *Zhenyu He, Guhao Feng, Shengjie Luo, Kai Yang, Di He, Jingjing Xu, Zhi Zhang, Hongxia Yang, Liwei Wang.* Arxiv 2024.

26. [**Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens.**](https://arxiv.org/abs/2401.17377) *Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/liujch1998/infini-gram)](https://github.com/liujch1998/infini-gram)

## 6. Long Term Memory

1. [**Unleashing Infinite-Length Input Capacity for Large-scale Language Models with Self-Controlled Memory System.**](https://arxiv.org/abs/2304.13343) *Xinnian Liang, Bing Wang, Hui Huang, Shuangzhi Wu, Peihao Wu, Lu Lu, Zejun Ma, Zhoujun Li.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wbbeyourself/SCM4LLMs)](https://github.com/wbbeyourself/SCM4LLMs)

2. [**MemoryBank: Enhancing Large Language Models with Long-Term Memory.**](https://arxiv.org/abs/2305.10250) *Wanjun Zhong, Lianghong Guo, Qiqi Gao, He Ye, Yanlin Wang.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend)](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

3. [**Improve Long-term Memory Learning Through Rescaling the Error Temporally.**](https://arxiv.org/abs/2307.11462) *Shida Wang, Zhanglu Yan.* Arxiv 2023. 

4. [**Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models.**](https://arxiv.org/abs/2308.15022) *Qingyue Wang, Liang Ding, Yanan Cao, Zhiliang Tian, Shi Wang, Dacheng Tao, Li Guo.* Arxiv 2023. 

5. [**Empowering Working Memory for Large Language Model Agents.**](https://arxiv.org/abs/2312.17259) *Jing Guo, Nan Li, Jianchuan Qi, Hang Yang, Ruiqiao Li, Yuzhen Feng, Si Zhang, Ming Xu.* Arxiv 2024. 

6. [**Evolving Large Language Model Assistant with Long-Term Conditional Memory.**](https://arxiv.org/abs/2312.17257) *Ruifeng Yuan, Shichao Sun, Zili Wang, Ziqiang Cao, Wenjie Li.* Arxiv 2024. 

7. [**Commonsense-augmented Memory Construction and Management in Long-term Conversations via Context-aware Persona Refinement.**](https://arxiv.org/abs/2401.14215) *Hana Kim, Kai Tzu-iunn Ong, Seoyeon Kim, Dongha Lee, Jinyoung Yeo.* Arxiv 2024. 

## 7. RAG

1. [**Walking Down the Memory Maze: Beyond Context Limit through Interactive Reading.**](https://arxiv.org/abs/2310.05029) *Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz.* Arxiv 2023. 

2. [**Attendre: Wait To Attend By Retrieval With Evicted Queries in Memory-Based Transformers for Long Context Processing.**](https://arxiv.org/abs/2401.04881) *、Zi Yang, Nan Hua.* Arxiv 2024. 

## 8. Compress

1. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

2. [**Compressing Context to Enhance Inference Efficiency of Large Language Models.**](https://arxiv.org/abs/2310.06201) *Yucheng Li, Bo Dong, Chenghua Lin, Frank Guerin.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/liyucheng09/Selective_Context)](https://github.com/liyucheng09/Selective_Context)

3. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) *Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) *Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

5. [**System 2 Attention (is something you might need too).**](https://arxiv.org/abs/2311.11829) *Jason Weston, Sainbayar Sukhbaatar.* Arxiv 2023.

6. [**DSFormer: Effective Compression of Text-Transformers by Dense-Sparse Weight Factorization.**](https://arxiv.org/abs/2312.13211) *Rahul Chand, Yashoteja Prabhu, Pratyush Kumar.* Arxiv 2023.

7. [**Soaring from 4K to 400K: Extending LLM's Context with Activation Beacon.**](https://arxiv.org/abs/2401.03462) *Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

8. [**Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization.**](https://arxiv.org/abs/2401.07793) *Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

## 9. Benchmark and Evaluation

1. [**Long Range Arena : A Benchmark for Efficient Transformers.**](https://arxiv.org/abs/2011.04006) *Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler.* ICLR 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/long-range-arena)](https://github.com/google-research/long-range-arena)

2. [**LOT: A Story-Centric Benchmark for Evaluating Chinese Long Text Understanding and Generation.**](https://aclanthology.org/2022.tacl-1.25.pdf) *Jian Guan, Zhuoer Feng, Yamei Chen, Ruilin He, Xiaoxi Mao, Changjie Fan, Minlie Huang.* TACL 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LOT-LongLM)](https://github.com/thu-coai/LOT-LongLM)

3. [**SCROLLS: Standardized CompaRison Over Long Language Sequences.**](https://arxiv.org/abs/2201.03533) *Uri Shaham, Elad Segal, Maor Ivgi, Avia Efrat, Ori Yoran, Adi Haviv, Ankit Gupta, Wenhan Xiong, Mor Geva, Jonathan Berant, Omer Levy.* EMNLP 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/tau-nlp/scrolls)](https://github.com/tau-nlp/scrolls)

4. [**MuLD: The Multitask Long Document Benchmark.**](https://aclanthology.org/2022.lrec-1.392/) *George Hudson, Noura Al Moubayed.* LREC 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ghomasHudson/muld)](https://github.com/ghomasHudson/muld)

5. [**Lost in the Middle: How Language Models Use Long Contexts.**](https://arxiv.org/abs/2307.03172) *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nelson-liu/lost-in-the-middle)](https://github.com/nelson-liu/lost-in-the-middle)

6. [**L-Eval: Instituting Standardized Evaluation for Long Context Language Models.**](https://arxiv.org/abs/2307.11088) *Chenxin An, Shansan Gong, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenLMLab/LEval)](https://github.com/OpenLMLab/LEval)

7. [**LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding.**](https://arxiv.org/abs/2308.14508) *Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, Jiankai Tang, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

8. [**Content Reduction, Surprisal and Information Density Estimation for Long Documents.**](https://arxiv.org/abs/2309.06009) *Shaoxiong Ji, Wei Sun, Pekka Marttinen.* Arxiv 2023.

9. [**BAMBOO: A Comprehensive Benchmark for Evaluating Long Text Modeling Capacities of Large Language Models.**](https://arxiv.org/abs/2309.13345) *Zican Dong, Tianyi Tang, Junyi Li, Wayne Xin Zhao, Ji-Rong Wen.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/BAMBOO)](https://github.com/RUCAIBox/BAMBOO)

10. [**Retrieval meets Long Context Large Language Models.**](https://arxiv.org/abs/2309.13345) *Peng Xu, Wei Ping, Xianchao Wu, Lawrence McAfee, Chen Zhu, Zihan Liu, Sandeep Subramanian, Evelina Bakhturina, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2023.

11. [**LooGLE: Long Context Evaluation for Long-Context Language Models.**](https://arxiv.org/pdf/2311.04939v1.pdf) *Jiaqi Li, Mengmeng Wang, Zilong Zheng, Muhan Zhang.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/loogle)](https://github.com/bigai-nlco/loogle)

12. [**The Impact of Reasoning Step Length on Large Language Models.**](https://arxiv.org/abs/2401.04925v1) *Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du.* Arxiv 2024.

13. [**DocFinQA: A Long-Context Financial Reasoning Dataset.**](https://arxiv.org/abs/2401.06915) *Varshini Reddy, Rik Koncel-Kedziorski, Viet Dac Lai, Chris Tanner.* Arxiv 2024.

14. [**LongFin: A Multimodal Document Understanding Model for Long Financial Domain Documents.**](https://arxiv.org/abs/2401.15050) *Ahmed Masry, Amir Hajian.* Arxiv 2024.

15. [**PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models.**](https://arxiv.org/abs/2401.15042) *Haochen Tan, Zhijiang Guo, Zhan Shi, Lu Xu, Zhili Liu, Xiaoguang Li, Yasheng Wang, Lifeng Shang, Qun Liu, Linqi Song.* Arxiv 2024.

16. [**LongHealth: A Question Answering Benchmark with Long Clinical Documents.**](https://arxiv.org/abs/2401.14490) *Lisa Adams, Felix Busch, Tianyu Han, Jean-Baptiste Excoffier, Matthieu Ortala, Alexander Löser, Hugo JWL. Aerts, Jakob Nikolas Kather, Daniel Truhn, Keno Bressem.* Arxiv 2024.

17. [**Long-form evaluation of model editing.**](https://arxiv.org/abs/2402.09394) *Domenic Rosati, Robie Gonzales, Jinkun Chen, Xuemin Yu, Melis Erkan, Yahya Kayani, Satya Deepika Chavatapalli, Frank Rudzicz, Hassan Sajjad.* Arxiv 2024.

## 10. Blogs

1. [**Extending Context is Hard…but not Impossible†.**](https://kaiokendev.github.io/context) *kaiokendev.* 2023.

2. [**NTK-Aware Scaled RoPE.**](https://www.reddit.com/r/LocalLLaMA/comments/14lz7j5/ntkaware_scaled_rope_allows_llama_models_to_have/) *u/bloc97
.* 2023.

3. [**The Secret Sauce behind 100K context window in LLMs: all tricks in one place.**](https://blog.gopenai.com/how-to-speed-up-llms-and-use-100k-context-window-all-tricks-in-one-place-ffd40577b4c) *Galina Alperovich.* 2023.

4. [**Transformer升级之路：7、长度外推性与局部注意力.**](https://kexue.fm/archives/9431) *苏剑林(Jianlin Su).* 2023.

5. [**Transformer升级之路：9、一种全局长度外推的新思路.**](https://kexue.fm/archives/9603) *苏剑林(Jianlin Su).* 2023.

6. [**Transformer升级之路：12、无限外推的ReRoPE.**](https://kexue.fm/archives/9708) *苏剑林(Jianlin Su).* 2023.

7. [**Transformer升级之路：14、当HWFA遇见ReRoPE.**](https://kexue.fm/archives/9731) *苏剑林(Jianlin Su).* 2023.

8. [**Transformer升级之路：15、Key归一化助力长度外推.**](https://kexue.fm/archives/9859) *苏剑林(Jianlin Su).* 2023.

## Acknowledgements
Please contact me if I miss your names in the list, I will add you back ASAP!
