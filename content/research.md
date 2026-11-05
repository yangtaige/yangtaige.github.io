+++
date = '2026-04-20T14:09:52-07:00'
title = 'Research'
schools = ["UC Berkeley", "ShanghaiTech"]
fields = ["BME", "CS"]
languages = ["Python"]
topics = ["Imaging", "ML", "Security"]
+++
### Holographic Particle Velocimetry via Gaussian-Parameterized Particles *(Feb 2026 - Present)*
Undergraduate Researcher | **Computational Imaging Lab, UC Berkeley**\
*Advised by Dr. Nalini Singh & Mingxuan Cai & Prof. Laura Waller*
**Publication:** Taige Yang, Nalini Singh, Mingxuan Cai, and Laura Waller.
“Holographic Particle Velocimetry via Gaussian-Parameterized Particles.”
*21st International Microscopy Congress (IMC21)*, 2026.

[Abstract (PDF)](/files/imc21-paper.pdf) · [Poster (PDF)](/files/imc21-poster.pdf)
<img src="/image/research/holograph.png" alt="Holograph" style="width: 100%; max-width: 600px; border-radius: 8px; margin: 15px 0;">
<details>
  <summary><b>Details</b></summary>

- Developed a continuous-coordinate Gaussian particle representation and differentiable optical forward model for off-grid 3D localization from inline holograms.
- Extended frame-wise localization to continuous neural trajectories, jointly fitting particle positions, sizes, and amplitudes to multi-frame hologram measurements.
- Used hologram evidence to extend, merge, and prune trajectories after motion-aware matching, refining particle identities and temporal support.
- Introduced motion regularization using shared velocity fields fitted from other trajectories through cross-fitting; preparing a manuscript on the method.

</details>

---

### Zero-Day Vulnerability Detection via Revelio *(Mar 2026 - Jun 2026)*
Research Collaborator | **Sky Computing Lab, UC Berkeley**\
*Advised by Yiwei Hou*

[arXiv](https://arxiv.org/abs/2606.22263) · [Full blog](https://m1-llie.github.io/Revelio-agent-harness-is-as-important-as-model-for-cybersecurity/) · [Twitter](https://x.com/yiwei_hou/status/2050257349647167995) · [Sky Project](https://sky.cs.berkeley.edu/project/revelio/)
<details>
  <summary><b>Details</b></summary>
  <br>
  
  - **Framework Evaluation:** Benchmarked the *Revelio* framework's efficacy in detecting memory vulnerabilities within the V8 JavaScript engine, libtorrent, etc.
  - **Environment Orchestration:** Engineered Dockerized fuzzing environments leveraging **OSS-Fuzz** and an array of LLVM sanitizers (**ASan, MSan, UBSan**) to ensure comprehensive detection of memory errors and undefined behaviors.
  - **PoC Analysis:** Analyzed LLM-generated Proof of Concept for zero-day vulnerabilities to assess the precision of agent-based security auditing.
</details>

---

### Sleep Stage Classification via Mouse fMRI Signals *(Aug 2024 - Nov 2025)*
Undergraduate Researcher | **Translational Neuroimaging Lab, ShanghaiTech**\
*Advised by Prof. Zhiwei Ma & Yiyun Qi*

**Conference abstract:** **Taige Yang**, Yiyun Qi, Zhiwei Ma. “Decoding continuous sleep states in mice from regional fMRI dynamics.” *2026 Annual Meeting of the Magnetic Resonance Imaging Branch of the Chinese Society for Stereology*, Xi’an, China, October 23–26, 2026. Conference abstract; poster presentation (62-004). [Abstract](/files/sleep-fmri-abstract.pdf) · [Poster](/files/sleep-fmri-poster.pdf)

<img src="/image/research/mouse.png" alt="Brain Regions" style="width: 100%; max-width: 600px; border-radius: 8px; margin: 15px 0;">
<details>
  <summary><b>Details</b></summary>

- Initially explored dynamic functional-connectivity features and SVM, Random Forest, and MLP models for NREM/REM classification using electrophysiological labels.
- Subsequently developed Awake/NREM/REM decoding from regional fMRI time-series features using elastic-net multinomial logistic regression and hidden Markov models, with nested leave-one-mouse-out validation.
- Evaluated decoding across 24 mice: HMM temporal decoding increased pooled macro-F1 from 0.605 to 0.651; analyzed state-specific regional contributions using held-out feature perturbations.

</details>
