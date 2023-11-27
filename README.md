<p align="center">
  <h1 align="center">A Systematic Review of Deep Learning-based Research on Radiology Report Generation</h1>

The official github repository of the survey paper titled "[A Systematic Review of Deep Learning-based Research on Radiology Report Generation](https://arxiv.org/abs/2311.14199)".

We maintain this repository to summarize papers and resources related to the radiology report generation (RRG) task. 

In `reference.bib`, we summarize the `bibtex` references of existing RRG papers, widely used datasets, and related toolkits.

If you have any suggestions about papers, code implementations, and other resources, please feel free to [pull requests](https://github.com/synlp/RRG-Review/pulls).

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

> #### ACL 2023: [ORGAN: Observation-Guided Radiology Report Generation via Tree Reasoning](https://aclanthology.org/2023.acl-long.451/)
>
>> Wenjun Hou, Kaishuai Xu, Yi Cheng, Wenjie Li, Jiang Liu
>

> #### ACL 2023: [Replace and Report: NLP Assisted Radiology Report Generation](https://aclanthology.org/2023.findings-acl.683.pdf)
>
>> Kaveri Kale, Pushpak Bhattacharyya, Kshitij Jadhav
>>

> #### CVPR 2023: [Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Dynamic_Graph_Enhanced_Contrastive_Learning_for_Chest_X-Ray_Report_Generation_CVPR_2023_paper.pdf)
>
>> Mingjie Li, Bingqian Li, Zicong Chen, Haokun Lin, Xiaodan Liang, Xiaojun Chang
>>

> #### CVPR 2023: [Interactive and Explainable Region-guided Radiology Report Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf)
>
>> Tim Tanida, Philip Muller, Georgios Kaissis, Daniel Rueckert
>>

> #### CVPR 2023: [KiUT: Knowledge-injected U-Transformer for Radiology Report Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.pdf)
>
>> Zhongzhen Huang, Xiaofan Zhang, Shaoting Zhang
>>

> #### CVPR 2023: [METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf)
>
>> Zhanyu Wang, Lingqiao Liu, Lei Wang, Luping Zhou
>>

> #### IEEE Transactions on Multimedia, 2023: [Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation](https://ieeexplore.ieee.org/document/9606584)
>
>> Yan Yang, Jun Yu, Jian Zhang, Weidong Han, Hanliang Jiang, Qingming Huang
>>

> #### IEEE Transactions on Multimedia 2023: [Semi-supervised Medical Report Generation via Graph-guided Hybrid Feature Consistency](https://ieeexplore.ieee.org/document/10119200)
>
>> Ke Zhang, Hanliang Jiang, Jian Zhang, Qingming Huang, Jianping Fan, Jun Yu, Weidong Han
>>

> #### WWW 2023: [Auxiliary Signal‑guided Knowledge Encoder‑decoder for Medical Report Generation](https://arxiv.org/abs/2006.03744)
>
>> Mingjie Li, Rui Liu, Fuyu Wang, Xiaojun Chang, Xiaodan Liang
>>

> #### EACL 2023: [KGVL-BART: Knowledge Graph Augmented Visual Language BART for Radiology Report Generation](https://aclanthology.org/2023.eacl-main.246/)
>
>> Kaveri Kale, Pushpak Bhattacharyya, Milind Gune, Aditya Shetty, Rustom Lawyer
>>

### 2022

> #### ACL 2022: [Reinforced Cross-modal Alignment for Radiology Report Generation](https://aclanthology.org/2022.findings-acl.38/)
>
>> Han Qin, Yan Song
>> 

> #### IEEE Transactions on Medical Imaging 2022: [Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach](https://ieeexplore.ieee.org/document/9768661)
>
>> Zhanyu Wang, Hongwei Han, Lei Wang
>>

> #### EMNLP, 2022: [Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards](https://aclanthology.org/2022.findings-emnlp.319/)
>
>> Jean-Benoit Delbrouck, Pierre Chambon, Christian Bluethgen, Emily Tsai, Omar Almusa, Curtis P. Langlotz
>>

> #### EMNLP 2022: [Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation](https://aclanthology.org/2022.emnlp-main.480/)
>
>> Toru Nishino, Yasuhide Miura, Tomoki Taniguchi, Tomoko Ohkuma, Yuki Suzuki, Shoji Kido, Noriyuki Tomiyama
>
>> Datasets: JLiverCT, MIMIC-CXR
>>

> #### AACL 2022: [Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations](https://aclanthology.org/2022.aacl-main.47/)
>
>> Francesco Dalla Serra, William Clackett, Chaoyang Wang, Hamish MacKinnon, Fani Deligianni, Jeffrey Dalton, Alison Q O’Neil
>> 

### 2021

> #### ACL 2021: [Cross-modal Memory Networks for Radiology Report Generation](https://aclanthology.org/2021.acl-long.459.pdf)
>
>> Zhihong Chen, Yaling Shen, Yan Song, Xiang Wan
>>

> #### COLING 2021: [JPG - Jointly Learn to Align: Automated Disease Prediction and Radiology Report Generation](https://aclanthology.org/2022.coling-1.523/)
>
>> Jingyi You, Dongyuan Li, Manabu Okumura, Kenji Suzuki
>>

> #### EMNLP 2021: [Progressive Transformer-Based Generation of Radiology Reports](https://aclanthology.org/2021.findings-emnlp.241/)
>
>> Farhad Nooralahzadeh, Nicolas Perez Gonzales, Thomas Frauenfelder, Koji Fujimoto, Michael Krauthammer
>>

> #### EMNLP 2021: [Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation](https://aclanthology.org/2021.findings-emnlp.336.pdf)
>
>> An Yan, Zexue He, Xing Lu, Jiang Du, Eric Chang, Amilcare Gentili, Julian McAuley, Chun-Nan Hsu
>>

> #### CVPR 2021: [Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.pdf)
>
>> Fenglin Liu, Xian Wu, Shen Ge, Wei Fan, Yuexian zou
>>

> #### CVPR 2021: [A Self-boosting Framework for Automated Radiographic Report Generation](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf)
>
>> Zhanyu Wang, Luping Zhou, Lei Wang
>>

> #### ICCV 2021: [Visual-Textual Attentive Semantic Consistency for Medical Report Generation](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Visual-Textual_Attentive_Semantic_Consistency_for_Medical_Report_Generation_ICCV_2021_paper.pdf)
>
>> Yi Zhou, Lei Huang, Tao Zhou, Huazhu Fu, Ling Shao
>> 

### 2020

> #### EMNLP 2020: [Generating Radiology Reports via Memory-driven Transformer](https://aclanthology.org/2020.emnlp-main.112/)
>
>> Zhihong Chen, Yan Song, Tsung-Hui Chang, Xiang Wan
>>

> #### EMNLP 2020: [Reinforcement Learning with Imbalanced Dataset for Data-to-Text Medical Report Generation](https://aclanthology.org/2020.findings-emnlp.202/)
>
>> Toru Nishino, Ryuji Kano, Ryota Ozaki, Norihisa Nakano, Tomoko Ohkuma, Fuji Xerox
>>

> #### AAAI 2020: [When Radiology Report Generation Meets Knowledge Graph](https://arxiv.org/abs/2002.08277)
>
>> Yixiao Zhang, Xiaosong Wang, Ziyue Xu, Qihang Yu, Alan Yuille, Daguang Xu
>>

### 2019

> #### ACL 2019: [Show, Describe and Conclude: On Exploiting the Structure Information of Chest X-Ray Reports](https://aclanthology.org/P19-1657/)
>
>> Baoyu Jing, Zeya Wang, Eric Xing
>>

> #### AAAI 2019: [Knowledge-Driven Encode, Retrieve, Paraphrase for Medical Image Report Generation](https://ojs.aaai.org/index.php/AAAI/article/view/4637/4515)
>
>> Christy Y. Li, Xiaodan Liang, Zhiting Hu, Eric P. Xing
>>

### 2018

> #### ACL 2018: [On the Automatic Generation of Medical Imaging Reports](https://aclanthology.org/P18-1240/)
>
>> Baoyu Jing, Pengtao Xie, Eric P. Xing
>>

## Datasets

> #### J. Am. Medical Informatics Assoc.: [Preparing A Collection of Radiology Examinations for Distribution and Retrieval](https://pubmed.ncbi.nlm.nih.gov/26133894/)
>
>> Dina Demner-Fushman, Marc D. Kohli, Marc B. Rosenman, Sonya E. Shooshan, Laritza Rodriguez, Sameer Antani, George R. Thoma, Clement J. McDonald
>>
>> Official website: [https://openi.nlm.nih.gov/faq](https://openi.nlm.nih.gov/faq)

> #### Scientific Data: [IMIC-CXR, A De-identified Publicly Available Database of Chest Radiographs with Free-text Reports](https://www.nature.com/articles/s41597-019-0322-0)
>
>> Alistair E. W. Johnson, Tom J. Pollard, Seth J. Berkowitz, Nathaniel R. Greenbaum, Matthew P. Lungren, Chih-ying Deng, Roger G. Mark & Steven Horng
>>
>> Official website: [https://physionet.org/content/mimic-cxr/1.0.0/](https://physionet.org/content/mimic-cxr/1.0.0/)

> #### ArXiv: [MIMIC-CXR-JPG, A Large Publicly Available Database of Labeled Chest Radiographs](https://arxiv.org/abs/1901.07042)
>
>> Alistair E. W. Johnson, Tom J. Pollard, Seth J. Berkowitz, Nathaniel R. Greenbaum, Matthew P. Lungren, Chih-ying Deng, Roger G. Mark & Steven Horng
>>
>> Official website: [https://physionet.org/content/mimic-cxr/2.0.0/](https://physionet.org/content/mimic-cxr/2.0.0/)
