Authors: Yingqiang Gao, Lukas Fischer, Alexa Lintner, Sarah Ebling 
Affiliation: University of Zurich, Zurich University of Applied Sciences
Contact: yingqiang.gao@cl.uzh.ch  
GitHub: https://github.com/CharizardAcademy/NAACL-25-AD-Survey

Please submit an Issue or drop Yingqiang an email if you would like your work to be listed here.  

---

## 🧠 Overview
This repository provides a categorized collection of papers reviewed in our NAACL 2025 survey on automatic audio description (AD) generation using LLMs and VLMs. The reviewed works are grouped into the following key components of AD generation:

- 🎬 Dense Video Captioning (DVC)
- ✍️ AD Post-editing (APE)
- 🧪 AD Evaluation (ADE)

---

## 🎬 Dense Video Captioning (DVC)

These works tackle the challenge of generating rich, coherent captions from video content. We divide them into:

### 🔍 Visual Feature Extraction (VFE)
| Paper | Venue | Method \| Dataset |
|-------|-------|------------------|
| [Yun and Ro (2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Yun_SHViT_Single-Head_Vision_Transformer_with_Memory_Efficient_Macro_Design_CVPR_2024_paper.pdf) | CVPR’24 | <span style="color:rgb(19%, 55%, 91%)">SHViT</span>
| [Hassani et al. (2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Hassani_Neighborhood_Attention_Transformer_CVPR_2023_paper.pdf) | CVPR’23 | <span style="color:rgb(19%, 55%, 91%)">NAT</span> |
| [Chen et al. (2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Efficient_Video_Action_Detection_with_Token_Dropout_and_Context_Refinement_ICCV_2023_paper.pdf) | ICCV’23 | <span style="color:rgb(19%, 55%, 91%)">EVAD</span> |
| [Liu et al. (2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_EfficientViT_Memory_Efficient_Vision_Transformer_With_Cascaded_Group_Attention_CVPR_2023_paper.pdf) | CVPR’23 |  <span style="color:rgb(19%, 55%, 91%)">EfficientViT</span> |
|[Zhao et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_TubeR_Tubelet_Transformer_for_Video_Action_Detection_CVPR_2022_paper.pdf) | CVPR'22 |  <span style="color:rgb(19%, 55%, 91%)">TubeR</span> |
| [Liu et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Video_Swin_Transformer_CVPR_2022_paper.pdf) | CVPR'22 | <span style="color:rgb(19%, 55%, 91%)">Video Swin Transformer</span> |
| [Yang et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Lite_Vision_Transformer_With_Enhanced_Self-Attention_CVPR_2022_paper.pdf) | CVPR'22 |  <span style="color:rgb(19%, 55%, 91%)">Lite Vision Transformer</span> | 
| [Wu et al. (2022)](https://cdn.aaai.org/ojs/20176/20176-13-24189-1-2-20220628.pdf) | AAAI’22 | <span style="color:rgb(19%, 55%, 91%)">Pale Transformer</span> | 
| [Korbar and Zisserman (2022)](https://bmvc2022.mpi-inf.mpg.de/0639.pdf) | BMVC’22 | <span style="color:rgb(0%, 65%, 31%)">CLIP-ViT-B/32</span> |
| [Yin et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Yin_A-ViT_Adaptive_Tokens_for_Efficient_Vision_Transformer_CVPR_2022_paper.pdf) | CVPR'22 | <span style="color:rgb(19%, 55%, 91%)">A-ViT</span> |
| [Wu et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_MeMViT_Memory-Augmented_Multiscale_Vision_Transformer_for_Efficient_Long-Term_Video_Recognition_CVPR_2022_paper.pdf)| CVPR'22 | <span style="color:rgb(19%, 55%, 91%)">MemViT</span>|
| [Brown et al. (2021)](https://openaccess.thecvf.com/content/ICCV2021W/CVEU/papers/Brown_Face_Body_Voice_Video_Person-Clustering_With_Multiple_Modalities_ICCVW_2021_paper.pdf) | ICCV'21 | <span style="color:rgb(0%, 65%, 31%)">MuHPC \| VPCD</span> |
| [Huang et al. (2021)](https://arxiv.org/pdf/2106.03650) | arXiv'21 | <span style="color:rgb(19%, 55%, 91%)">Shuffle Transformer</span> |
| [Liu et al. (2021)](https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.pdf) | ICCV'21 | <span style="color:rgb(19%, 55%, 91%)">Swin Transformer</span> |
| [Rao et al. (2021)](https://papers.neurips.cc/paper_files/paper/2021/file/747d3443e319a22747fbb873e8b2f9f2-Paper.pdf) | NeurIPS’21 | <span style="color:rgb(19%, 55%, 91%)">DynamicViT</span> |
| [Wu et al. (2020)](https://link.springer.com/chapter/10.1007/978-3-030-58595-2_27) | ECCV'20 | <span style="color:rgb(19%, 55%, 91%)">Context-Aware RCNN</span> |
| [Huang et al. (2020)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490681.pdf) | ECCV'20 | <span style="color:rgb(99%, 76%, 0%)">MovieNet</span> |
| [Kukleva et al. (2020)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kukleva_Learning_Interactions_and_Relationships_Between_Movie_Characters_CVPR_2020_paper.pdf) | CVPR'20 | <span style="color:rgb(19%, 55%, 91%)">LIReC</span> |

### ✏️ Dense Caption Generation (DCG)
| Paper | Venue | Model Highlights |
|-------|-------|------------------|
| [Han et al. (2025)](https://arxiv.org/pdf/2312.10300) | ICLR'25 |  <span style="color:rgb(99%, 76%, 0%)">Shot2Story20K</span> |
| [Lin et al. (2024)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06601.pdf) | ECCV’24 | <span style="color:rgb(19%, 55%, 91%)">MovieSeq</span> |
| [Chu et al. (2024)](https://openreview.net/pdf?id=U42TkrEDzb) | ICLR'25 | <span style="color:rgb(19%, 55%, 91%)">LLM-AD</span> |
| [He et al. (2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/He_MA-LMM_Memory-Augmented_Large_Multimodal_Model_for_Long-Term_Video_Understanding_CVPR_2024_paper.pdf) | CVPR’24 | <span style="color:rgb(19%, 55%, 91%)">MA-LLM</span> |
| [Luo et al. (2024)](https://dl.acm.org/doi/pdf/10.1145/3689091.3690086) | MMGR'24 | <span style="color:rgb(19%, 55%, 91%)">Shotluck Holmes</span> |
| [Maaz et al. (2024)](https://arxiv.org/abs/2406.09418) | arXiv'24 | <span style="color:rgb(0%, 65%, 31%)">VideoGPT+ \| VCGBench-Diverse</span> |
| [Ye et al. (2024)](https://aclanthology.org/2024.lrec-main.998.pdf) | COLING'24 | <span style="color:rgb(19%, 55%, 91%)">MMAD</span> |
| [Yue et al. (2024)](https://arxiv.org/pdf/2404.13370) | arXiv'24 | <span style="color:rgb(99%, 76%, 0%)">Movie101-v2(zh/en)</span> | 
| [Zhou et al. (2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhou_Streaming_Dense_Video_Captioning_CVPR_2024_paper.pdf) | CVPR'24 | <span style="color:rgb(19%, 55%, 91%)">Streaming DVC</span> |
| [Blanco-Fernández et al. (2024)](https://arxiv.org/pdf/2406.14206) | arXiv'24 | <span style="color:rgb(19%, 55%, 91%)">LVC</span> |
| [Xie et al. (2024)](https://openaccess.thecvf.com/content/ACCV2024/papers/Xie_AutoAD-Zero_A_Training-Free_Framework_for_Zero-Shot_Audio_Description_ACCV_2024_paper.pdf) | ACCV'24 | AutoAD-Zero \| TV-AD |
| [Han et al. (2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Han_AutoAD_III_The_Prequel_-_Back_to_the_Pixels_CVPR_2024_paper.pdf) | CVPR’24 | AutoAD-III | XXX |
| [Yue et al. (2023)](https://aclanthology.org/2023.acl-long.257.pdf)| ACL'23 | XXX |
| [Jung et al. (2023)](https://aclanthology.org/2023.findings-acl.543.pdf) | ACL'23 | XXX |
| [Han et al. (2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Han_AutoAD_II_The_Sequel_-_Who_When_and_What_in_ICCV_2023_paper.pdf) | ICCV’23 | AutoAD-II |
| [Han et al. (2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Han_AutoAD_Movie_Description_in_Context_CVPR_2023_paper.pdf) | CVPR'23 | XXX |
| [Shen et al. (2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Shen_Accurate_and_Fast_Compressed_Video_Captioning_ICCV_2023_paper.pdf)| ICCV'23 | XXX |
| [Yang et al. (2023)](https://aclanthology.org/2023.acl-long.664.pdf) | ACL'23 | XXX |
| [Lin et al. (2023)](https://arxiv.org/pdf/2310.19773) | arXiv'23 | XXX |
| [Soldan et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Soldan_MAD_A_Scalable_Dataset_for_Language_Grounding_in_Videos_From_CVPR_2022_paper.pdf) | CVPR'22 | XXX |
| [Zhang et al. (2022)](https://aclanthology.org/2022.findings-emnlp.135.pdf) | EMNLP'22 | XXX | 
| [Zhu et al. (2022)](https://aclanthology.org/2022.coling-1.498.pdf) | COLING'22 | XXX |  
| [Deng et al. (2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_Sketch_Ground_and_Refine_Top-Down_Dense_Video_Captioning_CVPR_2021_paper.pdf) | CVPR'21 | XXX |
| [Wang et al. (2021)](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_End-to-End_Dense_Video_Captioning_With_Parallel_Decoding_ICCV_2021_paper.pdf) | ICCV'21 | XXX |
| [Liu and Wan (2021)](https://aclanthology.org/2021.acl-short.9.pdf) | ACL'21 | XXX |
| [Zhu and Yang (2020)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_ActBERT_Learning_Global-Local_Video-Text_Representations_CVPR_2020_paper.pdf) | CVPR'20 | XXX |
| [Lei et al. (2020)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660443.pdf) | ECCV'20 | XXX |
| [Fang et al. (2020)](https://aclanthology.org/2020.emnlp-main.61.pdf) | EMNLP'20 | XXX |
| [Gurari et al. (2020)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620409.pdf) | ECCV'20 | XXX |
| [Lin et al. (2020)](https://aclanthology.org/2020.findings-emnlp.98.pdf) | EMNLP'20 | XXX |
| [Shigeto et al. (2020)](https://aclanthology.org/2020.lrec-1.574.pdf) | LREC'20 | XXX |
| [Huang et al. (2020)](https://aclanthology.org/2020.aacl-main.48.pdf) | AACL'20 | XXX |
---

## ✍️ AD Post-editing (APE)

These works focus on improving raw machine-generated ADs using editing tools or models:

| Paper / Tool | Description |
|--------------|-------------|
| Minutella (2022) | Overview of professional AD editing tools |
| Pavel et al. (2020) – *Rescribe* | Tool for correcting and aligning AD scripts |
| Faltings et al. (2021) | Text editing by command |
| Raheja et al. (2023, 2024) | Instruction tuning for editing models |
| Shu et al. (2024) | Revision-based simplification |
| Kim et al. (2022) | Multi-task learning for text refinement |
| Mallinson et al. (2022) | Semi-autoregressive editing |
| Agrawal & Carpuat (2022) | Non-autoregressive AD editing |

---

## 🧪 AD Evaluation (ADE)

### 🧮 Automatic Evaluation Metrics
| Metric | Type | Paper |
|--------|------|-------|
| BLEU, ROUGE-L, METEOR | N-gram overlap | Papineni et al. (2002), Lin (2004), Banerjee and Lavie (2005) |
| BERTScore, CLIPScore | Embedding-based | Zhang et al. (2020), Hessel et al. (2021) |
| CIDEr, SPICE, SPIDEr | Image/video captioning | Vedantam et al. (2015), Anderson et al. (2016) |
| MNScore | Specialized for AD | Yue et al. (2023) |
| CRITIC, LLM-AD-Eval | Character-aware, LLM-based | Han et al. (2024) |

### 👥 Human Evaluation Studies
| Study | Focus Area |
|-------|------------|
| Lopez et al. (2018, 2021) | User preferences, personalization |
| Arias-Badia & Matamala (2023) | Easy-to-understand ADs |
| Reviers (2018), Gallego (2020) | Style differences in ADs |
| Wang et al. (2022) | Emotional response to AD |
| Yang et al. (2023b) | AD reception in China |
| Leong et al. (2023) | 3D virtual environments |

---

## 📌 Citation

If you find this resource useful, please cite our NAACL 2025 paper:

```bibtex
@inproceedings{gao2025adgeneration,
  title = {Audio Description Generation in the Era of LLMs and VLMs: A Review of Transferable Generative AI Technologies},
  author = {Yingqiang Gao and Lukas Fischer and Alexa Lintner and Sarah Ebling},
  booktitle = {Proceedings of the 2025 Conference of the North American Chapter of the Association for Computational Linguistics: Findings},
  year = {2025}
}
