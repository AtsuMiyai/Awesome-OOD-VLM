# Generalized Out-of-Distribution Detection and Beyond in Vision Language Model Era: A Survey
[![paper](https://img.shields.io/badge/Paper-arXiv24-b31b1b?style=for-the-badge)](http://arxiv.org/abs/2407.21794)
&nbsp;&nbsp;&nbsp;
[![paper](https://img.shields.io/badge/Issues&#44;%20Comments&#44;%20and%20Questions-are%20all%20welcomed&#33;-f39f37?style=for-the-badge)](https://github.com/AtsuMiyai/Awesome-OOD-VLM/issues)
&nbsp;&nbsp;&nbsp;
[![paper](https://img.shields.io/badge/Forum-SLACK-797ef6?style=for-the-badge)](https://openood.slack.com/)


## Generalized OOD Detection v2
|🚀 Our framework encapsulates the evolution of OOD detection and related tasks in the VLM era, fostering collaborative efforts among each community 🤝|
|-----------------------------------------|


<p align="center" width="100%">
<img src=figs/evo_vlm.png  width="100%" height="100%">
<div>
<div align="center">
<br>
    <a href='https://atsumiyai.github.io/' target='_blank'>Atsuyuki Miyai<sup>1</sup></a>&emsp;
    <a href='https://jingkang50.github.io/' target='_blank'>Jingkang Yang<sup>2,†</sup></a>&emsp;
    <a href='https://zjysteven.github.io/' target='_blank'>Jingyang Zhang<sup>3</sup></a>&emsp;
    <a href='https://pages.cs.wisc.edu/~alvinming/' target='_blank'>Yifei Ming<sup>4</sup></a>&emsp;
    <a href='https://yueqianlin.com/' target='_blank'>Yueqian Lin<sup>3</sup></a>&emsp;
    <br>
    <a href='https://yu1ut.com/' target='_blank'>Qing Yu<sup>1,5</sup></a>&emsp;
    <a href='https://scholar.google.co.jp/citations?hl=ja&user=2bCSG1AAAAAJ&view_op=list_works&authuser=1&sortby=pubdate' target='_blank'>Go Irie<sup>6</sup></a>&emsp;
    <a href='https://raihanjoty.github.io/' target='_blank'>Shafiq Joty<sup>4,2</sup></a>&emsp;
	  <a href='https://pages.cs.wisc.edu/~sharonli/' target='_blank'>Yixuan Li<sup>7</sup></a>&emsp;
    <a href='https://ece.duke.edu/faculty/hai-helen-li' target='_blank'>Hai Li<sup>3</sup></a>&emsp;
	  <a href='https://liuziwei7.github.io/' target='_blank'>Ziwei Liu<sup>2,†</sup></a>
    <br>
    <a href='https://scholar.google.com/citations?user=rE9iY5MAAAAJ&hl=en' target='_blank'>Toshihiko Yamasaki<sup>1</sup></a>&emsp;
    <a href='https://scholar.google.co.jp/citations?user=CJRhhi0AAAAJ&hl=en' target='_blank'>Kiyoharu Aizawa<sup>1</sup></a>
</div>
<div align="center">
    <sup>1</sup>The University of Tokyo&emsp;
    <sup>†</sup>S-Lab, <sup>2</sup>Nanyang Technological University&emsp;
    <sup>3</sup>Duke University&emsp;
    <sup>4</sup>Salesforce AI Research&emsp;
    <sup>5</sup>LY Corporation&emsp;
    <sup>6</sup>Tokyo University of Science&emsp;
    <sup>7</sup>University of Wisconsin-Madison&emsp;&emsp;
    <br>
</div>


## About This Repository
This is a repository of our survey paper. We hope that our survey can help readers and participants better understand the demanding challenges on OOD detection and related topics in the VLM era.     
This repository plays the following two roles:
- This repository provides an easily accessible list of the references mentioned in the paper Table 2. This list will continue to include more promising works as new ones emerge. Please feel free to recommend relevant and good works via [Pull Request](https://github.com/AtsuMiyai/Awesome-OOD-VLM/pulls).
- We hope that this repository will become a discussion panel for readers to ask questions, raise concerns, and make constructive comments. Feel free to post your ideas to [Issues](https://github.com/AtsuMiyai/Awesome-OOD-VLM/issues).


## Abstract
We present a **generalized OOD detection v2**, encapsulating the evolution of Anomaly Detection (AD), Novelty Detection (ND), Open-set Recognition (OSR), Out-of-distribution (OOD)
detection, and Outlier Detection (OD) in the VLM era. Our framework reveals that, with some field inactivity and integration, **the demanding challenges in the
VLM era have become OOD detection and AD**. In addition to the inter-field evolution, we also highlight the significant shift in the definition,
problem settings, and benchmarks; our work thus features a comprehensive review of the methodology for OOD detection, including
in-depth discussion over other related tasks to clarify their relationship to and influence on OOD detection. Finally, we explore **the
advancements in the emerging Large Vision Language Model (LVLM) era**, represented by GPT-4V. We conclude this survey with open
challenges and potential research directions of OOD detection in the VLM and LVLM era.


## Common Benchmarks
<details open>
<summary><b>CLIP-based OOD Detection</b></summary>

> - [ImageNet OOD Benchmark](https://github.com/deeplearning-wisc/large_scale_ood#out-of-distribution-dataset)
> - [ImageNet-20, ImageNet-10](https://github.com/deeplearning-wisc/MCM)
> - [ImageNet protocol](https://github.com/mala-lab/NegPrompt/)
</details>

<details open>
<summary><b>CLIP-based AD</b></summary>

> - [MVTec-AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)
> - [VisA](https://github.com/amazon-science/spot-diff)
</details>




## Methodology
We introduce methods for CLIP-based OOD detection and CLIP-based AD.    
To provide diverse perspectives on OOD detection approaches, we have encompassed a wide range of methods, including preprints.

### Timeline
![timeline.png](figs/timeline.png)
|:--:|


### Paper List 
![methods.png](figs/methods.png)
|:--:|


### CLIP-based OOD Detection

<details open>
<summary><b> Zero-shot</b></summary>

>-  [![ZOC](https://img.shields.io/badge/AAAI'22-ZOC-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2109.02748)
    [![Star](https://img.shields.io/github/stars/sesmae/ZOC.svg?style=social&label=Star)](https://github.com/sesmae/ZOC)
> - [![MCM](https://img.shields.io/badge/NeurIPS'22-MCM-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2211.13445)
    [![Star](https://img.shields.io/github/stars/deeplearning-wisc/MCM.svg?style=social&label=Star)](https://github.com/deeplearning-wisc/MCM), [![Star](https://img.shields.io/github/stars/AtsuMiyai/LoCoOp.svg?style=social&label=Star)](https://github.com/AtsuMiyai/LoCoOp), [![Star](https://img.shields.io/github/stars/Jingkang50/OpenOOD.svg?style=social&label=Star)](https://github.com/Jingkang50/OpenOOD)
> - [![GL-MCM](https://img.shields.io/badge/arXiv'23-GLMCM-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2304.04521)
    [![Star](https://img.shields.io/github/stars/AtsuMiyai/GL-MCM.svg?style=social&label=Star)](https://github.com/AtsuMiyai/GL-MCM), [![Star](https://img.shields.io/github/stars/AtsuMiyai/LoCoOp.svg?style=social&label=Star)](https://github.com/AtsuMiyai/LoCoOp)
> - [![CLIPN](https://img.shields.io/badge/ICCV'23-CLIPN-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2308.12213)
    [![Star](https://img.shields.io/github/stars/xmed-lab/CLIPN.svg?style=social&label=Star)](https://github.com/xmed-lab/CLIPN)
> - [![NegLabel](https://img.shields.io/badge/ICLR'24-NegLabel-fdd7e6?style=for-the-badge)](https://openreview.net/forum?id=xUO1HXz4an)
    [![Star](https://img.shields.io/github/stars/XueJiang16/NegLabel.svg?style=social&label=Star)](https://github.com/XueJiang16/NegLabel)
> - [![EOE](https://img.shields.io/badge/ICML'24-EOE-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2406.00806)
    [![Star](https://img.shields.io/github/stars/tmlr-group/EOE.svg?style=social&label=Star)](https://github.com/tmlr-group/EOE)
> - [![SeTAR](https://img.shields.io/badge/arXiv'24-SeTAR-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2406.12629)
    [![Star](https://img.shields.io/github/stars/X1AOX1A/SeTAR.svg?style=social&label=Star)](https://github.com/X1AOX1A/SeTAR)
</details>


<details open>
<summary><b> Few-shot</b></summary>

>- [![PEFT-MCM](https://img.shields.io/badge/IJCV'23-PEFTMCM-d0e9ff?style=for-the-badge)](https://link.springer.com/article/10.1007/s11263-023-01895-7)
   [![Star](https://img.shields.io/github/stars/deeplearning-wisc/MCM.svg?style=social&label=Star)](https://github.com/deeplearning-wisc/MCM), [![Star](https://img.shields.io/github/stars/AtsuMiyai/LoCoOp.svg?style=social&label=Star)](https://github.com/AtsuMiyai/LoCoOp)
> - [![LoCoOp](https://img.shields.io/badge/NeurIPS'23-LoCoOp-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2306.01293)
    [![Star](https://img.shields.io/github/stars/AtsuMiyai/LoCoOp.svg?style=social&label=Star)](https://github.com/AtsuMiyai/LoCoOp)
> - [![LSN](https://img.shields.io/badge/ICLR'24-LSN-d0e9ff?style=for-the-badge)](https://openreview.net/forum?id=nanyAujl6e)
> - [![IDPrompt](https://img.shields.io/badge/CVPR'24-IDPrompt-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2311.15243)
    [![Star](https://img.shields.io/github/stars/ycfate/ID-like.svg?style=social&label=Star)](https://github.com/ycfate/ID-like)
> - [![NegPrompt](https://img.shields.io/badge/CVPR'24-NegPrompt-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2404.03248)
    [![Star](https://img.shields.io/github/stars/mala-lab/negprompt.svg?style=social&label=Star)](https://github.com/mala-lab/negprompt)
> - [![GalLoP](https://img.shields.io/badge/ECCV'24-GalLoP-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2407.01400)
> - [![Dual-Adapter](https://img.shields.io/badge/arXiv'24-DualAdapter-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2405.16146)
> - [![LAPT](https://img.shields.io/badge/ECCV'24-LAPT-d0e9ff?style=for-the-badge)](https://arxiv.org/pdf/2407.08966)
    [![Star](https://img.shields.io/github/stars/YBZh/LAPT.svg?style=social&label=Star)](https://github.com/YBZh/LAPT)
</details>


<details open>
<summary><b> Others</b></summary>

>-  [![LSA](https://img.shields.io/badge/arXiv'23-LSA-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2312.01732)
    [![Star](https://img.shields.io/github/stars/LuFan31/LSA.svg?style=social&label=Star)](https://github.com/LuFan31/LSA)
>-  [![EmptyClass](https://img.shields.io/badge/arXiv'24-EmptyClass-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2405.16091)


</details>


### CLIP-based AD
<details open>
<summary><b> Zero-shot</b></summary>

>-  [![WinCLIP](https://img.shields.io/badge/CVPR'23-WinCLIP-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2303.14814)
    [![Star](https://img.shields.io/github/stars/caoyunkang/WinClip.svg?style=social&label=Star)](https://github.com/caoyunkang/WinClip)
> - [![APRIL-GAN](https://img.shields.io/badge/arXiv'23-APRILGAN-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2305.17382)
    [![Star](https://img.shields.io/github/stars/ByChelsea/VAND-APRIL-GAN.svg?style=social&label=Star)](https://github.com/ByChelsea/VAND-APRIL-GAN)
> - [![AnoCLIP](https://img.shields.io/badge/arXiv'23-AnoCLIP-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2308.15939)
    [![Star](https://img.shields.io/github/stars/hq-deng/AnoVL.svg?style=social&label=Star)](https://github.com/hq-deng/AnoVL)
> - [![AnomalyCLIP](https://img.shields.io/badge/ICLR'24-AnomalyCLIP-fdd7e6?style=for-the-badge)](https://arxiv.org/pdf/2310.18961)
    [![Star](https://img.shields.io/github/stars/zqhang/AnomalyCLIP.svg?style=social&label=Star)](https://github.com/zqhang/AnomalyCLIP)
> - [![RWDA](https://img.shields.io/badge/BMVC'23-RWDA-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2308.11119)
> - [![SDP](https://img.shields.io/badge/arXiv'23-SDP-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2311.00453)
> - [![FiLo](https://img.shields.io/badge/arXiv'24-FiLo-fdd7e6?style=for-the-badge)](https://arxiv.org/abs/2404.13671)
</details>


<details open>
<summary><b> Few-shot</b></summary>

>-  [![WinCLIP+](https://img.shields.io/badge/CVPR'23-WinCLIP+-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2303.14814)
    [![Star](https://img.shields.io/github/stars/caoyunkang/WinClip.svg?style=social&label=Star)](https://github.com/caoyunkang/WinClip)
> - [![APRIL-GAN](https://img.shields.io/badge/arXiv'23-APRILGAN-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2305.17382)
    [![Star](https://img.shields.io/github/stars/ByChelsea/VAND-APRIL-GAN.svg?style=social&label=Star)](https://github.com/ByChelsea/VAND-APRIL-GAN)
> - [![PromptAD](https://img.shields.io/badge/CVPR'24-PromptAD-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2404.05231)
    [![Star](https://img.shields.io/github/stars/FuNz-0/PromptAD.svg?style=social&label=Star)](https://github.com/FuNz-0/PromptAD)
> - [![InCTRL](https://img.shields.io/badge/CVPR'24-InCTRL-d0e9ff?style=for-the-badge)](https://arxiv.org/abs/2403.06495)
    [![Star](https://img.shields.io/github/stars/mala-lab/InCTRL.svg?style=social&label=Star)](https://github.com/mala-lab/InCTRL)
</details>


<details open>
<summary><b> Others</b></summary>

>-  [![LTAD](https://img.shields.io/badge/CVPR'24-LTAD-fdd7e6?style=for-the-badge)](https://arxiv.org/pdf/2403.20236v1)
</details>

---
## Early Advance in LVLM Era
![evolution_lvlm.png](figs/evo_lvlm.png)

In the LVLM Era, OOD detection and related topics have evolved as follows:

### (i) Sensory Anomaly Detection &rArr; **Sensory Anomaly Detection**
<details open>
<summary><b>AD</b></summary>

> - [![AnomalyGPT](https://img.shields.io/badge/AAAI'24-AnomalyGPT-c2e2de?style=for-the-badge)](https://arxiv.org/abs/2308.15366)
    [![Star](https://img.shields.io/github/stars/CASIA-IVA-Lab/AnomalyGPT.svg?style=social&label=Star)](https://github.com/CASIA-IVA-Lab/AnomalyGPT)
> - [![Myriad](https://img.shields.io/badge/arXiv'23-Myriad-c2e2de?style=for-the-badge)](https://arxiv.org/abs/2310.19070)
    [![Star](https://img.shields.io/github/stars/tzjtatata/Myriad.svg?style=social&label=Star)](https://github.com/tzjtatata/Myriad)
> - [![Generic AD](https://img.shields.io/badge/arXiv'23-GenericAD-c2e2de?style=for-the-badge)](https://arxiv.org/pdf/2311.02782)
    [![Star](https://img.shields.io/github/stars/caoyunkang/GPT4V-for-Generic-Anomaly-Detection.svg?style=social&label=Star)](https://github.com/caoyunkang/GPT4V-for-Generic-Anomaly-Detection)
</details>

### (ii) OOD Detection &rArr; **Unsolvable Problem Detection** 
<details open>
<summary><b>UPD</b></summary>

> - [![UPD](https://img.shields.io/badge/arXiv'24-UPD-c2e2de?style=for-the-badge)](https://arxiv.org/abs/2403.20331)
    [![Star](https://img.shields.io/github/stars/AtsuMiyai/UPD.svg?style=social&label=Star)](https://github.com/AtsuMiyai/UPD)

</details>


## Acknowledgment

This repository is built upon the foundation of the following resources:
[generalized OOD detection v1](https://github.com/Jingkang50/OODSurvey?tab=readme-ov-file), [OpenOOD codebase](https://github.com/Jingkang50/OpenOOD).


## Contact
If you have questions or find any mistake, please open an issue mentioning @AtsuMiyai.


## Citation
If you find our survey paper helpful for your research, please consider citing the following paper:
```bibtex
@article{miyai2024generalized2,
  title={Generalized Out-of-Distribution Detection and Beyond in Vision Language Model Era: A Survey},
  author={Miyai, Atsuyuki and Yang, Jingkang and Zhang, Jingyang and Ming, Yifei and Lin, Yueqian and Yu, Qing and Irie, Go and Joty, Shafiq and Li, Yixuan and Li, Hai and Liu, Ziwei and Yamasaki, Toshihiko and Aizawa, Kiyoharu},
  journal={arXiv preprint arXiv:2407.21794},
  year={2024}
}
```


Besides, please also consider citing our other projects that are closely related to this survey.    


- Our Directly Related Projects
```bibtex
# generalized OOD detection framework v1, survey
@article{yang2024generalized,
  title={Generalized out-of-distribution detection: A survey},
  author={Yang, Jingkang and Zhou, Kaiyang and Li, Yixuan and Liu, Ziwei},
  journal={IJCV},
  pages={1--28},
  year={2024},
}

# MCM (Zero-shot OOD detection)
@inproceedings{ming2022delving,
  title={Delving into out-of-distribution detection with vision-language representations},
  author={Ming, Yifei and Cai, Ziyang and Gu, Jiuxiang and Sun, Yiyou and Li, Wei and Li, Yixuan},
  booktitle={NeurIPS},
  year={2022}
}

# GL-MCM (Zero-shot OOD detection)
@article{miyai2023zero,
  title={Zero-Shot In-Distribution Detection in Multi-Object Settings Using Vision-Language Foundation Models},
  author={Miyai, Atsuyuki and Yu, Qing and Irie, Go and Aizawa, Kiyoharu},
  journal={arXiv preprint arXiv:2304.04521},
  year={2023}
}

# PEFT-MCM (Few-shot OOD detection, Concurrent work with LoCoOp)
@article{ming2024does,
  title={How Does Fine-Tuning Impact Out-of-Distribution Detection for Vision-Language Models?},
  author={Ming, Yifei and Li, Yixuan},
  journal={IJCV},
  volume={132},
  number={2},
  pages={596--609},
  year={2024},
}

# LoCoOp (Few-shot OOD detection, Concurrent work with PEFT-MCM)
@inproceedings{miyai2023locoop,
  title={LoCoOp: Few-Shot Out-of-Distribution Detection via Prompt Learning},
  author={Miyai, Atsuyuki and Yu, Qing and Irie, Go and Aizawa, Kiyoharu},
  booktitle={NeurIPS},
  year={2023}
}

# UPD
@article{miyai2024upd,
  title={Unsolvable Problem Detection: Evaluating Trustworthiness of Vision Language Models},
  author={Miyai, Atsuyuki and Yang, Jingkang and Zhang, Jingyang and Ming, Yifei and Yu, Qing and Irie, Go and Li, Yixuan and Li, Hai and Liu, Ziwei and Aizawa, Kiyoharu},
  journal={arXiv preprint arXiv:2403.20331},
  year={2024}
}
```

- Our Other Projects
```bibtex
# OpenOOD 
@inproceedings{yang2022openood,
  title={Openood: Benchmarking generalized out-of-distribution detection},
  author={Yang, Jingkang and Wang, Pengyun and Zou, Dejian and Zhou, Zitang and Ding, Kunyuan and Peng, Wenxuan and Wang, Haoqi and Chen, Guangyao and Li, Bo and Sun, Yiyou and others},
  booktitle={NeurIPS Datasets and Benchmarks Track},
  year={2022}
}

# OpenOOD v1.5 report
@article{zhang2023openood,
  title={OpenOOD v1.5: Enhanced Benchmark for Out-of-Distribution Detection},
  author={Zhang, Jingyang and Yang, Jingkang and Wang, Pengyun and Wang, Haoqi and Lin, Yueqian and Zhang, Haoran and Sun, Yiyou and Du, Xuefeng and Zhou, Kaiyang and Zhang, Wayne and Li, Yixuan and Liu, Ziwei and Chen, Yiran and Li, Hai},
  journal={arXiv preprint arXiv:2306.09301},
  year={2023}
}
```
