<p align="center">
  <img src="https://media1.tenor.com/m/FeIs2cPIbHwAAAAC/oyasumi-punpun-walking.gif" alt="PunPun walking" width="40%"/>
</p>

<h1 align="center">Ahmed Y. Radwan</h1>
<p align="center"><b>Trustworthy &amp; multimodal AI</b> · Applied ML Specialist at the <a href="https://vectorinstitute.ai/">Vector Institute</a>, Toronto</p>

<p align="center">
  <a href="https://ahmedradwan.me/"><img src="https://img.shields.io/badge/Website-ahmedradwan.me-111111?style=flat&logo=googlechrome&logoColor=white" alt="Ahmed Y. Radwan website"/></a>
  <a href="https://www.linkedin.com/in/ahmedyradwan/"><img src="https://img.shields.io/badge/LinkedIn-ahmedyradwan-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="Ahmed Y. Radwan on LinkedIn"/></a>
  <a href="mailto:ahmedyradwan02@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email Ahmed Y. Radwan"/></a>
  <a href="https://drive.google.com/file/d/1GrEMX25tAVBvUGCVh84Js_sGJhEdYQa9/view?usp=sharing"><img src="https://img.shields.io/badge/CV-555555?style=flat&logo=readthedocs&logoColor=white" alt="Ahmed Y. Radwan CV"/></a>
  <img src="https://komarev.com/ghpvc/?username=ahmedradwan02&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

I study whether AI that sees and hears can be trusted. I build benchmarks, detectors and agents for video, audio-visual and vision-language understanding, and I measure where these models break: when they lose track of *when* something happened, when they're fooled by generated video, and when they judge people from how they look.

### The questions behind my work

**Do multimodal models understand *when* things happen?**<br>
[SONIC-O1](https://arxiv.org/abs/2601.21666) *(EMNLP 2026)* is a human-verified benchmark of 60 hours of real-world conversational video across 13 domains. The best closed model beats the best open one by 22.6 points on temporal localization, and accuracy shifts by up to 21.4 points across demographic groups. [SONIC-O1-Agent](https://vectorinstitute.github.io/sonic-o1-agent/) answers with timestamped evidence and checks its own reasoning before it commits.

**Is this video real, and can the detector show why?**<br>
[MARS](https://vectorinstitute.github.io/mars) catches both face swaps and fully AI-generated video. It has the highest average AUROC of eight detectors across seven datasets, trains on about 5× less compute than the strongest baseline, and shows the patch- and frame-level evidence behind each call. I also co-wrote a [survey of deepfakes in the foundation-model era](https://www.preprints.org/manuscript/202608.1870), from generation to detection to how they spread on social media.

**Should a vision-language model judge you from your face?**<br>
[FairLens](https://arxiv.org/abs/2609.01691) tests eight VLMs on hiring, legal and healthcare questions about real face images. The main failure isn't unequal treatment. It's models inferring what an image can't support, instead of answering "cannot tell".

**Can we trust what language models and agents say and do?**<br>
[Factuality-aware preference learning](https://arxiv.org/abs/2601.03027) *(ACL 2026)* reduces hallucinations, [UnBias+](https://vectorinstitute.github.io/unbias-plus/) detects, explains and rewrites biased language, and my work on [agentic transparency](https://vectorinstitute.github.io/Agentic-Transparency/) and harness-aware evaluation asks what we should record and test when an agent acts over many steps.

Before this, I worked on self-supervised learning and domain adaptation for Wi-Fi sensing at York University (IEEE TNNLS, IoT Journal, COMST), and on TinyML for edge NLP at KAUST.

<details>
<summary><b>Publications</b></summary>
<br>

**Multimodal and visual understanding**
- MARS: Multiscale Appearance-Residual Streams for Video Forgery Detection · *arXiv 2026* · [paper](https://arxiv.org/abs/2611.12508)
- SONIC-O1: A Real-World Benchmark for Evaluating Multimodal LLMs on Audio-Video Understanding · *EMNLP 2026 Main* · [paper](https://arxiv.org/abs/2601.21666)
- FairLens: Benchmarking Fairness in Vision-Language Models for High-Stakes Decision-Making · *arXiv 2026* · [paper](https://arxiv.org/abs/2609.01691)
- HumaniBench: A Human-Centric Framework for Large Multimodal Models Evaluation · *ACM TIST 2026* · [paper](https://arxiv.org/abs/2505.11454)
- Deepfakes in the Foundation-Model Era: A Survey of Forensics, Generation and Distribution Across Social Media Lifecycle · *Preprint 2026* · [paper](https://www.preprints.org/manuscript/202608.1870)

**Reliable AI and agents**
- Reducing Hallucinations in LLMs via Factuality-Aware Preference Learning · *ACL 2026* · [paper](https://arxiv.org/abs/2601.03027)
- Harness-Aware Evaluation of LLM Agents: Systems, Benchmarks, and Protocols · *Preprint 2026* · [paper](https://www.preprints.org/manuscript/202609.2140)
- Transparency in Agentic AI: A Survey of Interpretability, Explainability, and Governance · *Preprint 2026* · [paper](https://doi.org/10.31224/6451)
- From Features to Actions: Explainability in Traditional and Agentic AI Systems · *FTC 2026* · [paper](https://arxiv.org/abs/2602.06841)
- Position: Sustainable Open-Source AI Requires Tracking the Cumulative Footprint of Derivatives · *arXiv 2026* · [paper](https://arxiv.org/abs/2601.21632)
- Addressing Bias Through Ensemble Learning and Regularized Fine-Tuning · *arXiv 2024* · [paper](https://arxiv.org/abs/2402.00910)
- SARD: A Human-AI Collaborative Story Generation · *HCI International 2024* · [paper](https://doi.org/10.48550/arXiv.2403.01575)

**Wi-Fi sensing and efficient ML**
- Contrastive Predictive Coding with Compression for Enhanced Channel State Feedback in Wireless Networks · *IEEE TNNLS* · [paper](https://ieeexplore.ieee.org/abstract/document/11599644)
- MU-SHOT-Fi: Self-Supervised Multi-User Wi-Fi Sensing with Source-free Unsupervised Domain Adaptation · *IEEE IoT Journal* · [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11489060)
- A Tutorial-cum-Survey on Self-Supervised Learning for Wi-Fi Sensing: Trends, Challenges, and Outlook · *IEEE COMST* · [paper](https://arxiv.org/abs/2506.12052)
- TinyML NLP Scheme for Semantic Wireless Sentiment Classification with Privacy Preservation · *EuCNC & 6G Summit 2025* · [paper](https://doi.org/10.48550/arXiv.2411.06291)

</details>

<sub>Python · PyTorch · Hugging Face · vLLM · LangGraph · FastAPI · Docker</sub>
