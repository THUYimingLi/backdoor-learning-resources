# Awesome Backdoor Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome Backdoor Learning resources (**Still under development**). Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers).

#### Why Backdoor Learning?
Backdoor learning is an emerging research area, which discusses the security issues of the training process towards machine learning algorithms. It is critical for safely adopting third-party algorithms in reality.  Although backdoor learning shares certain similarity with adversarial learning (which concentrates on the security issues of the inference process), they do have essential differences and can be easily distinguished.

Note: *Backdoor* is also commonly called the *Neural Trojan*.


## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help to contribute this list by contacting [me](http://liyiming.tech) or add [pull request](https://github.com/THUYimingLi/awesome-backdoor-learning/pulls)

Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents
- [Survey](#survey)
- [Image Classification](#image-classification) 
  - [Poisoning-based Attack](#poisoning-based-attack)
  - [Non-poisoning-based Attack](#non-poisoning-based-attack)
  - [Backdoor Defense](#backdoor-defense)
- [Attack and Defense Towards Other Tasks](#attack-and-defense-towards-other-tasks)  
- [Properties Discussion and Evaluation](#properties-discussion-and-evaluation)
- [Application in other Tasks](#application-in-other-tasks)


## Survey
- A Survey on Neural Trojans. 
  [[pdf]](https://eprint.iacr.org/2020/201.pdf)
  - Yuntao Liu, Ankit Mondal, Abhishek Chakraborty, Michael Zuzak, Nina Jacobsen, Daniel Xing, and Ankur Srivastava. 2020.

## Image Classification
### Poisoning-based Attack
#### 2020
- Hidden Trigger Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1910.00033.pdf)
  [[code]](https://github.com/UMBCvision/Hidden-Trigger-Backdoor-Attacks)
  - Aniruddha Saha, Akshayvarun Subramanya, and Hamed Pirsiavash. *AAAI 2020*.

- Bypassing Backdoor Detection Algorithms in Deep Learning.
  [[pdf]](https://arxiv.org/pdf/1905.13409.pdf)
  - Te Juin Lester Tan, and Reza Shokri. *EuroS&P 2020*.

- Backdoor Embedding in Convolutional Neural Network Models via Invisible Perturbation.
  [[pdf]](https://arxiv.org/pdf/1808.10307.pdf)
  - Cong Liao, Haoti Zhong, Anna Squicciarini, Sencun Zhu, and David Miller. *ACM CODASPY 2020*.

- Live Trojan Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2004.11370.pdf)
  [[code]](https://github.com/robbycostales/live-trojans)
  - Robby Costales, Chengzhi Mao, Raphael Norwitz, Bryan Kim, and Junfeng Yang. *CVPRW 2020*.

- Backdooring and Poisoning Neural Networks with Image-Scaling Attacks.
  [[pdf]](https://arxiv.org/pdf/2003.08633.pdf)
  - Erwin Quiring, and Konrad Rieck. *IEEE DLS 2020*.

- Blind Backdoors in Deep Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2005.03823.pdf)
  - Eugene Bagdasaryan, and Vitaly Shmatikov. arXiv 2020.

- Dynamic Backdoor Attacks Against Machine Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2003.03675.pdf)
  - Ahmed Salem, Rui Wen, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv 2020.  

#### 2019
- A New Backdoor Attack in CNNS by Training Set Corruption Without Label Poisoning.
  [[pdf]](https://arxiv.org/pdf/1902.11237.pdf)
  - M.Barni, K.Kallas, and B.Tondi. *ICIP 2019*.
  
- Label-Consistent Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1912.02771.pdf)
  - Alexander Turner, Dimitris Tsipras, and Aleksander Madry. arXiv 2019.

- Invisible Backdoor Attacks Against Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1909.02742.pdf)
  - Shaofeng Li, Benjamin Zi Hao Zhao, Jiahao Yu, Minhui Xue, Dali Kaafar, and Haojin Zhu. arXiv 2019.
  
#### 2017
- BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain.
  [[pdf]](https://arxiv.org/pdf/1708.06733.pdf)
  [[journal]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8685687)
  - Tianyu Gu, Brendan Dolan-Gavitt, and Siddharth Garg. arXiv 2017 (*IEEE Access 2019*).

- Targeted Backdoor Attacks on Deep Learning Systems Using Data Poisoning.
  [[pdf]](https://arxiv.org/pdf/1712.05526.pdf)
  [[code]](https://github.com/GeorgePisl/backdoor-attacks-based-on-deep-learning)
  - Xinyun Chen, Chang Liu, Bo Li, Kimberly Lu, and Dawn Song. arXiv 2017.
  
- Trojaning Attack on Neural Networks.
  [[pdf]](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=2782&context=cstech)
  - Yingqi Liu, Shiqing Ma, Yousra Aafer, Wen-Chuan Lee, and Juan Zhai. *NDSS 2017*.


### Non-poisoning-based Attack  
- An Embarrassingly Simple Approach for Trojan Attack in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2006.08131.pdf)
  [[code]](https://github.com/trx14/TrojanNet)
  - Ruixiang Tang, Mengnan Du, Ninghao Liu, Fan Yang, and Xia Hu. *KDD 2020*.

- TBT: Targeted Neural Network Attack with Bit Trojan.
  [[pdf]](https://arxiv.org/abs/1909.05193)
  [[code]](https://github.com/adnansirajrakin/TBT-CVPR2020)
  - Adnan Siraj Rakin, Zhezhi He, and Deliang Fan. *CVPR 2020*.

- TrojanNet: Embedding Hidden Trojan Horse Models in Neural Network.
  [[pdf]](https://arxiv.org/pdf/2002.10078.pdf)
  - Chuan Guo, Ruihan Wu, and Kilian Q. Weinberger. arXiv 2020.

- Backdooring Convolutional Neural Networks via Targeted Weight Perturbations.
  [[pdf]](https://arxiv.org/pdf/1812.03128.pdf)
  - Jacob Dumford, and Walter Scheirer. arXiv 2018.
  
### Backdoor Defense
#### 2020

#### 2019

#### 2018


## Attack and Defense Towards Other Tasks
### 2020
- Backdoor Attacks against Transfer Learning with Pre-trained Deep Learning Models.
  [[pdf]](https://arxiv.org/pdf/2001.03274.pdf)
  - Shuo Wang, Surya Nepal, Carsten Rudolph, Marthie Grobler, Shangyu Chen, and Tianle Chen. *IEEE Transactions on Services Computing 2020*.

- Weight Poisoning Attacks on Pre-trained Models.
  [[pdf]](https://arxiv.org/pdf/2004.06660.pdf)
  [[code]](https://github.com/neulab/RIPPLe)
  - Keita Kurita, Paul Michel, and Graham Neubig. *ACL 2020*.

- Clean-Label Backdoor Attacks on Video Recognition Models.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.pdf)
  - Shihao Zhao, Xingjun Ma, Xiang Zheng, James Bailey, Jingjing Chen, and Yu-Gang Jiang. *CVPR 2020*.

- NeuroAttack: Undermining Spiking Neural Networks Security through Externally Triggered Bit-Flips.
  [[pdf]](https://arxiv.org/pdf/2005.08041.pdf)
  - Valerio Venceslai, Alberto Marchisio, Ihsen Alouani, Maurizio Martina, and Muhammad Shafique. *IJCNN 2020*.

- Backdoor Attacks to Graph Neural Networks. 
  [[pdf]](https://arxiv.org/pdf/2006.11165.pdf)
  - Zaixi Zhang, Jinyuan Jia, Binghui Wang, and Neil Zhenqiang Gong. arXiv 2020.
  
- Backdoor Attacks on Federated Meta-Learning. 
  [[pdf]](https://arxiv.org/pdf/2006.07026.pdf)
  - Chien-Lun Chen, Leana Golubchik, and Marco Paolieri. arXiv 2020. 

- BadNL: Backdoor Attacks Against NLP Models.
  [[pdf]](https://arxiv.org/pdf/2006.01043.pdf)
  - Xiaoyi Chen, Ahmed Salem, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv 2020.

- Targeted Forgetting and False Memory Formation in Continual Learners through Adversarial Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2002.07111.pdf)
  - Muhammad Umer, Glenn Dawson, Robi Polikar. arXiv 2020.

- Exploring Backdoor Poisoning Attacks Against Malware Classifiers.
  [[pdf]](https://arxiv.org/pdf/2003.01031.pdf)
  - Giorgio Severi, Jim Meyer, Scott Coull, and Alina Oprea. arXiv 2020.

### 2019
- A Backdoor Attack Against LSTM-based Text Classification Systems.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8836465)
  - Jiazhu Dai, Chuanshuai Chen, and Yufeng Li. *IEEE Access 2019*.

- Design of Intentional Backdoors in Sequential Models.
  [[pdf]](https://arxiv.org/pdf/1902.09972.pdf)
  - Zhaoyuan Yang, Naresh Iyer, Johan Reimann, and Nurali Virani. arXiv 2019.

- Trojan Attacks on Wireless Signal Classification with Adversarial Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1910.10766.pdf)
  - Kemal Davaslioglu, and Yalin E. Sagduyu. *DySPAN 2019*.


### 2018
- How to Backdoor Federated Learning.
  [[pdf]](https://arxiv.org/pdf/1807.00459.pdf)
  - Eugene Bagdasaryan, Andreas Veit, Yiqing Hua, Deborah Estrin, and Vitaly Shmatikov. arXiv 2019.


## Properties Discussion and Evaluation
- Rethinking the Trigger of Backdoor Attack.
  [[pdf]](https://arxiv.org/pdf/2004.04692.pdf)
  - Yiming Li, Tongqing Zhai, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shutao Xia. arXiv 2020.


## Application in other Tasks
- Turning Your Weakness into a Strength: Watermarking Deep Neural Networks by Backdooring.
  [[pdf]](https://arxiv.org/pdf/1802.04633.pdf)
  [[code]](https://github.com/adiyoss/WatermarkNN)
  - Yossi Adi, Carsten Baum, Moustapha Cisse, Benny Pinkas, and Joseph Keshet. *USENIX Security 2018*. 

- Towards Probabilistic Verification of Machine Unlearning.
  [[pdf]](https://arxiv.org/pdf/2003.04247.pdf)
  [[code]](https://github.com/inspire-group/unlearning-verification)
  - David Marco Sommer, Liwei Song, Sameer Wagh, and Prateek Mittal. arXiv 2020. 

