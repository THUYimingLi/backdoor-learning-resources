# Backdoor Learning Resources


A curated list of **Backdoor Learning** resources. For more details and our categorization criteria, please refer to our [survey](https://www.researchgate.net/publication/343006441_Backdoor_Learning_A_Survey).

#### Why Backdoor Learning?
Backdoor learning is an emerging research area, which discusses the security issues of the training process towards machine learning algorithms. It is critical for safely adopting third-party algorithms in reality.  Although backdoor learning shares certain similarity with adversarial learning (which concentrates on the security issues of the inference process), they do have essential differences and can be easily distinguished.

Note: 'Backdoor' is also commonly called the 'Neural Trojan' or 'Trojan'.


## Citation
If our repo or survey is useful for your research, please cite our paper as follows:
```
@article{li2020backdoor,
  title={Backdoor learning: A survey},
  author={Li, Yiming and Wu, Baoyuan and Jiang, Yong and Li, Zhifeng and Xia, Shu-Tao},
  journal={arXiv preprint arXiv:2007.08745},
  year={2020}
}
```


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
  - Author 1, Author 2, and Author 3. *Conference/Journal*, Year.
```


## Table of Contents
- [Related Survey](#related-survey)
- [Image and Video Classification](#image-and-video-classification) 
  - [Poisoning-based Attack](#poisoning-based-attack)
  - [Non-poisoning-based Attack](#non-poisoning-based-attack)
  - [Backdoor Defense](#backdoor-defense)
- [Attack and Defense Towards Other Tasks and Paradigms](#attack-and-defense-towards-other-tasks-and-paradigms)  
- [Properties Discussion and Evaluation](#properties-discussion-and-evaluation)
- [Backdoor Attack for Good](#backdoor-attack-for-good)
- [Toolbox](#toolbox)
- [Competition](#competition)


## Related Survey
- Backdoor Learning: A Survey.
  [[pdf]](https://www.researchgate.net/publication/343006441_Backdoor_Learning_A_Survey)
  - Yiming Li, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shu-Tao Xia. arXiv, 2020.

- Backdoor Attacks and Countermeasures on Deep Learning: A Comprehensive Review.
  [[pdf]](https://arxiv.org/pdf/2007.10760.pdf)
  - Yansong Gao, Bao Gia Doan, Zhi Zhang, Siqi Ma, Anmin Fu, Surya Nepal, and Hyoungshick Kim. arXiv, 2020.

- Data Security for Machine Learning: Data Poisoning, Backdoor Attacks, and Defenses.
  [[pdf]](https://arxiv.org/pdf/2012.10544.pdf)
  - Micah Goldblum, Dimitris Tsipras, Chulin Xie, Xinyun Chen, Avi Schwarzschild, Dawn Song, Aleksander Madry, Bo Li, and Tom Goldstein. arXiv, 2020.

- Deep Learning Backdoors.
  [[pdf]](https://arxiv.org/pdf/2007.08273.pdf)
  - Shaofeng Li, Shiqing Ma, Minhui Xue, and Benjamin Zi Hao Zhao. arXiv, 2020.

- A Survey on Neural Trojans. 
  [[pdf]](https://eprint.iacr.org/2020/201.pdf)
  - Yuntao Liu, Ankit Mondal, Abhishek Chakraborty, Michael Zuzak, Nina Jacobsen, Daniel Xing, and Ankur Srivastava. *ISQED*, 2020.

## Image and Video Classification
### Poisoning-based Attack
#### 2021
- A Master Key Backdoor for Universal Impersonation Attack against DNN-based Face Verification.
  [[link]](https://www.sciencedirect.com/science/article/pii/S0167865521000210)
  - WeiGuo, Benedetta Tondi, and Mauro Barni. *Pattern Recognition Letters*, 2021.

- WaNet - Imperceptible Warping-based Backdoor Attack.
  [[pdf]](https://openreview.net/pdf?id=eEn8KTtJOx)
  - Tuan Anh Nguyen, and Anh Tuan Tran. *ICLR*, 2021.

- Deep Feature Space Trojan Attack of Neural Networks by Controlled Detoxification.
  [[pdf]](https://arxiv.org/pdf/2012.11212.pdf)
  [[code]](https://github.com/Megum1/DFST)
  - Siyuan Cheng, Yingqi Liu, Shiqing Ma, and Xiangyu Zhang. *AAAI*, 2021.
  
- Backdoors Hidden in Facial Features: A Novel Invisible Backdoor Attack against Face Recognition Systems.
  [[link]](https://link.springer.com/article/10.1007/s12083-020-01031-z)
  - Mingfu Xue, Can He, Jian Wang, and Weiqiang Liu. *Peer-to-Peer Networking and Applications*, 2021. 

- Invisible Poison: A Blackbox Clean Label Backdoor Attack to Deep Neural Networks.
  [[pdf]](https://www.lions.odu.edu/~h1wu/paper/infocom21.pdf)
  - Rui Ning, Jiang Li, ChunSheng Xin, and Hongyi Wu. *INFOCOM*, 2021.

#### 2020
- One-to-N & N-to-One: Two Advanced Backdoor Attacks against Deep Learning Models.
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9211729)
  - Mingfu Xue, Can He, Jian Wang, and Weiqiang Liu. *IEEE Transactions on Dependable and Secure Computing*, 2020.

- Invisible Backdoor Attacks on Deep Neural Networks via Steganography and Regularization.
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9186317/)
  [[arXiv Version (2019)]](https://arxiv.org/pdf/1909.02742.pdf)
  - Shaofeng Li, Minhui Xue, Benjamin Zi Hao Zhao, Haojin Zhu, and Xinpeng Zhang. *IEEE Transactions on Dependable and Secure Computing*, 2020.

- Composite Backdoor Attack for Deep Neural Network by Mixing Existing Benign Features.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3372297.3423362)
  - Junyu Lin, Lei Xu, Yingqi Liu, Xiangyu Zhang. *CCS*, 2020.

- Input-Aware Dynamic Backdoor Attack. 
  [[pdf]](https://arxiv.org/pdf/2010.08138.pdf)
  [[code]](https://github.com/VinAIResearch/input-aware-backdoor-attack-release)
  - Anh Nguyen, and Anh Tran. *NeurIPS 2020*.

- Hidden Trigger Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1910.00033.pdf)
  [[code]](https://github.com/UMBCvision/Hidden-Trigger-Backdoor-Attacks)
  - Aniruddha Saha, Akshayvarun Subramanya, and Hamed Pirsiavash. *AAAI*, 2020.

- Bypassing Backdoor Detection Algorithms in Deep Learning.
  [[pdf]](https://arxiv.org/pdf/1905.13409.pdf)
  - Te Juin Lester Tan, and Reza Shokri. *EuroS&P*, 2020.

- Backdoor Embedding in Convolutional Neural Network Models via Invisible Perturbation.
  [[pdf]](https://arxiv.org/pdf/1808.10307.pdf)
  - Cong Liao, Haoti Zhong, Anna Squicciarini, Sencun Zhu, and David Miller. *ACM CODASPY*, 2020.


- Reflection Backdoor: A Natural Backdoor Attack on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2007.02343.pdf)
  [[code]](https://github.com/DreamtaleCore/Refool)
  - Yunfei Liu, Xingjun Ma, James Bailey, and Feng Lu. *ECCV*, 2020.

- Can Adversarial Weight Perturbations Inject Neural Backdoors?
  [[pdf]](https://arxiv.org/pdf/2008.01761.pdf)
  - Siddhant Garg, Adarsh Kumar, Vibhor Goel, and Yingyu Liang. *CIKM*, 2020.

- Clean-Label Backdoor Attacks on Video Recognition Models.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.pdf)
  [[code]](https://github.com/ShihaoZhaoZSH/Video-Backdoor-Attack)
  - Shihao Zhao, Xingjun Ma, Xiang Zheng, James Bailey, Jingjing Chen, and Yu-Gang Jiang. *CVPR*, 2020.

- Escaping Backdoor Attack Detection of Deep Learning.
  [[link]](https://link.springer.com/chapter/10.1007/978-3-030-58201-2_29)
  - Yayuan Xiong, Fengyuan Xu, Sheng Zhong, and Qun Li. *IFIP SEC*, 2020.

- Live Trojan Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2004.11370.pdf)
  [[code]](https://github.com/robbycostales/live-trojans)
  - Robby Costales, Chengzhi Mao, Raphael Norwitz, Bryan Kim, and Junfeng Yang. *CVPR Workshop*, 2020.

- Backdooring and Poisoning Neural Networks with Image-Scaling Attacks.
  [[pdf]](https://arxiv.org/pdf/2003.08633.pdf)
  - Erwin Quiring, and Konrad Rieck. *IEEE S&P Workshop*, 2020.

- Backdoor Attack with Sample-Specific Triggers.
  [[pdf]](https://arxiv.org/abs/2012.03816)
  - Yuezun Li, Yiming Li, Baoyuan Wu, Longkang Li, Ran He, and Siwei Lyu. arXiv, 2020.

- Blind Backdoors in Deep Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2005.03823.pdf)
  - Eugene Bagdasaryan, and Vitaly Shmatikov. arXiv, 2020.

- HaS-Nets: A Heal and Select Mechanism to Defend DNNs Against Backdoor Attacks for Data Collection Scenarios.
  [[pdf]](https://arxiv.org/pdf/2012.07474.pdf)
  - Hassan Ali, Surya Nepal, Salil S. Kanhere, and Sanjay Jha. arXiv, 2020.

- FaceHack: Triggering Backdoored Facial Recognition Systems Using Facial Characteristics.
  [[pdf]](https://arxiv.org/pdf/2006.11623.pdf)
  - Esha Sarkar, Hadjer Benkraouda, and Michail Maniatakos. arXiv, 2020.

- Light Can Hack Your Face! Black-box Backdoor Attack on Face Recognition Systems.
  [[pdf]](https://arxiv.org/pdf/2009.06996.pdf)
  - Haoliang Li, Yufei Wang, Xiaofei Xie, Yang Liu, Shiqi Wang, Renjie Wan, Lap-Pui Chau, and Alex C. Kot. arXiv, 2020.

- Class-Oriented Poisoning Attack.
  [[pdf]](https://arxiv.org/pdf/2008.00047.pdf)
  - Bingyin Zhao, and Yingjie Lao. arXiv, 2020.

- Dynamic Backdoor Attacks Against Machine Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2003.03675.pdf)
  - Ahmed Salem, Rui Wen, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv, 2020.  

#### 2019
- Latent Backdoor Attacks on Deep Neural Networks.
  [[pdf]](http://people.cs.uchicago.edu/~huiyingli/publication/fr292-yaoA.pdf)
  - Yuanshun Yao, Huiying Li, Haitao Zheng and Ben Y. Zhao. *CCS*, 2019.

- A New Backdoor Attack in CNNS by Training Set Corruption Without Label Poisoning.
  [[pdf]](https://arxiv.org/pdf/1902.11237.pdf)
  - M.Barni, K.Kallas, and B.Tondi. *ICIP*, 2019.
  
- Label-Consistent Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1912.02771.pdf)
  [[code]](https://github.com/MadryLab/label-consistent-backdoor-code)
  - Alexander Turner, Dimitris Tsipras, and Aleksander Madry. arXiv, 2019.
 
#### 2017
- BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain.
  [[pdf]](https://arxiv.org/pdf/1708.06733.pdf)
  [[journal]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8685687)
  - Tianyu Gu, Brendan Dolan-Gavitt, and Siddharth Garg. arXiv, 2017 (*IEEE Access*, 2019).

- Targeted Backdoor Attacks on Deep Learning Systems Using Data Poisoning.
  [[pdf]](https://arxiv.org/pdf/1712.05526.pdf)
  [[code]](https://github.com/GeorgePisl/backdoor-attacks-based-on-deep-learning)
  - Xinyun Chen, Chang Liu, Bo Li, Kimberly Lu, and Dawn Song. arXiv, 2017.
  
- Trojaning Attack on Neural Networks.
  [[pdf]](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=2782&context=cstech)
  - Yingqi Liu, Shiqing Ma, Yousra Aafer, Wen-Chuan Lee, and Juan Zhai. *NDSS*, 2017.


### Non-poisoning-based Attack  
- An Embarrassingly Simple Approach for Trojan Attack in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2006.08131.pdf)
  [[code]](https://github.com/trx14/TrojanNet)
  - Ruixiang Tang, Mengnan Du, Ninghao Liu, Fan Yang, and Xia Hu. *KDD*, 2020.

- TBT: Targeted Neural Network Attack with Bit Trojan.
  [[pdf]](https://arxiv.org/abs/1909.05193)
  [[code]](https://github.com/adnansirajrakin/TBT-CVPR2020)
  - Adnan Siraj Rakin, Zhezhi He, and Deliang Fan. *CVPR*, 2020.

- DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection.
  [[pdf]](https://arxiv.org/pdf/2101.06896.pdf)
  - Yuanchun Li, Jiayi Hua, Haoyu Wang, Chunyang Chen, and Yunxin Liu. *ICSE*, 2021.

- TrojanNet: Embedding Hidden Trojan Horse Models in Neural Network.
  [[pdf]](https://arxiv.org/pdf/2002.10078.pdf)
  - Chuan Guo, Ruihan Wu, and Kilian Q. Weinberger. arXiv, 2020.

- Don't Trigger Me! A Triggerless Backdoor Attack Against Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2010.03282.pdf)
  - Ahmed Salem, Michael Backes, and Yang Zhang. arXiv, 2020.

- Backdooring Convolutional Neural Networks via Targeted Weight Perturbations.
  [[pdf]](https://arxiv.org/pdf/1812.03128.pdf)
  - Jacob Dumford, and Walter Scheirer. arXiv, 2018.
  
### Backdoor Defense
#### Preprocessing based Empirical Defense
- Rethinking the Trigger of Backdoor Attack.
  [[pdf]](https://arxiv.org/pdf/2004.04692.pdf)
  - Yiming Li, Tongqing Zhai, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shutao Xia. arXiv, 2020.

- DeepSweep: An Evaluation Framework for Mitigating DNN Backdoor Attacks using Data Augmentation.
  [[pdf]](https://arxiv.org/pdf/2012.07006.pdf)
  [[code]](https://github.com/YiZeng623/DeepSweep)
  - Yi Zeng, Han Qiu, Shangwei Guo, Tianwei Zhang, Meikang Qiu, and Bhavani Thuraisingham. *AsiaCCS*, 2021.

- Februus: Input Purification Defense Against Trojan Attacks on Deep Neural Network Systems.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3427228.3427264)
  [[code]](https://februustrojandefense.github.io/)
  - Bao Gia Doan, Ehsan Abbasnejad, and Damith C. Ranasinghe. *ACSAC*, 2020.

- Neural Trojans.
  [[pdf]](https://arxiv.org/pdf/1710.00942.pdf)
  - Yuntao Liu, Yang Xie, and Ankur Srivastava. *ICCD*, 2017.

- ConFoc: Content-Focus Protection Against Trojan Attacks on Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2007.00711.pdf)
  - Miguel Villarreal-Vasquez, and Bharat Bhargava. arXiv, 2021.
  
- Model Agnostic Defense against Backdoor Attacks in Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1908.02203.pdf)
  - Sakshi Udeshi, Shanshan Peng, Gerald Woo, Lionell Loh, Louth Rawshan, and Sudipta Chattopadhyay. arXiv, 2019.

#### Model Reconstruction based Empirical Defense
- Neural Attention Distillation: Erasing Backdoor Triggers from Deep Neural Networks.
  [[pdf]](https://openreview.net/pdf?id=9l0K4OM-oXE)
  [[code]](https://github.com/bboylyg/NAD)
  - Yige Li, Xingjun Ma, Nodens Koren, Lingjuan Lyu, Xixiang Lyu, and Bo Li. *ICLR*, 2021.

- Bridging Mode Connectivity in Loss Landscapes and Adversarial Robustness.
  [[pdf]](https://arxiv.org/pdf/2005.00060.pdf)
  [[code]](https://github.com/IBM/model-sanitization)
  - Pu Zhao, Pin-Yu Chen, Payel Das, Karthikeyan Natesan Ramamurthy, and Xue Lin. *ICLR*, 2020.

- Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1805.12185.pdf)
  [[code]](https://github.com/kangliucn/Fine-pruning-defense)
  - Kang Liu, Brendan Dolan-Gavitt, and Siddharth Garg. *RAID*, 2018.   

- Neural Trojans.
  [[pdf]](https://arxiv.org/pdf/1710.00942.pdf)
  - Yuntao Liu, Yang Xie, and Ankur Srivastava. *ICCD*, 2017.
  
- Disabling Backdoor and Identifying Poison Data by using Knowledge Distillation in Backdoor Attacks on Deep Neural Networks.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3411508.3421375)
  - Kota Yoshida, and Takeshi Fujino. *CCS Workshop*, 2020.

- Defending against Backdoor Attack on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2002.12162.pdf)
  - Hao Cheng, Kaidi Xu, Sijia Liu, Pin-Yu Chen, Pu Zhao, and Xue Lin. *KDD Workshop*, 2019.

- Neural Network Laundering: Removing Black-Box Backdoor Watermarks from Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2004.11368.pdf)
  - William Aiken, Hyoungshick Kim, and Simon Woo. arXiv, 2020.

- HaS-Nets: A Heal and Select Mechanism to Defend DNNs Against Backdoor Attacks for Data Collection Scenarios.
  [[pdf]](https://arxiv.org/pdf/2012.07474.pdf)
  - Hassan Ali, Surya Nepal, Salil S. Kanhere, and Sanjay Jha. arXiv, 2020.


#### Trigger Synthesis based Empirical Defense
- Detection of Backdoors in Trained Classiﬁers Without Access to the Training Set.
  [[pdf]](http://arxiv.org/pdf/1908.10498)
  - Z Xiang, DJ Miller, and G Kesidis. *IEEE Transactions on Neural Networks and Learning Systems*, 2020.

- Towards Inspecting and Eliminating Trojan Backdoors in Deep Neural Networks.
  [[pdf]](http://www.personal.psu.edu/wzg13/publications/icdm20.pdf)
  [[previous version]](https://arxiv.org/pdf/1908.01763.pdf)
  [[code]](https://github.com/UsmannK/TABOR)
  - Wenbo Guo, Lun Wang, Xinyu Xing, Min Du, and Dawn Song. *ICDM*, 2020.

- GangSweep: Sweep out Neural Backdoors by GAN.
  [[pdf]](https://www.lions.odu.edu/~h1wu/paper/gangsweep.pdf)
  - Liuwan Zhu, Rui Ning, Cong Wang, Chunsheng Xin, and Hongyi Wu. *ACM MM*, 2020.

- Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks.
  [[pdf]](https://gangw.web.illinois.edu/class/cs598/papers/sp19-poisoning-backdoor.pdf)
  [[code]](https://github.com/bolunwang/backdoor)
  - Bolun Wang, Yuanshun Yao, Shawn Shan, Huiying Li, Bimal Viswanath, Haitao Zheng, Ben Y. Zhao. *IEEE S&P*, 2019.

- Defending Neural Backdoors via Generative Distribution Modeling.
  [[pdf]](https://arxiv.org/pdf/1910.04749.pdf)
  [[code]](https://github.com/superrrpotato/Defending-Neural-Backdoors-via-Generative-Distribution-Modeling)
  - Ximing Qiao, Yukun Yang, and Hai Li. *NeurIPS*, 2019.

- DeepInspect: A Black-box Trojan Detection and Mitigation Framework for Deep Neural Networks.
  [[pdf]](https://www.ijcai.org/proceedings/2019/0647.pdf)
  - Huili Chen, Cheng Fu, Jishen Zhao, Farinaz Koushanfar. *IJCAI*, 2019.

- Revealing Perceptible Backdoors in DNNs Without the Training Set via the Maximum Achievable Misclassification Fraction Statistic.
  [[pdf]](https://ieeexplore.ieee.org/abstract/document/9231861)
  - Zhen Xiang, David J. Miller, Hang Wang, and George Kesidis. *MLSP*, 2020.

- Backdoor Scanning for Deep Neural Networks through K-Arm Optimization.
  [[pdf]](https://arxiv.org/pdf/2102.05123.pdf)
  - Guangyu Shen, Yingqi Liu, Guanhong Tao, Shengwei An, Qiuling Xu, Siyuan Cheng, Shiqing Ma, and Xiangyu Zhang. arXiv, 2021.

- Scalable Backdoor Detection in Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2006.05646.pdf)
  - Haripriya Harikumar, Vuong Le, Santu Rana, Sourangshu Bhattacharya, Sunil Gupta, and Svetha Venkatesh. arXiv, 2020.

- NNoculation: Broad Spectrum and Targeted Treatment of Backdoored DNNs.
  [[pdf]](https://arxiv.org/pdf/2002.08313.pdf)
  [[code]](https://github.com/akshajkumarv/NNoculation)
  - Akshaj Kumar Veldanda, Kang Liu, Benjamin Tan, Prashanth Krishnamurthy, Farshad Khorrami, Ramesh Karri, Brendan Dolan-Gavitt, and Siddharth Garg. arXiv, 2020.

#### Model Diagnosis based Empirical Defense
- Detecting AI Trojans Using Meta Neural Analysis.
  [[pdf]](https://arxiv.org/pdf/1910.03137.pdf)
  - Xiaojun Xu, Qi Wang, Huichen Li, Nikita Borisov, Carl A. Gunter, and Bo Li. *IEEE S&P*, 2021.

- Universal Litmus Patterns: Revealing Backdoor Attacks in CNNs.
  [[pdf]](https://arxiv.org/pdf/1906.10842.pdf)
  [[code]](https://umbcvision.github.io/Universal-Litmus-Patterns/)
  - Soheil Kolouri, Aniruddha Saha, Hamed Pirsiavash, and Heiko Hoffmann. *CVPR*, 2020.

- One-Pixel Signature: Characterizing CNN Models for Backdoor Detection.
  [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720324.pdf)
  - Shanjiaoyang Huang, Weiqi Peng, Zhiwei Jia, and Zhuowen Tu. *ECCV*, 2020.
  
- Practical Detection of Trojan Neural Networks: Data-Limited and Data-Free Cases.
  [[pdf]](https://arxiv.org/pdf/2007.15802.pdf)
  [[code]](https://github.com/wangren09/TrojanNetDetector)
  - Ren Wang, Gaoyuan Zhang, Sijia Liu, Pin-Yu Chen, Jinjun Xiong, and Meng Wang. *ECCV*, 2020.

- Detecting Backdoor Attacks via Class Difference in Deep Neural Networks.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9233317)
  - Hyun Kwon. *IEEE Access*, 2020.

- Detecting Trojaned DNNs Using Counterfactual Attributions.
  [[pdf]](https://arxiv.org/pdf/2012.02275.pdf)
  - Karan Sikka, Indranil Sur, Susmit Jha, Anirban Roy, and Ajay Divakaran. arXiv, 2020.

- Cassandra: Detecting Trojaned Networks from Adversarial Perturbations.
  [[pdf]](https://arxiv.org/pdf/2007.14433.pdf)
  - Xiaoyu Zhang, Ajmal Mian, Rohit Gupta, Nazanin Rahnavard, and Mubarak Shah. arXiv, 2020.
  
- Odyssey: Creation, Analysis and Detection of Trojan Models.
  [[pdf]](https://arxiv.org/pdf/2007.08142.pdf)
  [[dataset]](https://lcwn-lab.github.io/Odessey/)
  - Marzieh Edraki, Nazmul Karim, Nazanin Rahnavard, Ajmal Mian, and Mubarak Shah. arXiv, 2020.

- Noise-response Analysis for Rapid Detection of Backdoors in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2008.00123.pdf)
  - N. Benjamin Erichson, Dane Taylor, Qixuan Wu, and Michael W. Mahoney. arXiv, 2020.

- NeuronInspect: Detecting Backdoors in Neural Networks via Output Explanations.
  [[pdf]](https://arxiv.org/pdf/1911.07399.pdf)
  - Xijie Huang, Moustafa Alzantot, and Mani Srivastava. arXiv, 2019.


#### Poison Suppression based Empirical Defense
- Robust Anomaly Detection and Backdoor Attack Detection via Differential Privacy.
  [[pdf]](https://arxiv.org/pdf/1911.07116.pdf)
  [[code]](https://www.dropbox.com/sh/rt8qzii7wr07g6n/AAAbwokv2sfBeE9XAL2pXv_Aa?dl=0)
  - Min Du, Ruoxi Jia, and Dawn Song. *ICLR*, 2020.  
  
- Strong Data Augmentation Sanitizes Poisoning and Backdoor Attacks Without an Accuracy Trade-off.
  [[pdf]](https://arxiv.org/pdf/2011.09527.pdf)
  - Eitan Borgnia, Valeriia Cherepanova, Liam Fowl, Amin Ghiasi, Jonas Geiping, Micah Goldblum, Tom Goldstein, and Arjun Gupta. *ICASSP*, 2021.
  
- On the Effectiveness of Mitigating Data Poisoning Attacks with Gradient Shaping.
  [[pdf]](https://arxiv.org/pdf/2002.11497.pdf)
  [[code]](https://github.com/Sanghyun-Hong/Gradient-Shaping)
  - Sanghyun Hong, Varun Chandrasekaran, Yiğitcan Kaya, Tudor Dumitraş, and Nicolas Papernot. arXiv, 2020.  

- What Doesn't Kill You Makes You Robust(er): Adversarial Training against Poisons and Backdoors.
  [[pdf]](https://arxiv.org/pdf/2102.13624.pdf)
  - Jonas Geiping, Liam Fowl, Gowthami Somepalli, Micah Goldblum, Michael Moeller, and Tom Goldstein. arXiv, 2021.

- DP-InstaHide: Provably Defusing Poisoning and Backdoor Attacks with Differentially Private Data Augmentations.
  [[pdf]](https://arxiv.org/pdf/2103.02079.pdf)
  - Eitan Borgnia, Jonas Geiping, Valeriia Cherepanova, Liam Fowl, Arjun Gupta, Amin Ghiasi, Furong Huang, Micah Goldblum, and Tom Goldstein. arXiv, 2021.


- Removing Backdoor-Based Watermarks in Neural Networks with Limited Data.
  [[pdf]](https://arxiv.org/pdf/2008.00407.pdf)
  - Xuankai Liu, Fengting Li, Bihan Wen, and Qi Li. arXiv, 2020.  



#### Sample Filtering based Empirical Defense
- Demon in the Variant: Statistical Analysis of DNNs for Robust Backdoor Contamination Detection.
  [[pdf]](https://arxiv.org/pdf/1908.00686.pdf)
  [[code]](https://github.com/TDteach/backdoor)
  - Di Tang, XiaoFeng Wang, Haixu Tang, and Kehuan Zhang. *USENIX Security*, 2021.

- CLEANN: Accelerated Trojan Shield for Embedded Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2009.02326.pdf)
  - Mojan Javaheripi, Mohammad Samragh, Gregory Fields, Tara Javidi, and Farinaz Koushanfar. *ICCAD*, 2020.


- Robust Anomaly Detection and Backdoor Attack Detection via Differential Privacy.
  [[pdf]](https://arxiv.org/pdf/1911.07116.pdf)
  [[code]](https://www.dropbox.com/sh/rt8qzii7wr07g6n/AAAbwokv2sfBeE9XAL2pXv_Aa?dl=0)
  - Min Du, Ruoxi Jia, and Dawn Song. *ICLR*, 2020.  
  

- SentiNet: Detecting Localized Universal Attacks Against Deep Learning Systems.
  [[pdf]](https://arxiv.org/pdf/1812.00292.pdf)
  - Edward Chou, Florian Tramèr, and Giancarlo Pellegrino. *IEEE S&P Workshop*, 2020.

- STRIP: A Defence Against Trojan Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1902.06531.pdf)
  [[extension]](https://arxiv.org/pdf/1911.10312.pdf)
  [[code]](https://github.com/garrisongys/STRIP)
  - Yansong Gao, Chang Xu, Derui Wang, Shiping Chen, Damith C. Ranasinghe, and Surya Nepal. *ACSAC*, 2019.

- Detecting Backdoor Attacks on Deep Neural Networks by Activation Clustering.
  [[pdf]](https://arxiv.org/pdf/1811.03728.pdf)
  [[code]](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/defences/detector/poison/activation_defence.py)
  - Bryant Chen, Wilka Carvalho, Nathalie Baracaldo, Heiko Ludwig, Benjamin Edwards, Taesung Lee, Ian Molloy, and Biplav Srivastava. *AAAI Workshop*, 2019.

- Deep Probabilistic Models to Detect Data Poisoning Attacks.
  [[pdf]](https://arxiv.org/pdf/1912.01206.pdf)
  - Mahesh Subedar, Nilesh Ahuja, Ranganath Krishnan, Ibrahima J. Ndiour, and Omesh Tickoo. *NeurIPS Workshop*, 2019.  

- Spectral Signatures in Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1811.00636.pdf)
  [[code]](https://github.com/MadryLab/backdoor_data_poisoning)
  - Brandon Tran, Jerry Li, and Aleksander Madry. *NeurIPS*, 2018.  

- Exposing Backdoors in Robust Machine Learning Models.
  [[pdf]](https://arxiv.org/pdf/2003.00865.pdf)
  - Ezekiel Soremekun, Sakshi Udeshi, and Sudipta Chattopadhyay. arXiv, 2020.

- A Unified Framework for Analyzing and Detecting Malicious Examples of DNN Models.
  [[pdf]](https://arxiv.org/pdf/2006.14871.pdf)
  - Kaidi Jin, Tianwei Zhang, Chao Shen, Yufei Chen, Ming Fan, Chenhao Lin, and Ting Liu. arXiv, 2020.

- HaS-Nets: A Heal and Select Mechanism to Defend DNNs Against Backdoor Attacks for Data Collection Scenarios.
  [[pdf]](https://arxiv.org/pdf/2012.07474.pdf)
  - Hassan Ali, Surya Nepal, Salil S. Kanhere, and Sanjay Jha. arXiv, 2020.

- Poison as a Cure: Detecting & Neutralizing Variable-Sized Backdoor Attacks in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1911.08040.pdf)
  - Alvin Chan, and Yew-Soon Ong. arXiv, 2019.  
  
#### Certificated Defense
- Certified Robustness to Label-Flipping Attacks via Randomized Smoothing.
  [[pdf]](https://arxiv.org/pdf/2002.03018.pdf)
  - Elan Rosenfeld, Ezra Winston, Pradeep Ravikumar, J. Zico Kolter. *ICML*, 2020.

- On Certifying Robustness against Backdoor Attacks via Randomized Smoothing.
  [[pdf]](https://arxiv.org/pdf/2002.11750.pdf)
  - Binghui Wang, Xiaoyu Cao, Jinyuan jia, and Neil Zhenqiang Gong. *CVPR Workshop*, 2020.

- RAB: Provable Robustness Against Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2003.08904.pdf)
  [[code]](https://github.com/AI-secure/Robustness-Against-Backdoor-Attacks)
  - Maurice Weber, Xiaojun Xu, Bojan Karlas, Ce Zhang, and Bo Li. arXiv, 2020.



## Attack and Defense Towards Other Tasks and Paradigms
### Natural Language Processing 
- Exploring the Universal Vulnerability of Prompt-based Learning Paradigm.
 [[pdf]](https://arxiv.org/abs/2204.05239)
  - Lei Xu, Yangyi Chen, Ganqu Cui, Hongcheng Gao, Zhiyuan Liu. *NAACL-Findings*, 2022.


- T-Miner: A Generative Approach to Defend Against Trojan Attacks on DNN-based Text Classification.
  [[pdf]](https://arxiv.org/pdf/2103.04264.pdf)
  - Ahmadreza Azizi, Ibrahim Asadullah Tahmid, Asim Waheed, Neal Mangaokar, Jiameng Pu, Mobin Javed, Chandan K. Reddy, and Bimal Viswanath. *USENIX Security*, 2021.

- Weight Poisoning Attacks on Pre-trained Models.
  [[pdf]](https://arxiv.org/pdf/2004.06660.pdf)
  [[code]](https://github.com/neulab/RIPPLe)
  - Keita Kurita, Paul Michel, and Graham Neubig. *ACL*, 2020.
  
- A Backdoor Attack Against LSTM-based Text Classification Systems.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8836465)
  - Jiazhu Dai, Chuanshuai Chen, and Yufeng Li. *IEEE Access*, 2019.

- Poison Attacks against Text Datasets with Conditional Adversarially Regularized Autoencoder.
  [[pdf]](https://arxiv.org/pdf/2010.02684.pdf)
  - Alvin Chan, Yi Tay, Yew-Soon Ong, and Aston Zhang. *EMNLP-Findings*, 2020.

- Detecting Universal Trigger’s Adversarial Attack with Honeypot.
  [[pdf]](https://arxiv.org/abs/2011.10492)
  - Thai Le, Noseong Park, Dongwon Lee. arXiv, 2020.  

- ONION: A Simple and Effective Defense Against Textual Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2011.10369.pdf)
  - Fanchao Qi, Yangyi Chen, Mukai Li, Zhiyuan Liu, and Maosong Sun. arXiv, 2020.

- Mitigating Backdoor Attacks in LSTM-based Text Classification Systems by Backdoor Keyword Identification.
  [[pdf]](https://arxiv.org/pdf/2007.12070.pdf)
  - Chuanshuai Chen, and Jiazhu Dai. arXiv, 2020.

- Trojaning Language Models for Fun and Profit.
  [[pdf]](https://arxiv.org/pdf/2008.00312.pdf)
  - Xinyang Zhang, Zheng Zhang, and Ting Wang. arXiv, 2020.

- BadNL: Backdoor Attacks Against NLP Models.
  [[pdf]](https://arxiv.org/pdf/2006.01043.pdf)
  - Xiaoyi Chen, Ahmed Salem, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv, 2020.
  
### Graph Neural Networks
- Graph Backdoor.
  [[pdf]](https://arxiv.org/pdf/2006.11890.pdf)
  - Zhaohan Xi, Ren Pang, Shouling Ji, and Ting Wang. *USENIX Security*, 2021.
  
- Backdoor Attacks to Graph Neural Networks. 
  [[pdf]](https://arxiv.org/pdf/2006.11165.pdf)
  - Zaixi Zhang, Jinyuan Jia, Binghui Wang, and Neil Zhenqiang Gong. *NeurIPS Workshop*, 2020.  
  
### Reinforcement Learning
- TrojDRL: Evaluation of Backdoor Attacks on Deep Reinforcement Learning.
  [[pdf]](https://arxiv.org/pdf/1903.06638.pdf)
  - Panagiota Kiourti, Kacper Wardega, Susmit Jha, and Wenchao Li. *DAC*, 2020.

- Stop-and-Go: Exploring Backdoor Attacks on Deep Reinforcement Learning-based Traffic Congestion Control Systems.
  [[pdf]](https://arxiv.org/pdf/2003.07859.pdf)
  - Yue Wang, Esha Sarkar, Michail Maniatakos, and Saif Eddin Jabari. arXiv, 2020.

  
- Design of Intentional Backdoors in Sequential Models.
  [[pdf]](https://arxiv.org/pdf/1902.09972.pdf)
  - Zhaoyuan Yang, Naresh Iyer, Johan Reimann, and Nurali Virani. arXiv, 2019.
  
  
### Collaborative Learning
- How to Backdoor Federated Learning.
  [[pdf]](https://arxiv.org/pdf/1807.00459.pdf)
  - Eugene Bagdasaryan, Andreas Veit, Yiqing Hua, Deborah Estrin, and Vitaly Shmatikov. *AISTATS*, 2020 (arXiv, 2018).

- Stability-Based Analysis and Defense against Backdoor Attacks on Edge Computing Services.
  [[link]](https://ieeexplore.ieee.org/abstract/document/9354927)
  - Yi Zhao, Ke Xu, Haiyang Wang, Bo Li, and Ruoxi Jia. *IEEE Network*, 2021.

- Curse or Redemption? How Data Heterogeneity Affects the Robustness of Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2102.00655.pdf)
  - Syed Zawad, Ahsan Ali, Pin-Yu Chen, Ali Anwar, Yi Zhou, Nathalie Baracaldo, Yuan Tian, and Feng Yan. *AAAI*, 2021.

- Attack of the Tails: Yes, You Really Can Backdoor Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2007.05084.pdf)
  - Hongyi Wang, Kartik Sreenivasan, Shashank Rajput, Harit Vishwakarma, Saurabh Agarwal, Jy-yong Sohn, Kangwook Lee, and Dimitris Papailiopoulos. *NeurIPS*, 2020.
  
- DBA: Distributed Backdoor Attacks against Federated Learning.
  [[pdf]](https://openreview.net/pdf?id=rkgyS0VFvr)
  - Chulin Xie, Keli Huang, Pinyu Chen, and Bo Li. *ICLR*, 2020.
  
- Defending Against Backdoors in Federated Learning with Robust Learning Rate.
  [[pdf]](https://arxiv.org/pdf/2007.03767.pdf)
  - Mustafa Safa Ozdayi, Murat Kantarcioglu, and Yulia R. Gel. *AAAI*, 2021.

- The Limitations of Federated Learning in Sybil Settings.
  [[pdf]](https://www.cs.ubc.ca/~bestchai/papers/foolsgold-raid2020.pdf)
  [[extension]](https://arxiv.org/pdf/1808.04866.pdf)
  [[code]](https://github.com/DistributedML/FoolsGold)
  - Clement Fung, Chris J.M. Yoon, and Ivan Beschastnikh. *RAID*, 2020 (arXiv, 2018).

- Backdoor Attacks and Defenses in Feature-partitioned Collaborative Learning.
  [[pdf]](https://arxiv.org/pdf/2007.03608.pdf)
  - Yang Liu, Zhihao Yi, and Tianjian Chen. *ICML Workshop*, 2020.

- Can You Really Backdoor Federated Learning?
  [[pdf]](https://arxiv.org/pdf/1911.07963.pdf)
  - Ziteng Sun, Peter Kairouz, Ananda Theertha Suresh, and H. Brendan McMahan. *NeurIPS Workshop*, 2019.

- On Provable Backdoor Defense in Collaborative Learning.
  [[pdf]](https://arxiv.org/pdf/2101.08177.pdf)
  - Ximing Qiao, Yuhua Bai, Siping Hu, Ang Li, Yiran Chen, and Hai Li. arXiv, 2021.

- Robust Federated Learning with Attack-Adaptive Aggregation.
  [[pdf]](https://arxiv.org/pdf/2102.05257.pdf)
  [[code]](https://github.com/cpwan/Attack-Adaptive-Aggregation)
  - Ching Pui Wan, and Qifeng Chen. arXiv, 2021.

- Meta Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2102.05561.pdf)
  - Omid Aramoon, Pin-Yu Chen, Gang Qu, and Yuan Tian. arXiv, 2021.

- FLGUARD: Secure and Private Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2101.02281.pdf)
  - Thien Duc Nguyen, Phillip Rieger, Hossein Yalame, Helen Möllering, Hossein Fereidooni, Samuel Marchal, Markus Miettinen, Azalia Mirhoseini, Ahmad-Reza Sadeghi, Thomas Schneider, and Shaza Zeitouni. arXiv, 2021.

- Toward Robustness and Privacy in Federated Learning: Experimenting with Local and Central Differential Privacy.
  [[pdf]](https://arxiv.org/pdf/2009.03561.pdf)
  - Mohammad Naseri, Jamie Hayes, and Emiliano De Cristofaro. arXiv, 2020.

- Backdoor Attacks on Federated Meta-Learning. 
  [[pdf]](https://arxiv.org/pdf/2006.07026.pdf)
  - Chien-Lun Chen, Leana Golubchik, and Marco Paolieri. arXiv, 2020. 

- Dynamic backdoor attacks against federated learning.
  [[pdf]](https://arxiv.org/pdf/2011.07429.pdf)
  - Anbu Huang. arXiv, 2020.

- Federated Learning in Adversarial Settings.
  [[pdf]](https://arxiv.org/pdf/2010.07808.pdf)
  - Raouf Kerkouche, Gergely Ács, and Claude Castelluccia. arXiv, 2020.

- BlockFLA: Accountable Federated Learning via Hybrid Blockchain Architecture.
  [[pdf]](https://arxiv.org/pdf/2010.07427.pdf)
  - Harsh Bimal Desai, Mustafa Safa Ozdayi, and Murat Kantarcioglu. arXiv, 2020.

- Mitigating Backdoor Attacks in Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2011.01767.pdf)
  - Chen Wu, Xian Yang, Sencun Zhu, and Prasenjit Mitra. arXiv, 2020.

- BaFFLe: Backdoor detection via Feedback-based Federated Learning.
  [[pdf]](https://arxiv.org/pdf/2011.02167.pdf)
  - ebastien Andreina, Giorgia Azzurra Marson, Helen Möllering, and Ghassan Karame. arXiv, 2020.

- Learning to Detect Malicious Clients for Robust Federated Learning. 
  [[pdf]](https://arxiv.org/pdf/2002.00211.pdf)
  - Suyi Li, Yong Cheng, Wei Wang, Yang Liu, and Tianjian Chen. arXiv, 2020.
  
- Attack-Resistant Federated Learning with Residual-based Reweighting.
  [[pdf]](https://arxiv.org/pdf/1912.11464.pdf)
  [[code]](https://github.com/fushuhao6/Attack-Resistant-Federated-Learning)
  - Shuhao Fu, Chulin Xie, Bo Li, and Qifeng Chen. arXiv, 2019.
  
### Transfer Learning
- Backdoor Attacks against Transfer Learning with Pre-trained Deep Learning Models.
  [[pdf]](https://arxiv.org/pdf/2001.03274.pdf)
  - Shuo Wang, Surya Nepal, Carsten Rudolph, Marthie Grobler, Shangyu Chen, and Tianle Chen. *IEEE Transactions on Services Computing*, 2020.

- Weight Poisoning Attacks on Pre-trained Models.
  [[pdf]](https://arxiv.org/pdf/2004.06660.pdf)
  [[code]](https://github.com/neulab/RIPPLe)
  - Keita Kurita, Paul Michel, and Graham Neubig. *ACL*, 2020.

- Latent Backdoor Attacks on Deep Neural Networks.
  [[pdf]](http://people.cs.uchicago.edu/~huiyingli/publication/fr292-yaoA.pdf)
  - Yuanshun Yao, Huiying Li, Haitao Zheng and Ben Y. Zhao. *CCS*, 2019.
  
- Red Alarm for Pre-trained Models: Universal Vulnerabilities by Neuron-Level Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2101.06969.pdf)
  [[code]](https://github.com/thunlp/NeuBA)
  - Zhengyan Zhang, Guangxuan Xiao, Yongwei Li, Tian Lv, Fanchao Qi, Zhiyuan Liu, Yasheng Wang, Xin Jiang, and Maosong Sun. arXiv, 2021.

### Others
- Backdoor Attack against Speaker Verification
  [[pdf]](https://arxiv.org/pdf/2010.11607.pdf)
  [[code]](https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification)
  - Tongqing Zhai, Yiming Li, Ziqi Zhang, Baoyuan Wu, Yong Jiang, and Shu-Tao Xia. *ICASSP*, 2021.
  - 
- Explanation-Guided Backdoor Poisoning Attacks Against Malware Classifiers.
  [[pdf]](https://arxiv.org/pdf/2003.01031.pdf)
  - Giorgio Severi, Jim Meyer, Scott Coull, and Alina Oprea. *USENIX Security*, 2021.
 
 
- NeuroAttack: Undermining Spiking Neural Networks Security through Externally Triggered Bit-Flips.
  [[pdf]](https://arxiv.org/pdf/2005.08041.pdf)
  - Valerio Venceslai, Alberto Marchisio, Ihsen Alouani, Maurizio Martina, and Muhammad Shafique. *IJCNN*, 2020.

- Explainability Matters: Backdoor Attacks on Medical Imaging.
  [[pdf]](https://arxiv.org/pdf/2101.00008.pdf)
  - Munachiso Nwadike, Takumi Miyawaki, Esha Sarkar, Michail Maniatakos, and Farah Shamout. *AAAI Workshop*, 2021.

- Trojan Attacks on Wireless Signal Classification with Adversarial Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1910.10766.pdf)
  - Kemal Davaslioglu, and Yalin E. Sagduyu. *DySPAN*, 2019.

- Backdoor Attacks on the DNN Interpretation System.
  [[pdf]](https://arxiv.org/pdf/2011.10698.pdf)
  - Shihong Fang, and Anna Choromanska. *NeurIPS Workshop*, 2020.

- Hidden Backdoor Attack against Semantic Segmentation Models.
  [[pdf]](https://arxiv.org/pdf/2103.04038.pdf)
  - Yiming Li, Yanjie Li, Yalei Lv, Baoyuan Wu, Yong Jiang, and Shu-Tao Xia. arXiv, 2021.

- Embedding and Synthesis of Knowledge in Tree Ensemble Classifiers.
  [[pdf]](https://arxiv.org/pdf/2010.08281.pdf)
  - Wei Huang, Xingyu Zhao, and Xiaowei Huang. arXiv, 2020.

- BAAAN: Backdoor Attacks Against Autoencoder and GAN-Based Machine Learning Models.
  [[pdf]](https://arxiv.org/pdf/2010.03007.pdf)
  - Ahmed Salem, Yannick Sautter, Michael Backes, Mathias Humbert, and Yang Zhang. arXiv, 2020.

- Targeted Forgetting and False Memory Formation in Continual Learners through Adversarial Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2002.07111.pdf)
  - Muhammad Umer, Glenn Dawson, Robi Polikar. arXiv, 2020.

- Backdoors in Neural Models of Source Code.
  [[pdf]](https://arxiv.org/pdf/2006.06841)
  - Goutham Ramakrishnan, and Aws Albarghouthi. arXiv, 2020.

- EEG-Based Brain-Computer Interfaces Are Vulnerable to Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2011.00101.pdf)
  - Lubin Meng, Jian Huang, Zhigang Zeng, Xue Jiang, Shan Yu, Tzyy-Ping Jung, Chin-Teng Lin, Ricardo Chavarriaga, and Dongrui Wu. arXiv, 2020.

- Bias Busters: Robustifying DL-based Lithographic Hotspot Detectors Against Backdooring Attacks.
  [[pdf]](https://arxiv.org/pdf/2004.12492.pdf)
  - Kang Liu, Benjamin Tan, Gaurav Rajavendra Reddy, Siddharth Garg, Yiorgos Makris, and Ramesh Karri. arXiv, 2020.


## Properties Discussion and Evaluation
- On the Trade-off between Adversarial and Backdoor Robustness.
  [[pdf]](https://papers.nips.cc/paper/2020/file/8b4066554730ddfaa0266346bdc1b202-Paper.pdf)
  - Cheng-Hsin Weng, Yan-Ting Lee, and Shan-Hung Wu. *NeurIPS*, 2020.

- A Tale of Evil Twins: Adversarial Inputs versus Poisoned Models.
  [[pdf]](https://arxiv.org/pdf/1911.01559.pdf)
  [[code]](https://github.com/alps-lab/imc)
  - Ren Pang, Hua Shen, Xinyang Zhang, Shouling Ji, Yevgeniy Vorobeychik, Xiapu Luo, Alex Liu, and Ting Wang. *CCS*, 2020.

- Systematic Evaluation of Backdoor Data Poisoning Attacks on Image Classiﬁers.
  [[pdf]](https://arxiv.org/pdf/2004.11514.pdf)
  - Loc Truong, Chace Jones, Brian Hutchinson, Andrew August, Brenda Praggastis, Robert Jasper, Nicole Nichols, and Aaron Tuor. *CVPR Workshop*, 2020.

- On Evaluating Neural Network Backdoor Defenses.
  [[pdf]](https://arxiv.org/pdf/2010.12186.pdf)
  - Akshaj Veldanda, and Siddharth Garg. *NeurIPS Workshop*, 2020.

- Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and Data Poisoning Attacks.
  [[pdf]](https://arxiv.org/pdf/2006.12557.pdf)
  [[code]](https://github.com/aks2203/poisoning-benchmark)
  - Avi Schwarzschild, Micah Goldblum, Arjun Gupta, John P Dickerson, and Tom Goldstein. *NeurIPS Workshop*, 2020.

- Rethinking the Trigger of Backdoor Attack.
  [[pdf]](https://arxiv.org/pdf/2004.04692.pdf)
  - Yiming Li, Tongqing Zhai, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shutao Xia. arXiv, 2020.      

- TROJANZOO: Everything You Ever Wanted to Know about Neural Backdoors (But were Afraid to Ask).
  [[pdf]](https://arxiv.org/pdf/2012.09302.pdf)
  [[code]](https://github.com/ain-soph/trojanzoo)
  - Ren Pang, Zheng Zhang, Xiangshan Gao, Zhaohan Xi, Shouling Ji, Peng Cheng, and Ting Wang. arXiv, 2020.

- Poisoned Classifiers are Not Only Backdoored, They are Fundamentally Broken.
  [[pdf]](https://arxiv.org/pdf/2010.09080.pdf)
  [[code]](https://github.com/locuslab/breaking-poisoned-classifier)
  - Mingjie Sun, Siddhant Agarwal, and J. Zico Kolter. arXiv, 2020.

- Effect of Backdoor Attacks over the Complexity of the Latent Space Distribution.
  [[pdf]](https://arxiv.org/pdf/2012.01931.pdf)
  [[code]](https://github.com/henrychacon/Backdoor_attacks/tree/main/D-Vine_copula_auto_encoder)
  - Henry D. Chacon, and Paul Rad. arXiv, 2020.

- Trembling Triggers: Exploring the Sensitivity of Backdoors in DNN-based Face Recognition.
  [[pdf]](https://link.springer.com/article/10.1186/s13635-020-00104-z)
  - Cecilia Pasquini, and Rainer Böhme. *EURASIP Journal on Information Security*, 2020. 

- Backdoor Attacks on Facial Recognition in the Physical World.
  [[pdf]](https://arxiv.org/pdf/2006.14580.pdf)
  [[Master Thesis]](https://newtraell.cs.uchicago.edu/files/ms_paper/ewillson.pdf)
  - Emily Wenger, Josephine Passanati, Yuanshun Yao, Haitao Zheng, and Ben Y. Zhao. arXiv, 2020.

- Noise-response Analysis for Rapid Detection of Backdoors in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2008.00123.pdf)
  - N. Benjamin Erichson, Dane Taylor, Qixuan Wu, and Michael W. Mahoney. arXiv, 2020.

## Backdoor Attack for Good
- Open-sourced Dataset Protection via Backdoor Watermarking.
  [[pdf]](https://arxiv.org/pdf/2010.05821.pdf)
  - Yiming Li, Ziqi Zhang, Jiawang Bai, Baoyuan Wu, Yong Jiang, and Shu-Tao Xia. *NeurIPS Workshop*, 2020.

- Using Honeypots to Catch Adversarial Attacks on Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1904.08554.pdf)
  - Shawn Shan, Emily Wenger, Bolun Wang, Bo Li, Haitao Zheng, Ben Y. Zhao. *CCS*, 2020. (**Note:** Unfortunately, it was bypassed by Nicholas Carlini most recently. [[arXiv]](https://arxiv.org/pdf/2009.10975.pdf))
  
- Turning Your Weakness into a Strength: Watermarking Deep Neural Networks by Backdooring.
  [[pdf]](https://arxiv.org/pdf/1802.04633.pdf)
  [[code]](https://github.com/adiyoss/WatermarkNN)
  - Yossi Adi, Carsten Baum, Moustapha Cisse, Benny Pinkas, and Joseph Keshet. *USENIX Security*, 2018. 

- What Do Deep Nets Learn? Class-wise Patterns Revealed in the Input Space.
  [[pdf]](https://arxiv.org/pdf/2101.06898.pdf)
  - Shihao Zhao, Xingjun Ma, Yisen Wang, James Bailey, Bo Li, and Yu-Gang Jiang. arXiv, 2021.

- What Do You See? Evaluation of Explainable Artificial Intelligence (XAI) Interpretability through Neural Backdoors.
  [[pdf]](https://arxiv.org/pdf/2009.10639.pdf)
  - Yi-Shan Lin, Wen-Chuan Lee, and Z. Berkay Celik. arXiv, 2020.

- Towards Probabilistic Verification of Machine Unlearning.
  [[pdf]](https://arxiv.org/pdf/2003.04247.pdf)
  [[code]](https://github.com/inspire-group/unlearning-verification)
  - David Marco Sommer, Liwei Song, Sameer Wagh, and Prateek Mittal. arXiv, 2020. 

## Toolbox
- [TrojanZoo](https://github.com/ain-soph/trojanzoo)

## Competition
- [IARPA TrojAI Competition](https://pages.nist.gov/trojai/docs/about.html)
