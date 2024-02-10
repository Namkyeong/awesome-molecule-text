# Awesome-molecule-text
This repository is the collection of papers about **Molecular Machine Learning (MoML) with its textual description**,
aiming to harness the capabilities of language models for learning the accumulated human knowledge in molecular science.
The papers are organized in the order of their publication dates.

We will try to make this list updated. If you find any error or any missed paper, please feel free to open issues or pull requests.


## Various Molecule-Text Tasks

We categorize various downstream tasks for molecule-text models and provide examples of notable works in each category.

|                | Text &rarr; Mol | Mol &rarr; Text | Mol + Text |
|----------------|---------------------|---------------------|--------------------| 
| Discriminative | Molecule Retrieval [1] <br/> Molecule Property Prediction [4] | Text Retrieval [4] | Zero-Shot Learning [7, 9] | 
| Generative     | Molecule Generation [2, 6] <br/> Molecule Editing [4] | Molecule Captioning [2, 6] <br/> Molecular Question-Answering [25] | 

## :rotating_light: Workshop Alert
[Language + Molecules workshop](https://language-plus-molecules.github.io/), which aims to synthsize language and molecules for scientific insight and discovery, will be held at [ACL 2024](https://2024.aclweb.org/)!

## Papers
1. [2021 EMNLP] Text2Mol: Cross-Modal Molecule Retrieval with Natural Language Queries [[Paper]](https://aclanthology.org/2021.emnlp-main.47/) [[Code]](https://github.com/cnedwards/text2mol)
2. [2022 EMNLP] Translation between Molecules and Natural Language (MolT5) [[Paper]](https://aclanthology.org/2022.emnlp-main.26/) [[Code]](https://github.com/blender-nlp/MolT5)
3. [2022 Nature Communications] A deep-learning system bridging molecule structure and biomedical text with comprehension comparable to human professionals [[Paper]](https://www.nature.com/articles/s41467-022-28494-3) [[Code]](https://github.com/thunlp/KV-PLM)
4. [2022 Nature Machine Intelligence] MoleculeSTM: Multi-modal Molecule Structure-text Model for Text-based Retrieval and Editing [[Paper]](https://arxiv.org/abs/2212.10789) [[Code]](https://github.com/chao1224/MoleculeSTM)
5. [2022 arXiv] A Molecular Multimodal Foundation Model Associating Molecule Graphs with Natural Language [[Paper]](https://arxiv.org/abs/2209.05481) [[Code]](https://github.com/BingSu12/MoMu)
6. [2023 ICML] Unifying Molecular and Textual Representations via Multi-task Language Modeling [[Paper]](https://arxiv.org/abs/2301.12586) [[Code]](https://github.com/GT4SD/multitask_text_and_chemistry_t5) 
7. [2023 ICML] Enhancing Activity Prediction Models in Drug Discovery with the Ability to Understand Human Language [[Paper]](https://proceedings.mlr.press/v202/seidl23a/seidl23a.pdf) [[Code]](https://github.com/ml-jku/clamp)
8. [2023 WCB @ ICML] Extracting Molecular Properties from Natural Language with Multimodal Contrastive Learning [[Paper]](https://arxiv.org/abs/2307.12996)
9. [2023 NeurIPS] GIMLET: A Unified Graph-Text Model for Instruction-Based Molecule Zero-Shot Learning [[Paper]](https://arxiv.org/abs/2306.13089) [[Code]](https://github.com/zhao-ht/GIMLET)
10. [2023 NeurIPS Benchmark & Dataset] What can Large Language Models do in chemistry? A comprehensive benchmark on eight tasks [[Paper]](https://arxiv.org/abs/2305.18365) [[Code]](https://github.com/ChemFoundationModels/ChemLLMBench)
11. [2023 ACL Short] MolXPT: Wrapping Molecules with Text for Generative Pre-training [[Paper]](https://aclanthology.org/2023.acl-short.138/)
12. [2023 EMNLP] MolCA: Molecular Graph-Language Modeling with Cross-Modal Projector and Uni-Modal Adapter [[Paper]](https://arxiv.org/abs/2310.12798) [[Code]](https://github.com/acharkq/MolCA)
13. [2023 EMNLP] BioT5: Enriching Cross-modal Integration in Biology with Chemical Knowledge and Natural Language Associations [[Paper]](https://arxiv.org/abs/2310.07276) [[Code]](https://github.com/QizhiPei/BioT5)
14. [2023 EMNLP] ReLM: Leveraging Language Models for Enhanced Chemical Reaction Prediction [[Paper]](https://arxiv.org/pdf/2310.13590.pdf) [[Code]](https://github.com/syr-cn/relm)
15. [2023 EMNLP] Predictive Chemistry Augmented with Text Retrieval [[Paper]](https://arxiv.org/abs/2312.04881) [[Code]](https://github.com/thomas0809/textreact)
16. [2023 arXiv] MolFM: A Multimodal Molecular Foundation Model [[Paper]](https://arxiv.org/abs/2307.09484) [[Code]](https://github.com/PharMolix/OpenBioMed)
17. [2023 arXiv] Can Large Language Models Empower Molecular Property Prediction? [[Paper]](https://arxiv.org/abs/2307.07443) [[Code]](https://github.com/chnq/llm4mol)
18. [2023 arXiv] Interactive Molecular Discovery with Natural Language [[Paper]](https://arxiv.org/abs/2306.11976) [[Code]](https://github.com/Ellenzzn/ChatMol/tree/main)
19. [2023 arXiv] Empowering Molecule Discovery for Molecule-Caption Translation with Large Language Models: A ChatGPT Perspective [[Paper]](https://arxiv.org/abs/2306.06615) [[Code]](https://github.com/phenixace/MolReGPT)
20. [2023 arXiv] From Artificially Real to Real: Leveraging Pseudo Data from Large Language Models for Low-Resource Molecule Discovery [[Paper]](https://arxiv.org/abs/2309.05203)
20. [2023 arXiv] GIT-Mol: A Multi-modal Large Language Model for Molecular Science with Graph, Image, and Text [[Paper]](https://arxiv.org/abs/2308.06911)
21. [2023 arXiv] Mol-Instructions: A Large-Scale Biomolecular Instruction Dataset for Large Language Models [[Paper]](https://arxiv.org/abs/2306.08018) [[Code]](https://github.com/zjunlp/Mol-Instructions)
22. [2023 arXiv] Catalyst Property Prediction with CatBERTa: Unveiling Feature Exploration Strategies through Large Language Models [[Paper]](https://arxiv.org/abs/2309.00563) [[Code]](https://github.com/hoon-ock/CatBERTa)
23. [2023 arXiv] GPT-MolBERTa: GPT Molecular Features Language Model for molecular property prediction [[Paper]](https://arxiv.org/abs/2310.03030) [[Code]](https://github.com/Suryanarayanan-Balaji/GPT-MolBERTa)
24. [2024 ICLR] Towards 3D Molecule-Text Interpretation in Language Models [[Paper]](https://openreview.net/forum?id=xI4yNlkaqh)
25. [2024 ICLR rejected] Text2Data: Low-Resource Data Generation with Textual Control [[Paper]](https://openreview.net/forum?id=Y2Txh5uGRe)
26. [2024 ICLR rejected] Text-guided Diffusion Model for 3D Molecule Generation [[Paper]](https://openreview.net/forum?id=FdUloEgBSE)
27. [2024 ICLR rejected] Form follows Function: Text-to-Text Conditional Graph Generation based on Functional Requirements [[Paper]](https://openreview.net/forum?id=Pu3qMB9aKD)
28. [2024 ICLR rejected] Data-Efficient Molecular Generation with Hierarchical Textual Inversion [[Paper]](https://openreview.net/forum?id=wwotGBxtC3)
29. [2024 arXiv] MolTC: Towards Molecular Relational Modeling In Language Models [[Paper]](https://arxiv.org/abs/2402.03781) [[Code]](https://github.com/MangoKiller/MolTC)



## Survey on Molecules and Language Models
1. [2023 arXiv] Transformers and Large Language Models for Chemistry and Drug Discovery [[Paper]](https://arxiv.org/abs/2310.06083)
2. [2023 arXiv] Language models in molecular discovery [[Paper]](https://arxiv.org/abs/2309.16235)
3. [2024 arXiv] Scientific Language Modeling: A Quantitative Review of Large Language Models in Molecular Science [[Paper]](https://arxiv.org/abs/2402.04119)


## Acknowledgements
This repository is contributed and maintained by [Namkyeong Lee](https://namkyeong.github.io/), [Tianfan Fu](https://futianfan.github.io/), and [Siddhartha Laghuvarapu](https://siddharthal.github.io/).



