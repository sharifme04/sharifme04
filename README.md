<div align="center">

# Md. Sharif Hossain

### Senior Software Engineer · Frontend · AI-Native Development · Computational Engineering & HPC

[![Location](https://img.shields.io/badge/📍-Berlin%2C%20Germany-0078D4?style=flat-square)](https://github.com/sharifme04)
[![Email](https://img.shields.io/badge/📧-sharifmech04%40gmail.com-EA4335?style=flat-square)](mailto:sharifmech04@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sharifme04-181717?style=flat-square&logo=github)](https://github.com/sharifme04)
[![Profile Views](https://komarev.com/ghpvc/?username=sharifme04&style=flat-square&color=0078D4)](https://github.com/sharifme04)

</div>

---

## 🚀 About Me

**7+ years** Senior Software Engineer building production systems across frontend, mobile, backend, and realtime communication — and an **M.Sc. in Computational Materials Science** with hands-on FEM simulation research. I work across the full stack, apply **AI-native development** workflows daily (Claude, GPT, Gemini), and build scientific computing projects in Rust from first principles.

I am **not limited to one domain** — I can deliver across:

<table>
<tr>
<td>🖥️ Frontend — React, TypeScript, React Native, Flutter, Angular</td>
<td>⚙️ Backend — Node.js, Axum (Rust), PostgreSQL, Redis, MongoDB</td>
</tr>
<tr>
<td>🤖 AI-Native Development — Claude, GPT, Gemini, MCP, prompt engineering, multi-model workflows</td>
<td>🔬 Computational / HPC — FEM, MD, DEM, Monte Carlo, Rust from scratch</td>
</tr>
<tr>
<td>📱 Mobile — Flutter (offline-first, Drift/SQLite, flutter_rust_bridge FFI)</td>
<td>☁️ Cloud & DevOps — AWS, Docker, GitHub Actions CI/CD</td>
</tr>
</table>

---

## 🔬 Scientific Computing Portfolio — Rust (All From Scratch)

> No ML or physics frameworks. Every solver built from mathematical first principles.

<table>
<tr>
<th>Project</th>
<th>Key Methods</th>
<th>Highlights</th>
</tr>
<tr>
<td><b>🧮 <a href="https://github.com/sharifme04/fem-solver">2D FEM Solver — Linear Elasticity</a></b></td>
<td>CST elements · COO→CSR sparse assembly · Conjugate Gradient · Rayon parallel</td>
<td>Von Mises stress · O(h²) convergence · validated vs Euler–Bernoulli</td>
</tr>
<tr>
<td><b>⚛️ <a href="https://github.com/sharifme04/md-simulator">N-Body Molecular Dynamics</a></b></td>
<td>Nosé–Hoover thermostat · 5-step NH Velocity-Verlet · O(N) cell list</td>
<td>NVE energy drift &lt;0.002% over 50k steps · Q coupling study (Q=10 vs Q=100)</td>
</tr>
<tr>
<td><b>🪨 <a href="https://github.com/sharifme04/dem-solver">2D DEM Silo Simulator</a></b></td>
<td>Spring-dashpot contact · Coulomb friction (µ=0.5) · Velocity Verlet · O(N) cell list</td>
<td>Peak F_max ~18 kN · friction vs frictionless comparison · PFC2D reimplementation</td>
</tr>
<tr>
<td><b>📈 <a href="https://github.com/sharifme04/mc-option-pricer">Monte Carlo Option Pricer</a></b></td>
<td>GBM path simulation · antithetic variates · Nelder-Mead calibration · Rayon</td>
<td>10k–1M paths · 2× sample efficiency · Greeks via central finite differences</td>
</tr>
<tr>
<td><b>🧱 <a href="https://github.com/sharifme04/hpc-stencil-solver">HPC 2D Poisson Solver</a></b></td>
<td>Jacobi · Red-Black Gauss-Seidel · CG with CSR SpMV · OpenMP/Rayon</td>
<td>3.35× parallel speedup at N=1000 · L1/L2 cache crossover analysis · MLUP/s benchmarks</td>
</tr>
<tr>
<td><b>📐 <a href="https://github.com/sharifme04/optim-solver">Numerical Optimisation Engine</a></b></td>
<td>Steepest descent (Armijo) · CG Fletcher-Reeves + Polak-Ribière · Adam · SGD</td>
<td>CG 19× faster than steepest descent on Rosenbrock · κ=1–500 study · NN training from scratch</td>
</tr>
<tr>
<td><b>🔵 <a href="https://github.com/sharifme04/stochastic-geometry-cpp">Stochastic Geometry Framework (C++)</a></b></td>
<td>MT19937 RNG · Boolean sphere model · Minkowski functionals · NLopt COBYLA</td>
<td>Contrast function minimised to &lt;2×10⁻¹² · TU Freiberg doctoral-level course</td>
</tr>
</table>

---

## 🎓 Education

### M.Sc. Computational Materials Science — 2011–2015
**TU Bergakademie Freiberg, Germany**

Doctoral-level coursework:

| Course | Grade | Topics |
|---|---|---|
| Selected Topics of FEM | 1.7 | CST elements, sparse assembly, weak form derivation |
| High Performance Computing & Optimisation | — | OpenMP, NUMA topology, hardware counters, BLAS benchmarking |
| Stochastic Methods for Materials Science | — | NLopt COBYLA, Monte Carlo confidence bands, Boolean models |
| Molecular Dynamics | — | Nosé–Hoover thermostat, symplecticity proofs, Velocity Verlet |
| Numerical Analysis of Differential Equations | — | ODE/PDE solvers, stability, convergence |
| Dislocation Theory & DEM | 2.8 | Contact mechanics, granular flow |

**Master Thesis** — FEM Simulation, Fraunhofer Institute for Mechanics of Materials (IWM), Germany *(2014–2015)*

**Research Engineer (Project Role)** — FEM Simulation, Montanuniversity Leoben, Austria *(Feb–Jun 2016)*

### B.Sc. Mechanical Engineering — 2004–2009
**Chittagong University of Engineering and Technology (CUET), Bangladesh**

---

## 🧠 Technical Skills

<table>
<tr>
<td valign="top" width="50%">

**Scientific / HPC**
- FEM · Molecular Dynamics · DEM
- Monte Carlo simulation
- Numerical ODE/PDE solvers
- Sparse linear algebra (COO, CSR, CG, SpMV)
- Constrained nonlinear optimisation (NLopt COBYLA, Nelder-Mead)
- Cache-aware stencil solvers · MLUP/s benchmarking
- OpenMP · Rayon parallel computing

</td>
<td valign="top" width="50%">

**Languages & Stacks**
- 💻 **TypeScript / JavaScript** — React, React Native, Angular, Node.js, Express
- 📱 **Dart / Flutter** — offline-first mobile, flutter_rust_bridge FFI
- 🦀 **Rust** — FEM, MD, Monte Carlo, HPC solvers, Axum backend
- 🐍 **Python** — NumPy, SciPy, matplotlib
- ⚙️ **C / C++** — NLopt, numerical algorithms

</td>
</tr>
<tr>
<td valign="top">

**Backend & Systems**
- Axum (Rust) · Node.js · Express
- Redis pub/sub · PostgreSQL · MongoDB
- WebSocket gateway · WebRTC (ICE/STUN/TURN)
- End-to-end encryption (Double Ratchet-inspired, AEAD)

</td>
<td valign="top">

**AI-Native Development**
- Claude · GPT · Gemini — daily engineering workflows
- Prompt engineering · MCP server · Context-file design
- Multi-model validation · Architecture planning · Technical audits
- AI-assisted implementation at architecture scale

**Cloud & DevOps**
- AWS EC2 · S3 · Lambda · API Gateway · DynamoDB · SNS · IAM
- GitHub Actions CI/CD · Docker · Prometheus

</td>
</tr>
</table>

---

## 💼 Industry Experience

### Senior Frontend Developer · ML!PA Consulting GmbH, Berlin *(Nov 2022 – Dec 2025)*
- Built large-scale **React + TypeScript** web applications with Apollo GraphQL and complex state management
- Developed **React Native** mobile solutions integrating GPS tracking and IoT device data
- Implemented **Playwright E2E** testing suites and established CI/CD quality gates
- Designed reusable UI component systems with Material UI, Storybook, and Figma
- Integrated **Claude, GPT, Gemini** into daily engineering workflows — architecture reviews, code auditing, prompt-driven implementation

### Senior Software Developer · MYEGO2GO, Berlin *(Oct 2020 – Sep 2022)*
- Built the entire mobile web app from scratch through to production — sole frontend engineer on the web product
- Implemented a complete **biometric liveness-detection flow**: OCR-based ID extraction, real-time liveness challenge (eye/smile sequence), verification completion
- Tech stack: React.js, React Native, Redux-saga, Node.js, AWS

### Personal Engineering Project — AI-Assisted Realtime Communication Platform *(2025–2026)*
- **Rust backend** (Axum + Tokio) with WebSocket gateway, Redis pub/sub fan-out, PostgreSQL
- **Flutter** offline-first mobile client: memory cache (<50 ms UI), outbox queue, background sync, SQLite (Drift)
- Custom **WebRTC signaling** relay in Rust; ICE/STUN/TURN with exponential backoff reconnect
- Custom binary protocol (`payra_proto`) via `flutter_rust_bridge` FFI — session resumption, sequence-based delivery, adaptive keepalive; Rust codec running on-device
- **E2EE**: Double Ratchet-inspired key ratcheting, AEAD ciphers
- Iterative architecture audits resolving triple-sync race conditions, ICE restart timing bugs, message deduplication failures

### Earlier Roles *(2017–2020)*
- **Software Engineer** · Simplo GmbH, Berlin
- **Frontend Developer** · Medici Living Group, Berlin
- **Software Developer (Full-Stack)** · Meramo Verlag GmbH, Berlin
  - React, Redux, Node.js, Express, MongoDB, Apollo GraphQL, D3.js

---

## 📊 GitHub Stats

<div align="center">

![Sharif's GitHub stats](https://github-readme-stats.vercel.app/api?username=sharifme04&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sharifme04&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

</div>

---

## 🌍 Languages

**Bangla** (Native) · **English** (Fluent) · **German** (B1)

---

## 🎯 Open To

I am open to a **wide range of roles** — not limited to scientific computing:

| Domain | What I bring |
|---|---|
| 🖥️ Frontend / Full-Stack | React, TypeScript, React Native, Flutter, Angular — 7+ years production |
| 🤖 AI-Native / AI-Assisted Engineering | Daily Claude/GPT/Gemini workflows, MCP, prompt engineering, multi-model validation |
| ⚙️ Backend & Systems | Rust (Axum), Node.js, PostgreSQL, Redis, WebSocket, WebRTC |
| 🔬 Computational / HPC / Simulation | FEM, MD, DEM, Monte Carlo, HPC solvers — Rust from scratch |
| 📱 Mobile | Flutter offline-first, Drift/SQLite, flutter_rust_bridge FFI |

> ⭐ Available for **frontend, full-stack, AI-native, backend, or computational engineering** roles · Berlin or remote

---

<div align="center">
<sub>Berlin, Germany · sharifmech04@gmail.com · github.com/sharifme04</sub>
</div>