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

**Publication:** 
**Taige Yang**, Nalini Singh, Mingxuan Cai, and Laura Waller.
“Holographic Particle Velocimetry via Gaussian-Parameterized Particles.”
*21st International Microscopy Congress (IMC21)*, 2026.

[Abstract (PDF)](https://virtual.oxfordabstracts.com/event/75996/submission/1842) · [Poster (PDF)](/files/imc21-poster.pdf)

<figure class="test6-reconstruction" aria-label="Test6 holograms and reconstructed particle trajectories">
  <div class="test6-panels">
    <figure>
      <a href="/image/research/test6-hologram-measured.webp">
        <img src="/image/research/test6-hologram-measured.webp" width="750" height="730" alt="Measured Test6 hologram at frame 1, with the approximate Vorticella region outlined and a 100 μm scale bar.">
      </a>
      <figcaption>Measured hologram</figcaption>
    </figure>
    <figure>
      <a href="/image/research/test6-hologram-predicted.webp">
        <img src="/image/research/test6-hologram-predicted.webp" width="750" height="730" alt="Predicted Test6 hologram at frame 1, on the same spatial and intensity scales as the measurement.">
      </a>
      <figcaption>Predicted hologram</figcaption>
    </figure>
  </div>
  <div class="test6-panels test6-trajectories">
    <figure>
      <a href="/image/research/test6-trajectories-2d.webp">
        <img src="/image/research/test6-trajectories-2d.webp" width="1200" height="1200" alt="XY projection of Test6 particle trajectories, colored by track, with the approximate Vorticella region outlined." loading="lazy">
      </a>
      <figcaption>XY projection</figcaption>
    </figure>
    <figure>
      <a href="/image/research/test6-trajectories-3d.webp">
        <img src="/image/research/test6-trajectories-3d.webp" width="1200" height="1200" alt="The same particle trajectories in a 3D volume with independently scaled axes. A box marks the approximate Vorticella region and its estimated focus range." loading="lazy">
      </a>
      <figcaption>3D trajectories</figcaption>
    </figure>
  </div>
</figure>

<details>
  <summary><b>Details</b></summary>

- Developed a differentiable optical model that predicts normalized in-line hologram contrast from Gaussian particles.
- Initialized particle locations frame by frame, then jointly refined 3D trajectories across the sequence. Used agreement with the measured holograms to extend, merge, and prune tracks.
- Across five Vorticella feeding current datasets, we reconstructed more than 1,000 tracer particle trajectories.

</details>

---

### Sleep Stage Classification via Mouse fMRI Signals *(Aug 2024 - Nov 2025)*
Undergraduate Researcher | **Translational Neuroimaging Lab, ShanghaiTech**\
*Advised by Prof. Zhiwei Ma & Yiyun Qi*

**Publication:** 
**Taige Yang**, Yiyun Qi, Zhiwei Ma. “Decoding continuous sleep states in mice from regional fMRI dynamics.” *2026 Annual Meeting of the Magnetic Resonance Imaging Branch of the Chinese Society for Stereology*, Xi’an, China, October 23–26, 2026. Conference abstract; poster presentation (62-004). [Abstract](/files/sleep-fmri-abstract.pdf) · [Poster](/files/sleep-fmri-poster.pdf)

<div class="fmri-panels">
  <figure class="research-figure">
    <a href="/image/research/fmri-roi-importance.webp">
      <img src="/image/research/fmri-roi-importance.webp" width="1474" height="908" alt="Poster Figure 2A. Brain maps show changes in held-out F1 after perturbing each region's features for Awake, NREM, and REM." loading="lazy">
    </a>
    <figcaption>ROI importance</figcaption>
  </figure>
  <figure class="research-figure">
    <a href="/image/research/fmri-coefficient-importance.webp">
      <img src="/image/research/fmri-coefficient-importance.webp" width="1474" height="908" alt="Poster Figure 2B. Brain maps show the norm of regional coefficient contrasts for Awake, NREM, and REM." loading="lazy">
    </a>
    <figcaption>Coefficient importance</figcaption>
  </figure>
</div>

<details>
  <summary><b>Details</b></summary>

- Initially explored dynamic functional-connectivity features and SVM, Random Forest, and MLP models for NREM/REM classification using electrophysiological labels.
- Subsequently developed Awake/NREM/REM decoding from regional fMRI time-series features using elastic-net multinomial logistic regression and hidden Markov models.
- Evaluated decoding across 24 mice; analyzed state-specific regional contributions using held-out feature perturbations.

</details>

---

### Zero-Day Vulnerability Detection via Revelio *(Mar 2026 - Jun 2026)*
Research Collaborator | **Sky Computing Lab, UC Berkeley**\
*Advised by Yiwei Hou*

[arXiv](https://arxiv.org/abs/2606.22263) · [Blog](https://m1-llie.github.io/Revelio-agent-harness-is-as-important-as-model-for-cybersecurity/) · [Twitter](https://x.com/yiwei_hou/status/2050257349647167995) · [Project Page](https://sky.cs.berkeley.edu/project/revelio/)

<figure class="research-figure">
  <a href="/image/research/revelio-workflow.webp">
    <img src="/image/research/revelio-workflow.webp" width="1532" height="368" alt="Overview of Revelio's two stages: hypothesis generation and hypothesis confirmation." loading="lazy">
  </a>
  <figcaption>Revelio workflow. <a href="https://arxiv.org/pdf/2606.22263v1#page=2">Figure 1 from the Revelio preprint</a>.</figcaption>
</figure>

<details>
  <summary><b>Details</b></summary>

- Evaluated LLM-agent-generated proof-of-concept exploits on repositories like V8 and libtorrent using OSS-Fuzz, Docker, and LLVM sanitizers.
- Analyzed detection accuracy and failure modes of agent-based vulnerability auditing on real-world codebases.

</details>
