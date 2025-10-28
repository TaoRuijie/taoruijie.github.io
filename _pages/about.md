---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am the Audio AI Enginner in Zoom, Singapore. Prior to that, from 2023 to 2024, I was the Research Fellow in National University of Singapore (NUS). I received the PhD and Master Degree from NUS in 2023 and 2019, supervised by Prof. [Li Haizhou](https://scholar.google.com.sg/citations?user=z8_x7C8AAAAJ&hl=en), Bachelor Degree from Soochow University in 2018.

My research interest includes (audio-only or audio-visual) speech processing: enhancement, extraction and seperation; speaker processing: recognition, diarization, active speaker detection and anti-spoofing. I also work in self-supervised learning. I have published more than 30 papers at the top international AI conferences and journals such as TASLP, TMM, ACM MM, ICASSP, INTERSPEECH. <a href='https://scholar.google.com/citations?user=sdXITx8AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FTaoRuijie%2Ftaoruijie.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 📜 Research Area

| Research Area | Tasks |
| -------- | -------- |
| Speech processing  | (Audio-visual) speech enhancement, extraction and separation |
| Speaker processing | (Audio-visual) speaker recognition, verification, diarization and anti-spoofing |
| Multi-modal speech processing | Active speaker detection, cross-modal speaker recognition |
| Algoirthm | Self-supervised learning, fundamental model |

# 🏫 Education

- *2019.08 - 2023.09*, Ph.D. in Speech Processing and Computer Vision, National University of Singapore (NUS), Singapore.
- *2018.08 - 2019.06*, M.Sc. in Electronic and Computer Engineer, National University of Singapore (NUS), Singapore.
- *2014.09 - 2018.06*, B.Eng. in Electronic Engineer, Soochow University, Suzhou, China.

# Working Experience
- *2024.12 - Now*, Audio AI Enginner, Zoom, Singapore.
- *2023.08 - 2024.11*, Research Fellow, National University of Singapore (NUS), Singapore.


# 📝 Publication

**2025**
- [Voice Conversion Augmentation for Speaker Recognition on Defective Datasets](https://arxiv.org/pdf/2404.00863), **Ruijie Tao**, Zhan Shi, Yidi Jiang, Tianchi Liu, Haizhou Li, **APSIPA**, <font color="red">Best Paper</font>, 2025.
- [Interpolating Speaker Identities in Embedding Space for Data Expansion](https://arxiv.org/pdf/2508.19210?), Tianchi Liu, Ruijie Tao, Qiongqiong Wang, Yidi Jiang, Hardik B Sailor, Ke Zhang, Jingru Lin, Haizhou Li, **APSIPA**, 2025.
- [Audio-Visual Target Speaker Extraction with Reverse Selective Auditory Attention](https://arxiv.org/pdf/2404.18501), **Ruijie Tao**, Xinyuan Qian, Yidi Jiang, Junjie Li, Jiadong Wang, Haizhou Li, **TASLP**, 2025.
- [A Benchmark for Multi-speaker Anonymization](https://arxiv.org/pdf/2407.05608), Xiaoxiao Miao, **Ruijie Tao**, Chang Zeng, Xin Wang, **TIFS**, 2025.
- [Target Speech Diarization with Multimodal Prompts](https://arxiv.org/pdf/2406.07198), Yidi Jiang, **Ruijie Tao**, Zhengyang Chen, Yanmin Qian, Haizhou Li, **TASLP**, 2025.
- [QAMO: Quality-aware Multi-centroid One-class Learning For Speech Deepfake Detection](https://arxiv.org/pdf/2509.20679), Duc-Tuan Truong, Tianchi Liu, **Ruijie Tao**, Junjie Li, Kong Aik Lee, Eng Siong Chng, **Under Review**, 2025;
- [Addressing Gradient Misalignment in Data-Augmented Training for Robust Speech Deepfake Detection]([https://arxiv.org/pdf/2509.20679](https://arxiv.org/pdf/2509.20682?)), Duc-Tuan Truong, Tianchi Liu, Junjie Li, **Ruijie Tao**, Kong Aik Lee, Eng Siong Chngg, **Under Review**, 2025;

**2024**
- [Enhancing Real-World Active Speaker Detection with Multi-Modal Extraction Pre-Training](https://arxiv.org/pdf/2404.00861), **Ruijie Tao**, Xinyuan Qian, Rohan Kumar Das, Xiaoxue Gao, Jiadong Wang, Haizhou Li, **TMM**, 2024.
- [Multi-Stage Face-Voice Association Learning with Keynote Speaker Diarization](https://arxiv.org/pdf/2407.17902) **Ruijie Tao**, Shi Zhan, Yidi Jiang, Duc-Tuan Truong, Eng-Siong Chng, Massimo Alioto and Haizhou Li. **ACM Multimedia**, 2024, [![](https://img.shields.io/github/stars/TaoRuijie/MFV-KSD?style=social&label=Code+Stars)](https://github.com/TaoRuijie/MFV-KSD)
- [Voice Conversion Augmentation for Speaker Recognition on Defective Datasets](https://arxiv.org/pdf/2404.00863), **Ruijie Tao**, Zhan Shi, Yidi Jiang, Tianchi Liu, Haizhou Li, **Under Review**, 2024.
- [How Do Neural Spoofing Countermeasures Detect Partially Spoofed Audio?](https://arxiv.org/pdf/2406.02483.pdf), Tianchi Liu, Lin Zhang, Rohan Kumar Das, Yi Ma, **Ruijie Tao**, Haizhou Li, **INTERSPEECH**, <font color="red">Oral</font>, 2024.
- [Temporal-Channel Modeling in Multi-head Self-Attention for Synthetic Speech Detection](https://arxiv.org/pdf/2406.17376), Duc-Tuan Truong, **Ruijie Tao**, Tuan Nguyen, Hieu-Thi Luong, Kong Aik Lee, Eng Siong Chng, **INTERSPEECH**, 2024. [![](https://img.shields.io/github/stars/ductuantruong/tcm_add?style=social&label=Code+Stars)](https://github.com/ductuantruong/tcm_add)
- [Emphasized Non-Target Speaker Knowledge in Knowledge Distillation for Automatic Speaker Verification](https://arxiv.org/pdf/2309.14838.pdf), Duc-Tuan Truong, **Ruijie Tao**, Jia Qi Yip, Kong Aik Lee, Eng Siong Chng, **ICASSP**, 2024. [![](https://img.shields.io/github/stars/ductuantruong/enskd?style=social&label=Code+Stars)](https://github.com/ductuantruong/enskd)
- [Audio-Visual Active Speaker Extraction for Sparsely Overlapped Multi-talker Speech](https://arxiv.org/pdf/2309.08408.pdf), Junjie Li, **Ruijie Tao**, Zexu Pan, Meng Ge, Shuai Wang, Haizhou Li, **ICASSP**, 2024.
- [Prompt-driven Target Speech Diarization](https://arxiv.org/pdf/2310.14823.pdf), Yidi Jiang, Zhengyang Chen, **Ruijie Tao**, Liqun Deng, Yanmin Qian and Haizhou Li, **ICASSP**, <font color="red">Oral</font>, 2024.
- [USED: Universal Speaker Extraction and Diarization](https://arxiv.org/pdf/2309.10674.pdf), Junyi Ao, Mehmet Sinan Yıldırım, Meng Ge, Shuai Wang, **Ruijie Tao**, Yanmin Qian, Liqun Deng, Longshuai Xiao, Haizhou Li, **TASLP**, 2024.


**2023**
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://ieeexplore.ieee.org/document/10106039), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Speaker recognition with two-step multi-modal deep cleansing](https://arxiv.org/pdf/2210.15903.pdf), **Ruijie Tao**, Kong Aik Lee, Shi Zhan and Haizhou Li, **ICASSP**, 2023. [![](https://img.shields.io/github/stars/TaoRuijie/AVCleanse?style=social&label=Code+Stars)](https://github.com/TaoRuijie/AVCleanse)
- [Deep Cross-modal Retrieval between Space Image and Acoustic Speech](https://ieeexplore.ieee.org/abstract/document/10285477), Xinyuan Qian, Wei Xue, Qiquan Zhang, **Ruijie Tao** and Haizhou Li, **TMM**, 2023.
- [Bi-directional Image-Speech Retrieval Through Geometric Consistency](https://av4d.org/papers/iccv23/p2.pdf), Xinyuan Qian, Wei Xue, Qiquan Zhang, **Ruijie Tao**, Yiming Wang, Kainan Chen, Haizhou Li, **ICCV Workshop**, 2023.
- [Target Active Speaker Detection with Audio-visual Cues](https://arxiv.org/pdf/2305.12831.pdf), Yidi Jiang, **Ruijie Tao**, Zexu Pan and Haizhou Li, **INTERSPEECH**, 2023. [![](https://img.shields.io/github/stars/Jiang-Yidi/TS-TalkNet?style=social&label=Code+Stars)](https://github.com/Jiang-Yidi/TS-TalkNet)

**2022**
- [Self-supervised Speaker Recognition with Loss-gated Learning](https://arxiv.org/pdf/2110.03869.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li. **ICASSP**, 2022, [![](https://img.shields.io/github/stars/TaoRuijie/Loss-Gated-Learning?style=social&label=Code+Stars)](https://github.com/TaoRuijie/Loss-Gated-Learning)
- [Selective Hearing through Lip-reading](https://arxiv.org/pdf/2106.07150.pdf), Zexu Pan, **Ruijie Tao**, Chenglin Xu, Haizhou Li, **TASLP**, 2022.
- [Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://arxiv.org/pdf/2110.07058.pdf), Kristen Grauman, Andrew Westbury, Eugene Byrne, ..., **Ruijie Tao**, ..., et al, **CVPR**, <font color="red">Oral, Best Paper Finallist</font>, 2022. [![](https://img.shields.io/github/stars/facebookresearch/Ego4d?style=social&label=Code+Stars)](https://github.com/facebookresearch/Ego4d)

**2021**

- [Is Someone Speaking? Exploring Long-term Temporal Features for Audio-visual Active Speaker Detection](https://arxiv.org/pdf/2107.06592.pdf), **Ruijie Tao**, Zexu Pan, Rohan Kumar Das, Xinyuan Qian, Mike Zheng Shou, Haizhou Li, **ACM Multimedia**, <font color="red">Oral</font>, 2021, [![](https://img.shields.io/github/stars/TaoRuijie/TalkNet_ASD?style=social&label=Code+Stars)](https://github.com/TaoRuijie/TalkNet_ASD)
- [NUS-HLT Report for ActivityNet Challenge 2021 AVA (Speaker)](https://static.googleusercontent.com/media/research.google.com/zh-CN//ava/2021/S3_NUS_Report_AVA_ActiveSpeaker_2021.pdf), **Ruijie Tao**, Zexu Pan, Rohan Kumar Das, Xinyuan Qian, Mike Zheng Shou, Haizhou Li, **CVPR Workshop Report**, 2021.
- [Muse: Multi-modal target speaker extraction with visual cues](https://arxiv.org/pdf/2010.07775.pdf), Zexu Pan, **Ruijie Tao**, Chenglin Xu, and Haizhou Li, **ICASSP**, 2021. 
- [HLT-NUS Submission for 2020 NIST Conversational Telephone Speech SRE](https://arxiv.org/pdf/2111.06671.pdf), Rohan Kumar Das, **Ruijie Tao** and Haizhou Li, **Arxiv**, 2021. [![](https://img.shields.io/github/stars/TaoRuijie/ECAPATDNN?style=social&label=Code+Stars)](https://github.com/TaoRuijie/ECAPATDNN)
- [I4U System Description for NIST SRE'20 CTS Challenge](https://arxiv.org/pdf/2211.01091.pdf), Kong Aik Lee, Tomi Kinnunen, Daniele Colibro, ..., **Ruijie Tao**, ..., et al, **Arxiv**, 2021.

**2020** 

- [Audio-visual Speaker Recognition with a Cross-modal Discriminative Network](https://arxiv.org/abs/2008.03894), **Ruijie Tao**, Rohan Kumar Das and Haizhou Li, **INTERSPEECH**, 2020.
- [HLT-NUS Submission for 2019 NIST Multimedia Speaker Recognition Evaluation](http://www.apsipa.org/proceedings/2020/pdfs/0000605.pdf), Rohan Kumar Das, **Ruijie Tao**, Jichen Yang, Wei Rao, Cheng Yu and Haizhou Li, **APSIPA**, 2020. 

# 💻 Open Source Code
- *Audio-visual target speech extraction* [![](https://github.com/TaoRuijie/SEANet)]
- *Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/ECAPATDNN?style=social&label=ECAPA-TDNN)](https://github.com/TaoRuijie/ECAPATDNN)
- *Active Speaker Detection Framework* [![](https://img.shields.io/github/stars/TaoRuijie/TalkNet_ASD?style=social&label=TalkNet-ASD)](https://github.com/TaoRuijie/TalkNet_ASD)
- *Self-supervised Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/Loss-Gated-Learning?style=social&label=LGL)](https://github.com/TaoRuijie/Loss-Gated-Learning)
- *Audio-visual Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/AVCleanse?style=social&label=AVCleanse)](https://github.com/TaoRuijie/AVCleanse)
- *Cross-modal Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/MFV-KSD?style=social&label=MFV-KSD)](https://github.com/TaoRuijie/MFV-KSD)
- *Ego4d Benchmark* [![](https://img.shields.io/github/stars/facebookresearch/Ego4d?style=social&label=Ego4d)](https://github.com/facebookresearch/Ego4d)

# 👔 Internship and Visiting Experience

- *2022.02 - 2022.08*, Visiting Student, Chinese University of Hong Kong (CUHKSZ), Shenzhen, China.
- *2015.07 - 2015.08*, Visiting Student, University of Cambridge, Cambridge, UK.

# 🎖 Others

**Award**
- APSIPA Best Paper Award (1 of 500+), 2025
- The 1st place winner in FAME Challenge, ACM-Multimedia, 2024
- Egocentric Vision (EgoVis) 2022/2023 Distinguished Paper Award, 2024
- IEEE SLP Student Travel Grant, ICASSP Best Paper Nominee (Corresponding author), 2024
- Nanyang Speech Technology Forum, Best Student Paper Award, 2023
- PREMIA, Best Student Paper Award, 2022
- CVPR Best Paper Nominee, 2022
- The 2nd place winner in NIST Speaker Recognition Evaluation (SRE), 2021
- The 3rd place winner in the ActivityNet Challenge (Speaker), CVPR Workshop, 2021
- NUS Research Scholarship, 2019

**Reviewer**

- Computer Vision and Pattern Recognition Conference (CVPR),
- ACM-Multimedia (MM),
- IEEE Transactions on Audio, Speech, and Language Processing (TASLP),
- IEEE Transactions on Information Forensics and Security (TIFS),
- IEEE The International Conference on Acoustics, Speech, & Signal Processing (ICASSP),
- IEEE Spoken Language Technology Workshop(SLT),
- The International Speech Communication Association (INTERSPEECH),
- Signal Processing Letters (SPL),
- Digital Signal Processing (DSP),
- Computer Speech & Language (CSL),
- IEEE Open Journal of Signal Processing (OJSP),
- International Symposium on Chinese Spoken Language Processing (ISCSLP).

**Teaching**

- EE3801 Data Engineering Principles, NUS undergraduate course
- EE5132 Wireless and Sensor Networks, NUS graduate course

