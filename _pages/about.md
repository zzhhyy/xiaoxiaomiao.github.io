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


I am an assistant professor at Singapore Institute of Technology until July 2025 and will join [Duke KunShan University](https://www.dukekunshan.edu.cn) as a tenure-track assistant professor in August 2025. 
Prior to that, from 2021 to 2023, I was a postdoctoral researcher at the National Institute of Informatics (NII), Japan, supervised by Prof [Junichi Yamagishi](https://scholar.google.com/citations?user=nRrdjtwAAAAJ&hl=zh-CN).
I received my Ph.D. degree from the Institute of Acoustics, Chinese Academy of Sciences/University of Chinese Academy of Sciences, in 2021, supervised by Prof [Pengyuan Zhang](https://scholar.google.com/citations?user=-Op9f5sAAAAJ&hl=en).
During 2018 and 2019, I was at the University of Kent, UK, as a Visiting Student, supervised by Prof [Ian McLoughlin](https://scholar.google.com/citations?user=mcnKgPoAAAAJ&hl=en).

My research interest includes speech security, speaker and language recognition, machine learning and deep learning. I am a co-organizer of the
[VoicePrivacy challenge](https://www.voiceprivacychallenge.org) 2022, 2024 and [Attacker Challenge at ICASSP 2025](https://www.voiceprivacychallenge.org/attacker/). I have published more than 30 papers at the top international AI conferences and journals such as IEEE/ACM Transactions on Audio, Speech, and Language Processing (TASLP), Neural Networks, Computer Speech & Language (CSL), ICASSP, INTERSPEECH.

# Teaching
- AAI3001, Deep Learning and Computer Science, SIT undergraduate course
- INF2008, Machine Learning, SIT undergraduate course
  
# Projects as PI
- Biometrics Security
  - 2022-2023 JSPS KAKENHI Grant-in-Aid for Research Start-up (22K21319): Language-independent speaker anonymization with multiple privacy-related attributes, Budget: 2.2 million JPY.
  - 2024-2026 MOE AcRF Tier 1 (GMS1048): User-centric Personalized Voice Protection, Budget: 150K SGD.

- Large Language Model
  - 2024-2025 MOE Ignition Grant: Generative AI Aided Safety Investigation System, Budget: 180K SGD (Including 30K cash contribution from Singapore SMRT).

# Patent and License as the First Author
- Japanese patent: Deep-learning based speaker anonymization method.
- Japanese program commercial license granted by Japan Broadcasting Corporation (NHK): VocalGuard, a speaker anonymization program.

# Academic Activities
- Organizer: Attacker Challenge at ICASSP 2025, VoicePrivacy Challenge 2024 and 2022.
- Session chair: ICASSP 2024, INTERSPEECH 2023, ISCSLP 2022.
- Reviewer: IEEE TASLP, IEEE TPAMI, IEEE SPL, CSL, ICASSP, INTERSPEECH, etc.


# Selected Publication

**2025**
- [The First VoicePrivacy Attacker Challenge](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10888513), Natalia Tomashenko, **Xiaoxiao Miao**, Emmanuel Vincent, and Junichi Yamagishi, *ICASSP*, 2025

**2024**  
- [The VoicePrivacy 2022 Challenge: Progress and Perspectives in Voice Anonymisation](https://doi.org/10.1109/TASLP.2024.3430530), Michele Panariello, Natalia Tomashenko, Xin Wang, **Xiaoxiao Miao**, Pierre Champion, Hubert Nourtel, Massimiliano Todisco, Nicholas Evans, Emmanuel Vincent, Junichi Yamagishi, *TASLP*, 2024.
- [VoicePAT: An Efficient Open-source Evaluation Toolkit for Voice Privacy Research](https://doi.org/10.1109/OJSP.2023.3344375), Sarina Meyer*, **Xiaoxiao Miao***, Ngoc Thang Vu, *IEEE Open Journal of Signal Processing*, 2024.
- [The VoicePrivacy 2024 Challenge Evaluation Plan](https://arxiv.org/abs/2404.02677), Natalia Tomashenko, **Xiaoxiao Miao**, Pierre Champion, Sarina Meyer, Xin Wang, Emmanuel Vincent, Michele Panariello, Nicholas Evans, Junichi Yamagishi, Massimiliano Todisco, *arXiv preprint*, 2024.
- [Joint Speaker Encoder and Neural Back-end Model for Fully End-to-End Automatic Speaker Verification with Multiple Enrollment Utterances](https://doi.org/10.1016/j.csl.2024.101619), Chang Zeng, **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *Computer Speech and Language*, 2024
- [SynVox2: Towards a privacy-friendly VoxCeleb2 dataset](https://arxiv.org/abs/2404.18501), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *ICASSP*, 2024.

**2023**
- [Speaker Anonymization using Orthogonal Householder Neural Network](https://doi.org/10.1109/TASLP.2023.3313429), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, Natalia Tomashenko, *TASLP*, 2023.

**2022**
- [Analyzing Language-Independent Speaker Anonymization Framework under Unseen Conditions](https://arxiv.org/pdf/2404.00861), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *INTERSPEECH*, 2022.
- 
**2021**
- [D-MONA: A dilated mixed-order non-local attention network for speaker and language recognition](https://doi.org/10.1016/j.neunet.2021.03.014), **Xiaoxiao Miao**, Ian McLoughlin, Wenchao Wang, Pengyuan Zhang, *Neural Networks*, 2021.
- [Variance Normalised Features for Language and Dialect Discrimination](https://doi.org/10.1007/s00034-020-01641-1), **Xiaoxiao Miao**, Ian McLoughlin, Yan Song, *Circuits, Systems, and Signal Processing*, 2021.
- [A New Time–Frequency Attention Tensor Network for Language Identification](https://doi.org/10.1007/s00034-019-01286-9), **Xiaoxiao Miao**, Ian McLoughlin, Yanyong Hong, *Circuits, Systems, and Signal Processing*, 2020.


# Open Source Code
- *Language-Independent Speaker Anonymization* [![](https://img.shields.io/github/stars/nii-yamagishilab/SSL-SAS)](https://github.com/nii-yamagishilab/SSL-SAS)
- *Multi-Speaker Anonymization* [![](https://img.shields.io/github/stars/xiaoxiaomiao323/MSA)](https://github.com/xiaoxiaomiao323/MSA)
- *Voice Anonymization Toolkit* [![](https://img.shields.io/github/stars/DigitalPhonetics/VoicePAT)](https://github.com/DigitalPhonetics/VoicePAT)
- *VoicePrivacy Challenge 2024* [![](https://img.shields.io/github/stars/Voice-Privacy-Challenge/Voice-Privacy-Challenge-2024)](https://github.com/Voice-Privacy-Challenge/Voice-Privacy-Challenge-2024)

# Award
- Outstanding reviewer award in INTERSPEECH, 2023
- Best paper nomination award in Odyssey, 2022
- The 2th place in MGB-5 challenge - Fine-grained Arabic Dialect Identification, ASRU, 2019
- Merit Student of University Chinese Academy of Science, 2018
- Best paper nomination award in NCMMSC, 2017


