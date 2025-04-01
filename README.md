# Audio Description Generation in the Era of LLMs and VLMs: A Review of Transferable Generative AI Technologies  
NAACL 2025 Findings Paper | [📄 PDF](link-to-paper)  

Authors: Yingqiang Gao, Lukas Fischer, Alexa Lintner, Sarah Ebling  
Contact: yingqiang.gao@cl.uzh.ch  
GitHub: https://github.com/CharizardAcademy/NAACL-25-AD-Survey  

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
| Paper | Venue | Model Highlights |
|-------|-------|------------------|
| Yun and Ro (2024) | CVPR’24 | Vanilla ViT |
| Hassani et al. (2023) | CVPR’23 | Swin Transformer |
| Chen et al. (2023) | ICCV’23 | EfficientViT |
| Liu et al. (2023) | CVPR’23 | EfficientViT |
| Korbar and Zisserman (2022) | BMVC’22 | CLIP-ViT-B/32 |
| Wu et al. (2022b) | AAAI’22 | Pale Transformer |
| Rao et al. (2021) | NeurIPS’21 | DynamicViT |
| …and more |

### ✏️ Dense Caption Generation (DCG)
| Paper | Venue | Model Highlights |
|-------|-------|------------------|
| Lin et al. (2024) | ECCV’24 | CLIP-ViT-B/16 + LLaMA-2 |
| Chu et al. (2024) | arXiv’24 | GPT-4V + GPT-4 |
| He et al. (2024) | CVPR’24 | CLIP-ViT-G/14 + Vicuna |
| Luo et al. (2024) | arXiv’24 | TinyLlaVA |
| Han et al. (2023c) | CVPR’23 | AutoAD |
| Han et al. (2023b) | ICCV’23 | AutoAD-II |
| Han et al. (2024) | CVPR’24 | AutoAD-III |
| Xie et al. (2024) | arXiv’24 | AutoAD-Zero |
| …and more |

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
