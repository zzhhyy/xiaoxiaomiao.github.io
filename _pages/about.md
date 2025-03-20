---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include styles.html %} 

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

My research interest includes speech security, speaker and language recognition, and machine learning. I am a co-organizer of the
[VoicePrivacy challenge](https://www.voiceprivacychallenge.org) 2022, 2024 and [Attacker Challenge at ICASSP 2025](https://www.voiceprivacychallenge.org/attacker/). My work has been published at the top international AI conferences and journals such as IEEE/ACM Transactions on Audio, Speech, and Language Processing (TASLP), Neural Networks, Computer Speech and Language (CSL), ICASSP, INTERSPEECH.


<div class="warning">
  <div class="warning-title">
    <p>Recruiting</p>
  </div>
  <div class="warning-text">
    <p>
          <p style="margin-top:-0.8em">

      I’m looking for a <strong>full-time research assistant</strong> with a <strong>master's degree</strong>, starting in <strong>August 2025</strong> at <strong>Duke Kunshan University</strong>, to work with me on the <strong>voice privacy</strong> topic and assist with the <strong>machine learning course</strong> as a TA. If you are interested in working with me, drop me an email at <a href="mailto:xiaoxiao.miao@singaporetech.edu.sg">xiaoxiao.miao@singaporetech.edu.sg</a> with your <strong>CV</strong> and <strong>transcripts</strong> attached.
    </p>
        </p>
  </div>
</div>

# Teaching
- AAI3001, Deep Learning and Computer Vision, SIT undergraduate course
- INF2008, Machine Learning, SIT undergraduate course
  
# Projects as PI
- Biometrics Security
  - 2022-2023 JSPS KAKENHI Grant-in-Aid for Research Start-up (22K21319): Language-independent speaker anonymization with multiple privacy-related attributes, Budget: 2.2M JPY.
  - 2024-2026 MOE AcRF Tier 1 (R-R13-A405-0005): User-centric Personalized Voice Protection, Budget: 150K SGD.

- Large Language Model
  - 2024-2025 MOE Ignition Grant (R-IE3-A405-0005): Generative AI Aided Safety Investigation System, Budget: 180K SGD (Including 30K cash contribution from Singapore SMRT).

# Patent and License as the First Author
- Japanese patent: Deep-learning based speaker anonymization method.
- Japanese program commercial license granted by Japan Broadcasting Corporation (NHK): VocalGuard, a speaker anonymization program.

# Academic Activities
- Organizer: Attacker Challenge at ICASSP 2025, VoicePrivacy Challenge 2024 and 2022.
- Session chair: ICASSP 2024, INTERSPEECH 2023, ISCSLP 2022.
- Reviewer: IEEE TASLP, IEEE TPAMI, IEEE SPL, CSL, ICASSP, INTERSPEECH, etc.


# Publication

**2025**
- [The First VoicePrivacy Attacker Challenge](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10888513), Natalia Tomashenko, **Xiaoxiao Miao**, Emmanuel Vincent, and Junichi Yamagishi, *ICASSP*, 2025

**2024**  
- [Spoofing-Aware Speaker Verification Robust Against Domain and Channel Mismatches](https://ieeexplore.ieee.org/abstract/document/10832246), Chang Zeng, **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *SLT*, 2024.
- [Instructsing: High-Fidelity Singing Voice Generation Via Instructing Yourself](https://ieeexplore.ieee.org/abstract/document/10832285), Chang Zeng, Chunhui Wang, **Xiaoxiao Miao**, Jian Zhao, Zhonglin Jiang, Yong Chen, *SLT*, 2024.
- [The First VoicePrivacy Attacker Challenge Evaluation Plan](https://arxiv.org/abs/2410.07428), Natalia Tomashenko, Xiaoxiao Miao, Emmanuel Vincent, Junichi Yamagishi, *arXiv*, 2024.
- [The VoicePrivacy 2022 Challenge: Progress and Perspectives in Voice Anonymisation](https://doi.org/10.1109/TASLP.2024.3430530), Michele Panariello, Natalia Tomashenko, Xin Wang, **Xiaoxiao Miao**, Pierre Champion, Hubert Nourtel, Massimiliano Todisco, Nicholas Evans, Emmanuel Vincent, Junichi Yamagishi, *TASLP*, 2024.
- [The VoicePrivacy 2024 Challenge Evaluation Plan](https://arxiv.org/abs/2404.02677), Natalia Tomashenko, **Xiaoxiao Miao**, Pierre Champion, Sarina Meyer, Xin Wang, Emmanuel Vincent, Michele Panariello, Nicholas Evans, Junichi Yamagishi, Massimiliano Todisco, *arXiv preprint*, 2024.
- [Joint Speaker Encoder and Neural Back-end Model for Fully End-to-End Automatic Speaker Verification with Multiple Enrollment Utterances](https://doi.org/10.1016/j.csl.2024.101619), Chang Zeng, **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *Computer Speech and Language*, 2024
- [SynVox2: Towards a privacy-friendly VoxCeleb2 dataset](https://arxiv.org/abs/2404.18501), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *ICASSP*, 2024.
- [Libri2Vox Dataset: Target Speaker Extraction with Diverse Speaker Conditions and Synthetic Data](https://arxiv.org/abs/2412.12512), Yun Liu, Xuechen Liu, **Xiaoxiao Miao**, Junichi Yamagishi, Under Review, 2024.
- [Adapting General Disentanglement-Based Speaker Anonymization for Enhanced Emotion Preservation](https://arxiv.org/abs/2408.05928), **Xiaoxiao Miao**, Yuxiang Zhang, Xin Wang, Natalia Tomashenko, Donny Cheng Lock Soh, Ian Mcloughlin, Under Review, 2024.
- [A benchmark for multi-speaker anonymization](https://arxiv.org/abs/2407.05608), **Xiaoxiao Miao**, Ruijie Tao, Chang Zeng, Xin Wang, Under Review, 2024.

**2023**
- [VoicePAT: An Efficient Open-source Evaluation Toolkit for Voice Privacy Research](https://doi.org/10.1109/OJSP.2023.3344375), Sarina Meyer\*, **Xiaoxiao Miao\***, Ngoc Thang Vu, *IEEE Open Journal of Signal Processing*, 2023.
- [Speaker Anonymization using Orthogonal Householder Neural Network](https://doi.org/10.1109/TASLP.2023.3313429), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, Natalia Tomashenko, *TASLP*, 2023.
- [Speaker-Text Retrieval via Contrastive Learning](https://arxiv.org/abs/2312.06055), Xuechen Liu, Xin Wang, Erica Cooper, **Xiaoxiao Miao**, Junichi Yamagishi, *arXiv preprint*, 2023.
- [Hiding speaker’s sex in speech using zero-evidence speaker representation in an analysis/synthesis pipeline](https://ieeexplore.ieee.org/abstract/document/10096749), Paul-Gauthier Noé, **Xiaoxiao Miao**, Xin Wang, Junichi Yamagishi, Jean-François Bonastre, Driss Matrouf, *ICASSP*, 2023.

**2022**
- [Attention back-end for automatic speaker verification with multiple enrollment utterances](https://ieeexplore.ieee.org/abstract/document/9746688), Chang Zeng, Xin Wang, Erica Cooper, **Xiaoxiao Miao**, Junichi Yamagishi, *ICASSP*, 2022
- [Analyzing Language-Independent Speaker Anonymization Framework under Unseen Conditions](https://arxiv.org/pdf/2404.00861), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, *INTERSPEECH*, 2022.
- [Language-independent speaker anonymization approach using self-supervised pre-trained models](https://arxiv.org/abs/2202.13097), **Xiaoxiao Miao**, Xin Wang, Erica Cooper, Junichi Yamagishi, Natalia Tomashenko, *Odyssey*, 2022
- [GuidedMix: An on‐the‐fly data augmentation approach for robust speaker recognition system](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.12354), Runqiu Xiao, Zhuo Li, **Xiaoxiao Miao**, Wenchao Wang, Pengyuan Zhang, Electronics Letters, 2022
  
**2021**
- [D-MONA: A dilated mixed-order non-local attention network for speaker and language recognition](https://doi.org/10.1016/j.neunet.2021.03.014), **Xiaoxiao Miao**, Ian McLoughlin, Wenchao Wang, Pengyuan Zhang, *Neural Networks*, 2021.
- [Variance Normalised Features for Language and Dialect Discrimination](https://doi.org/10.1007/s00034-020-01641-1), **Xiaoxiao Miao**, Ian McLoughlin, Yan Song, *Circuits, Systems, and Signal Processing*, 2021.
- [Adaptive Margin Circle Loss for Speaker Verification](https://www.isca-archive.org/interspeech_2021/xiao21b_interspeech.html), Runqiu Xiao, **Xiaoxiao Miao**, Wenchao Wang, Pengyuan Zhang, Bin Cai, Liuping Luo, *INTERSPEECH*, 2021

**2020-2018**
- [A New Time–Frequency Attention Tensor Network for Language Identification](https://doi.org/10.1007/s00034-019-01286-9), **Xiaoxiao Miao**, Ian McLoughlin, Yanyong Hong, *Circuits, Systems, and Signal Processing*, 2020.
- [Lstm-tdnn with convolutional front-end for dialect identification in the 2019 multi-genre broadcast challenge](https://arxiv.org/abs/1912.09003), Xiaoxiao Miao, Ian McLoughlin, *arXiv*, 2019.
- [A New Time-Frequency Attention Mechanism for TDNN and CNN-LSTM-TDNN, with Application to Language Identification](https://www.isca-archive.org/interspeech_2019/miao19b_interspeech.pdf), **Xiaoxiao Miao**, Ian McLoughlin, Yonghong Yan, *INTERSPEECH*, 2019.
- [Improved conditional generative adversarial net classification for spoken language recognition](https://ieeexplore.ieee.org/abstract/document/8639522), **Xiaoxiao Miao**, Ian McLoughlin, Shengyu Yao, Yonghong Yan, *SLT*, 2018.
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


