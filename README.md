<h1 align="center">
  Hi 👋, I'm Cheng Dai
</h1>

[![Views](https://komarev.com/ghpvc/?username=dccc2025&label=Views&color=blueviolet&style=flat&base=13)](https://github.com/dccc2025) [![Personal Website](https://img.shields.io/badge/Personal%20Website-dccc2025.github.io-blue?logo=google-chrome&logoColor=white)](https://dccc2025.github.io/) [![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Cheng%20Dai-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=zh-CN&user=vJrsT54AAAAJ)

<h3 align="center">
  <i>"Post-training 4D world models, and high-performance training and inference infrastructure."</i>
</h3>

### 🧬 About Me
- 🎓 My former research focused on **computational imaging**, **agentic benchmarks**, and **embodied intelligence**.
- 🔬 My current research focuses on post-training 4D world models. I am moving toward high-performance training and inference infrastructure, to support reliable perception, reasoning, and interaction in real-world environments.
- 🎯 I am actively seeking **27 Fall PhD opportunities**.
- 🌐 **[Personal Website](https://dccc2025.github.io/)** · **[CV](https://dccc2025.github.io/files/ChengDai_cv.pdf)** · **[Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=vJrsT54AAAAJ)**

### 📝 Selected Works

**[HAIR: HADAR-Based Thermal Infrared Hyperspectral Image Restoration](https://arxiv.org/abs/2605.13664)** · *IEEE TIP, under review*<br>
<em><b>Cheng Dai</b><sup>&#42;</sup>, Jiale Lin<sup>&#42;</sup>, Bingxuan Song, Yifei Chen, Jiashuo Chen, Xin Yuan, and Fanglin Bao</em><br>
A physics-driven restoration framework for ground-based thermal-infrared hyperspectral images. It combines HADAR rendering with spectral calibration and TeX decompose-synthesize restoration, based on the radiative transfer equation.<br>
[Paper](https://arxiv.org/abs/2605.13664) · [Homepage](https://github.com/jialelin2007/HAIR)

**[TeX-1500: A Paired Real-World LWIR Hyperspectral Dataset and Benchmark for Temperature-Emissivity-Texture Decomposition](https://arxiv.org/abs/2606.03806)** · *arXiv preprint; will submit to Nature by 2027*<br>
<em><b>Cheng Dai</b><sup>&#42;</sup>, Jiale Lin<sup>&#42;</sup>, Hongyi Xu, Bingxuan Song, Ziyang Xie, Fanglin Bao</em><br>
A paired real-world long-wave infrared hyperspectral dataset and benchmark for supervised temperature-emissivity-texture decomposition, together with TeX-UNet as a wavelength-aware baseline.<br>
[Paper](https://arxiv.org/abs/2606.03806) · [Homepage](https://github.com/dccc2025/TeX-1500) · [Pretrained Models](https://huggingface.co/dccc2025/TeX-UNet) · [Dataset](https://huggingface.co/datasets/jialelin2007/TeX-1500)

**[T²exture: Sparse Active Thermal Texture Imaging](https://arxiv.org/abs/2608.02192)** · *AAAI, under review*<br>
<em>Jiashuo Chen<sup>&#42;</sup>, <b>Cheng Dai</b><sup>&#42;</sup> (co-first author and listed alphabetically), Yanan Hu and Fanglin Bao</em><br>
A sparse-active thermal texture imaging framework that reconstructs temporally dense thermal-texture sequences from passive LWIR frames and a few actively perturbed keyframes, using pretrained visible representations.<br>
[Paper](https://arxiv.org/abs/2608.02192) · [Code](https://github.com/dccc2025/T2exture) · [Dataset](https://huggingface.co/datasets/chenjiashuo/T2exture_datasets) · [Model Weights](https://huggingface.co/chenjiashuo/T2exture_model)

**[FrontierPhysics: Evaluate Agents for End-to-End Frontier Physics Research](https://arxiv.org/html/2611.06910)** · *Technical Report; will submit to Nature by December 2026*<br>
<em>Bingran You, ..., <b>Cheng Dai</b>, ..., Gerbrand Ceder, Hartmut Haeffner (108 authors)</em><br>
FrontierPhysics evaluates whether AI agents can carry out end-to-end physics research across 56 tasks in theoretical, computational, and experimental physics. Each agent receives a principal-investigator-style prompt and must produce a manuscript with structured outputs, graded by deterministic verifiers and expert rubrics.<br>
[Paper](https://arxiv.org/html/2611.06910) · [Hugging Face](https://huggingface.co/papers/2611.06910) · [OpenReview](https://openreview.net/forum?id=Q4Iyl2xyt4) · [Artificial Analysis](https://artificialanalysis.ai/) · [AA Post](https://x.com/ArtificialAnlys/status/2125691597602058284) · [X trending](https://x.com/i/trending/2118486932200296639)

**[OVOK: A Recursive Self-Improving Agentic Framework for Video-Based Articulated Robot State Estimation](https://arxiv.org/abs/2611.32185)** · *CVPR 2027, under review*<br>
<em><b>Cheng Dai</b><sup>&#42;†</sup>, Renkai Luo<sup>&#42;</sup>, Guanfeng Tang, Siming Li, Hao Zhao</em><br>
OVOK (One Video to Kinetics) is a recursive, self-improving agentic framework for video-based articulated robot state estimation. It recovers articulated robot state from video through recursive self-improvement.<br>
[Paper](https://arxiv.org/abs/2611.32185)

**GaIR-Agent: Gaussian Inverse Rendering via Closed-Loop Reasoning and Physical Refinement** · *CVPR 2027, under review*<br>
<em>Siming Li<sup>&#42;</sup>, Renkai Luo<sup>&#42;</sup>, <b>Cheng Dai</b>, Guanfeng Tang, Hao Zhao</em><br>
GaIR-Agent is the first agentic framework for Gaussian inverse rendering, coupling visual reasoning with physically based optimization. It reaches state-of-the-art relighting on FIPT-Synthetic and NeuSky Synthetic, outperforming external baselines in PSNR, LPIPS, and MAE, and cuts material-target generation time by 85.6% indoors and 90.2% outdoors versus the non-agentic pipeline.

**IGGLoop: Instance-Grounded Gaussian Looped Transformer for Feed-Forward 4D Driving Scene Reconstruction** · *CVPR 2027, under review*<br>
<em>Guanfeng Tang<sup>&#42;</sup>, Renkai Luo<sup>&#42;</sup>, <b>Cheng Dai</b>, Siming Li, Hao Zhao</em><br>
IGGLoop unifies instance segmentation, tracking, Gaussian reconstruction, and motion estimation for feed-forward 4D driving scenes. It is competitive on Waymo, nuScenes, and Argoverse 2, with a 2.57% PSNR gain on Waymo over the state-of-the-art pose-free baseline, 6.4% of that baseline's parameters, and a 3.45× speedup; recovered assets support independent insertion, removal, and repositioning.

<sub><sup>&#42;</sup> Equal contribution. <sup>†</sup> Project lead.</sub>

---

### 🌍 Connect with Me
- Email: [daichengwhu2025@gmail.com](mailto:daichengwhu2025@gmail.com)
- WeChat: daicheng1291317948
- LinkedIn: [Cheng Dai](https://www.linkedin.com/in/cheng-dai-443432403/) -- Welcome to connect with me!
- Personal Website: [dccc2025.github.io](https://dccc2025.github.io/)
- Google Scholar: [Cheng Dai](https://scholar.google.com/citations?hl=zh-CN&user=vJrsT54AAAAJ)
- **Always open to research collaborations and exciting side-projects! Welcome to contact me!**

---


### ✨ Just for Fun

> I want everyone in the future to work on HADAR! ✊😎🪛

---

<!---
dccc2025/dccc2025 is a ✨ special ✨ repository because its `README.md` appears on the GitHub profile.
--->
