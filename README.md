# ATRNet-LUDO
### A Large-Scale Real-World Dataset and Benchmark for UAV Ground Active Object Detection

[![arXiv](https://img.shields.io/badge/arXiv-xxxx.xxxxx-b31b1b?style=flat-square)](https://arxiv.org/abs/xxxx.xxxxx)
[![DOI](https://img.shields.io/badge/Dataset-DOI-007ec6?style=flat-square)](https://zenodo.org/doi/xxxx)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey?style=flat-square)]()
[![Python](https://img.shields.io/badge/Code-Python%203.8+-3776ab?style=flat-square)]()

<img src="./assets/teaser.jpg" width="800px">

</div>

---

## ✨ Highlights
- **First large-scale real-world UGAOD dataset**: 121,000 multi-view panoramic aerial images + 1.21 million single-target patches, covering 10 vehicle categories across 40 real scenarios.
- **Multi-task support**: Enables 5 representative perception tasks: single/multi-target AOD, occluded target detection, and UAV visual localization.
- **Standardized benchmark**: Formal evaluation protocol and metrics for UAV-ground single-target active object detection, enabling fair comparison of policy learning methods.
- **Strong baseline**: A novel World Model-driven Policy Learning (WMPL) framework built on AOD-JEPA, significantly boosting cross-scenario policy generalization.

---

## 📊 Dataset Overview

| Item | Details |
|------|---------|
| Total panoramic images | 121,000 |
| Single-target image patches | 1.21 million |
| Object categories | 10 vehicle types |
| Scenarios | 40 real-world scenes |
| Viewpoints | Multi-view aerial perspectives |
| Supported tasks | Single-target AOD, Multi-target AOD, Occluded target detection, Target recognition, Visual localization |
| Annotation format | COCO-compatible JSON |

---

## 🖼️ Visualization Examples

<div align="center">
<img src="./assets/sample1.jpg" width="32%"> <img src="./assets/sample2.jpg" width="32%"> <img src="./assets/sample3.jpg" width="32%">
<p>Multi-view panoramic samples, occluded target cases, and local patch examples</p>
</div>

---

## 📥 Download & Data Structure

### Download Links
| Data Split | Size | Link |
|------------|------|------|
| Full dataset (all panoramas + patches) | ~XX GB | [Zenodo](https://zenodo.org/doi/xxxx) |
| Mini subset (for quick validation) | ~XX GB | [Google Drive / OneDrive]() |
| Evaluation code & benchmark toolkit | - | [GitHub](./code) |

### File Structure
