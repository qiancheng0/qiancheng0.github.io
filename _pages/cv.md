---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download [CV](http://qiancheng0.github.io/files/CV_ChengQian.pdf)
======

Education
======
* B.Eng. in Computer Science and Technology, Tsinghua University, Beijing, China, 2020-2024 (expected)

Academic
======
* **GPA**: 3.90 / 4.00.
* Selected Courses of **A & A+**: Linear Algebra, Introduction to Complex Analysis, Foundation of Object-Oriented Programming, Software Engineering, Introduction to Artificial Intelligence, Artificial Neural Networks, Fundamentals of Computer Graphics, A General Introduction to Economics, Writing and Communication.
* A member of THUNLP (THU Natural Language Processing Group), advised by Associate Professor Zhiyuan Liu.

Research Interests
======
* Natural language processing, pre-trained language models.
* Data efficient tuning and training efficient tuning (tuning with limited resources).
* Life long pre-training and continual learning in NLP.
* Interpretability of the language model, and its alignment to human instructions.
* Tool learning and tool creation of large language models.

Publications
======
(*indicates equal contribution)

* **Cheng Qian**, Xinran Zhao, Sherry Tongshuang Wu. Exploring the Impacts of External Knowledge Distractors to Parametric Knowledge Graphs. ([Paper](https://arxiv.org/pdf/2305.14318.pdf) / [Code](https://github.com/qiancheng0/EKD_Impacts_PKG))

  **Cheng Qian**, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji. CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation. ([Paper](https://arxiv.org/pdf/2305.14318.pdf))

  **Cheng Qian**, Chenyan Xiong, Zhenghao Liu, Zhiyuan Liu. Toolink: Linking Toolkit Creation and Using through Chain-of-Solving on Open-Source Model. ([Paper](http://qiancheng0.github.io/files/Tune_on_Tool))

* Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, **Cheng Qian**, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun. Tool Learning with Foundation Models. Submitted to Nature Machine Intelligence, under review. ([Paper](https://arxiv.org/pdf/2304.08354.pdf) / [Code](https://github.com/OpenBMB/BMTools))

* Yujia Qin\*, **Cheng Qian**\*, Yankai Lin, Xu Han, Zhiyuan Liu, Maosong Sun and Jie Zhou. Recyclable Tuning for Continual Pre-training. ACL 2023 findings. ([Paper](https://arxiv.org/pdf/2305.08702.pdf) / [Code](https://github.com/thunlp/RecyclableTuning))

* Yujia Qin\*, **Cheng Qian**\*, Jing Yi\*, Weize Chen, Yankai Lin, Xu Han, Zhiyuan Liu, Maosong Sun and Jie Zhou. Exploring Mode Connectivity for Pre-trained Language Models. EMNLP 2022. ([Paper](https://arxiv.org/pdf/2210.14102.pdf) / [Code](https://github.com/thunlp/Mode-Connectivity-PLM))

Research Experience
======

* Mar 2023 - Jun 2023: **CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation**
  * Directed by Professor Heng Ji, UIUC Blender Lab, and Associate Professor Zhiyuan Liu, THUNLP.
  * Investigated into the Large Language Model's ability to create useful tools to solve the queries, and devised the CREATOR framework, which leverages the model's tool creation ability through four stages: creation, decision, execution and rectification.
  * Disentangled the model's abstract and concrete reasoning abilities and raised the models performance under MATH and TabMWP benchmarks. Released the Creation Challenge dataset which aims to test the model's tool creation ability. Proved the effectiveness and generalization ability of our method.
  * First author. Paper submitted to EMNLP 2023, under review.
* Mar 2023 - Jun 2023: **Toolink: Linking Toolkit Creation and Using through Chain-of-Solving on Open-Source Model**
  * Directed by Associate Professor Chenyan Xiong, CMU LTI, Associate Professor Zhenghao Liu, Northeastern University, and Associate Professor Zhiyuan Liu, THUNLP.
  * Investigated how the LLM's tool using ability can be transferred to smaller, open-sourced models to help solve various tasks and raise performance.
  * Paper submitted, under review.
* Jan 2023 - Apr 2023: **Tool Learning with Foundational Models**
  * Explored the Large Language Model's ability to utilize external tools in various scenarios, and formulated a general tool learning framework, in which the foundational model understands human instructions,  adjusts its tool-using plan through reasoning, and effectively conquer the target tasks.
  * Contributed to part of the survey paper writing, conducted experiments and case studies under various scenarios including online shopping, cooking assistant, weather inquiry, and search engine.
  * Contributor to the paper. Nature Machine Intelligence under review.
* Aug 2022 – Jan 2023: **Recyclable Tuning for Continual Pretraining**	 		           
  * Directed by Associate Professor Zhiyuan Liu, THUNLP.
  * Formulated the task of compatible tuning as PLM continually acquire fresh knowledge from emerging data, and explored how to make earlier adapted weights compatible with subsequent upgraded PLMs.
  * Explored the parametric connections among continually pre-trained models; Proposed CLoP, which enables compatible tuning in a data-efficient and training efficient way; Experimented on various NLP tasks and demonstrated the superiority of CLoP; Construct the first benchmark regarding to the field of compatible tuning.
  * Co-first author. Accepted by ACL 2022 findings.
  * Project selected to THU Undergraduate Academic Advancement program and won ￥30K support.
* Mar 2022 – Jul 2022: **Exploring Mode Connectivity for Pre-trained Language Models**
  * Directed by Associate Professor Zhiyuan Liu, THUNLP.
  * Analysed the geometric connections of different minima in loss landscape through the lens of mode connectivity, which measures whether two minima can be connected with a low loss path.
  * Explored how various hyperparameters and training data affect PLMs’ mode connectivity; Discovered the role of pre-training in facilitating mode connectivity and pulling task boundaries closer; Investigated into how PLMs task knowledge change along the connected path quantitatively.
  * Co-first author. Accepted by EMNLP 2022 main conference.
  * Project established in THU Student Research Training Program.
* Mar 2022 – Jun 2022: **THUPat: A Convenient Campus Helper**					        
  * Directed by Associate Researcher Chun Yu, Theory and Practice of Human Computer Interaction course project.
  * Proposed “pat” for the first time as the medium in human-phone interaction. Built an open source android software THUPat that can help with various kinds of campus events via simply patting the phone.
  * Collaborator. Software released in THU and benefited the campus community.
* Jul 2022 – Aug 2022: **Quantum Automata: Capability and Efficiency**		         
  * Directed by Professor Zhengfeng Ji and Professor Mingsheng Ying, Topics in Quantum Computing course project.
  * Defined the efficiency of quantum automata from 3 different perspectives with respect to acceptance probability, space and time; Proposed an algorithm that can effectively optimize quantum automata’s acceptance probability, applying the knowledge from neural network.
  * First author. Course thesis won high recognition.


Awards
======
* December-9th Scholarship, highest scholarship in Dept. of CST, 1/180. (2021)
* Volunteering & Social Survey Excellence Scholarship, Dept. of CST, 1/180. (2022)
* Awards of Excellent Student Cadre, Tsinghua University. (2021)
* Second Prize in National Undergraduate Physics Competition, Beijing Physics Society. (2021)
* Third Prize in THU Challenge Cup Academic Competition, Tsinghua University. (2022)

Languages
======
Mandarin(Native), English(Fluent)
* TOEFL  115/120 (Reading 30, Listening 30, Speaking 26, Writing 29).
* GRE  Verbal Reasoning 162/170, Quantitative Reasoning 170/170, Analytical Writing 4/6.

Skills & Expertise 
======
* Highly self-motivated researcher. 
* Strong interpersonal skills with a good sense of teamwork.
* Programming Skills: Python, C/C++.
* Rich experience in state-of-the-art deep learning techniques.

Service and leadership
======
* Serve as COLING 2022 reviewer.

