+++
date = '2026-06-06'
title = 'Taige Yang'
hideMeta = true
description = "Curriculum Vitae of Taige Yang"
url = '/cv/'
layout = 'cv'
type = 'page'
+++

<div class="cv-intro">
  <div class="cv-intro-contact">
    <p><strong><a href="/cv/extended/">Extended version →</a></strong></p>
    <p>Email: <span id="cv-email"></span> | GitHub: <a href="https://github.com/yangtaige">yangtaige</a></p>
  </div>
  <img class="cv-portrait" src="/image/profile/myself.jpg" alt="Portrait of Taige Yang">
</div>
<script>(function(){var e=atob('c2h0aWdlcnlhbmdAZ21haWwuY29t');var a=document.createElement('a');a.href='mailto:'+e;a.textContent=e;document.getElementById('cv-email').appendChild(a);})();</script>

### Education

**University of California, Berkeley** — Visiting Student, Computer Science <span style="float:right">Aug 2025 – June 2026</span>\
GPA: 4.0 / 4.0

**ShanghaiTech University** — B.Eng. Biomedical Engineering *(in progress)* <span style="float:right">Sept 2023 – Present</span>\
GPA: 3.84 / 4.0\
Minor in Information Technology\
**Honors & Awards:** 
Outstanding Student, 2023–2024;\
Special Scholarship for Undergraduate 3+1 Overseas Exchange Program, 2025–2026

## Publications & Manuscripts

1. Yiwei Hou, Hao Wang, Muxi Lyu, Marius Momeu, Eric Nguyen, **Taige Yang**, Koushik Sen, Dawn Song, David Wagner. "Revelio: Cost-Efficient Agentic Memory Safety Vulnerability Detection Across Repository-Scale Codebases." Submitted to *USENIX Security '27*. [arXiv:2606.22263](https://arxiv.org/abs/2606.22263), 2026.
2. **Taige Yang**, Nalini Singh, Mingxuan Cai, Laura Waller. “Holographic Particle Velocimetry via Gaussian-Parameterized Particles.” *21st International Microscopy Congress (IMC21)*, Liverpool, UK, 2026. Accepted for poster presentation (LB2 865). [Abstract](/files/imc21-paper.pdf) · [Poster](/files/imc21-poster.pdf)

### Research Experience

**Computational Imaging Lab, UC Berkeley** — Undergraduate Researcher <span style="float:right">Feb 2026 – Present</span>\
*Holographic Particle Velocimetry via Gaussian-Parameterized Particles* | Advisors: Dr. Nalini Singh, Mingxuan Cai, Prof. Laura Waller
- Developed a continuous-coordinate Gaussian particle representation and analytical holographic forward model for off-grid 3D particle localization, with ASM-based initialization.
- Extended the framework to temporal particle tracking and continuous 4D velocity-field reconstruction using physics-informed neural networks.
- Built an end-to-end physics-based pipeline integrating holographic localization, tracking, and flow reconstruction.

**Sky Computing Lab, UC Berkeley** — Research Collaborator <span style="float:right">Mar 2026 – Jun 2026</span>\
*Revelio: Repository-Scale Memory-Safety Vulnerability Detection* | Advisor: Yiwei Hou
- Evaluated LLM-agent-generated proof-of-concept exploits on V8, libtorrent, etc. using OSS-Fuzz, Docker, and LLVM sanitizers.
- Analyzed detection accuracy and failure modes of agent-based vulnerability auditing on real-world codebases.

**Translational Neuroimaging Lab, ShanghaiTech** — Undergraduate Researcher <span style="float:right">Aug 2024 – Nov 2025</span>\
*Sleep Stage Classification via Mouse fMRI* ｜ Advisors: *Prof. Zhiwei Ma & Yiyun Qi*
- Extracted dynamic functional-connectivity features from resting-state fMRI and trained SVM, Random Forest, and MLP models for NREM/REM classification.
- Analyzed cross-modal correlations with ECoG ground truth and identified subcortical biomarkers associated with sleep-state transitions.

### Selected Projects

**CS162: Operating Systems** — UC Berkeley <span style="float:right">Spring 2026</span>\
*C · Rust*
- Implemented major Pintos OS functionality in C, including system calls, multithreading/synchronization, process management, memory-safety checks, and a 64-entry buffer cache.
- Built distributed MapReduce and Raft-based key-value systems, together with concurrent systems programming projects including an HTTP server, shell, and memory allocator.

**CS161: Computer Security** — UC Berkeley <span style="float:right">Fall 2025</span>\
*Go · C · x86 Assembly*
- Designed and implemented a secure file-sharing system in Go using symmetric/asymmetric cryptography, authenticated encryption, key derivation, and revocation.
- Exploited memory-safety and web vulnerabilities including buffer overflows, ASLR bypass, format strings, SQL injection, XSS, CSRF, and TOCTOU races.

**BME1312: AI in Medical Imaging** — ShanghaiTech <span style="float:right">Spring 2025</span>\
*Python · PyTorch*
- Reconstructed 5× undersampled dynamic cardiac cine MRI using a cascaded 3D U-Net with attention and data-consistency layers (PSNR 37.07 dB, SSIM 0.9626).
- Developed cardiac segmentation models including U-Net and MedNeXt, achieving Dice 0.9611 on the left ventricle.

### Skills

**Programming:** Python · PyTorch · C · Go · Rust · MATLAB · RISC-V/x86 Assembly
**Tools:** Git · Docker · GDB · Valgrind · Cadence
**Research:** Computational Imaging · Inverse Problems · Machine Learning · Medical Imaging · Systems & Security
