# OmniMocap-X

**OmniMoCap-X** is the largest unified multimodal motion capture dataset for whole-body human motion generation, supporting 10 diverse tasks including T2M, M2D, S2G, HOI, HSI, and HHI.

> Companion dataset for the paper: **"OmniMotion-X: Versatile Multimodal Whole-Body Motion Generation"** (arXiv 2025)

<p align="center">
  <a href="https://arxiv.org/abs/2510.19789">📜 Paper</a> |
  <a href="https://github.com/GuoweiXu368/OmniMotion-X">💻 Code</a>
</p>

---

## 📊 Dataset Highlights

- **286.2 hours** of high-quality motion capture data
- **64.3 million frames** across **28 public MoCap datasets**
- Unified in **SMPL-X** format at **30 FPS**
- Supports **10 motion generation tasks**:  
  `T2M`, `M2D`, `S2G`, `HOI`, `HSI`, `HHI`, `Motion Prediction`, `In-betweening`, `Completion`, `Trajectory-guided Synthesis`
- **Hierarchical, structured captions** generated via **GPT-4o** on rendered videos
- **Reference motion** enabled for autoregressive generation

See Table 3 in the [paper](https://arxiv.org/abs/2510.19789) for full dataset composition.

---

## 🚧 Release Plan

We will release the dataset in **two phases** due to licensing constraints:

### ✅ Phase 1 (Coming Soon)
- Processed **SMPL-X motion sequences** from datasets with **permissive licenses**
- **Structured captions** (JSON/Text)
- **Data loading & preprocessing scripts**

### 🔒 Phase 2 (Code Only)
- **Processing pipelines** for datasets that **cannot be redistributed**
- Instructions to **reproduce OmniMoCap-X** from original sources

> ⚠️ By using this dataset, you agree to comply with the original licenses of each constituent dataset.

---

## 🤝 Cite Us

If you use OmniMoCap-X in your research, please cite:

```bibtex
@article{xu2025omnimotion,
  title={OmniMotion-X: Versatile Multimodal Whole-Body Motion Generation},
  author={Xu, Guowei and Bian, Yuxuan and Zeng, Ailing and Shi, Mingyi and Huang, Shaoli and Li, Wen and Duan, Lixin and Xu, Qiang},
  journal={arXiv preprint arXiv:2510.19789},
  year={2025}
}
