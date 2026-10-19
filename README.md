<div align="center">

# Manas Mehta

ML research · remote-sensing super-resolution · evaluation of AI oversight
Final-year B.Tech CSE, GLS University, Ahmedabad · open to research internships (Jan – May 2027)

[Email](mailto:manasmehta1110@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/manas-mehta1110) &nbsp;·&nbsp; [X](https://x.com/Manas_Mehta_) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/ManasMehta)

</div>

<br>

I work on empirical questions in deep learning where the honest answer might be "no": I design experiments that could falsify my own hypotheses, and report the result either way.

---

### Research interests

- **Super-resolution for satellite imagery** — physically constrained models, calibrated uncertainty, hallucination control, cross-sensor domain gaps
- **Evaluation of AI oversight** — whether LLM monitors can justify verdicts with evidence, and training them to
- **Evaluation methodology** — ablation design, seed-paired significance testing, held-out generalization

---

### Papers

**Does Optical Guidance Help Thermal Super-Resolution? An Empirical Ablation Study on HLS Satellite Imagery**
M. Mehta. *Under review, IEEE Geoscience and Remote Sensing Letters.*
A dual-stream residual-attention network (DualEDSRPlus) on Landsat-8 TIRS + Sentinel-2 HLS imagery from 9 regions. A 25-run ablation (5 configurations × 5 seeds, seed-paired t-test / Wilcoxon) shows every trained model beats classical baselines by 10–20 dB PSNR — but removing the optical guide, the factor motivating the study, *improves* PSNR by 3.8 dB (p = 0.048). Held-out-region generalization is reported as an open limitation.
[Code & reproducibility manifest →](https://github.com/ManasMehta1110/Guided-Thermal-Super-Resolution)

**GroundingBench: Measuring Evidence-Grounded AI Oversight**
M. Mehta. *Preprint in preparation.*
Seven frontier models from five organizations get the verdict on agent traces right 70–100% of the time, yet only 0.06% of correct misbehavior verdicts cite the step that actually proves it. A Qwen2.5-1.5B overseer trained with GRPO + LoRA under a grounding-bonused reward reaches 74.1% grounded citations on the hardest class.
[Code →](https://github.com/ManasMehta1110/GroundingBench) &nbsp;·&nbsp; [Demo →](https://huggingface.co/spaces/ManasMehta/GroundingBench)

**Stabilized Reinforcement Learning for Image Captioning using SE-ResNet-D**
M. Mehta, V. Sharma, M. Chopade. *2026.*
Controlled encoder comparison (ResNet-50, SE-ResNet-50, ResNet-50-D) for attention-based captioning on MS-COCO, trained on a single 4 GB GPU: ResNet-50-D reaches 31.3 BLEU-4 / 98.2 CIDEr; SE blocks give no measurable gain. Pure SCST reward-hacks — 77.9% of captions end on a dangling function word — and a stabilized mixed objective cuts that to 0% for 1.8 CIDEr.
[Code →](https://github.com/ManasMehta1110/Image-Captioning-using-Resnet-D-with-SE-blocks)

---

### Projects

**Spectra-SR** — Sentinel-2 super-resolution ×4 (10 m → 2.5 m) with a 3.57M-parameter HAT transformer, a physics-based data-consistency projection, and a calibrated per-pixel uncertainty head (2σ coverage 0.946 vs 0.955 nominal). Ranked 1st of 6 on ESA's OpenSR-Test for reflectance, spectral, and hallucination fidelity, with the highest change precision in the table; beats bicubic on 52/62 real scenes. Loses on Indian PlanetScope pairs (−1.31 dB) — shown, not hidden. Tiled GeoTIFF pipeline, 121-test CI.
[Code →](https://github.com/ManasMehta1110/Spectra-SR) &nbsp;·&nbsp; [Demo →](https://spectra-sr.streamlit.app) &nbsp;·&nbsp; [Report →](https://manasmehta1110.github.io/Spectra-SR)

**TheSnitch** — OpenEnv reinforcement-learning environment that trains an LLM overseer to detect misbehavior in multi-agent tool-use traces. Built with a 3-person team for the Meta × PyTorch OpenEnv Hackathon (Top 100); I owned the reward logic, evaluation pipeline, and correctness auditing. The precursor to GroundingBench.
[Code →](https://github.com/Mihir1107/snitch-env)

**Fake News Detector** — RoBERTa fine-tuned on the LIAR benchmark for binary misinformation classification (71.4% F1, 78.3% recall on the held-out test split), containerized and deployed on Hugging Face Spaces.
[Code →](https://github.com/ManasMehta1110/BERT-FakeNews-Detector) &nbsp;·&nbsp; [Demo →](https://huggingface.co/spaces/ManasMehta/BERT-FakeNews-Detector)

---

### Recognition

- **National Finalist**, Smart India Hackathon 2025 — Remote Sensing & Geospatial domain
- **Top 100 Finalist**, Meta × PyTorch OpenEnv Hackathon 2026

---

<div align="center">

<sub>Python · PyTorch · Hugging Face (Transformers, TRL, PEFT) · Rasterio · FastAPI · Docker</sub>

</div>
