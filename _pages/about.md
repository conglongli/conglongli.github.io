---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m currently a Senior Researcher at [Microsoft DeepSpeed team](https://www.microsoft.com/en-us/research/project/deepspeed/), working on improving performance and efficiency of deep learning training and inference ([deepspeed.ai](https://www.deepspeed.ai/), [github repo](https://github.com/microsoft/DeepSpeed)). In general, I work on improving performance and resource efficiency of all kinds of computer systems via experimental research, data analysis, and algorithm/policy optimizations. My broad research interests lead to experience and publications in many areas including deep learning, similarity search, distributed caching systems, networks, and computer architecture.

I received Ph.D. in Computer Science from [Carnegie Mellon University](https://www.cmu.edu/) in 2020, advised by [Professor David G. Andersen](https://www.cs.cmu.edu/~dga/). I received both B.S. (2013) and M.S. (2014) in Computer Science from [Rice University](https://www.rice.edu/), advised by [Professor Alan L. Cox](https://profiles.rice.edu/faculty/alan-l-cox) and supported by the Graduate Research Fellowship.

Publications
======
1. [DeepSpeed Data Efficiency: Improving Deep Learning Model Quality and Training Efficiency via Efficient Data Sampling and Routing.](https://arxiv.org/abs/2212.03597)
  * **Conglong Li**, Zhewei Yao, Xiaoxia Wu, Minjia Zhang, Yuxiong He.
  * *[arXiv preprint arXiv:2212.03597](https://arxiv.org/abs/2212.03597).* \[[tutorial](https://www.deepspeed.ai/tutorials/data-efficiency/)\]\[[blog](https://www.deepspeed.ai/2022/12/11/data-efficiency.html)\]
1. [Random-LTD: Random and Layerwise Token Dropping Brings Efficient Training for Large-scale Transformers.](https://arxiv.org/abs/2211.11586)
  * Zhewei Yao, Xiaoxia Wu, **Conglong Li**, Connor Holmes, Minjia Zhang, Cheng Li, Yuxiong He.
  * *[arXiv preprint arXiv:2211.11586](https://arxiv.org/abs/2211.11586).* \[[tutorial](https://www.deepspeed.ai/tutorials/data-efficiency/#2-random-layerwise-token-dropping-random-ltd)\]
1. [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model.](https://arxiv.org/abs/2211.05100)
  * Teven Le Scao et al. (391 authors. I contributed to code and infrastructure to train BLOOM on the Jean Zay supercomputer as a member of the Engineering team.)
  * *[arXiv preprint arXiv:2211.05100](https://arxiv.org/abs/2211.05100).*
1. [Maximizing Communication Efficiency for Large-scale Training via 0/1 Adam.](https://arxiv.org/abs/2202.06009)
  * Yucheng Lu, **Conglong Li**, Minjia Zhang, Christopher De Sa, Yuxiong He.
  * *[arXiv preprint arXiv:2202.06009](https://arxiv.org/abs/2202.06009).* \[[tutorial](https://www.deepspeed.ai/tutorials/zero-one-adam/)\]
1. [1-bit LAMB: Communication Efficient Large-Scale Large-Batch Training with LAMB's Convergence Speed.](https://arxiv.org/abs/2104.06069)
  * **Conglong Li**, Ammar Ahmad Awan, Hanlin Tang, Samyam Rajbhandari, Yuxiong He.
  * In *[HiPC 2022](https://hipc.org/).* \[[tutorial](https://www.deepspeed.ai/tutorials/onebit-lamb/)\]\[[arxiv](https://arxiv.org/abs/2104.06069)\]
  * *[HiPC 2022 Best Paper Award (2 out of 34)](https://web.archive.org/web/20221222201832/https://hipc.org/advance-program/).*
1. [The Stability-Efficiency Dilemma: Investigating Sequence Length Warmup for Training GPT Models.](https://openreview.net/forum?id=JpZ5du_Kdh)
  * **Conglong Li**, Minjia Zhang, Yuxiong He.
  * In *[NeurIPS 2022](https://openreview.net/forum?id=JpZ5du_Kdh).* \[[tutorial](https://www.deepspeed.ai/tutorials/curriculum-learning/)\]\[[arxiv](https://arxiv.org/abs/2108.06084)\]
  * (This paper was titled "Curriculum Learning: A Regularization Method for Efficient and Stable Billion-Scale GPT Model Pre-Training" in early arxiv version.)
1. [XTC: Extreme Compression for Pre-trained Transformers Made Simple and Efficient.](https://openreview.net/forum?id=xNeAhc2CNAl)
  * Xiaoxia Wu, Zhewei Yao, Minjia Zhang, **Conglong Li**, Yuxiong He.
  * In *[NeurIPS 2022](https://openreview.net/forum?id=xNeAhc2CNAl).* \[[tutorial](https://www.deepspeed.ai/tutorials/model-compression/#3-tutorial-for-xtc-simple-yet-effective-compression-pipeline-for-extreme-compression)\]\[[arxiv](https://arxiv.org/abs/2206.01859)\]
  * *[NeurIPS 2022 Oral-Equivalent Paper (199 out of 2672)](https://web.archive.org/web/20221127222319/https://nips.cc/virtual/2022/events/highlighted).*
1. [ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers.](https://openreview.net/forum?id=f-fVCElZ-G1)
  * Zhewei Yao, Reza Yazdani Aminabadi, Minjia Zhang, Xiaoxia Wu, **Conglong Li**, Yuxiong He.
  * In *[NeurIPS 2022](https://openreview.net/forum?id=f-fVCElZ-G1).* \[[tutorial](https://www.deepspeed.ai/tutorials/model-compression/#2-tutorial-for-zeroquant-efficient-and-affordable-post-training-quantization)\]\[[arxiv](https://arxiv.org/abs/2206.01861)\]
1. [DeepSpeed-MoE: Advancing Mixture-of-Experts Inference and Training to Power Next-Generation AI Scale.](https://proceedings.mlr.press/v162/rajbhandari22a.html)
  * Samyam Rajbhandari, **Conglong Li**, Zhewei Yao, Minjia Zhang, Reza Yazdani Aminabadi, Ammar Ahmad Awan, Jeff Rasley, Yuxiong He.
  * In *[ICML 2022](https://proceedings.mlr.press/v162/rajbhandari22a.html).* \[[tutorial](https://www.deepspeed.ai/tutorials/mixture-of-experts-nlg/)\]\[[arxiv](https://arxiv.org/abs/2201.05596)\]
1. [1-bit Adam: Communication Efficient Large-Scale Training with Adam’s Convergence Speed.](http://proceedings.mlr.press/v139/tang21a.html)
  * Hanlin Tang, Shaoduo Gan, Ammar Ahmad Awan, Samyam Rajbhandari, **Conglong Li**, Xiangru Lian, Ji Liu, Ce Zhang, Yuxiong He.
  * In *[ICML 2021](http://proceedings.mlr.press/v139/tang21a.html).* \[[tutorial](https://www.deepspeed.ai/tutorials/onebit-adam/)\]\[[arxiv](https://arxiv.org/abs/2102.02888)\]
1. [Learned Adaptive Accuracy-Cost Optimization for Machine Learning Systems.](paper/thesis-2020.pdf)
  * **Conglong Li**.
  * *[Ph.D. Thesis](http://reports-archive.adm.cs.cmu.edu/anon/2020/abstracts/20-105.html).*
1. [Improving Approximate Nearest Neighbor Search through Learned Adaptive Early Termination.](paper/ann-sigmod2020.pdf)
  * **Conglong Li**, Minjia Zhang, David G. Andersen, Yuxiong He.
  * In *[ACM SIGMOD 2020](https://dl.acm.org/doi/abs/10.1145/3318464.3380600).* [[source code](https://github.com/efficient/faiss-learned-termination)]
1. [Scaling Video Analytics on Constrained Edge Nodes.](paper/filterforward-sysml2019.pdf)
  * Christopher Canel, Thomas Kim, Giulio Zhou, **Conglong Li**, Hyeontaek Lim, David G. Andersen, Michael Kaminsky, Subramanya R. Dulloor.
  * In *[SysML 2019](https://mlsys.org/Conferences/2019/).* (This conference was renamed to MLSys from 2020.) [[source code](https://github.com/viscloud/ff)]
1. [Better Caching in Search Advertising Systems with Rapid Refresh Predictions.](paper/adscache-www2018.pdf)
  * **Conglong Li**, David G. Andersen, Qiang Fu, Sameh Elnikety, Yuxiong He.
  * In *[WWW 2018](https://dl.acm.org/doi/abs/10.1145/3178876.3186176).*
1. [Workload Analysis and Caching Strategies for Search Advertising Systems.](paper/adscache-socc2017.pdf)
  * **Conglong Li**, David G. Andersen, Qiang Fu, Sameh Elnikety, Yuxiong He.
  * In *[ACM SoCC 2017](https://dl.acm.org/doi/abs/10.1145/3127479.3129255).*
1. [Using Indirect Routing to Recover from Network Traffic Scheduling Estimation Error.](paper/albedo-ancs2017.pdf)
  * **Conglong Li**, Matthew K. Mukerjee, David G. Andersen, Srinivasan Seshan, Michael Kaminsky, George Porter, Alex C. Snoeren.
  * In *[ACM/IEEE ANCS 2017](https://ieeexplore.ieee.org/abstract/document/7966896).*
1. [Scheduling Techniques for Hybrid Circuit/Packet Networks.](paper/solstice-conext2015.pdf)
  * He Liu, Matthew K. Mukerjee, **Conglong Li**, Nicolas Feltman, George Papen, Stefan Savage, Srinivasan Seshan, Geoffrey M. Voelker, David G. Andersen, Michael Kaminsky, George Porter, Alex C. Snoeren.
  * In *[ACM CoNEXT 2015](https://dl.acm.org/doi/abs/10.1145/2716281.2836126).*
1. [GD-Wheel: A Cost-Aware Replacement Policy for Key-Value Stores.](paper/gdwheel-eurosys2015.pdf)
  * **Conglong Li**, Alan L. Cox.
  * In *[ACM EuroSys 2015](https://dl.acm.org/doi/abs/10.1145/2741948.2741956).*
1. [Reducing DRAM Row Activations with Eager Read/Write Clustering.](paper/writeback-taco2013.pdf)
  * Myeongjae Jeon, **Conglong Li**, Alan L. Cox, Scott Rixner.
  * In *[ACM TACO 2013](https://dl.acm.org/doi/abs/10.1145/2541228.2555300).*
1. [GD-Wheel: A Cost-Aware Replacement Policy for Key-Value Stores.](paper/gdwheel-ladis2013.pdf)
  * **Conglong Li**, Alan L. Cox.
  * In *7th Workshop on Large-Scale Distributed Systems and Middleware (LADIS 2013).*

Last updated: 2022/12/30

