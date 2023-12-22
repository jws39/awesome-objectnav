# Awesome ObjectNav 
Inspired by the [awesome-embodied-vision](https://github.com/ChanganVR/awesome-embodied-vision) and [awesome-vln](https://github.com/daqingliu/awesome-vln).

By Jingwen Sun (sunj39@cardiff.ac.uk), School of Computer Science and Informatics at Cardiff University. If you see papers missing from the list, please send me an email.

## Table of Content

* [Survey](#survey)
* [Simulators](#simulators)
* [Datasets](#datasets)

* [Methods](#methods)
  * [End-to-end Methods](#end-to-end)
  * [Modular Methods](#modular)
  * [Zero-shot Methods](#zero-shot)
* [Related Tasks](#related-tasks)
* [MISC](#misc)

## <span id='survey'>Survey</span>

* **On Evaluation of Embodied Navigation Agents** <br>
  *Peter Anderson, Angel Chang, Devendra Singh Chaplot, Alexey Dosovitskiy, Saurabh Gupta, Vladlen Koltun, Jana Kosecka, Jitendra Malik, Roozbeh Mottaghi, Manolis Savva, Amir R. Zamir* <br>
  arXiv, 2018. [[Paper]](https://arxiv.org/abs/1807.06757)

* **ObjectNav Revisited On Evaluation of Embodied Agents Navigating to Objects**<br>*Dhruv Batra, Aaron Gokaslan, Ani Kembhavi, Oleksandr Maksymets, Roozbeh Mottaghi1, Manolis Savva, Alexander Toshev, Erik Wijmans*<br> arXiv, 2020. [[Paper]](https://arxiv.org/abs/2006.13171)

* **From Seeing to Moving: A Survey on Learning for Visual Indoor Navigation**<br>*Xin Ye and Yezhou Yang*<br>arXiv, 2020. [[Paper]](https://arxiv.org/pdf/2002.11310.pdf)

* **Deep Learning for Embodied Visual Navigation Research: A survey**<br>*Fengda Zhu, Yi Zhu, Vincent CS Lee, Xiaodan Liang and Xiaojun Chang*<br>arXiv, 2020. [[Paper]](https://arxiv.org/abs/2108.04097)

* **A Survey of Embodied AI: From Simulators to Research Tasks**<br>*Jiafei Duan , Samson Yu, Hui Li Tan , Hongyuan Zhu, and Cheston Tan*<br>IEEE Transactions on Emerging Topics in Computational Intelligence, 2022. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9687596)

* **A Survey of Visual Navigation: From Geometry to Embodied AI**<br>*Tianyao Zhang, Xiaoguang Hu, Jin Xiao, Guofeng Zhang*<br>Engineering Applications of Artificial Intelligence, 2022. [[Paper]](https://www.sciencedirect.com/science/article/pii/S095219762200207X)

* **Navigating to Objects in the Real World** <br>*Theophile Gervet, Soumith Chintala, Dhruv Batra, Jitendra Malik, Devendra Singh Chaplot* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2212.00922)

## <span id='simulators'>Simulators</span>

* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
  *Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
  arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)
* **Building Generalizable Agents with a Realistic and Rich 3D Environment (House3D)** <br>
  *Yi Wu, Yuxin Wu, Georgia Gkioxari, Yuandong Tian* <br>
  arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1801.02209.pdf) [[Code]](https://github.com/facebookresearch/House3D)
* **RoboTHOR: An Open Simulation-to-Real Embodied AI Platform** <br>
  *Matt Deitke, Winson Han, Alvaro Herrasti, Aniruddha Kembhavi, Eric Kolve, Roozbeh Mottaghi, Jordi Salvador, Dustin Schwenk, Eli VanderBilt, Matthew Wallingford, Luca Weihs, Mark Yatskar, Ali Farhadi* <br>
  CVPR, 2020. [[Paper]](https://arxiv.org/abs/2004.06799) [[Website]](https://ai2thor.allenai.org/robothor)
* **Gibson Env: Real-World Perception for Embodied Agents** <br>
  *Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
  CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)
* **Habitat: A Platform for Embodied AI Research** <br>
  *Manolis Savva, Abhishek Kadian, Oleksandr Maksymets, Yili Zhao, Erik Wijmans, Bhavana Jain, Julian Straub, Jia Liu, Vladlen Koltun, Jitendra Malik, Devi Parikh, Dhruv Batra* <br>
  ICCV, 2019. [[Paper]](https://arxiv.org/abs/1904.01201) [[Code]](https://github.com/facebookresearch/habitat-api) [[Website]](https://aihabitat.org/)
* **VirtualHome: Simulating Household Activities via Programs** <br>
  *Xavier Puig\*, Kevin Ra\*, Marko Boben\*, Jiaman Li, Tingwu Wang, Sanja Fidler, Antonio Torralba* <br>
  CVPR, 2018. [[Paper]](http://virtual-home.org/paper/virtualhome.pdf) [[Code]](https://github.com/xavierpuigf/virtualhome) [[Website]](http://virtual-home.org/)
* **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** <br>
  *Mohit Shridhar, Xingdi Yuan, Marc-Alexandre Côté, Yonatan Bisk, Adam Trischler, Matthew Hausknecht*<br>
  ICLR, 2021. [[Paper]](https://arxiv.org/abs/2010.03768) [[Code]](https://github.com/alfworld/alfworld) [[Website]](https://alfworld.github.io/)
* **ManipulaTHOR: A Framework for Visual Object Manipulation** <br>
  *Kiana Ehsani, Winson Han, Alvaro Herrasti, Eli VanderBilt, Luca Weihs, Eric Kolve, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
  CVPR, 2021. [[Paper]](https://arxiv.org/pdf/2104.11213.pdf) [[Code]](https://github.com/allenai/manipulathor) [[Website]](https://ai2thor.allenai.org/manipulathor/)
* **🏘️ ProcTHOR: Large-Scale Embodied AI Using Procedural Generation** <br>
  *Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Jordi Salvador, Kiana Ehsani, Winson Han, Eric Kolve, Ali Farhadi, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
  arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2206.06994.pdf) [[Website]](https://procthor.allenai.org/)

## <span id='datasets'>Datasets</span> 

* **AI2-THOR: An Interactive 3D Environment for Visual AI** <br>
  *Eric Kolve, Roozbeh Mottaghi, Winson Han, Eli VanderBilt, Luca Weihs, Alvaro Herrasti, Daniel Gordon, Yuke Zhu, Abhinav Gupta, Ali Farhadi* <br>
  arXiv, 2017. [[Paper]](https://arxiv.org/abs/1712.05474) [[Code]](https://github.com/allenai/ai2thor) [[Website]](https://ai2thor.allenai.org/)
* **Matterport3D: Learning from RGB-D Data in Indoor Environments** <br>
  *Angel Chang, Angela Dai, Thomas Funkhouser, Maciej Halber, Matthias Nießner, Manolis Savva, Shuran Song, Andy Zeng, Yinda Zhang* <br>
  3DV, 2017. [[Paper]](https://arxiv.org/pdf/1709.06158.pdf) [[Code]](https://github.com/niessner/Matterport) [[Website]](https://niessner.github.io/Matterport/)
* **Gibson Env: Real-World Perception for Embodied Agents** <br>
  *Fei Xia, Amir Zamir, Zhi-Yang He, Alexander Sax, Jitendra Malik, Silvio Savarese* <br>
  CVPR, 2018. [[Paper]](https://arxiv.org/abs/1808.10654) [[Code]](https://github.com/StanfordVL/GibsonEnv) [[Website]](http://gibsonenv.stanford.edu/)
* **The Replica Dataset: A Digital Replica of Indoor Spaces** <br>
  *Julian Straub, Thomas Whelan, Lingni Ma, Yufan Chen, Erik Wijmans, Simon Green, Jakob J. Engel, Raul Mur-Artal, Carl Ren, Shobhit Verma, Anton Clarkson, Mingfei Yan, Brian Budge, Yajie Yan, Xiaqing Pan, June Yon, Yuyang Zou, Kimberly Leon, Nigel Carter, Jesus Briales, Tyler Gillingham, Elias Mueggler, Luis Pesqueira, Manolis Savva, Dhruv Batra, Hauke M. Strasdat, Renzo De Nardi, Michael Goesele, Steven Lovegrove, Richard Newcombe* <br>
  arXiV, 2019. [[Paper]](https://arxiv.org/pdf/1906.05797.pdf) [[Code]](https://github.com/facebookresearch/Replica-Dataset)
* **Actionet: An Interactive End-to-End Platform for Task-Based Data Collection and Augmentation in 3D Environments** <br>
  *Jiafei Duan, Samson Yu, Hui Li Tan, Cheston Tan* <br>
  ICIP, 2020. [[Paper]](https://arxiv.org/pdf/2010.01357.pdf) [[Code]](https://github.com/SamsonYuBaiJian/actionet)
* **Habitat-Matterport 3D Dataset (HM3D): 1000 Large-scale 3D Environments for Embodied AI** <br>
  *Santhosh K. Ramakrishnan, Aaron Gokaslan, Erik Wijmans, Oleksandr Maksymets, Alex Clegg, John Turner, Eric Undersander, Wojciech Galuba, Andrew Westbury, Angel X. Chang, Manolis Savva, Yili Zhao, Dhruv Batra* <br>
  NeurIPS, 2021. [[Paper]](https://openreview.net/forum?id=-v4OuqNs5P) [[Website]](https://aihabitat.org/datasets/hm3d/)
* **Habitat-Matterport 3D Semantics Dataset**<br>*Karmesh Yadav, Ram Ramrakhya, Santhosh Kumar Ramakrishnan, Theo Gervet, John Turner, Aaron Gokaslan, Noah Maestre, Angel Xuan Chang, Dhruv Batra, Manolis Savva, Alexander William Clegg, Devendra Singh Chaplot*<br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2210.05633) [[Website]](https://aihabitat.org/datasets/hm3d-semantics/)
* **🏘️ ProcTHOR: Large-Scale Embodied AI Using Procedural Generation** <br>
  *Matt Deitke, Eli VanderBilt, Alvaro Herrasti, Luca Weihs, Jordi Salvador, Kiana Ehsani, Winson Han, Eric Kolve, Ali Farhadi, Aniruddha Kembhavi, Roozbeh Mottaghi* <br>
  arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2206.06994.pdf) [[Website]](https://procthor.allenai.org/)

## <span id='methods'>Methods</span>

### <span id='end-to-end'>End-to-end Methods</span>

#### Visual Representation

- **Visual Representations for Semantic Target Driven Navigation** <br>
  *Arsalan Mousavian, Alexander Toshev, Marek Fiser, Jana Kosecka, Ayzaan Wahid, James Davidson* <br>
  ICRA, 2019. [[Paper]](https://ieeexplore.ieee.org/document/8793493) [[Code]](https://github.com/arsalan-mousavian/Navigation)
- **Indoor Navigation for Mobile Agents: A Multimodal Vision Fusion Model** <br>*Dongfang Liu, Yiming Cui, Zhiwen Cao, Yingjie Chen* <br>International Joint Conference on Neural Networks, 2020. [[Paper]](https://ieeexplore.ieee.org/document/9207265)
- **Situational Fusion of Visual Representation for Visual Navigation** <br>
  *William B. Shen, Danfei Xu, Yuke Zhu, Leonidas J. Guibas, Li Fei-Fei, Silvio Savarese* <br>
  ICCV, 2019. [[Paper]](https://ieeexplore.ieee.org/document/9009052)
- **Offline Visual Representation Learning for Embodied Navigation** <br>*Karmesh Yadav, Ram Ramrakhya, Arjun Majumdar, Vincent-Pierre Berges, Sachit Kuhar, Dhruv Batra, Alexei Baevski, Oleksandr Maksymets* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2204.13226)

- **Learning Object Relation Graph and Tentative Policy for Visual Navigation** <br>
  *Heming Du, Xin Yu, Liang Zheng* <br>
  ECCV, 2020. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-58571-6_2) [[Code]](https://github.com/xiaobaishu0097/ECCV-VN)
- **Visual Object Search by Learning Spatial Context** <br>*Raphael Druon , Yusuke Yoshiyasu , Asako Kanezaki , and Alassane Watt* <br>RAL, 2020. [[Paper]](https://ieeexplore.ieee.org/document/8963758)
- **Exploiting Scene-specific Features for Object Goal Navigation** <br>*Tommaso Campari, Paolo Eccher, Luciano Serafini, Lamberto Ballan* <br>ECCV, 2020. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-66823-5_24)
- **Indoor Target-Driven Visual Navigation based on Spatial Semantic Information** <br>*Jiaojie Yan, Qieshi Zhang, Jun Cheng, Ziliang Ren, Tian Li, Zhuo Yang* <br>ICIP, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9898026)

- **Visual Semantic Navigation using Scene Priors** <br>
  *Wei Yang, Xiaolong Wang, Ali Farhadi, Abhinav Gupta, Roozbeh Mottaghi* <br>
  ICLR, 2019. [[Paper]](https://arxiv.org/abs/1810.06543)
- **Reinforcement Learning Based Navigation with Semantic Knowledge of Indoor Environments** <br>*Tai-Long Nguyen, Do-Van Nguyen, Thanh-Ha Le* <br>International Conference on Knowledge and Systems Engineering (KSE), 2019. [[Paper]](https://ieeexplore.ieee.org/document/8919366)
- **Learning Hierarchical Relationships for Object-goal Navigation** <br>
  *Yiding Qiu, Anwesan Pal, Henrik I. Christensen* <br>
  CoRL, 2020. [[Paper]](https://arxiv.org/abs/2003.06749) [[Code]](https://github.com/cassieqiuyd/MJOLNIR)
- **Deep Reinforcement Learning for Visual Semantic Navigation with Memory** <br>*Iury Batista de Andrade Santos, Roseli A. F. Romero* <br>Latin American Robotics Symposium (LARS), 2020. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9307029)
- **Visual Navigation via Reinforcement Learning and Relational Reasoning** <br>*Kang Zhou, Chi Guo, Huyin Zhang* <br>SmartWorld, 2021. [[Paper]](https://ieeexplore.ieee.org/document/9604417)
- **Object Goal Visual Navigation using Semantic Spatial Relationships** <br>*Jingwen Guo, Zhisheng Lu, Ti Wang, Weibo Huang, and Hong Liu* <br>First CAAI International Conference on Artificial Intelligence (CICAI), 2021. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-93046-2_7)
- **Hierarchical Object-to-Zone Graph for Object Navigation** <br>
  *Sixian Zhang, Xinhang Song, Yubing Bai, Weijie Li, Yakui Chu, Shuqiang Jiang* <br>
  ICCV, 2021. [[Paper]](https://arxiv.org/abs/2109.02066) [[Code]](https://github.com/sx-zhang/HOZ.git) [[Video]](https://drive.google.com/file/d/1UtTcFRhFZLkqgalKom6_9GpQmsJfXAZC/view) 

- **Visual Navigation With Spatial Attention** <br>
  *Bar Mayo, Tamir Hazan, Ayellet Tal* <br>
  CVPR, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Mayo_Visual_Navigation_With_Spatial_Attention_CVPR_2021_paper.pdf) [[Code]](https://github.com/barmayo/spatial_attention)
- **VTNet: Visual Transformer Network for Object Goal Navigation** <br>
  *Heming Du, Xin Yu, Liang Zheng* <br>
  ICLR, 2021. [[Paper]](https://openreview.net/pdf?id=DILxQP08O3B) [[Code]](https://github.com/xiaobaishu0097/ICLR_VTNet)
- **Object Memory Transformer for Object Goal Navigation** <br>*Rui Fukushima, Kei Ota, Asako Kanezaki, Yoko Sasaki, Yusuke Yoshiyasu* <br>ICRA, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9812027) 
- **Unbiased Directed Object Attention Graph for Object Navigation** <br>*Ronghao Dang, Zhuofan Shi, Liuyi Wang, Zongtao He, Chengju Liu, Qijun Chen* <br>ACM International Conference on Multimedia, 2022. [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3547852)
- **Double Graph Attention Networks for Visual Semantic Navigation** <br>*Yunlian Lyu, Mohammad Sadegh Talebi* <br>Neural Processing Letters, 2023. [[Paper]](https://dl.acm.org/doi/abs/10.1007/s11063-023-11190-8)

#### Policy Learning

- **Learning to Learn How to Learn: Self-Adaptive Visual Navigation Using Meta-Learning** <br>
  *Mitchell Wortsman, Kiana Ehsani, Mohammad Rastegari, Ali Farhadi, Roozbeh Mottaghi* <br>
  CVPR, 2019. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wortsman_Learning_to_Learn_How_to_Learn_Self-Adaptive_Visual_Navigation_Using_CVPR_2019_paper.pdf) [[Code]](https://github.com/allenai/savn) [[Website]](https://prior.allenai.org/projects/savn)
- **Efficient Robotic Object Search Via HIEM Hierarchical Policy Learning with Intrinsic-Extrinsic Modeling** <br>*Xin Ye, Yezhou Yang* <br>RAL, 2021. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9387146) [[Code]](https://github.com/Xin-Ye-1/HIEM)

* **THDA: Treasure Hunt Data Augmentation for Semantic Navigation** <br>
*Oleksandr Maksymets, Vincent Cartillier, Aaron Gokaslan, Erik Wijmans, Wojciech Galuba, Stefan Lee, Dhruv Batra* <br>
ICCV, 2021. [[Paper]](https://ieeexplore.ieee.org/document/9711292)
* **Auxiliary Tasks and Exploration Enable ObjectGoal Navigation** <br>
*Peter Karkus, Shaojun Cai, David Hsu* <br>
ICCV, 2021. [[Paper]](https://ieeexplore.ieee.org/document/9710020) [[Code]](https://github.com/joel99/objectnav) [[Website]](https://joel99.github.io/objectnav/)
* **ForeSI: Success-Aware Visual Navigation Agent**<br>*Mahdi Kazemi Moghaddam, Ehsan Abbasnejad, Qi Wu, Javen Qinfeng shi, Anton Van Den Hengel* <br>WACV, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9707055)
* **Habitat-Web: Learning Embodied Object-Search Strategies from Human Demonstrations at Scale** <br>*Ram Ramrakhya, Eric Undersander, Dhruv Batra, Abhishek Das* <br>CVPR, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9880429) [[Website]](https://ram81.github.io/projects/habitat-web) [[Code]](https://github.com/Ram81/habitat-web)
* **A General Purpose Supervisory Signal for Embodied Agents**<br>*Kunal Pratap Singh, Jordi Salvador, Luca Weihs, Aniruddha Kembhavi* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2212.01186#:~:text=Training%20effective%20embodied%20AI%20agents,sensors%20for%20depth%20and%20localization.)
* **PIRLNav: Pretraining with Imitation and RL Finetuning for OBJECTNAV**<br>*Ram Ramrakhya, Dhruv Batra, Erik Wijmans, Abhishek Das* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2301.07302) [[Website]](https://ram81.github.io/projects/pirlnav)
* **Search for or Navigate to Dual Adaptive Thinking for Object Navigation**<br>*Ronghao Dang, Liuyi Wang, Zongtao He, Shuai Su, Chengju Liu, Qijun Chen* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2208.00553)

* **Layout-based Causal Inference for Object Navigation**<br>*Sixian Zhang, Xinhang Song, Weijie Li , Yubing Bai, Xinyao Yu, Shuqiang Jiang* <br>CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Layout-Based_Causal_Inference_for_Object_Navigation_CVPR_2023_paper.pdf)
* **Skill-based Hierarchical Reinforcement Learning for Target Visual Navigation**<br>*Shuo Wang, Zhihao Wu, Xiaobo Hu, Youfang Lin, and Kai Lv* <br>IEEE Transactions on Multimedia, 2023. [[Paper]](https://ieeexplore.ieee.org/document/10041739)

* **Object-Goal Visual Navigation via Effective Exploration of Relations Among Historical States**<br>*Heming Du, Lincheng Li, Zi Huang, Xin Yu* <br>CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Du_Object-Goal_Visual_Navigation_via_Effective_Exploration_of_Relations_Among_Historical_CVPR_2023_paper.pdf)

* **Multiple Thinking Achieving Meta-Ability Decoupling for Object Navigation**<br>*Ronghao Dang, Lu Chen, Liuyi Wang, Zongtao He, Chengju Liu, Qijun Chen* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2302.01520)

* **Implicit Obstacle Map-driven Indoor Navigation Model for Robust Obstacle Avoidance**<br>*Wei Xie, Haobo Jiang, Shuo Gu, Jin Xie* <br>Proceedings of the 31st ACM International Conference on Multimedia, 2023. [[Paper]](https://dl.acm.org/doi/10.1145/3581783.3612100)

* **Skill Fusion in Hybrid Robotic Framework for Visual Object Goal Navigation**<br>*Aleksei Staroverov, Kirill Muravyev, Konstantin Yakovlev and Aleksandr I. Panov* <br>Robotics, 2023. [[Paper]](https://www.mdpi.com/2218-6581/12/4/104)

* **Learning to Terminate in Object Navigation**<br>*Yuhang Song, Anh Nguyen, Chun-Yi Lee* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2309.16164v1)

* **Skill-Dependent Representations for Object Navigation**<br>*Youkai Wang, Yue Hu, Wansen Wu, Ting Liu and Yong Pen*g<br>International Conference on Intelligent Robotics and Control Engineering (IRCE), 2023. [[Paper]](https://ieeexplore.ieee.org/document/10255036)

* **A Few Shot Adaptation of Visual Navigation Skills to New Observations using Meta-Learning**<br>*Qian Luo, Maks Sorokin and Sehoon Ha*<br>ICRA, 2021. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9561056)

* **Unsupervised Reinforcement Learning of Transferable Meta-Skills for Embodied Navigation**<br>*Juncheng Li, Xin Wang, Siliang Tang, Haizhou Shi, Fei Wu, Yueting Zhuang and  William Yang Wang* <br>CVPR, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Unsupervised_Reinforcement_Learning_of_Transferable_Meta-Skills_for_Embodied_Navigation_CVPR_2020_paper.pdf)

* **Multi goals and multi scenes visual mapless navigation in indoor using meta-learning and scene priors**<br>*Fei Li, Chi Guo, Binhan Luo and Huyin Zhang*<br>Neurocomputing, 2021. [[Paper]](https://www.sciencedirect.com/science/article/pii/S0925231221004707)

* **Context vector-based visual mapless navigation in indoor using hierarchical semantic information and meta-learning**<br>*Fei Li, Chi Guo, Huyin Zhang and Binhan Luo* <br>Complex & Intelligent Systems, 2023. [[Paper]](https://link.springer.com/article/10.1007/s40747-022-00902-7)


### <span id='modular'>Modular Methods</span> 

#### Grid Map without Prediction

- **Cognitive Mapping and Planning for Visual Navigation** <br>*Saurabh Gupta, Varun Tolani, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik* <br>CVPR, 2017. [[Paper]](https://arxiv.org/abs/1702.03920)
- **Object Goal Navigation using Goal-Oriented Semantic Exploration** <br>
  *Devendra Singh Chaplot, Dhiraj Prakashchand Gandhi, Abhinav Gupta, Russ R. Salakhutdinov* <br>
  NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/2c75cf2681788adaca63aa95ae028b22-Abstract.html) [[Website]](https://devendrachaplot.github.io/projects/semantic-exploration) [[Code]](https://github.com/devendrachaplot/Object-Goal-Navigation)
- **Stubborn: A Strong Baseline for Indoor Object Navigation** <br>*Haokuan Luo, Albert Yue, Zhang-Wei Hong, Pulkit Agrawal* <br>IROS, 2022. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9981646) [[Code]](https://github.com/Improbable-AI/Stubborn)
- **A Contextual Bandit Approach for Learning to Plan in Environments with Probabilistic Goal Configurations** <br>*Sohan Rudra, Saksham Goel, Anirban Santara, Claudio Gentile, Laurent Perron, Fei Xia, Vikas,Sindhwani, Carolina Parada*  <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2211.16309)
- **3D-Aware Object Goal Navigation via Simultaneous Exploration and Identification** <br>*Jiazhao Zhang, Liu Dai, Fanpeng Meng, Kingman Fan, Xuelin Chen, Kai Xu, He Wang* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2212.00338)

#### Grid Map with Prediction

- **SSCNav Confidence-Aware Semantic Scene Completion for Visual Semantic Navigation** <br>*Yiqing Liang, Boyuan Chen, Shuran Song* <br>ICRA, 2021. [[Paper]](https://ieeexplore.ieee.org/document/9560925) [[Website]](https://sscnav.cs.columbia.edu/) [[Code]](https://github.com/columbia-ai-robotics/SSCNav)
- **Learning to Map for Active Semantic Goal Navigation**<br>*Georgios Georgakis, Bernadette Bucher, Karl Schmeckpeper, Siddharth Singh, Kostas Daniilidis* <br>ICLR, 2022. [[Paper]](https://arxiv.org/abs/2106.15648) [[Code]](https://github.com/ggeorgak11/L2M)
- **PONI: Potential Functions for ObjectGoal Navigation with Interaction-free Learning** <br>*Santhosh Kumar Ramakrishnan, Devendra Singh Chaplot, Ziad Al-Halah, Jitendra Malik, Kristen Grauman* <br>CVPR, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9879980) [[Code]](https://github.com/srama2512/PONI)
- **Navigating to Objects in Unseen Environments by Distance Prediction** <br>*Minzhao Zhu, Binglei Zhao, Tao Kong* <br>IROS, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9981766) 
- **Predicting Dense and Context-aware Cost Maps for Semantic Robot Navigation** <br>*Yash Goel, Narunas Vaskevicius, Luigi Palmieri, Nived Chebrolu, Cyrill Stachniss* <br>IROS, 2022. [[Paper]](https://iros2022-pnarude.github.io/pdf/PNARUDE_IROS2022_Yash_Goel_Narunas_Vaskevicius_Predicting_Dense_and_Context-aware_Cost_Maps_for_Semantic_Robot_Navigation.pdf)
- **Object Goal Navigation with End-to-End Self-Supervision** <br>*So Yeon Minyz, Yao-Hung Hubert Tsaiy, Wei Dingy, Ali Farhadiy, Ruslan Salakhutdinovz, Yonatan Biskz, Jian Zhangy* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2212.05923)

#### Graph-based Map Representation 

- **Semantic Visual Navigation by Watching YouTube Videos** <br>
  *Matthew Chang, Arjun Gupta, Saurabh Gupta* <br>
  NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/2cd4e8a2ce081c3d7c32c3cde4312ef7-Abstract.html) [[Website]](https://matthewchang.github.io/value-learning-from-videos/)
- **GCExp: Goal-Conditioned Exploration for Object Goal Navigation** <br>*Gulshan Kumar, N. Sai Shankar, Himansu Didwania, R.D. Roychoudhury, Brojeshwar Bhowmick, K. Madhava Krishna* <br>IEEE International Conference on Robot & Human Interactive Communication (RO-MAN), 2021. [[Paper]](https://ieeexplore.ieee.org/document/9515530)
- **Spatial Relation Graph and Graph Convolutional Network for Object Goal Navigation** <br>*D. A. Sasi Kiran, Kritika Anand, Chaitanya Kharyal, Gulshan Kumar, Nandiraju Gireesh, Snehasis Banerjee, Ruddra dev Roychoudhury, Mohan Sridharan* <br>International Conference on Automation Science and Engineering (CASE), 2022. [[Paper]](https://ieeexplore.ieee.org/document/9926534)
- **Hierarchical Landmark Policy Optimization for Visual Indoor Navigation** <br>*Aleksey Staroverov, Aleksandr I. Panov* <br>IEEE Access, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9795006)
- **Online Learning of Reusable Abstract Models for Object Goal Navigation** <br>*Tommaso Campari, Leonardo Lamanna, Paolo Traverso, Luciano Serafini, Lamberto Ballan* <br>CVPR, 2022. [[Paper]](https://ieeexplore.ieee.org/document/9879130)
- **ReVoLT: Relational Reasoning and Voronoi Local Graph Planning** <br>*Junjia Liu, Jianfei Guo, Zehui Meng, Jingtao Xue* <br> arXiv, 2023. [[Paper]](https://arxiv.org/abs/2301.02382) [[Website]](https://ventusff.github.io/ReVoLT-website/)
- **How To Not Train Your Dragon: Training-free Embodied Object Goal Navigation with Semantic Frontiers** <br>*Junting Chen, Guohao Li, Suryansh Kumar, Bernard Ghanem,Fisher Yu*<br> RSS, 2023. [[Paper]](https://arxiv.org/abs/2305.16925) [[Website]](https://sgtvincent.github.io/StructNav/)

### <span id='zero-shot'>Zero-shot Methods</span>

- **CLIP on Wheels: Zero-Shot Object Navigation as Object Localization and Exploration** <br>*Samir Yitzhak Gadre, Mitchell Wortsman, Gabriel Ilharco,Ludwig Schmidt,Shuran Song* <br>arXiv, 2022. [[Paper]](https://arxiv.org/pdf/2203.10421.pdf) [[Website]](https://cow.cs.columbia.edu/)
- **EmbCLIP: Simple but Effective CLIP Embeddings for Embodied AI** <br>*Apoorv Khandelwal, Luca Weihs, Roozbeh Mottaghi, Aniruddha Kembhavi* <br>CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Khandelwal_Simple_but_Effective_CLIP_Embeddings_for_Embodied_AI_CVPR_2022_paper.html) [[Code]](https://github.com/allenai/embodied-clip)
- **ZSON: Zero-Shot Object-Goal Navigation using Multimodal Goal Embeddings** <br>*Arjun Majumdar, Gunjan Aggarwal, Bhavika Devnani, Judy Hoffman, Dhruv Batra* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2206.12403) 
- **Zero Experience Required: Plug Play Modular Transfer Learning for Semantic Navigation** <br>*Ziad Al-Halah, Santhosh K. Ramakrishnan, Kristen Grauman* <br>CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Al-Halah_Zero_Experience_Required_Plug__Play_Modular_Transfer_Learning_for_CVPR_2022_paper.pdf) [[Code]](https://github.com/ziadalh/zero_experience_required) [[Website]](https://vision.cs.utexas.edu/projects/zsel/)
- **Zero-Shot Object Goal Visual Navigation** <br> *Qianfan Zhao, Lu Zhang, Bin He, Hong Qiao, Zhiyong Liu* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2206.07423) [[Code]](https://github.com/pioneer-innovation/Zero-Shot-Object-Navigation)
- **Generative Meta-Adversarial Network for Unseen Object Navigation**<br>*Sixian Zhang, Weijie Li, Xinhang Song, Yubing Bai, Shuqiang Jiang* <br>ECCV, 2022. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-19842-7_18)

- **Zero-Shot Object Searching Using Large-scale Object Relationship Prior**<br>*Hongyi Chen, Ruinian Xu, Shuo Cheng, Patricio A. Vela, Danfei Xu* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2303.06228)

- **Can an Embodied Agent Find Your “Cat-shaped Mug”?LLM-Based Zero-Shot Object Navigation**<br>*Vishnu Sashank Dorbala, James F. Mullen Jr, and Dinesh Manocha* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2303.03480) [[Website]](https://gamma.umd.edu/researchdirections/socrob/lgx/) [[Code]](https://github.com/vdorbala/LGX)

- **L3MVN: Leveraging Large Language Models for Visual Target Navigation**<br>*Bangguo Yu, Hamidreza Kasaei, Ming Cao* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2304.05501)

- **ESC: Exploration with Soft Commonsense Constraints for Zero-shot Object Navigation**<br>*Kaiwen Zhou, Kaizhi Zheng, Connor Pryor, Yilin Shen, Hongxia Jin, Lise Getoor, Xin Eric Wang* <br>ICML, 2023. [[Paper]](https://arxiv.org/abs/2301.13166) [[Website]](https://sites.google.com/ucsc.edu/escnav/home)

- **Co-NavGPT: Multi-Robot Cooperative Visual Semantic Navigation using Large Language Models**<br>*Bangguo Yu, Hamidreza Kasaei, Ming Cao* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2310.07937)

- **Semantic Policy Network for Zero-Shot Object Goal Visual Navigation**<br>*Qianfan Zhao, Lu Zhang, Bin He, and Zhiyong Liu* <br>IEEE Robotics and Automation Letters (RAL), 2023. [[Paper]](https://ieeexplore.ieee.org/document/10265178)

- **Bridging Zero-shot Object Navigation and Foundation Models through Pixel-Guided Navigation Skill**<br>*Wenzhe Cai, Siyuan Huang, Guangran Cheng, Yuxing Long, Peng Gao, Changyin Sun, Hao Dong* <br>arXiv, 2023. [[Paper]](https://arxiv.org/abs/2309.10309) [[Code]](https://github.com/wzcai99/Pixel-Navigator?utm_source=catalyzex.com)


## <span id='related-tasks'>Related Tasks</span>

### MultiON 

- **MultiON: Benchmarking Semantic Map Memory using Multi-Object Navigation** <br>*Saim Wani, Shivansh Patel, Unnat Jain, Angel X. Chang, Manolis Savva* <br>NeurIPS, 2020. [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/6e01383fd96a17ae51cc3e15447e7533-Abstract.html) [[Code]](https://github.com/saimwani/multiON) [[Website]](https://shivanshpatel35.github.io/multi-ON/)
- **SGoLAM: Simultaneous Goal Localization and Mapping for Multi-Object Goal Navigation** <br>*Junho Kim, Eun Sun Lee, Mingi Lee, Dongsu Zhang, Young Min Kim* <br>arXiv, 2021. [[Paper]](https://arxiv.org/abs/2110.07171) [[Code]](https://github.com/eunsunlee/SGoLAM)
- **Learning Active Camera for Multi-Object Navigation** <br>*Peihao Chen, Dongyu Ji, Kunyang Lin, Weiwen Hu, Wenbing Huang, Thomas H. Li, Mingkui Tan, Chuang Gan* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2210.07505) 
- **Learning Long-Horizon Robot Exploration Strategies for Multi-Object Search in Continuous Action Spaces**<br>*Fabian Schmalstieg, Daniel Honerkamp, Tim Welschehold, Abhinav Valada* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2205.11384)
- **Multi-Object Navigation with Dynamically Learned Neural Implicit Representations** <br>*Pierre Marza, Laetitia Matignon, Olivier Simonin, Christian Wolf* <br>arXiv, 2022. [[Paper]](https://arxiv.org/abs/2210.05129)
- **Teaching Agents how to Map Spatial Reasoning for Multi-Object Navigation** <br>*Pierre Marza, Laetitia Matignon, Olivier Simonin, Christian Wolf* <br>IROS, 2022. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9982216)

### ION

- **ION: Instance-level Object Navigation** <br>*Weijie Li, Xinhang Song, Yubing Bai, Sixian Zhang, Shuqiang Jiang* <br>ACM International Conference on Multimedia, 2021. [[Paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475575)

### RoomNav

- **Bayesian Relational Memory for Semantic Visual Navigation** <br>*Yi Wu, Yuxin Wu, Aviv Tamar, Stuart Russell, Georgia Gkioxari, Yuandong Tian* <br>ICCV, 2019. [[Paper]](https://arxiv.org/abs/1909.04306) [[Code]](https://github.com/jxwuyi/HouseNavAgent?utm_source=catalyzex.com)

## <span id='misc'>MISC</span>
* **Embodied AI Workshop**<br>CVPR, 2020/2021/2022/2023. [[Website]](https://embodied-ai.org/#overview)
* **iGibson Challenge 2022** <br>
  CVPR, 2022. [[Website]](http://svl.stanford.edu/igibson/challenge.html)
* **Closing the Reality Gap in Sim2Real Transfer for Robotics** <br>
  RSS, 2022. [[Website]](https://sim2real.github.io/?fbclid=IwAR0fyyc_k8AmmYYRHbJJtjqGonAn1TUhUPWEdEpwpMbuwIkTgxmC13TJjG4)
* **Robustness of Embodied Point Navigation Agents**<br>ECCV 2022 Workshop, [[Website]](https://m43.github.io/projects/embodied-ai-robustness/)
* **PyRobot: An Open-source Robotics Framework for Research and Benchmarking** <br>
  *Adithya Murali, Tao Chen, Kalyan Vasudev Alwala, Dhiraj Gandhi, Lerrel Pinto, Saurabh Gupta, Abhinav Gupta* <br>
  arXiv, 2019. [[Paper]](https://arxiv.org/abs/1906.08236) [[Code]](https://github.com/facebookresearch/pyrobot) [[Website]](https://www.pyrobot.org/)
* **AllenAct: A Framework for Embodied AI Research** <br>
  *Luca Weihs, Jordi Salvador, Klemen Kotar, Unnat Jain, Kuo-Hao Zeng, Roozbeh Mottaghi, Aniruddha Kembhavi* <br>
  arXiv, 2020. [[Paper]](https://arxiv.org/abs/2008.12760) [[Website]](https://allenact.org/)
* **ROBUSTNAV: Towards Benchmarking Robustness in Embodied Navigation** <br>*Prithvijit Chattopadhyay, Judy Hoffman, Roozbeh Mottaghi, Aniruddha Kembhavi* <br>ICCV, 2021. [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Chattopadhyay_RobustNav_Towards_Benchmarking_Robustness_in_Embodied_Navigation_ICCV_2021_paper.pdf) [[Website]](https://prior.allenai.org/projects/robustnav) [[Code]](https://github.com/allenai/robustnav)

