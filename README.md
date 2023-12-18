<p align="center">
  <h1 align="center">A Systematic Review of Deep Learning-based Research on Radiology Report Generation</h1>

The official GitHub repository of the survey paper titled "[A Systematic Review of Deep Learning-based Research on Radiology Report Generation](https://arxiv.org/abs/2311.14199)".

We maintain this repository to summarize papers and resources related to the radiology report generation (RRG) task. 

In `reference.bib`, we summarize the `bibtex` references of existing RRG papers, widely used datasets, and related toolkits.

If you have any suggestions about papers, code implementations, and other resources, please feel free to [start a new issue](https://github.com/synlp/RRG-Review/issues) or [pull requests](https://github.com/synlp/RRG-Review/pulls).

Papers involving **large language models (LLMs)** are in **boldface**.

## Citation

If your research is related to our work, please cite the following paper:

```markdown
@misc{liu2023systematic,
      title={A Systematic Review of Deep Learning-based Research on Radiology Report Generation}, 
      author={Chang Liu and Yuanhe Tian and Yan Song},
      year={2023},
      eprint={2311.14199},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

<details><summary>Table of Contents</summary><p>

- [Citation](#citation)
- [Papers](#papers)
  - [2023](#2023)
  - [2022](#2022)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
- [Datasets](#datasets)
</p></details><p></p>

## Papers
### 2023

[ACL 2023] ORGAN: Observation-Guided Radiology Report Generation via Tree Reasoning [[paper]](https://aclanthology.org/2023.acl-long.451/)

[ACL 2023] Replace and Report: NLP Assisted Radiology Report Generation [[paper]](https://aclanthology.org/2023.findings-acl.683.pdf)

[CVPR 2023] Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Dynamic_Graph_Enhanced_Contrastive_Learning_for_Chest_X-Ray_Report_Generation_CVPR_2023_paper.pdf)

[CVPR 2023] Interactive and Explainable Region-guided Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf)

[CVPR 2023] KiUT: Knowledge-injected U-Transformer for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.pdf)

[CVPR 2023] METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf)

[EACL 2023] KGVL-BART: Knowledge Graph Augmented Visual Language BART for Radiology Report Generation [[paper]](https://aclanthology.org/2023.eacl-main.246/)

[TMM 2023] Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation [[paper]](https://ieeexplore.ieee.org/document/9606584)

[TMM 2023] Semi-supervised Medical Report Generation via Graph-guided Hybrid Feature Consistency [[paper]](https://ieeexplore.ieee.org/document/10119200)

[WWW 2023] Auxiliary Signal‑guided Knowledge Encoder‑decoder for Medical Report Generation [[paper]](https://arxiv.org/abs/2006.03744)

**[arXiv 2023] MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model** [[paper]](https://arxiv.org/abs/2312.02233)

**[arXiv 2023] LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation** [[paper]](https://arxiv.org/abs/2305.11490) [[code]](https://github.com/hyn2028/llm-cxr)

**[arXiv 2023] Towards Generalist Biomedical AI** [[paper]](https://arxiv.org/abs/2307.14334) [[reproduced code]](https://github.com/kyegomez/Med-PaLM)

[arXiv 2023] Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data [[paper]](https://arxiv.org/abs/2308.02463) [[project]](https://chaoyi-wu.github.io/RadFM/) [[code]](https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file)

### 2022

[AACL 2022] Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations [[paper]](https://aclanthology.org/2022.aacl-main.47/)

[ACL 2022] Reinforced Cross-modal Alignment for Radiology Report Generation [[paper]](https://aclanthology.org/2022.findings-acl.38/)

[EMNLP, 2022] Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards [[paper]](https://aclanthology.org/2022.findings-emnlp.319/)

[EMNLP 2022] Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation [[paper]](https://aclanthology.org/2022.emnlp-main.480/)

[MICCAI 2022] RepsNet: Combining Vision with Language for Automated Medical Reports [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68)

[MICCAI 2022] A Self-guided Framework for Radiology Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56)

[TMI 2022] Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach [[paper]](https://ieeexplore.ieee.org/document/9768661)


### 2021

[ACL 2021] Cross-modal Memory Networks for Radiology Report Generation [[paper]](https://aclanthology.org/2021.acl-long.459.pdf)

[COLING 2021] JPG - Jointly Learn to Align: Automated Disease Prediction and Radiology Report Generation [[paper]](https://aclanthology.org/2022.coling-1.523/)

[EMNLP 2021] Progressive Transformer-Based Generation of Radiology Reports [[paper]](https://aclanthology.org/2021.findings-emnlp.241/)

[EMNLP 2021] Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation [[paper]](https://aclanthology.org/2021.findings-emnlp.336.pdf)

[CVPR 2021] Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.pdf)

[CVPR 2021] A Self-boosting Framework for Automated Radiographic Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf)

[ICCV 2021] Visual-Textual Attentive Semantic Consistency for Medical Report Generation [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Visual-Textual_Attentive_Semantic_Consistency_for_Medical_Report_Generation_ICCV_2021_paper.pdf)

[MICCAI 2021] RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting [[paper]](https://miccai2021.org/openaccess/paperlinks/2021/09/01/390-Paper1026.html)

[NeurIPS 2021] Auto-encoding Knowledge Graph for Unsupervised Medical Report Generation [[paper]](https://proceedings.neurips.cc/paper/2021/file/876e1c59023b1a0e95808168e1a8ff89-Paper.pdf)


### 2020

[AAAI 2020] When Radiology Report Generation Meets Knowledge Graph [[paper]](https://arxiv.org/abs/2002.08277)

[EMNLP 2020] Generating Radiology Reports via Memory-driven Transformer [[paper]](https://aclanthology.org/2020.emnlp-main.112/)

[EMNLP 2020] Reinforcement Learning with Imbalanced Dataset for Data-to-Text Medical Report Generation [[paper]](https://aclanthology.org/2020.findings-emnlp.202/)



### 2019

[AAAI 2019] Knowledge-Driven Encode, Retrieve, Paraphrase for Medical Image Report Generation [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4637/4515)

[ACL 2019] Show, Describe and Conclude: On Exploiting the Structure Information of Chest X-Ray Reports [[paper]](https://aclanthology.org/P19-1657/)

[MICCAI 2019] Automatic Radiology Report Generation based on Multi-view Image Fusion and Medical Concept Enrichment [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-32226-7_80)

### 2018

[ACL 2018] On the Automatic Generation of Medical Imaging Reports [[paper]](https://aclanthology.org/P18-1240/)

[MICCAI 2018] Multimodal Recurrent Model with Attention for Automated Radiology Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-00928-1_52)


## Datasets

[J. Am. Medical Informatics Assoc.] Preparing A Collection of Radiology Examinations for Distribution and Retrieval [[paper]](https://pubmed.ncbi.nlm.nih.gov/26133894/) [[dataset]](https://openi.nlm.nih.gov/faq)

[Scientific Data] MIMIC-CXR, A De-identified Publicly Available Database of Chest Radiographs with Free-text Reports [[paper]](https://www.nature.com/articles/s41597-019-0322-0) [[dataset]](https://physionet.org/content/mimic-cxr/1.0.0/)

[arXiv] MIMIC-CXR-JPG, A Large Publicly Available Database of Labeled Chest Radiographs [[paper]](https://arxiv.org/abs/1901.07042) [[dataset]](https://physionet.org/content/mimic-cxr/2.0.0/)

