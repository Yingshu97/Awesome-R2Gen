<p align="center">
  <h1 align="center">Awesome Radiology Report Generation</h1>

# Introduction

This GitHub repository serves as a comprehensive hub for the R2Gen project's developments over recent years. Here, you will find links to academic papers, alongside direct links to the corresponding code repositories, if available. 

Additionally, we have systematically presented the performance metrics of R2Gen on the **MIMIC-CXR dataset** within these publications. Our aim is to provide an easily navigable and resource-rich platform for researchers and enthusiasts alike, fostering greater collaboration and innovation in our field.

Given the current surge in popularity of **Large Language models**, we have specifically highlighted the R2Gen models that leverage these LLMs. Additionally, we have introduced a comments column to each entry, where we note the unique features or significant highlights of certain studies.



Whether you have suggestions, have spotted an error that needs correction, or wish to contribute, please feel free to [start a new issue](https://github.com/Yingshu97/Awesome-R2Gen/issues) or [pull requests](https://github.com/Yingshu97/Awesome-R2Gen/pulls), your input is highly valued. 

# To-Do Lists

- [ ] Add Clinic efficacy scores

# Papers

| Year |                         Model                         |                            Title                             |                             Code                             | B-1   | B-2  | B-3  | B-4  | ROUGE | METEOR | CIDEr | LLM | Comments                                |
| :--: | :---------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | ----- | ----- | ----- | ----- | ----- | ------ | ----- | ------------------ | --------------------------------------- |
| 2020 |                         R2Gen                         | [Generating Radiology Reports via Memory-driven Transformer](https://arxiv.org/abs/2010.16056) |         [code](https://github.com/zhjohnchan/R2Gen)          | 0.353 | 0.218 | 0.145 | 0.103 | 0.277 | 0.142  |       |                    |                                         |
| 2020 |                         ASKG                          | [Auxiliary Signal-Guided Knowledge Encoder-Decoder for Medical Report Generation](https://arxiv.org/abs/2006.03744) |         [code](https://github.com/mlii0117/COV-CTR)          | \-    |       |       |       |       |        |       |                    | different dataset                       |
| 2021 |                       R2GenCMN                        | [Cross-modal Memory Networks for Radiology Report Generation](https://aclanthology.org/2021.acl-long.459.pdf) |        [code](https://github.com/zhjohnchan/R2GenCMN)        | 0.353 | 0.218 | 0.148 | 0.106 | 0.278 | 0.142  |       |                    |                                         |
| 2021 |                         PPKED                         | [Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation](https://arxiv.org/abs/2106.06963) |                                                              | 0.36  | 0.224 | 0.149 | 0.106 | 0.284 | 0.149  |       |                    | no mimic                                |
| 2021 |                   AlignTransformer                    | [AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7) |                                                              | 0.378 | 0.235 | 0.156 | 0.112 | 0.283 | 0.158  |       |                    | no mimic                                |
| 2021 |                     Self-boosting                     | [A Self-boosting Framework for Automated Radiographic Report Generation](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf) |                                                              | \-    |       |       |       |       |        |       |                    | no mimic                                |
| 2021 |                   Knowledge Matters                   | [Knowledge Matters: Radiology Report Generation with General and Specific Knowledge](https://arxiv.org/abs/2112.15009) |        [code](https://github.com/LX-doctorAI1/GSKET)         | 0.363 | 0.228 | 0.156 | 0.115 | 0.284 |        | 0.203 |                    |                                         |
| 2021 |                          CA                           | [Contrastive Attention for Automatic Chest X-ray Report Generation](https://arxiv.org/pdf/2106.06965.pdf) |                                                              | 0.35  | 0.219 | 0.152 | 0.109 | 0.283 | 0.151  |       |                    |                                         |
| 2021 |                          WCL                          | [Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation](https://arxiv.org/abs/2109.12242) |            [code](https://github.com/zzxslp/WCL)             | 0.373 |       |       | 0.107 | 0.274 | 0.144  |       |                    |                                         |
| 2021 |                         CMCL                          | [Competence-based Multimodal Curriculum Learning for Medical Report Generation](https://arxiv.org/abs/2206.14579) |                                                              | 0.344 | 0.217 | 0.14  | 0.097 | 0.281 | 0.133  |       |                    |                                         |
| 2021 |                        RATCHET                        | [RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting](https://arxiv.org/abs/2107.02104) |        [code](https://github.com/farrell236/RATCHET)         | 0.232 |       |       |       | 0.24  |        | 0.493 |                    |                                         |
| 2021 |                           -                           | [Variational Topic Inference for Chest X-Ray Report Generation](https://arxiv.org/pdf/2107.07314.pdf) | [code](https://github.com/ivonajdenkoska/variational-xray-report-gen) | 0.418 | 0.293 | 0.152 | 0.109 | 0.302 | 0.177  |       |                    |                                         |
| 2021 |                           -                           | [Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation](https://arxiv.org/pdf/2010.10042.pdf) |                                                              | \-    |       |       |       |       |        |       |                    | with new optimisation method            |
| 2022 |                         MSAT                          | [A Medical Semantic-Assisted Transformer for Radiographic Report Generation](https://arxiv.org/abs/2208.10358) |         [code](https://github.com/wang-zhanyu/MSAT)          | 0.373 | 0.235 | 0.162 | 0.12  | 0.282 | 0.143  | 0.299 |                    |                                         |
| 2022 |                        XProNet                        | [Cross-modal Prototype Driven Network for Radiology Report Generation](https://arxiv.org/abs/2207.04818) | [code](https://github.com/markin-wang/xpronet?tab=readme-ov-file) | 0.344 | 0.215 | 0.146 | 0.105 | 0.279 | 0.238  |       |                    | Very high IU-xray score, prototype      |
| 2022 |                        CAMANet                        | [CAMANet: Class Activation Map Guided Attention Network for Radiology Report Generation](https://arxiv.org/pdf/2211.01412.pdf) |        [code](https://github.com/Markin-Wang/CAMANet)        | 0.374 | 0.23  | 0.155 | 0.112 | 0.279 | 0.145  | 0.161 |                    | Very high IU-xray score                 |
| 2022 |                 Purely on Transformer                 | [Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach](https://ieeexplore.ieee.org/document/9768661?denied=) |                                                              | 0.351 | 0.223 | 0.157 | 0.118 | 0.287 |        | 0.281 |                    |                                         |
| 2022 |           Reinforced Cross-modal Alignment            | [Reinforced Cross-modal Alignment for Radiology Report Generation](https://aclanthology.org/2022.findings-acl.38.pdf) |                                                              | 0.381 | 0.232 | 0.155 | 0.109 | 0.287 | 0.151  |       |                    |                                         |
| 2022 |                         M2KT                          | [Radiology Report Generation with a Learned Knowledge Base and Multi-modal Alignment](https://arxiv.org/abs/2112.15011) |         [code](https://github.com/LX-doctorAI1/M2KT)         | 0.386 | 0.237 | 0.157 | 0.111 | 0.274 |        | 0.111 |                    |                                         |
| 2022 |                        TranSQ                         | [TranSQ: Transformer-Based Semantic Query for Medical Report Generation](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58) |        [code](https://github.com/zjukongming/TranSQ)         | 0.423 | 0.261 | 0.171 | 0.116 | 0.286 | 0.168  |       |                    | image size 384                          |
| 2022 |                      self-guided                      | [A Self-guided Framework for Radiology Report Generation](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56) | [code](https://github.com/LijunRio/A-Self-Guided-Framework)  | \-    |       |       |       |       |        |       |                    | just iu xray                            |
| 2022 |                        RepsNet                        | [RepsNet: Combining Vision with Language for Automated Medical Reports](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68) |                                                              | \-    |       |       |       |       |        |       |                    | with vqa and just iu xray               |
| 2022 |                           -                           | [Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards](https://aclanthology.org/2022.findings-emnlp.319.pdf) | [code](https://github.com/jbdel/vilmedic?tab=readme-ov-file) | \-    |       |       | 0.116 | 0.259 |        |       |                    | RadGraph reward                         |
| 2022 |            Factual Accuracy is not Enough             | [Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation](https://aclanthology.org/2022.emnlp-main.480.pdf) |                                                              | \-    |       |       | 0.168 | 0.122 |        |       |                    | one different dataset                   |
| 2022 |                           -                           | [Cross-Modal Causal Intervention for Medical Report Generation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9879084) |                                                              | \-    |       |       |       |       |        |       |                    | eye dataset                             |
| 2022 |                        HReMRG                         | [Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty](https://arxiv.org/pdf/2210.13729.pdf) |                                                              | 0.481 | 0.343 | 0.256 | 0.192 | 0.38  | 0.207  | 0.372 |                    |                                         |
| 2022 |                           -                           | [Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations](https://aclanthology.org/2022.aacl-main.47.pdf) |                                                              | 0.363 | 0.245 | 0.178 | 0.136 | 0.313 | 0.161  |       |                    |                                         |
| 2023 |                           -                           | [A Systematic Review of Deep Learning-based Research on Radiology Report Generation](https://arxiv.org/pdf/2311.14199.pdf) |                                                              | \-    |       |       |       |       |        |       |                    | Survey                                  |
| 2023 |                         ORGAN                         | [ORGAN: Observation-Guided Radiology Report Generation via Tree Reasoning](https://arxiv.org/abs/2306.06466) |            [code](https://github.com/wjhou/ORGan)            | 0.407 | 0.256 | 0.172 | 0.123 | 0.293 | 0.162  |       |                    |                                         |
| 2023 |                     METransformer                     | [METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens](https://arxiv.org/abs/2304.02211) |                                                              | 0.386 | 0.25  | 0.169 | 0.124 | 0.291 | 0.152  | 0.362 |                    |                                         |
| 2023 |                         KiUT                          | [KiUT: Knowledge-injected U-Transformer for Radiology Report Generation](https://arxiv.org/abs/2306.11345) |                                                              | 0.393 | 0.243 | 0.159 | 0.113 | 0.285 | 0.152  |       |                    |                                         |
| 2023 |                       R2GenGPT                        | [R2GenGPT: Radiology Report Generation with Frozen LLMs](https://arxiv.org/abs/2309.09812) |       [code](https://github.com/wang-zhanyu/R2GenGPT)        | 0.411 | 0.267 | 0.186 | 0.134 | 0.297 | 0.16   | 0.269 | :heavy_check_mark: |                                         |
| 2023 |                         RECAP                         | [RECAP: Towards Precise Radiology Report Generation via Dynamic Disease Progression Reasoning](https://arxiv.org/abs/2310.13864) |            [code](https://github.com/wjhou/Recap)            | 0.429 | 0.267 | 0.177 | 0.125 | 0.288 | 0.168  |       |                    |                                         |
| 2023 |                          DCL                          | [Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation](https://arxiv.org/pdf/2303.10323.pdf) |           [code](https://github.com/mlii0117/DCL)            | \-    |       |       | 0.109 | 0.284 | 0.15   | 0.281 |                    |                                         |
| 2023 |                     PhenotypeCLIP                     | [PhenotypeCLIP: Phenotype-based Contrastive Learning for Medical Imaging Report Generation](https://aclanthology.org/2023.emnlp-main.989.pdf) |                                                              | \-    |       |       | 0.119 | 0.286 | 0.158  | 0.259 |                    |                                         |
| 2023 |                        LLM-CXR                        | [LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation](https://arxiv.org/abs/2305.11490) |          [code](https://github.com/hyn2028/llm-cxr)          | \-    |       |       |       |       |        |       | :heavy_check_mark: |                                         |
| 2023 |                        MAIRA-1                        | [MAIRA-1: A specialised large multimodal model for radiology report generation](https://arxiv.org/abs/2311.13668) |                                                              |       |       |       |       |       |        |       | :heavy_check_mark: |                                         |
| 2023 |                       MedXChat                        | [MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model](https://arxiv.org/abs/2312.02233) |                                                              |       |       |       |       |       |        |       |                    |                                         |
| 2023 |         Pragmatic Radiology Report Generation         | [Pragmatic Radiology Report Generation](https://arxiv.org/pdf/2311.17154.pdf) |                                                              | \-    |       |       |       |       |        |       | :heavy_check_mark: | Differnet eval way                      |
| 2023 |                        RadLLM                         | [RadLLM: A Comprehensive Healthcare Benchmark of Large Language Models for Radiology](https://arxiv.org/pdf/2307.13693.pdf) |                                                              | \-    |       |       |       |       |        |       | :heavy_check_mark: | A new benchmark                         |
| 2023 |                       RaDialog                        | [RaDialog: A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance](https://arxiv.org/pdf/2311.18681.pdf) |        [code](https://github.com/ChantalMP/RaDialog)         | 0.346 |       |       | 0.095 | 0.271 | 0.14   |       | :heavy_check_mark: | With chat                               |
| 2023 |           Towards Generalist Biomedical AI            | [Towards Generalist Biomedical AI](https://arxiv.org/pdf/2307.14334.pdf) |         [code](https://github.com/kyegomez/Med-PaLM)         | 0.323 |       |       | 0.115 | 0.275 |        | 0.262 | :heavy_check_mark: |                                         |
| 2023 |                         RadFM                         | [Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data](https://arxiv.org/pdf/2308.02463.pdf) | [code](https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file) | \-    |       |       |       |       |        |       | :heavy_check_mark: |                                         |
| 2023 |                         VLCI                          | [Cross-Modal Causal Intervention for Medical Report Generation](https://arxiv.org/pdf/2303.09117.pdf) |         [code](https://github.com/WissingChen/VLCI)          | 0.4   | 0.245 | 0.165 | 0.119 | 0.28  | 0.15   | 0.19  |                    |                                         |
| 2023 |                           -                           | [Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning](https://arxiv.org/pdf/2312.15869.pdf) |                                                              |       |       |       |       |       |        |       |                    | Segment-enhanced                        |
| 2023 |                           -                           | [Radiology Report Generation Using Transformers Conditioned with Non-imaging Data](https://arxiv.org/pdf/2311.11097.pdf) |                                                              | 0.333 | 0.21  | 0.142 | 0.088 |       |        |       |                    | Non-imaging data                        |
| 2023 |                  Replace and Report                   | [Replace and Report: NLP Assisted Radiology Report Generation](https://aclanthology.org/2023.findings-acl.683.pdf) |                                                              | 0.833 | 0.807 | 0.794 | 0.785 | 0.833 | 0.861  | 0.861 |                    | Structured report                       |
| 2023 |                    CvT2DistilGPT2                     | [Improving Chest X-Ray Report Generation by Leveraging Warm Starting](https://arxiv.org/pdf/2201.09405.pdf) |       [code](https://github.com/aehrc/cvt2distilgpt2)        | 0.393 | 0.248 | 0.171 | 0.127 | 0.286 | 0.155  | 0.389 |                    | different image size                    |
| 2023 |                         RGRG                          | [Interactive and Explainable Region-guided Radiology Report Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf) |           [code](https://github.com/ttanida/rgrg)            | 0.373 | 0.249 | 0.175 | 0.126 | 0.264 | 0.168  | 0.495 |                    | w/ object detection and image size: 512 |
| 2023 |                       KGVL-BART                       | [KGVL-BART: Knowledge Graph Augmented Visual Language BART for Radiology Report Generation](https://aclanthology.org/2023.eacl-main.246.pdf) |         [code](https://github.com/yeliu918/KG-BART)          | \-    |       |       |       |       |        |       |                    | different dataset, w/ KG                |
| 2023 |                      Style-Aware                      | [Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting](https://arxiv.org/pdf/2310.17811v2.pdf) |                                                              | \-    |       |       |       |       |        |       | :heavy_check_mark: |                                         |
| 2023 |                       MVCO-DOT                        | [MVCO-DOT: MULTI-VIEW CONTRASTIVE DOMAIN TRANSFER NETWORK FOR MEDICAL REPORT GENERATION](https://arxiv.org/pdf/2304.07465.pdf) |                                                              | \-    |       |       |       |       |        |       |                    | Multi view                              |
| 2023 |                Unify, Align and Refine                | [Unify, Align and Refine: Multi-Level Semantic Alignment for Radiology Report Generation](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unify_Align_and_Refine_Multi-Level_Semantic_Alignment_for_Radiology_Report_ICCV_2023_paper.pdf) |                                                              | 0.363 | 0.229 | 0.158 | 0.107 | 0.289 | 0.157  | 0.246 |                    | image size: 128                         |
| 2023 |                           -                           | [Self Adaptive Global-Local Feature Enhancement for Radiology Report Generation](https://arxiv.org/pdf/2211.11380.pdf) |                                                              | 0.363 | 0.235 | 0.164 | 0.118 | 0.301 | 0.136  |       |                    |                                         |
| 2023 |                           -                           | [Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation](https://ieeexplore.ieee.org/document/10045710) |                                                              | \-    |       |       |       |       |        |       |                    |                                         |
| 2023 |                         SGT++                         | [SGT++: Improved Scene Graph-guided Transformer for Surgical Report Generation](https://ieeexplore.ieee.org/document/10330637) |                                                              | \-    |       |       |       |       |        |       |                    | different dataset                       |
| 2023 |              From Observation to Concept              | [From Observation to Concept: A Flexible Multi-view Paradigm for Medical Report Generation](https://ieeexplore.ieee.org/document/10356722) |                                                              | 0.391 | 0.249 | 0.172 | 0.125 | 0.304 | 0.16   |       |                    |                                         |
| 2023 |                           -                           | [Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9606584) |                                                              | 0.362 | 0.251 | 0.188 | 0.143 | 0.326 |        | 0.273 |                    |                                         |
| 2023 |                           -                           | [Semi-Supervised Medical Report Generation via Graph-Guided Hybrid Feature Consistency](https://ieeexplore.ieee.org/document/10119200) |                                                              | 0.362 | 0.229 | 0.157 | 0.113 | 0.284 | 0.153  |       |                    | semi-supervised                         |
| 2024 | Complex Organ Mask Guided Radiology Report Generation | [Complex Organ Mask Guided Radiology Report Generation](https://arxiv.org/pdf/2311.02329.pdf) |        [code](https://github.com/GaryGuTC/COMG_model)        | 0.346 | 0.216 | 0.145 | 0.104 | 0.279 | 0.137  |       |                    |                                         |
| 2024 |                         ICON                          | [ICON: Improving Inter-Report Consistency of Radiology Report Generation via Lesion-aware Mix-up Augmentation](https://arxiv.org/pdf/2402.12844.pdf) |            [code](https://github.com/wjhou/ICon)             | 0.429 | 0.266 | 0.178 | 0.126 | 0.287 | 0.17   |       |                    |                                         |