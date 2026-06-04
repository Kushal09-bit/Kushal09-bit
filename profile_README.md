# Hi, I'm Sai Kushal Yadav 👋
### CSE (AI) Graduate · Amrita Vishwa Vidyapeetham, Bengaluru

I build AI systems that are not just accurate — but **secure and privacy-aware**.

---

## 🔬 Featured Projects

### 🔐 FedPlate — Privacy-Preserving License Plate Recognition
> *Proved standard Federated Learning is hackable. Then fixed it.*

- Built a **YOLOv8 + CRNN** pipeline for license plate detection and recognition
- Implemented **Federated Learning** (custom FedAvg in native PyTorch) across 3 clients
- Added **Differential Privacy** (gradient clipping + Gaussian noise) and **Homomorphic Encryption** (TenSEAL CKKS) as dual-layer defense
- Simulated a **Gradient Inversion Attack** — proved our system blocks image reconstruction that standard FL cannot
- Final accuracy: **89.4%** with strong mathematical privacy guarantees

📂 [View Project →](https://github.com/Kushal09-bit/Privacy-Preserving-ALPR)

---

### 🛡️ ShadowTrace FL — Federated Privacy Risk Detection for Web Browsers
> *Your browser knows more about you than you think. We fix that — with math.*

- Built a **Chrome browser extension** that classifies every browsing session as HIGH / MEDIUM / LOW privacy risk in real time using 8 behavioural and network features
- Implemented **Federated Random Forest** (FedAvg) across 5 heterogeneous client profiles — achieved **~92% accuracy**, outperforming a centralised baseline by **+1.1%**
- Enforced **Differential Privacy** via the Gaussian mechanism (ε=1.0, δ=1e-5, σ=0.4716) — formal (ε,δ)-DP guarantee on shared model weights at **zero accuracy cost**
- Built a **dual-pipeline blocking architecture**: `declarativeNetRequest` blocks tracker requests at the network layer before they complete; `webRequest` monitors in parallel for scoring and proof logging
- Achieved **100% interception of 24 tracker domains** on live sites (timesofindia.com) — **214 requests stopped per page load**, independently verified via Chrome DevTools
- Discovered that **URL entropy (r=0.961) outpredicts raw tracker count (r=0.922)** — catches obfuscated trackers that domain blocklists miss entirely
- Found a novel behavioural signal: **session duration (r=−0.895)** — users spend less time on tracker-heavy pages, a signal invisible to any server-side tool
- Built a real-time dashboard: live entropy gauge, privacy score trend chart, proof-of-block log, and site whitelist/blacklist with instant dynamic rule activation

**Tech:** JavaScript (ES2020) · Chrome Manifest V3 · declarativeNetRequest · FedAvg · Gaussian Mechanism · Random Forest · Shannon Entropy · Canvas API

📂 [View Project →](https://github.com/Kushal09-bit/ShadowTrace-FL)

---

## 🛠️ Skills

**AI / ML**
`Python` `PyTorch` `YOLOv8` `OpenCV` `Federated Learning` `Differential Privacy` `Homomorphic Encryption` `CRNN` `Random Forest` `Streamlit`

**Privacy & Security**
`Gaussian Mechanism` `(ε,δ)-DP` `Gradient Inversion Defense` `TenSEAL CKKS` `Secure Aggregation` `Network Interception`

**Browser & Web**
`JavaScript (ES2020)` `Chrome Extensions (MV3)` `declarativeNetRequest` `Canvas API` `HTML5` `CSS3`

**CS Fundamentals**
`Data Structures & Algorithms` `OOP` `Computer Vision` `Deep Learning`

**Tools**
`Git` `GitHub` `VS Code` `Linux` `Jupyter`

---

## 📂 Projects

| Project | Description | Tech |
|---|---|---|
| [ShadowTrace FL](https://github.com/Kushal09-bit/ShadowTrace-FL) | Federated privacy risk detection + tracker blocking Chrome extension with DP | JS, FedAvg, Gaussian DP, Chrome MV3 |
| [Privacy-Preserving ALPR](https://github.com/Kushal09-bit/Privacy-Preserving-ALPR) | Federated license plate recognition with DP + Homomorphic Encryption | PyTorch, YOLOv8, TenSEAL |
| [QuantamBanking](https://github.com/Kushal09-bit/QuantamBanking) | Banking application | Python |
| [Pricing-inventory](https://github.com/Kushal09-bit/Pricing-inventory) | Inventory and pricing system | Python |

---

## 📊 GitHub Stats

![Kushal's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Kushal09-bit&show_icons=true&theme=dark&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Kushal09-bit&layout=compact&theme=dark&hide_border=true)

---

## 📫 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/kushal-yadav-63ab89374/)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-red?style=flat&logo=gmail)](https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox)

---

*"Privacy and performance are not mutually exclusive."*
