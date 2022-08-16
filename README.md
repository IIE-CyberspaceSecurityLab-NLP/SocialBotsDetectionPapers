# SocialBotDetectionPapers
Important papers on SocialBots detection

## Contents

- [SocialBotDetectionPapers](#social-bot-detection-papers)
  - [Introduction](#introduction)
    - [Overview and Statistics](#statistics)
    - [Keywords Convention](#keywords-convention)
  - [Toolkits](#toolkits)
  - [Datasets](#datasets)
    - [Bot Repository](#Repository)
    - [TwiBot](#TwiBot)
  - [Papers](#papers)
    - [Survey](#survey)
    - [Research Papers](#research-papers)
  - [Organizations](#organizations)
  - [Contribution](#contribution)
  - [Social bot detection site](#site)


## Introduction

This is a paper list and other useful sources about **Social bot deteting**. 

### Overview and Statistics

### Keywords Convention

![](https://img.shields.io/badge/-UserInfo-green) which mainly focus on user info features.

![](https://img.shields.io/badge/-Text-blue) which mainly focus on the text features.

![](https://img.shields.io/badge/-SocialGraph-red) which mainly focus on social graph and use the graph-based methods.

![](https://img.shields.io/badge/-Temporal-orange) which mainly focus on temporal patterns.

![](https://img.shields.io/badge/Conference-CCF--A-red) Conference Rank (A, B, C) from China Computer Federation.

### Toolkits

### Datasets

#### BotRepository

1. **cresci-2015**

    **Description**: A dataset of (i) genuine and (ii) fake Twitter accounts, manually annotated. Released in CSV format.

    > Cresci, S., Di Pietro, R., Petrocchi, M., Spognardi, A., & Tesconi, M. (2015). Fame for sale: efficient detection of fake Twitter followers. Decision Support Systems, 80, 56-71. [[pdf](https://arxiv.org/abs/1509.04098)]


2. **cresci-2017**

    **Description**: A dataset of (i) genuine, (ii) traditional, and (iii) social spambot Twitter accounts, annotated by CrowdFlower contributors. Released in CSV format.

    > Cresci, S., Di Pietro, R., Petrocchi, M., Spognardi, A., & Tesconi, M. (2017, April). The paradigm-shift of social spambots: Evidence, theories, and tools for the arms race. In Proceedings of the 26th International Conference on World Wide Web Companion (pp. 963-972). ACM. [[pdf](https://arxiv.org/abs/1701.03017)]
    > 
    > Cresci, S., Di Pietro, R., Petrocchi, M., Spognardi, A., & Tesconi, M. (2017). Social Fingerprinting: detection of spambot groups through DNA-inspired behavioral modeling. IEEE Transactions on Dependable and Secure Computing. [[pdf](https://arxiv.org/abs/1703.04482)]


3. **caverlee-2011**

    **Description**: This social honeypot dataset collected from December 30, 2009 to August 2, 2010 on Twitter. The dataset contains 22,223 content polluters, their number of followings over time, 2,353,473 tweets, and 19,276 legitimate users, their number of followings over time and 3,259,693 tweets.
    
    > Lee, Kyumin, Brian David Eoff, and James Caverlee. "Seven Months with the Devils: A Long-Term Study of Content Polluters on Twitter." ICWSM. 2011. [[pdf](https://people.engr.tamu.edu/caverlee/pubs/lee11icwsm.pdf)]


4. **varol-2017**

    **Description**: This dataset contains annotation of 2573 Twitter accounts. Annotation and data crawl is completed in April 2016.
    
    > Varol, Onur, Emilio Ferrara, Clayton A. Davis, Filippo Menczer, and Alessandro Flammini. "Online Human-Bot Interactions: Detection, Estimation, and Characterization." ICWSM (2017). [[pdf](https://arxiv.org/abs/1703.03107)]


5. **gilani-2017**

    **Description**: Manually annotated human and bot accounts. Labels and user objects.
    
    > Gilani, Zafar, Reza Farahbakhsh, Gareth Tyson, Liang Wang, and Jon Crowcroft. "Of bots and humans (on twitter)." In Proceedings of the 2017 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining 2017, pp. 349-354. ACM, 2017. [[pdf](http://www.eecs.qmul.ac.uk/~tysong/files/Bots-ASONAM17.pdf)]


6. **cresci-stock-2018**

    **Description**: Automated accounts that act in coordinate fashion. Labels and user objects.
    
    > Cresci, Stefano, Fabrizio Lillo, Daniele Regoli, Serena Tardelli, and Maurizio Tesconi. "$ FAKE: Evidence of Spam and Bot Activity in Stock Microblogs on Twitter." In Twelfth International AAAI Conference on Web and Social Media. 2018. [[pdf](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/viewFile/17871/17055)]

    > Cresci, Stefano, Fabrizio Lillo, Daniele Regoli, Serena Tardelli, and Maurizio Tesconi. "Cashtag piggybacking: Uncovering spam and bot activity in stock microblogs on Twitter." ACM Transactions on the Web (TWEB) 13, no. 2 (2019): 11. [[pdf](https://arxiv.org/abs/1804.04406)]


7. **midterm-2018**

    **Description**: Manually labeled human and bot accounts from 2018 US midterm elections. Labels and processed user objects.
    
    > Yang, Kai-Cheng, Onur Varol, Pik-Mai Hui, and Filippo Menczer. "Scalable and generalizable social bot detection through data selection." In Proceedings of the AAAI Conference on Artificial Intelligence, vol. 34, no. 01, pp. 1096-1103. 2020. [[pdf](https://arxiv.org/abs/1911.09179v1)]


8. **pronbots-2019**

    **Description**: Pronbots shared by Andy Patel (github.com/r0zetta/pronbot2). Labels and user objects.
    
    > Yang, Kai‐Cheng, Onur Varol, Clayton A. Davis, Emilio Ferrara, Alessandro Flammini, and Filippo Menczer. "Arming the public with artificial intelligence to counter social bots." Human Behavior and Emerging Technologies 1, no. 1 (2019): 48-61. [[pdf](https://arxiv.org/abs/1901.00912)]


9. **celebrity-2019**

    **Description**: Celebrity accounts collected as authentic users. Labels and user objects.
    
    > Yang, Kai‐Cheng, Onur Varol, Clayton A. Davis, Emilio Ferrara, Alessandro Flammini, and Filippo Menczer. "Arming the public with artificial intelligence to counter social bots." Human Behavior and Emerging Technologies 1, no. 1 (2019): 48-61. [[pdf](https://arxiv.org/abs/1901.00912)]


10. **vendor-purchased-2019**

    **Description**: Fake follower accounts purchased from several companies. Labels and user objects.
    
    > Yang, Kai‐Cheng, Onur Varol, Clayton A. Davis, Emilio Ferrara, Alessandro Flammini, and Filippo Menczer. "Arming the public with artificial intelligence to counter social bots." Human Behavior and Emerging Technologies 1, no. 1 (2019): 48-61. [[pdf](https://arxiv.org/abs/1901.00912)]


11. **botometer-feedback-2019**

    **Description**: Botometer feedback accounts manually labeled by K.C. Yang. Labels and user objects.
    
    > Yang, Kai‐Cheng, Onur Varol, Clayton A. Davis, Emilio Ferrara, Alessandro Flammini, and Filippo Menczer. "Arming the public with artificial intelligence to counter social bots." Human Behavior and Emerging Technologies 1, no. 1 (2019): 48-61. [[pdf](https://arxiv.org/abs/1901.00912)]


12. **political-bots-2019**

    **Description**: Automated political accounts run by @rzazula (now suspended), shared by @josh_emerson on Twitter. Labels and user objects.
    
    > Yang, Kai‐Cheng, Onur Varol, Clayton A. Davis, Emilio Ferrara, Alessandro Flammini, and Filippo Menczer. "Arming the public with artificial intelligence to counter social bots." Human Behavior and Emerging Technologies 1, no. 1 (2019): 48-61. [[pdf](https://arxiv.org/abs/1901.00912)]


13. **cresci-rtbust-2019**

    **Description**: Manually annotated bot and human accounts. Labels and user objects.
    
    > Mazza, Michele, Stefano Cresci, Marco Avvenuti, Walter Quattrociocchi, and Maurizio Tesconi. "Rtbust: Exploiting temporal patterns for botnet detection on twitter." In Proceedings of the 10th ACM Conference on Web Science, pp. 183-192. 2019. [[pdf](https://arxiv.org/abs/1902.04506)]


14. **botwiki-2019**

    **Description**: Self-identified bots from https://botwiki.org. Labels and user objects.
    
    >     Yang, Kai-Cheng, Onur Varol, Pik-Mai Hui, and Filippo Menczer. "Scalable and generalizable social bot detection through data selection." In Proceedings of the AAAI Conference on Artificial Intelligence, vol. 34, no. 01, pp. 1096-1103. 2020. [[pdf](https://arxiv.org/abs/1911.09179v1)]


15. **verified-2019**

    **Description**: Verified human accounts. Labels and user objects.
    
    > Yang, Kai-Cheng, Onur Varol, Pik-Mai Hui, and Filippo Menczer. "Scalable and generalizable social bot detection through data selection." In Proceedings of the AAAI Conference on Artificial Intelligence, vol. 34, no. 01, pp. 1096-1103. 2020. [[pdf](https://arxiv.org/abs/1911.09179v1)]


16. **Kaiser**

    **Description**: 27 manually annotated German bots, 532 official accounts of German members of parliament, 516 accounts of members of the 115th U.S. Congress
    
    > Rauchfleisch, Adrian; Kaiser, Jonas, 2020, "The False positive problem of automatic bot detection in social science research", https://doi.org/10.7910/DVN/XVCKRS, Harvard Dataverse, V2. [[pdf](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0241045&type=printable)]  


17. **Astroturf**

    **Description**: Hyper-active political bots participating in follow trains and/or systematically deleting high volumes of content
    
    > ohsen Sayyadiharikandeh, Onur Varol, Kai-Cheng Yang, Alessandro Flammini, and Filippo Menczer. "Detection of Novel Social Bots by Ensembles of Specialized Classifiers." CIKM. 2020. [[pdf](https://arxiv.org/abs/2006.06867)]


**The above dataset can be downloaded along with [[Bot Repository](https://botometer.osome.iu.edu/bot-repository/datasets.html)].** 


#### TwiBot

1. **TwiBot-20**

    **Description**: TwiBot-20 is a comprehensive sample of the Twittersphere and it is representative of the current generation of Twitter bots and genuine users. To download the full dataset, please contact the creator directly. [[dataset](https://github.com/BunsenFeng/TwiBot-20)]
    
    > Shangbin Feng, Herun Wan, Ningnan Wang, Jundong Li, and Minnan Luo. "TwiBot-20: A Comprehensive Twitter Bot Detection Benchmark." CIKM. 2021. [[pdf](https://arxiv.org/pdf/2106.13088.pdf)]
    
 
2. **TwiBot-22**

    **Description**:TwiBot-22 is the largest and most comprehensive Twitter bot detection benchmark to date. Specifically, TwiBot-22 is designed to address the challenges of limited dataset scale, imcomplete graph structure, and low annotation quality in previous datasets. [[dataset](https://drive.google.com/drive/folders/1YwiOUwtl8pCd2GD97Q_WEzwEUtSPoxFs)]
    
    > hangbin Feng, Zhaoxuan Tan, Herun Wan, Ningnan Wang, Zilong Chen, Binchi Zhang, Qinghua Zheng, Wenqian Zhang, Zhenyu Lei, Shujie Yang, Xinshun Feng, Qingyue Zhang, Hongrui Wang, Yuhan Liu, Yuyang Bai, Heng Wang, Zijian Cai, Yanbo Wang, Lijing Zheng, Zihan Ma, Jundong Li, Minnan Luo.
TwiBot-22: Towards Graph-Based Twitter Bot Detection. CoRR abs/2206.04564 (2022) [[pdf](https://arxiv.org/pdf/2206.04564.pdf)]


### Papers

#### Survey

1. **Taming Social Bots: Detection, Exploration and Measurement.** CIKM 2019. ![](https://img.shields.io/badge/Conference-CCF--B-blue)
   
   *Mueen, A; Chavoshi, N; Minnich, A*  [[pdf](https://dl.acm.org/doi/pdf/10.1145/3357384.3360315)]

2. **Bots, Socks, and Vandals: Advances in Identifying Malicious Actors in Social and Online Platforms.** IPDPS 2018. 

   *Subrahmanian, VS.* 

3. **Detection of Bots in Social Media: A Systematic Review.**  INFORMATION PROCESSING & MANAGEMENT 2020. ![](https://img.shields.io/badge/Journal-CCF--B-blue)

   *Orabi, M; Mouheb, D; Al Aghbari, Z; Kamel, I.*  [[pdf](https://sci.bban.top/pdf/10.1016/j.ipm.2020.102250.pdf#view=FitH)]

4. **Detection of malicious social bots: A survey and a refined taxonomy** EXPERT SYSTEMS WITH APPLICATIONS 2020. ![](https://img.shields.io/badge/Journal-CCF--C-green)
  
   *Latah, M* [[pdf](https://sci.bban.top/pdf/10.1016/j.eswa.2020.113383.pdf#view=FitH)]

5. **A review on social spam detection: Challenges, open issues, and future directions.** EXPERT SYSTEMS WITH APPLICATIONS 2021. ![](https://img.shields.io/badge/Journal-CCF--C-green)

   *Rao, SJ; Verma, AK; Bhatia, T.*  [[pdf](https://pdf.bban.top/uptodate/S0957417421011209.pdf#navpanes=0&view=FitH)]


6. **Detecting Social Bots on Twitter: A Literature Review.** IIT 2018.

   *Alothali, E; Zaki, N; Mohamed, EA; Alashwal, H.*  [[pdf](https://sci.bban.top/pdf/10.1109/INNOVATIONS.2018.8605995.pdf#view=FitH)]
   

7. **A Decade of Social Bot Detection.** COMMUNICATIONS OF THE ACM 2020. 

   *Cresci, S.*  [[pdf](https://dl.acm.org/doi/pdf/10.1145/3409116?casa_token=onGHn6FEtxcAAAAA:h8qw7Uoo2Shq5jNErhLYjaKyKhWhgpYLgXVIDvmvWsNYgSqwtOWnIcQipfIKMghnmCY34Uffty0rjA)]


8. **The Rise of Social Botnets: Attacks and Countermeasures.** Ieee Transactions on Dependable and Secure Computing 2018. ![](https://img.shields.io/badge/Journal-CCF--A-red) 

    *J. X. Zhang, R. Zhang, Y. C. Zhang and G. H. Yan.* [[pdf](https://ieeexplore.ieee.org/ielaam/8858/8528978/7790819-aam.pdf)]
  

9. **Feature extractions and selection of bot detection on Twitter A systematic literature review.** Inteligencia Artificial 2022. 

    *Raad Al-azawi, Safaa O. Al-Mamory.* [[pdf](https://click.endnote.com/viewer?doi=10.4114%2Fintartif.vol25iss69pp57-86&token=WzM2ODMyNzksIjEwLjQxMTQvaW50YXJ0aWYudm9sMjVpc3M2OXBwNTctODYiXQ.uv5pA_lw8e4aMi35YkTSESiDXI8)]
  
  
#### Research Papers

1. **SocialBotHunter: Botnet Detection in Twitter-like Social Networking Services Using Semi-Supervised Collective Classification.** TDSC 2018. ![](https://img.shields.io/badge/Conference-CCF--A-red) ![](https://img.shields.io/badge/-SocialGraph-red)

   *A. Dorri, M. Abadi, M. Dadfarnia.*  [[pdf](https://www.researchgate.net/profile/Mahila-Dadfarnia/publication/328604276_SocialBotHunter_Botnet_Detection_in_Twitter-Like_Social_Networking_Services_Using_Semi-Supervised_Collective_Classification/links/61cc08e0d450060816750432/SocialBotHunter-Botnet-Detection-in-Twitter-Like-Social-Networking-Services-Using-Semi-Supervised-Collective-Classification.pdf)]


2. **Real-time Detection of Content Polluters in Partially Observable Twitter Networks.** WWW 2020. ![](https://img.shields.io/badge/Conference-CCF--A-red) ![](https://img.shields.io/badge/-Temporal-orange) ![](https://img.shields.io/badge/-Text-blue)

   *M. Nasim, A. Nguyen, N. Lothian, R. Cope, L. Mitchell.*  [[pdf](https://dl.acm.org/doi/pdf/10.1145/3184558.3191574)]

3. **Detect Me If You Can: Spam Bot Detection Using Inductive Representation Learning.** WWW 2019. ![](https://img.shields.io/badge/Conference-CCF--A-red) ![](https://img.shields.io/badge/-SocialGraph-red) ![](https://img.shields.io/badge/-UserInfo-green)

   *Alhosseini, SA; Bin Tareaf, R; Najafi, P; Meinel, C.* [[pdf](https://dl.acm.org/doi/pdf/10.1145/3308560.3316504?casa_token=vev1jOrgwa8AAAAA:p4CgCuQF1MaAu-gHs9aVges8pFT1gN6bIqfNb3OHGihu_po8-vih2MiSdjHsJDrHYnvTFvb2yLn2)]
  
  
4. **Less is More: Semi-Supervised Causal Inference for Detecting Pathogenic Users in Social Media.** WWW 2019. ![](https://img.shields.io/badge/Conference-CCF--A-red)

    *Alvari, H; Shaabani, E; Sarkar, S; Beigi, G; Shakarian, P.* [[pdf](https://dl.acm.org/doi/pdf/10.1145/3308560.3316500?casa_token=muvUn8j7y58AAAAA:MCpmdxTVNOSs--ZhID0mskoFooO94ypp_P_b28AaOPcl4ON16id0tqoK-vAHrZU0MnyAW3IjpiwY)]
  
  
5. **Scalable and Generalizable Social Bot Detection through Data Selection.** AAAI 2020. ![](https://img.shields.io/badge/Conference-CCF--A-red) ![](https://img.shields.io/badge/-UserInfo-green)

    *Yang, KC; Varol, O; Hui, PM; Menczer, F.* [[pdf](https://arxiv.org/abs/1911.09179v1)]
  
  
6. **Graph-Hist: Graph Classification from Latent Feature Histograms with Application to Bot Detection.** AAAI 2020. ![](https://img.shields.io/badge/Conference-CCF--A-red) ![](https://img.shields.io/badge/-UserInfo-green) ![](https://img.shields.io/badge/-Text-blue) ![](https://img.shields.io/badge/-SocialGraph-red)

    *Magelinski, T; Beskow, D; Carley, KM.* [[pdf](https://arxiv.org/abs/1910.01180)]
  
  
7. **Deep Contextualized Word Embedding for Text-based Online User Profiling to Detect Social Bots on Twitter.** ICDM 2020. ![](https://img.shields.io/badge/Conference-CCF--B-blue)  ![](https://img.shields.io/badge/-Text-blue)

    *M. Heidari, J. H. Jones and O. Uzuner.* [[pdf](https://ieeexplore.ieee.org/abstract/document/9346546)]
  
  
8. **Detection of Novel Social Bots by Ensembles of Specialized Classifiers.** CIKM 2020. ![](https://img.shields.io/badge/Conference-CCF--B-blue)

    *M. Sayyadiharikandeh, O. Varol, K. C. Yang, A. Flammini, F. Menczer and M.* [[pdf](https://arxiv.org/abs/2006.06867)]
  

9. **It's a Matter of Style: Detecting Social Bots through Writing Style Consistency** ICCCN 2019. ![](https://img.shields.io/badge/Conference-CCF--C-green)  ![](https://img.shields.io/badge/-Text-blue)

    *M. Cardaioli, M. Conti, A. Di Sorbo, E. Fabrizio, S. Laudanna, C. A.* [[pdf](https://ieeexplore.ieee.org/abstract/document/9522339)]
  

10. **Deep Q-Learning and Particle Swarm Optimization for Bot Detection in Online Social Networks.** ICCCN 2019. ![](https://img.shields.io/badge/Conference-CCF--C-green) 

    *G. Lingam, R. R. Rout, D. Somayajulu.* [[pdf](https://ieeexplore.ieee.org/abstract/document/8944493)]
  
  
11. **A Comparison of Machine Learning Approaches to Detect Botnet Traffic.** IJCNN 2018. ![](https://img.shields.io/badge/Conference-CCF--C-green)  

    *Abraham, B; Mandya, A; Bapat, R; Alali, F; Brown, DE; Veeraraghavan, M* [[pdf](https://ieeexplore.ieee.org/abstract/document/8944493)]
  
  
12. **Deep Dive on Politician Impersonating Accounts in Social Media.** ISCC 2019. ![](https://img.shields.io/badge/Conference-CCF--C-green)  ![](https://img.shields.io/badge/-Text-blue)

    *Zarei, K; Farahbakhsh, R; Crespi, N.* [[pdf](https://hal.archives-ouvertes.fr/hal-02363455/document)]
  
  
13. **Typification of Impersonated Accounts on Instagram.** IPCCC 2019. ![](https://img.shields.io/badge/Conference-CCF--C-green)  ![](https://img.shields.io/badge/-UserInfo-green)

    *Zarei, K; Farahbakhsh, R; Crespi, N.* [[pdf](https://hal.archives-ouvertes.fr/hal-02363432/document)]
  
14. **Detecting Fake Accounts on Social Media.** BIG DATA 2018. ![](https://img.shields.io/badge/Conference-CCF--C-green) 

    *Khaled, S; El-Tazi, N; Mokhtar, HMO.* [[pdf](https://www.researchgate.net/profile/Neamat-El-Tazi/publication/330629456_Detecting_Fake_Accounts_on_Social_Media/links/5ce7cabc92851c4eabba3d91/Detecting-Fake-Accounts-on-Social-Media.pdf)]
  
  
15. **Social Fingerprinting: Detection of Spambot Groups Through DNA-Inspired Behavioral Modeling.** Ieee Transactions on Dependable and Secure 
Computing 2018. ![](https://img.shields.io/badge/Journal-CCF--A-red) 

    *S. Cresci, R. Di Pietro, M. Petrocchi, A. Spognardi and M. Tesconi* [[pdf](https://arxiv.org/pdf/1703.04482.pdf)]
  
  
16. **Towards Learning-Based, Content-Agnostic Detection of Social Bot Traffic.** Ieee Transactions on Dependable and Secure Computing 2021. ![](https://img.shields.io/badge/Journal-CCF--A-red) 

    *Y. B. Feng, J. Li, L. Jiao and X. T. Wu.* [[pdf](https://ix.cs.uoregon.edu/~yebof/paper/feng2021botflowmon.pdf)]
  
  
17. **Bots in Social and Interaction Networks: Detection and Impact Estimation.** Acm Transactions on Information Systems 2020. ![](https://img.shields.io/badge/Journal-CCF--A-red)  ![](https://img.shields.io/badge/-SocialGraph-red)

    *M. Mendoza, M. Tesconi and S. Cresci.* [[pdf](https://dl.acm.org/doi/pdf/10.1145/3419369?casa_token=apEAC0HTWaEAAAAA:0G3IbwiK9ly3BRwIXshQSfysykJKNBGGpY0YvvneOV_4P5OfI9IVcEmKQgq61IxPNeuUkPoFzze6QQ)]
  
  
18. **HawkesEye: Detecting Fake Retweeters Using Hawkes Process and Topic Modeling.** IEEE TRANSACTIONS ON INFORMATION FORENSICS AND SECURITY 2020. ![](https://img.shields.io/badge/Journal-CCF--A-red)

    *Dutta, HS; Dutta, VR; Adhikary, A; Chakraborty, T.*[[pdf](https://ieeexplore.ieee.org/abstract/document/8976235)]
  
  
19. **Deep neural networks for bot detection.** Information Sciences 2018. ![](https://img.shields.io/badge/Journal-CCF--B-blue) ![](https://img.shields.io/badge/-Text-blue)

    *S. Kudugunta and E. Ferrara.* [[pdf](https://www.sciencedirect.com/science/article/pii/S0020025518306248?casa_token=VlSG4VG5Q1AAAAAA:Rr7ETJePv6QgwG-4ZByHlar0RISWhFWL37P_RwqqzO-Op5GY7VbjUof7EOXeQkU4A2K5yk4rdw)]
  
  
20. **Bot2Vec: A general approach of intra-community oriented representation learning for bot detection in different types of social networks.** Information Systems 2022. ![](https://img.shields.io/badge/Journal-CCF--B-blue) 

    *P. Pham, L. T. T. Nguyen, B. Vo and U. Yun.* [[pdf](https://www.sciencedirect.com/science/article/pii/S0306437921000302?casa_token=xvcqdg3mjnQAAAAA:uE44x-H8tyhKJ8wQFsO978kpz0RtZVlBp4QzNEgOQa1S7NPgYH_I5J9ZZWG_3c_ftp_xNVGtNw)]
  
  
21. **Are social bots a real threat? An agent-based model of the spiral of silence to analyse the impact of manipulative actors in social networks.** European Journal of Information Systems 2019. ![](https://img.shields.io/badge/Journal-CCF--B-blue)  
 
    *B. Ross, L. Pilz, B. Cabrera, F. Brachten, G. Neubaum and S. Stieglitz.*  [[pdf](https://www.tandfonline.com/doi/pdf/10.1080/0960085X.2018.1560920?casa_token=mZXkZneyeLoAAAAA:R8XdQCrBdfXOHOXTa0iMQwENR494LMSF9Dk5Vooy5s2VYMJp5OyOd5YLrgQegB1jqx87AaQxE_wH)]
  
  
22. **A one-class classification approach for bot detection on Twitter.** COMPUTERS & SECURITY 2020. ![](https://img.shields.io/badge/Journal-CCF--B-blue) 

    *Rodriguez-Ruiz, J; Mata-Sanchez, JI; Monroy, R; Loyola-Gonzalez, O; Lopez-Cuevas, A.* [[pdf](https://www.sciencedirect.com/science/article/pii/S0167404820300031?casa_token=qj2g063I6aoAAAAA:EusBps55uJTLOoTPvwrYm3wpKvI4GoVwf_lTtgybluZojFvsyO53nMt3mqWjNhtrz32JQaxZUA)]
  
 
23. **A Large-scale Behavioural Analysis of Bots and Humans on Twitter.** ACM TRANSACTIONS ON THE WEB 2019. ![](https://img.shields.io/badge/Journal-CCF--B-blue)  ![](https://img.shields.io/badge/-UserInfo-green)

    *Gilani, Z; Farahbakhsh, R; Tyson, G; Crowcroft, J.* [[pdf](chrome-extension://ikhdkkncnoglghljlkmcimlnlhkeamad/pdf-viewer/web/viewer.html?file=https%3A%2F%2Fdl.acm.org%2Fdoi%2Fpdf%2F10.1145%2F3298789%3Fcasa_token%3DpspkfnsBwoEAAAAA%3ABoyigjDnkPXD33NZP_IpXTUHvA6FtgMhckxMBltN20gqDDkBG0JObBe0flh6sZ-TOxYaA5VJkZe_MQ#=&zoom=110.00000000000001)]
  
  
24. **Feature selection using Benford's law to support detection of malicious social media bots.** INFORMATION SCIENCES 2021. ![](https://img.shields.io/badge/Journal-CCF--B-blue)

    *Mbona, I; Eloff, JHP.* [[pdf](https://www.sciencedirect.com/science/article/abs/pii/S0020025521009695)]
  
  
25. **Adaptive deep Q-learning model for detecting social bots and influential users in online social networks.** Applied Intelligence 2019. ![](https://img.shields.io/badge/Journal-CCF--C-green)

    *G. Lingam, R. R. Rout and D. Somayajulu.* [[pdf](https://jetcse.com/assets/papers/2019-10-06-5d99c7ae239021570359214.pdf)]
  
  
26. **A novel framework for detecting social bots with deep neural networks and active learning.** Knowledge-Based Systems 2021. ![](https://img.shields.io/badge/Journal-CCF--C-green) ![](https://img.shields.io/badge/-UserInfo-green)

    *Y. H. Wu, Y. Z. Fang, S. K. Shang, J. Jin, L. Wei and H. Z. Wang.* [[pdf](https://www.sciencedirect.com/science/article/abs/pii/S0950705120306547)]
  
  
27. **RoSGAS: Adaptive Social Bot Detection with ReinforcedSelf-Supervised GNN Architecture Search.** CoRR 2022. ![](https://img.shields.io/badge/-UserInfo-green)  ![](https://img.shields.io/badge/-Text-blue) ![](https://img.shields.io/badge/-SocialGraph-red)

    *Yingguang Yang, Renyu Yang, Yangyang Li, Kai Cui, Zhiqin Yang, Yue Wang, Jie Xu, Haiyong Xie.* [[pdf](https://arxiv.org/pdf/2206.06757.pdf
)]


28. **BotRGCN: Twitter Bot Detection with RelationalGraph Convolutional Networks.** ASONAM 2021 Short. ![](https://img.shields.io/badge/-UserInfo-green)  ![](https://img.shields.io/badge/-Text-blue) ![](https://img.shields.io/badge/-SocialGraph-red)

    *Shangbin Feng, Herun Wan, Ningnan Wang, Minnan Luo.* [[pdf](https://arxiv.org/pdf/2106.13092.pdf)]
  
  
29. **SATAR: A Self-supervised Approach to Twitter Account.** CIKM 2021. ![](https://img.shields.io/badge/Conference-CCF--B-blue)  ![](https://img.shields.io/badge/-Text-blue) ![](https://img.shields.io/badge/-UserInfo-green)

    *Shangbin Feng, Herun Wan, Ningnan Wang, Jundong Li, Minnan Luo.* [[pdf](https://arxiv.org/pdf/2106.13089.pdf)]
  
  
30. **TwiBot-20: A Comprehensive Twitter Bot Detection Benchmark.** CIKM 2021. ![](https://img.shields.io/badge/Conference-CCF--B-blue) 

    *Shangbin Feng, Herun Wan, Ningnan Wang, Jundong Li, Minnan Luo.* [[pdf](https://arxiv.org/pdf/2106.13088.pdf)]
  
  
31. **TwiBot-22: Towards Graph-Based Twitter Bot Detection.** 

    *Shangbin Feng, Zhaoxuan Tan, Herun Wan1, Ningnan Wang, Zilong Chen, Binchi Zhang, Qinghua Zheng1, Wenqian Zhang1, Zhenyu Lei1, Shujie Yang1, Xinshun Feng, Qingyue Zhang, Hongrui Wang, Yuhan Liu, Yuyang Bai, Heng Wang, Zijian Cai, Yanbo Wang, Lijing Zheng, Zihan Ma, Jundong Li, Minnan Luo.* [[pdf](https://arxiv.org/pdf/2206.04564.pdf)]
  
  
32. **Heterogeneity-Aware Twitter Bot Detection with Relational Graph Transformers.** AAAI 2022. ![](https://img.shields.io/badge/Conference-CCF--A-red)
![](https://img.shields.io/badge/-UserInfo-green)  ![](https://img.shields.io/badge/-Text-blue) ![](https://img.shields.io/badge/-SocialGraph-red)
  
    *Shangbin Feng, Zhaoxuan Tan, Rui Li, Minnan Luo.* [[pdf](https://arxiv.org/abs/2109.02927)]
  
  
33. **BotCamp: Bot-driven Interactions in Social Campaigns.** WWW 2019. ![](https://img.shields.io/badge/Conference-CCF--A-red)

    *Noor Abu-El-Rub, Abdullah Mueen*


### Organizations

1. **Institution**: Italian National Research Council
   
   **Department**: Institute for Informatics and Telematics IIT
   
   **Lab**: Maurizio Tesconi's Lab [[Lab Page](https://www.researchgate.net/lab/Maurizio-Tesconi-Lab)]
   
   
2. **GITAM University** 
   
   **Department**: GITAM · Department of Computer Science & Engineering [[Lab Page](https://www.researchgate.net/profile/Greeshma-Lingam)]
   
   
3. **Institution**: Arizona State University
   
   **Lab**: Paulo Shakarian's Lab [[Lab Page](https://labs.engineering.asu.edu/labv2/about-paulo-shakarian/)]
   
4. **Institution**: Indiana University Bloomington
   
   **Department**: Department of Informatics
   
   **Lab**: Filippo Menczer's Lab [[Lab Page](https://www.researchgate.net/lab/Filippo-Menczer-Lab)]
   
   
5. **Institution**: University of New Mexico
   
   **Department**: Department of Computer Science
  
   **Lab**: Abdullah Mueen's Lab [[Lab Page](https://www.researchgate.net/lab/Abdullah-Mueen-Lab)]
   
   
6. **Institution**: Beijing University of Posts & Telecommunications 


7. **Institution**: Carnegie Mellon University
   
   **Department**: Institute for Software Research
   
   **Lab**: Kathleen M Carley's Lab [[Lab Page](https://www.researchgate.net/lab/Kathleen-M-Carley-Lab)]
   
   
8. **Institution**: Xi’an Jiaotong University
   
   **Lab**: Luo Lab [[Lab Page](https://luoundergradxjtu.github.io/news.html)]
   

9. **Institution**: Sichuan University [[Lab Page](https://csri.scu.edu.cn/info/1009/1885.htm)]


10. **Institution**: Tsinghua University
    
    **Department**：TH · Department of Computer Science and Technology 
    
    **Lab**: Jie Tang's Lab [[Lab Page](https://www.researchgate.net/profile/Jie-Tang-19)]

   
## Social bot detection website

1. **Debot**

    **Description**: DeBot is real-time bot detection system. The project started on Feb 2015 and it has been collecting data since Aug 2015. High correlation in activities among users in social media is unusual and can be used as an indicator of bot behavior. DeBot identifies such bots in Twitter network. Our system reports and archives thousands of bot accounts every day. DeBot is an unsupervised method capable of detecting bots in a parameter-free fashion. In March 2017, DeBot has collected over 730K unique bots. Since we are detecting and archiving Twitter bots on a daily basis, we can offer two different service: bot archive API and on-demand bot detection platform.
    
    
    **Papers**
    
    > On-Demand Bot Detection and Archival System (WWW'17-Demo). Nikan Chavoshi, Hossein Hamooni and Abdullah Mueen, to appear In the Proceedings of World Wide Web Conference (Companion Volume). [[pdf](https://www.researchgate.net/publication/314179650_On-Demand_Bot_Detection_and_Archival_System)]
    
    > Temporal Patterns in Bot Activities (WWW'17-TempWeb). Nikan Chavoshi, Hossein Hamooni and Abdullah Mueen, to appear In the Proceedings of World Wide Web Conference (Companion Volume). [[pdf](https://www.researchgate.net/publication/314179583_Temporal_Patterns_in_Bot_Activities)]
    
    > DeBot: Twitter Bot Detection via Warped Correlation (ICDM'16). Nikan Chavoshi, Hossein Hamooni and Abdullah Mueen, to appear In the Proceedings of the 8th International Conference on 6th IEEE International Conference on Data Mining. [[pdf](https://www.researchgate.net/publication/308021270_DeBot_Twitter_Bot_Detection_via_Warped_Correlation)]
    
    > Identifying Correlated Bots in Twitter (SocInfo'16). Nikan Chavoshi, Hossein Hamooni and Abdullah Mueen, to appear In the Proceedings of the 8th International Conference on Social Informatics, pp. 14-21, SOCINFO 2016. [[pdf](Identifying Correlated Bots in Twitter)]
    
    
    **site**: [[Debot: Real-time Bot Detection via Activity Correlation](www.cs.unm.edu/~chavoshi/debot/)] 
    
  
 2. **Botometer**
 
    **Description**: Botometer (formerly BotOrNot) checks the activity of a Twitter account and gives it a score. Higher scores mean more bot-like activity. Botometer is a joint project of the Observatory on Social Media ([[OSoMe](https://osome.iu.edu/)]) and the Network Science Institute ([[IUNI](https://iuni.iu.edu/)]) at Indiana University.
    
    
    > The DARPA Twitter bot challenge VS Subrahmanian Amos Azaria Skylar Durst Vadim Kagan Aram Galstyan Kristina Lerman Linhong Zhu Emilio Ferrara Alessandro Flammini Filippo Menczer Andrew Stevens Alexander Dekhtyar Shuyang Gao Tad Hogg Yan Liu Onur Varol Prashant Shiralkar Vinod Vydiswaran Qiaozhu Mei Tim Hwang. IEEE Computer 49(6), June 2016. [[pdf](https://arxiv.org/pdf/1601.05140.pdf)]
    
    > The Rise of Social Bots. Emilio Ferrara Onur Varol Clayton A. Davis Filippo Menczer Alessandro Flammini. Comm. ACM 59(7), July 2016. [[pdf](https://cacm.acm.org/magazines/2016/7/204021-the-rise-of-social-bots/fulltext)]
     
    > Feature Engineering for Social Bot Detection. Onur Varol Clayton A. Davis Filippo Menczer Alessandro Flammini. Feature Engineering for Machine Learning and Data Analytics. [[pdf](https://doi.org/10.1201/9781315181080-12)]
    
    > BotOrNot: A System to Evaluate Social Bots. Clayton A. Davis Onur Varol Emilio Ferrara Alessandro Flammini Filippo Menczer. WWW Developers Day 2016.[[pdf](https://dl.acm.org/doi/10.1145/2872518.2889302)]
    
    > Online Human-Bot Interactions: Detection, Estimation, and Characterization. Onur Varol Emilio Ferrara Clayton A. Davis Filippo Menczer Alessandro Flammini. ICWSM 2017. [[pdf](https://aaai.org/ocs/index.php/ICWSM/ICWSM17/paper/view/15587)]
    
    > Arming the public with AI to counter social bots. Kai-Cheng Yang Onur Varol Clayton A. Davis Emilio Ferrara Alessandro Flammini Filippo Menczer. Human Behavior and Emerging Technologies. [[pdf](https://doi.org/10.1002/hbe2.115)]
    
    > Scalable and Generalizable Social Bot Detection through Data Selection. Kai-Cheng Yang Onur Varol Pik-Mai Hui Filippo Menczer. AAAI 2020. [[pdf](https://doi.org/10.1609/aaai.v34i01.5460)]
    
    > Detection of Novel Social Bots by Ensembles of Specialized Classifiers. Mohsen Sayyadiharikandeh Onur Varol Kai-Cheng Yang Alessandro Flammini. Filippo Menczer. CIKM 2020. [[pdf](https://dl.acm.org/doi/10.1145/3340531.3412698)]

    > Botometer 101: Social bot practicum for computational social scientists. Kai-Cheng Yang Emilio Ferrara Filippo Menczer. Technical Report. [[pdf](https://arxiv.org/abs/2201.01608)]
    
    
    **site**: [[Botometer](https://botometer.osome.iu.edu/)]
