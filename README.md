<p align="center">
  <h1 align="center">A Systematic Review of Deep Learning-based Research on Radiology Report Generation</h1>

The official GitHub repository of the survey paper titled "[A Systematic Review of Deep Learning-based Research on Radiology Report Generation](https://arxiv.org/abs/2311.14199)".

We maintain this repository to summarize papers and resources related to the radiology report generation (RRG) task. 

In `reference.bib`, we summarize the `bibtex` references of existing RRG papers, widely used datasets, and related toolkits.

If you have any suggestions about papers, code implementations, and other resources, please feel free to [start a new issue](https://github.com/synlp/RRG-Review/issues) or [pull requests](https://github.com/synlp/RRG-Review/pulls).

Papers involving **large language models (LLMs)** are in **boldface**.


# News 🔥

[2024 Jan. 9th] We have updated all accepted papers by EMNLP 2023.


# Table of Contents

- [News 🔥](#news-)
- [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [2024](#2024)
    - [2023](#2023)
    - [2022](#2022)
    - [2021](#2021)
    - [2020](#2020)
    - [2019](#2019)
    - [2018](#2018)
  - [Datasets](#datasets)
  - [Toolkits](#toolkits)

## Papers
### 2024
[arXiv 2024] ICON: Improving Inter-Report Consistency for Radiology Report Generation via Lesion-aware Mix-up Augmentation [[paper](https://arxiv.org/abs/2402.12844)] [[code](https://github.com/wjhou/ICon)]

[ACL 2024] Fine-Grained Image-Text Alignment in Medical Imaging Enables Explainable Cyclic Image-Report Generation [[paper]](https://aclanthology.org/2024.acl-long.514.pdf)

[AAAI 2024] Bootstrapping Large Language Models for Radiology Report Generation [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29826) [[code]](https://github.com/synlp/R2-LLM)

[AAAI 2024] PromptMRG: Diagnosis-Driven Prompts for Medical Report Generation [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/28038/28087)

[BSPC 2024] An Efficient but Effective Writer: Diffusion-based Semi-autoregressive Transformer for Automated Radiology Report Generation [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S1746809423010844)

[BSPC 2024] Unsupervised Disease Tags for Automatic Radiology Report Generation [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S1746809423011758)

[CVPR 2024] Instance-level Expert Knowledge and Aggregate Discriminative Attention for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Bu_Instance-level_Expert_Knowledge_and_Aggregate_Discriminative_Attention_for_Radiology_Report_CVPR_2024_paper.pdf)

[ICASSP 2024] Improving Radiology Report Generation with D^2-Net: When Diffusion Meets Discriminator [[paper](https://ieeexplore.ieee.org/abstract/document/10448326)] [[code](https://github.com/Yuda-Jin/D-2-Net)]

[Neurocomputing 2024] Improving Radiology Report Generation with Multi-grained Abnormality Prediction [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0925231224008932)

[Neurocomputing 2024] Trust It or Not: Confidence-guided Automatic Radiology Report Generation [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0925231224001450)

[TMI 2024] An Organ-aware Diagnosis Framework for Radiology Report Generation [[paper]](https://ieeexplore.ieee.org/abstract/document/10579857)

[TMI 2024] Multi-Grained Radiology Report Generation With Sentence-Level Image-Language Contrastive Learning [[paper]](https://ieeexplore.ieee.org/abstract/document/10458706)

[TMI 2024] PhraseAug: An Augmented Medical Report Generation Model with Phrasebook [[paper]](https://ieeexplore.ieee.org/abstract/document/10560051)

[TMM 2024] From Observation to Concept: A Flexible Multi-View Paradigm for Medical Report Generation [[paper]](https://ieeexplore.ieee.org/abstract/document/10356722)

[WACV 2024] Complex Organ Mask Guided Radiology Report Generation [[paper]](https://arxiv.org/pdf/2311.02329.pdf) [[code]](https://github.com/GaryGuTC/COMG_model)

### 2023

[arXiv 2023] LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation [[paper]](https://arxiv.org/abs/2305.11490) [[code]](https://github.com/hyn2028/llm-cxr) [[code]](https://github.com/hyn2028/llm-cxr)

[arXiv 2023] MAIRA-1: A Specialised Large Multimodal Model for Radiology Report Generation [[paper]](https://arxiv.org/abs/2311.13668) [[project]](https://www.microsoft.com/en-us/research/project/project-maira/)

[arXiv 2023] MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model [[paper]](https://arxiv.org/abs/2312.02233)

[arXiv 2023] Pragmatic Radiology Report Generation [[paper]](https://arxiv.org/pdf/2311.17154.pdf)

[arXiv 2023] RadLLM: A Comprehensive Healthcare Benchmark of Large Language Models for Radiology [[paper]](https://arxiv.org/pdf/2307.13693.pdf) [[project]](https://mohsenarjmandi.com/projects/)

[arXiv 2023] RaDialog: A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance [[paper]](https://arxiv.org/pdf/2311.18681.pdf) [[code]](https://github.com/ChantalMP/RaDialog)

[arXiv 2023] Towards Generalist Biomedical AI [[paper]](https://arxiv.org/abs/2307.14334) [[reproduced code]](https://github.com/kyegomez/Med-PaLM)

[arXiv 2023] Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data [[paper]](https://arxiv.org/abs/2308.02463) [[project]](https://chaoyi-wu.github.io/RadFM/) [[code]](https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file)

[arXiv 2023] Cross-Modal Causal Intervention for Medical Report Generation [[paper]](https://arxiv.org/pdf/2303.09117.pdf) [[code]](https://github.com/WissingChen/VLCI)

[arXiv 2023] Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning [[paper]](https://arxiv.org/pdf/2312.15869.pdf)

[arXiv 2023] Radiology Report Generation Using Transformers Conditioned with Non-imaging Data [[paper]](https://arxiv.org/pdf/2311.11097.pdf)

[arXiv 2023] Can Prompt Learning Benefit Radiology Report Generation? [[paper]](https://arxiv.org/pdf/2308.16269)

[ACL 2023] ORGAN: Observation-Guided Radiology Report Generation via Tree Reasoning [[paper]](https://aclanthology.org/2023.acl-long.451/) [[code]](https://github.com/wjhou/ORGan)

[ACL 2023] Replace and Report: NLP Assisted Radiology Report Generation [[paper]](https://aclanthology.org/2023.findings-acl.683.pdf)

[AMI 2023] Improving Chest X-ray Report Generation by Leveraging Warm Starting [[paper]](https://arxiv.org/pdf/2201.09405.pdf) [[code]](https://github.com/aehrc/cvt2distilgpt2)

[CBM 2023] Visual Prior-based Cross-modal Alignment Network for Radiology Report Generation [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0010482523009873)

[CBM 2023] Visual Prior-based Cross-modal Alignment Network for Radiology Report Generation [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0010482523009873)

[CVPR 2023] Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Dynamic_Graph_Enhanced_Contrastive_Learning_for_Chest_X-Ray_Report_Generation_CVPR_2023_paper.pdf) [[code]](https://github.com/mlii0117/DCL)

[CVPR 2023] Interactive and Explainable Region-guided Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf) [[code]](https://github.com/ttanida/rgrg)

[CVPR 2023] KiUT: Knowledge-injected U-Transformer for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.pdf)

[CVPR 2023] METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf)

[EACL 2023] KGVL-BART: Knowledge Graph Augmented Visual Language BART for Radiology Report Generation [[paper]](https://aclanthology.org/2023.eacl-main.246/) [[code]](https://github.com/yeliu918/KG-BART)

[EMNLP 2023] Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting [[paper]](https://arxiv.org/pdf/2310.17811v2.pdf) 

[EMNLP 2023] PhenotypeCLIP: Phenotype-based Contrastive Learning for Medical Imaging Report Generation [[paper]](https://aclanthology.org/2023.emnlp-main.989.pdf)

[EMNLP 2023] RECAP: Towards Precise Radiology Report Generation via Dynamic Disease Progression Reasoning [[paper]](https://aclanthology.org/2023.findings-emnlp.140.pdf) [[code]](https://github.com/wjhou/recap)

[ICASSP 2023] MvCo-DoT: Multi-View Contrastive Domain Transfer Network for Medical Report Generation [[paper]](https://arxiv.org/pdf/2304.07465.pdf)

[ICCV 2023] Unify, Align and Refine: Multi-Level Semantic Alignment for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unify_Align_and_Refine_Multi-Level_Semantic_Alignment_for_Radiology_Report_ICCV_2023_paper.pdf)

[ICIP 2023] Self Adaptive Global-Local Feature Enhancement for Radiology Report Generation [[paper]](https://arxiv.org/pdf/2211.11380.pdf)

[TMI 2023] Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation [[paper]](https://ieeexplore.ieee.org/document/10045710/)

[**TMI 2023] SGT++: Improved Scene Graph-guided Transformer for Surgical Report Generation** [[paper]](https://ieeexplore.ieee.org/document/10330637/)

[TMM 2024] From Observation to Concept: A Flexible Multi-view Paradigm for Medical Report Generation [[paper]](https://ieeexplore.ieee.org/document/10356722)

[TMM 2023] Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation [[paper]](https://ieeexplore.ieee.org/document/9606584)

[TMM 2023] Semi-supervised Medical Report Generation via Graph-guided Hybrid Feature Consistency [[paper]](https://ieeexplore.ieee.org/document/10119200)

[WWW 2023] Auxiliary Signal‑guided Knowledge Encoder‑decoder for Medical Report Generation [[paper]](https://arxiv.org/abs/2006.03744) [[code]](https://github.com/mlii0117/COV-CTR)



### 2022

[arXiv 2022] CAMANet: Class Activation Map Guided Attention Network for Radiology Report Generation [[paper]](https://arxiv.org/pdf/2211.01412.pdf)

[arXiv 2022] Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty [[paper]](https://arxiv.org/pdf/2210.13729.pdf)

[arXiv 2022] DeltaNet: Conditional Medical Report Generation for COVID-19 Diagnosis [[paper]](https://arxiv.org/pdf/2211.13229.pdf)

[AACL 2022] Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations [[paper]](https://aclanthology.org/2022.aacl-main.47/)

[ACL 2022] Reinforced Cross-modal Alignment for Radiology Report Generation [[paper]](https://aclanthology.org/2022.findings-acl.38/) [[code]](https://github.com/synlp/R2GenRL)

[BSPC 2022] Clinically Coherent Radiology Report Generation with Imbalanced Chest X-rays [[paper]](https://ieeexplore.ieee.org/abstract/document/9994871)

[BMVC 2022] On the Importance of Image Encoding in Automated Chest X-Ray Report Generation [[paper]](https://arxiv.org/ftp/arxiv/papers/2211/2211.13465.pdf) [[code]](https://github.com/mudabek/encoding-cxr-report-gen)

[COLING] Cross-modal Contrastive Attention Model for Medical Report Generation [[paper]](https://aclanthology.org/2022.coling-1.210.pdf)

[CVPR 2022] Cross-modal Clinical Graph Transformer for Ophthalmic Report Generation [[paper]](https://ieeexplore.ieee.org/document/9879084)

[ECCV 2022] Cross-Modal Prototype Driven Network for Radiology Report Generation [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136950558.pdf)

[EMNLP 2022] Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards [[paper]](https://aclanthology.org/2022.findings-emnlp.319/) [[code]](https://github.com/jbdel/vilmedic?tab=readme-ov-file)

[EMNLP 2022] Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation [[paper]](https://aclanthology.org/2022.emnlp-main.480/)

[ICBB 2022] Clinically Coherent Radiology Report Generation with Imbalanced Chest X-rays [[paper]](https://ieeexplore.ieee.org/document/9994871/)

[MIA 2022] Knowledge Matters: Chest Radiology Report Generation with General and Specific Knowledge [[paper]](https://pdf.sciencedirectassets.com/272154/1-s2.0-S1361841522X00042/1-s2.0-S1361841522001578/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFQaCXVzLWVhc3QtMSJGMEQCIFPdvXsyFRfWxMj7jhqb0f970F6Z4ob8tvvHZZFgZlFqAiBy5IiEQ4PlAir2yIwNA7JcWzUNL2TRxtu3sYh7y%2FoXDSq8BQjN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMbAYHoe7gNJJndbczKpAFMjLnJ6hkHKMbEX6fFEdWNQpY0sCwalqj8EXda%2B5sS86uDeKRlkUJeQWbUO8t1ufSC6aWd1V7SNHLUqgnLDqw7QGKPf07Xu5LSJtSOlTic1tMO%2B5HBQpunTtD3eeJFw%2FteLbzL4ZhClTjouaedBsNC8Qh0bDSjVVE5sdFCm%2Fifue7Ppobq2PCSU3XYSRpxxDloSQY4c0xZxbPlPxjB4rADrvDPefwPmT1MrlA74RYTRLmyE83f%2Bmqpah6Wj%2FH7%2FDBE4Qppv6C4ZNrZ9j1fs2JA%2Ful%2FMOd%2FJrffnIWpJDCFm6ZHTH7h%2Fef%2FuN5SMAUEjGNkP7d7UI3Q7CNpK8nlywWwLfEoK%2FDyt0%2F1gpSLfbl7%2FOisdRA%2BDRzemFQQnxBGAlXWyyB0F%2BMx6Jnrnm%2FaJhzw%2FlGCRrewLbDX6%2Fd8hHdEq1tnZaerP1O0N6JTH8A%2BhsB%2FXqETFmm3fal%2B2dpOyCCBvBQ%2F6H%2FtHqTRMFDJHclogE4YV3c3oUSww%2BzTBAAvxheuPC98ToQEYeZzk9tzhwIeJlSYNuQRmOOGpk9lL%2BnrwrNvRywI0g5Y0PIGrqxrtqnixt%2FWjCy5eq%2Bfr7gJIyufQBiKwxXOJHdAmiNRdueIidmU6HHCEAJdvKHBtKu95XQicIZW0s5tzpaH7JZ9TrePd3mkQfCXnnnOyifqKOHJcoCJwQGyX6OYty%2B1iDflrdvPHFKG9dSSVvLDEjtbxQ2pUZwPmk0rT777w7jtQcLofkdhgWaPy0XV3cZ3i3wF%2FYwazU0yUnlS%2F43Vi4m08Ii4J5WW1QVZ2V0f1Zmw6LwEOSVbIOW3t9mIP2rbLK7WAp16GrnHBw2Ibr2fHQ%2BMJWCeBHpvrw7vwqenKc2Dwrc%2BF4wx5yErAY6sgFrZ1xJ%2Ftc6v0oW48%2BDzNsaXNopwTfD5Mv8IXC3bXt%2FgWEarHdvGryQY1BH0ewnE5Nzea%2FyAGjO3docq3of%2B5581Dmv6oZ%2FePgzIPK0QQdp1HBYWhJRe0HG8hJ1LPgssqy3v1TH4YZx5zKF4lddQ4PO33vE6c%2BrxKHLsf4ZdPT7m2aramQkxiCEkCLJmroJtS3KRi1qVLtZwifqyQ06hZ2a5f7wWh79h%2BbEMjya1gjoD%2B2G&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231219T042855Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYVICNITU7%2F20231219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b50b28cc347b877a7dc441b3225995171c0d6a9a3f9f068b131abd437436c586&hash=7744bcd1a019821bc513a15cd2cb8cf13676616438298545a5c9398d0235fb03&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1361841522001578&tid=spdf-ec11110a-c807-441f-87d5-c1978b17d4fa&sid=533db39126ac0241317848c5289133cfb43bgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=120d5b5c540c0557060406&rr=837ce6cdad98078f&cc=hk) [[code]](https://github.com/LX-doctorAI1/GSKET)

[**MICCAI 2023] SGT: Scene Graph-Guided Transformer for Surgical Report Generation** [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16449-1_48) [[code]](https://github.com/ccccchenllll/SGT_master)

[MICCAI 2022] RepsNet: Combining Vision with Language for Automated Medical Reports [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68)

[MICCAI 2022] A Self-guided Framework for Radiology Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56) [[code]](https://github.com/LijunRio/A-Self-Guided-Framework)

[MICCAI 2022] A Medical Semantic-Assisted Transformer for Radiographic Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_63)

[MICCAI 2022] An Inclusive Task-Aware Framework for Radiology Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_54)

[MICCAI 2022] Lesion Guided Explainable Few Weak-Shot Medical Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_59)

[MICCAI 2022] TranSQ: Transformer-Based Semantic Query for Medical Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58) [[code]](https://github.com/zjukongming/TranSQ)

[TMI 2022] Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach [[paper]](https://ieeexplore.ieee.org/document/9768661)


### 2021

[ACL 2021] Cross-modal Memory Networks for Radiology Report Generation [[paper]](https://aclanthology.org/2021.acl-long.459.pdf) [[code]](https://github.com/cuhksz-nlp/R2GenCMN)

[COLING 2021] JPG - Jointly Learn to Align: Automated Disease Prediction and Radiology Report Generation [[paper]](https://aclanthology.org/2022.coling-1.523/)

[CVPR 2021] Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.pdf)

[CVPR 2021] A Self-boosting Framework for Automated Radiographic Report Generation [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf)

[EMNLP 2021] Automated Generation of Accurate & Fluent Medical X-ray Reports [[paper]](https://aclanthology.org/2021.emnlp-main.288/) [[code]](https://github.com/ginobilinie/xray_report_generation)

[EMNLP 2021] Progressive Transformer-Based Generation of Radiology Reports [[paper]](https://aclanthology.org/2021.findings-emnlp.241/) [[code]](https://github.com/uzh-dqbm-cmi/ARGON)

[EMNLP 2021] Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation [[paper]](https://aclanthology.org/2021.findings-emnlp.336.pdf) [[code]](https://github.com/zzxslp/WCL)

[ICCV 2021] Visual-Textual Attentive Semantic Consistency for Medical Report Generation [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Visual-Textual_Attentive_Semantic_Consistency_for_Medical_Report_Generation_ICCV_2021_paper.pdf)

[MICCAI 2021] RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting [[paper]](https://miccai2021.org/openaccess/paperlinks/2021/09/01/390-Paper1026.html) [[code]](https://github.com/farrell236/RATCHET)

[MICCAI 2021] Trust It or Not: Confidence-Guided Automatic Radiology Report Generation [[paper]](https://arxiv.org/pdf/2106.10887.pdf)

[MICCAI 2021] AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7)

[NAACL 2021] Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation [[paper]](https://aclanthology.org/2021.naacl-main.416.pdf) [[code]](https://github.com/ysmiura/ifcc)

[NeurIPS 2021] Auto-encoding Knowledge Graph for Unsupervised Medical Report Generation [[paper]](https://proceedings.neurips.cc/paper/2021/file/876e1c59023b1a0e95808168e1a8ff89-Paper.pdf)

[PMLR 2021] Retrieval-Based Chest X-Ray Report Generation Using a Pre-trained Contrastive Language-Image Model [[paper]](https://proceedings.mlr.press/v158/endo21a.html)


### 2020

[AAAI 2020] When Radiology Report Generation Meets Knowledge Graph [[paper]](https://arxiv.org/abs/2002.08277)

[ACCV 2020] Hierarchical X-Ray Report Generation via Pathology tags and Multi Head Attention [[paper]](https://openaccess.thecvf.com/content/ACCV2020/papers/Srinivasan_Hierarchical_X-Ray_Report_Generation_via_Pathology_tags_and_Multi_Head_ACCV_2020_paper.pdf)

[EMNLP 2020] Generating Radiology Reports via Memory-driven Transformer [[paper]](https://aclanthology.org/2020.emnlp-main.112/) [[code]](https://github.com/cuhksz-nlp/R2Gen)

[EMNLP 2020] Reinforcement Learning with Imbalanced Dataset for Data-to-Text Medical Report Generation [[paper]](https://aclanthology.org/2020.findings-emnlp.202/)



### 2019

[AAAI 2019] Knowledge-Driven Encode, Retrieve, Paraphrase for Medical Image Report Generation [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4637/4515)

[ACL 2019] Show, Describe and Conclude: On Exploiting the Structure Information of Chest X-Ray Reports [[paper]](https://aclanthology.org/P19-1657/)

[MICCAI 2019] Automatic Radiology Report Generation based on Multi-view Image Fusion and Medical Concept Enrichment [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-32226-7_80)

[BMVC 2019] Addressing Data Bias Problems for Chest X-ray Image Report Generation [[paper]](https://bmvc2019.org/wp-content/uploads/papers/1007-paper.pdf)

### 2018

[ACL 2018] On the Automatic Generation of Medical Imaging Reports [[paper]](https://aclanthology.org/P18-1240/) [[code]](https://github.com/ZexinYan/Medical-Report-Generation)

[MICCAI 2018] Multimodal Recurrent Model with Attention for Automated Radiology Report Generation [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-00928-1_52) [[code]](https://github.com/tengfeixue-victor/Medical-Report-Generation)

[NeurIPS 2018] Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation [[paper]](https://proceedings.neurips.cc/paper_files/paper/2018/file/e07413354875be01a996dc560274708e-Paper.pdf) 


## Datasets

[J. Am. Medical Informatics Assoc.] Preparing A Collection of Radiology Examinations for Distribution and Retrieval [[paper]](https://pubmed.ncbi.nlm.nih.gov/26133894/) [[dataset]](https://openi.nlm.nih.gov/faq)

[Scientific Data] MIMIC-CXR, A De-identified Publicly Available Database of Chest Radiographs with Free-text Reports [[paper]](https://www.nature.com/articles/s41597-019-0322-0) [[dataset]](https://physionet.org/content/mimic-cxr/1.0.0/)

[arXiv] MIMIC-CXR-JPG, A Large Publicly Available Database of Labeled Chest Radiographs [[paper]](https://arxiv.org/abs/1901.07042) [[dataset]](https://physionet.org/content/mimic-cxr/2.0.0/)

[arXiv] Detailed Annotations of Chest X-Rays via CT Projection for Report Understanding [[paper]](https://arxiv.org/pdf/2210.03416) [[dataset]](https://github.com/dataset-ninja/paxray)

[CVPR] ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf) [[dataset]](https://github.com/YeongHyeon/Download-ChestX-ray8)

[NeurIPS 2021 Datasets & Benchmark] FFA-IR: Towards an Explainable and Reliable Medical Report Generation Benchmark [[paper]](https://openreview.net/pdf?id=FgYTwJbjbf) [[dataset]](https://physionet.org/content/ffa-ir-medical-report/1.0.0/) [[GitHub]](https://github.com/mlii0117/FFA-IR)

[NeurIPS 2021 Datasets & Benchmark] RadGraph: Extracting Clinical Entities and Relations from Radiology Reports [[paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/c8ffe9a587b126f152ed3d89a146b445-Paper-round1.pdf) [[dataset]](https://physionet.org/content/radgraph/1.0.0/)

## Toolkits
[NeurIPS 2021 Datasets & Benchmark] RadGraph [[paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/c8ffe9a587b126f152ed3d89a146b445-Paper-round1.pdf) [[project]](https://ajay1994.github.io/blog/2021/06/20/RadGraph-Extracting-Clinical-Entities-and-Relations-from-Radiology-Reports) [[code]](https://physionet.org/content/radgraph/1.0.0/)

[AAAI 2019] CheXpert [[paper]](https://arxiv.org/pdf/1901.07031.pdf) [[code]](https://github.com/stanfordmlgroup/chexpert-labeler)

[AAAI 2019] NegBio [[paper]](https://arxiv.org/abs/1712.05898.pdf) [[code]](https://github.com/ncbi-nlp/NegBio)

[AAAI 2019] MIRQI [[paper]](https://arxiv.org/abs/2002.08277) [[code]](https://github.com/xiaosongwang/MIRQI)
