# 🚀 DevPilot — System Architecture & Sandbox Diagnostics

This document outlines the decoupled service topology, Piston containerized sandbox jails, and Groq LPU AI code diagnostics powering **DevPilot**.

---

## 1. Architectural Highlights
- **Monaco Editor Kernel**: High-fidelity code editor delivering sub-16ms typing latency, VS Code keybindings, and Abstract Syntax Tree (AST) tokenization.
- **Piston Sandbox Container Jail**: Linux cgroups v2, read-only root filesystems, 2.0s CPU timeouts, and 256MB RAM ceilings for multi-language execution (C++, Java, Python, JavaScript).
- **Groq LPU Diagnostic Engine**: Sub-200ms real-time explanation of compiler errors and automatic Big-O computational complexity proofs powered by Meta LLaMA 3 70B.
- **Decoupled API Gateway**: Express.js proxy with rate-limiting, error serialization, and zero credential exposure.

---

## 2. Technical Documentation & Formal Report
The complete 12-page IEEE-standard technical architecture report is published in:
- **LaTeX Source**: [`docs/report/project-report.tex`](file:///c:/Users/tharu/Documents/GITHUB%20REPO/GITHUB%20MANAGER/Dev-Pilot/docs/report/project-report.tex)
- **Compiled PDF**: [`docs/report/project-report.pdf`](file:///c:/Users/tharu/Documents/GITHUB%20REPO/GITHUB%20MANAGER/Dev-Pilot/docs/report/project-report.pdf)
