<div align="center">

# CVA: Context-aware Video-text Alignment for Video Temporal Grounding (CVPR 2026)

[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://byeol3325.github.io/projects/CVA/)
[![Paper](https://img.shields.io/badge/Paper-PDF-red.svg)](https://byeol3325.github.io/projects/CVA/CVA_for_arxiv.pdf)

</div>

## 📌 Notice
**The source code is currently being organized and will be released soon.** 

Due to ongoing projects and research commitments, the code cleaning process is taking some time. We are working hard to prepare a clean, reproducible, and easy-to-use codebase for the community.

If you have any urgent questions about the implementation details, methodology, or experimental results, please feel free to reach out directly. I am always happy to discuss our work!

📧 **Contact**: [byul3325@gmail.com](mailto:byul3325@gmail.com)

---

## 📖 Abstract

We propose **Context-aware Video-text Alignment (CVA)**, a novel framework to address a significant challenge in video temporal grounding: achieving temporally sensitive video-text alignment that remains robust to irrelevant background context.

Our framework is built on three key components:
1. **Query-aware Context Diversification (QCD)**: A novel data augmentation strategy that ensures only semantically unrelated content is mixed in, preventing false negatives.
2. **Context-invariant Boundary Discrimination (CBD) loss**: A contrastive loss that enforces semantic consistency at challenging temporal boundaries.
3. **Context-enhanced Transformer Encoder (CTE)**: A hierarchical architecture combining windowed self-attention and bidirectional cross-attention with learnable queries to capture multi-scale temporal context.

Through the synergy of these enhancements, CVA achieves state-of-the-art performance on major VTG benchmarks, including QVHighlights, Charades-STA, and TACoS.

## 🚀 Environment Setup & Usage
*(Instructions and scripts will be updated upon code release)*

## 📚 Citation
If you find our work useful in your research, please consider citing our paper:
```bibtex
@inproceedings{moon2026cva,
  title={CVA: Context-aware Video-text Alignment for Video Temporal Grounding},
  author={Moon, Sungho and Lee, Seunghun and Seo, Jiwan and Im, Sunghoon},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```
