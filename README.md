<div align="center">

# Manas Mehta

Independent Researcher · B.Tech Computer Science & Engineering, GLS University, Ahmedabad

[Email](mailto:manasmehta1110@gmail.com) &nbsp;·&nbsp; [GitHub](https://github.com/ManasMehta1110) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/manas-mehta1110) &nbsp;·&nbsp; [HuggingFace](https://huggingface.co/ManasMehta1110)

</div>

<br>

I work on empirical questions in deep learning where the honest answer might be "no" — designing experiments that could falsify my own hypotheses, not just confirm them, and reporting the result either way.

---

### Research Interests

- Guided and multimodal super-resolution for remote sensing imagery
- Evaluation methodology for empirical deep learning claims — ablation design, paired significance testing, held-out generalization
- Scalable oversight and evaluation of multi-agent LLM systems
- Applied NLP for misinformation and content classification

---

### Working Papers

**Does Optical Guidance Help Thermal Super-Resolution? An Empirical Ablation Study on HLS Satellite Imagery**
M. Mehta. *Manuscript in preparation for IEEE Geoscience and Remote Sensing Letters.*

A dual-stream residual-attention network (DualEDSRPlus) is evaluated against classical interpolation and guided-filter baselines on Landsat-8 TIRS / Sentinel-2 HLS imagery. A 25-run ablation (5 configurations x 5 seeds) isolates the contribution of optical guidance, attention, the SSIM loss term, and the training curriculum, with paired significance testing and a held-out-region generalization check. Every trained configuration exceeds classical baselines by 10-20dB median PSNR — but optical guidance itself, the factor motivating the study, does not survive scrutiny.

[Code & reproducibility manifest →](https://github.com/ManasMehta1110/Guided-Thermal-Super-Resolution)

**Image Captioning with SE-ResNet-50-D and Stabilized Self-Critical Sequence Training**
M. Mehta. *Manuscript under submission.*

An SE-ResNet-50-D encoder paired with an LSTM decoder and soft attention, fine-tuned via stabilized SCST with mixed cross-entropy/reward loss. BLEU-4 0.2301, CIDEr 0.6236 on the MS-COCO Karpathy test split.

[Code →](https://github.com/ManasMehta1110/Image-Captioning-using-Resnet-D-with-SE-blocks)

---

### Research Software

**TheSnitch** — an OpenEnv-based reinforcement learning environment training an LLM overseer to detect misbehavior in multi-agent tool-use traces. Built with a 3-person team for the Meta x PyTorch OpenEnv Hackathon; owned the reward logic, evaluation pipeline, and correctness auditing, including validation on held-out misbehavior variants unseen during training.
[Code →](https://github.com/Mihir1107/snitch-env)

**Fake News Detector** — RoBERTa fine-tuned on the LIAR benchmark for binary misinformation classification (71.4% F1, 78.3% recall on the held-out test split), containerized and deployed on HuggingFace Spaces.
[Code →](https://github.com/ManasMehta1110/BERT-FakeNews-Detector) &nbsp;·&nbsp; [Demo →](https://huggingface.co/spaces/ManasMehta/BERT-FakeNews-Detector)

---

### Recognition

- **National Finalist**, Smart India Hackathon 2025 — Remote Sensing & Geospatial Domain
- **Top-100 Finalist**, Meta x PyTorch OpenEnv Hackathon 2026

---

### Education

**B.Tech in Computer Science & Engineering**, GLS University, Ahmedabad — *expected May 2027*
Coursework: Deep Learning, Computer Vision, Data Structures & Algorithms, Linear Algebra, Database Management

---

<div align="center">

<sub>Python · PyTorch · HuggingFace Transformers · Rasterio · Docker</sub>

</div>
