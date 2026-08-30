+++
date = '2026-06-06'
title = 'Taige Yang — Extended CV'
hideMeta = true
description = "Extended curriculum vitae of Taige Yang"
url = '/cv/extended/'
layout = 'cv'
type = 'page'
+++

**[← Short version](/cv/)**

Email: <span id="cv-email"></span> | GitHub: [yangtaige](https://github.com/yangtaige)
<script>(function(){var e=atob('c2h0aWdlcnlhbmdAZ21haWwuY29t');var a=document.createElement('a');a.href='mailto:'+e;a.textContent=e;document.getElementById('cv-email').appendChild(a);})();</script>

---

### Education

**University of California, Berkeley** — Visiting Student, Computer Science <span style="float:right">Aug 2025 – June 2026</span>\
GPA: 4.0 / 4.0

**ShanghaiTech University** — B.Eng. Biomedical Engineering *(in progress)* <span style="float:right">Sept 2023 – Present</span>\
GPA: 3.84 / 4.0\
Minor in Information Technology\
**Honors & Awards:** 
Outstanding Student, 2023–2024;\
Special Scholarship for Undergraduate 3+1 Overseas Exchange Program, 2025–2026

---

## Publications & Manuscripts

1. Yiwei Hou, Hao Wang, Muxi Lyu, Marius Momeu, Eric Nguyen, **Taige Yang**, Koushik Sen, Dawn Song, David Wagner. "Revelio: Cost-Efficient Agentic Memory Safety Vulnerability Detection Across Repository-Scale Codebases." Submitted to *USENIX Security '27*. [arXiv:2606.22263](https://arxiv.org/abs/2606.22263), 2026.
2. **Taige Yang**, Nalini Singh, Mingxuan Cai, Laura Waller. “Holographic Particle Velocimetry via Gaussian-Parameterized Particles.” *21st International Microscopy Congress (IMC21)*, Liverpool, UK, 2026. Accepted for poster presentation (LB2 865). [Abstract](/files/imc21-paper.pdf) · [Poster](/files/imc21-poster.pdf)

---

### Research Experience

**Computational Imaging Lab, UC Berkeley** — Undergraduate Researcher <span style="float:right">Feb 2026 – Present</span>\
*Holographic Particle Velocimetry via Gaussian-Parameterized Particles* ｜ Advisors: *Dr. Nalini Singh, Mingxuan Cai and Prof. Laura Waller*
- Developed a continuous-coordinate Gaussian particle representation for off-grid 3D particle localization and trajectory reconstruction from holographic measurements.
- Designed an analytical holographic forward model and Angular Spectrum Method (ASM)-based initialization for physics-driven 3D reconstruction.
- Modeled continuous 4D velocity fields with physics-informed neural networks to regularize ill-posed fluid flow reconstruction.
- Built an end-to-end computational imaging pipeline integrating holographic particle localization, temporal tracking, and 4D flow field reconstruction.

**Sky Computing Lab, UC Berkeley** — Research Collaborator <span style="float:right">Mar 2026 – Jun 2026</span>\
*Revelio: Repository-Scale Memory-Safety Vulnerability Detection* ｜ Advisor: *Yiwei Hou*
- Benchmarked the *Revelio* framework's efficacy in detecting memory vulnerabilities in V8 and libtorrent.
- Engineered Dockerized fuzzing environments with OSS-Fuzz and LLVM sanitizers (ASan, MSan, UBSan).
- Analyzed LLM-generated Proof of Concept exploits to assess the precision of agent-based security auditing.

**Translational Neuroimaging Lab, ShanghaiTech** — Undergraduate Researcher <span style="float:right">Aug 2024 – Nov 2025</span>\
*Sleep Stage Classification via Mouse fMRI* ｜ Advisors: *Prof. Zhiwei Ma & Yiyun Qi*
- Applied spectral clustering to parcellate brain regions and extracted dynamic Functional Connectivity (dFC) features using sliding-window correlation matrices from fMRI signals.
- Trained SVM, Random Forest, and MLP models to classify NREM/REM sleep cycles using ECoG as ground truth.
- Identified subcortical biomarkers tightly coupled with sleep state transitions via cross-modal correlation analysis.

---

### Projects

**CS162: Operating Systems** — UC Berkeley <span style="float:right">Spring 2026</span>\
*C · Rust*
- Co-developed a monolithic Pintos OS kernel: implemented file operation syscalls, ROX memory protections, user-kernel boundary security check, 1:1 pthread-to-kernel-thread mapping, `pthread_join`/`pthread_exit` syscalls, kernel-backed mutexes and semaphores, `exit`/`wait` process control syscalls for multi-threaded processes, and a 64-entry buffer cache with N-th Chance clock eviction.
- Built a fault-tolerant distributed MapReduce framework with heartbeat-based failure recovery, and engineered a highly available distributed Key-Value store based on the Raft consensus algorithm.
- Engineered a concurrent HTTP/1.0 server using a custom thread pool, a POSIX-compatible shell with full job control and pipelines, and a `malloc`/`free` allocator with explicit free-list and block coalescing.

**CS152: Computer Architecture and Engineering** — UC Berkeley <span style="float:right">Spring 2026</span>\
*C · RISC-V Assembly*
- Reverse-engineered cache hierarchy (L1: 16 kB, 64 B line, 8-way) via microbenchmarks and hardware performance counters.
- Co-architected an Alpha 21264-style tournament branch predictor (4096-entry global + 1024-entry local + arbiter).
- Vectorized complex arithmetic and DGEMV in RISC-V Vector Assembly.
- Optimized multithreaded `matmul` achieving **~7.0× speedup** (MI) and **~2.2× speedup** (MSI) via matrix pre-transposition and cache-coherence-aware memory access.

**CS161: Computer Security** — UC Berkeley <span style="float:right">Fall 2025</span>\
*Go · C · x86 Assembly*
- Architected a cryptographically secure file-sharing system in Go using AES Encrypt-then-MAC, RSA hybrid encryption, and HashKDF-derived keys; implemented strict key-regenerating revocation.
- Exploited memory vulnerabilities (buffer overflows via sign-extension bugs, SFP pivots, stack canary leaks, ASLR bypass via `printf` info-leak, format string `%hn` writes, ret sleds, TOCTOU race conditions).
- Discovered and chained SQLi, stored/reflected XSS, CSRF, and directory traversal vulnerabilities in a mock web platform.

**CS61C: Great Ideas of Computer Architecture** — UC Berkeley <span style="float:right">Fall 2025</span>\
*C · RISC-V Assembly*
- Implemented a Snake game engine in C with dynamic memory management verified by Valgrind Memcheck.
- Hand-wrote a neural network forward-pass classifier in pure RV32I assembly with strict calling convention.
- Designed a two-stage pipelined RISC-V (RV32I) processor in Logisim with forwarding and hazard stall logic.

**CS188: Introduction to Artificial Intelligence** — UC Berkeley <span style="float:right">Fall 2025</span>\
*Python · PyTorch*
- Implemented A\* search with custom admissible heuristics, Alpha-Beta Pruning Minimax, and Expectimax agents.
- Built Q-Learning and Approximate Q-Learning agents with ε-greedy exploration; solved MDPs via Value Iteration.
- Engineered HMM-based ghost tracking with particle filtering; built a character-level GPT with attention mechanisms.

**BME1312: AI in Medical Imaging** — ShanghaiTech <span style="float:right">Spring 2025</span>\
*Python · PyTorch*
- Reconstructed dynamic cardiac cine MRI from 5× undersampled k-space data using a 3-stage cascaded 3D U-Net with CBAM attention and Data Consistency layers; achieved PSNR 37.07 dB and SSIM 0.9626.
- Developed 2D cardiac segmentation models (U-Net, MedNeXt, MMNet); achieved Dice 0.9611 on the left ventricle.
- Analyzed CE vs. Dice loss gradient formulations and applied combined dynamic-weighted loss for stable convergence.

**BME1107: Biomedical Electronics II** — ShanghaiTech <span style="float:right">Spring 2025</span>\
*Cadence*
- Designed a complete EEG signal processing module: folded-cascode OTA preamplifier (<30 µW, maps input to 0.7–1.6 V), sampling circuit, single-slope ADC with high-linearity ramp generator, and DAC.
- Suppressed end-to-end latency to <1 µs by aligning the ramp reference with preamplifier output and increasing CLK to 500 kHz.

**BME1109: Biomedical Electronics I** — ShanghaiTech <span style="float:right">Spring 2025</span>\
*PCB · Python*
- Designed and assembled a fully functional PCB-based ECG acquisition circuit, tested on human subjects.
- Developed a Python program for real-time electrocardiogram visualization and heart rate display.
- Collaborated with 2 classmates.

---

### Laboratory Experience

**BME1108: Human Anatomy and Physiology** — ShanghaiTech <span style="float:right">Spring 2025</span>
- Conducted hands-on cadaveric dissection observation, examining skeletal structures, musculature, internal organs, and the peripheral nervous system.

---

### Skills

**Programming:** Python · C · Go · Rust · RISC-V Assembly · x86 Assembly · MATLAB · SQL · C#

**Hardware:** Cadence (analog IC design & simulation) · PCB design and debugging

**Tools:** Git · PyTorch · GDB · Valgrind · Docker · Logisim · Unity

**Domain Knowledge:** Computer Security · Operating Systems · Computer Architecture · Machine Learning & AI · Medical Imaging · Computer Networks · Signals and Systems · Biomedical Engineering · Human Anatomy and Physiology
