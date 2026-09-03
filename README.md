# Avinash Rajavarapu

**Software Engineer at Microsoft**, working on OneDrive for iOS.

I build user-facing iOS features and the shared C++ data layers underneath them. Before Microsoft I was at ViaPlus (VINCI Highways), building a .NET/Angular image-review platform that ran at production scale. Most of my favourite work is performance and test-infrastructure work — problems where the constraint is measurable and the result is not a matter of opinion.

`Swift` · `C++` · `Python` · `TypeScript` — Hyderabad, India

---

## Experience

### Microsoft — Software Engineer (Apprentice)
`Nov 2025 – Present` · OneDrive for iOS

- Shipped **3 OneDrive Photos experiences** — Slideshows, GIF Maker and Posters — to approximately **1.5M users**, owning requirements, design, implementation, testing, rollout and monitoring.
- Cut GIF export peak memory **300 MB → 15 MB** by replacing O(n) whole-library loading with O(1) fetch-on-demand encoding.
- Raised playback from drops around **28 fps to a steady 54–60 fps** by moving encoding onto asynchronous background queues.
- Rebuilt the XCTest infrastructure with dependency injection, optimised mocks and parallel execution: line coverage **0% → 85%**, CI runtime **20 min → 8 min**.
- Built a heartbeat-monitoring harness that isolated a non-terminating test behind an opaque CI timeout, unblocking a multi-day team-wide build failure.
- Author production **C++** query/data-layer logic in OneDrive's shared cross-platform core.
- Built AI agents and reusable LLM skills for implementation, code review, test generation and documentation — roughly **3× faster delivery** against prior cycles.

### ViaPlus (VINCI Highways) — Software Engineer
`Jan 2025 – Nov 2025`

- Built an image-review system end to end and generalised it for reuse; **2 other project teams adopted it** instead of rebuilding the capability.
- Supported **1M+ daily reviews at sub-second load** across 3 projects, on 4–5 independently deployable .NET/C# services behind an Angular/TypeScript dashboard.
- Designed a relational schema that unified 3 projects onto 1 data model; wrote the joins, aggregations and window-function SQL behind the live dashboards.
- Found and reported **12 vulnerabilities, 7 critical** — including XSS, CSRF and payment/insecure-request exposure.

### Fiverr — Freelance Software Engineer
`May 2023 – Jan 2024`

- Delivered **20+ client projects** with a **4.9/5 rating** across 11 reviews, shipping 15+ end-to-end machine learning systems — speech recognition, deepfake detection, fake-news classification, image classification and time-series forecasting.

---

## Selected Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [Security Analysis of APKs](https://github.com/avinashrajavarapugit/Security-Analysis-of-APKs) | Reverse-engineers Android APKs with Androguard — disassembles Dalvik bytecode, extracts opcode-frequency features and analyses requested-permission graphs. Combining static and dynamic analysis raised **ROC-AUC 0.91 → 0.97**. | Python, Androguard, scikit-learn |
| [Automated Cloud Auditing & Remediation](https://github.com/avinashrajavarapugit/Automated-Cloud-Auditing-and-Remediation-System) | Audits AWS IAM and S3 configurations and prioritises remediation by severity using a logistic-regression classifier trained on vulnerability descriptions. **F1 71.1–92.2%** across six severity dimensions. Final-year major project, team of 4. | Python, scikit-learn, ScoutSuite, Flask |
| [Deepfake Video Detection](https://github.com/avinashrajavarapugit/Deep-Fake-Video-Detection) | Flags manipulated video by scoring audio–visual synchronisation: MFCC audio features and Mediapipe FaceMesh mouth-region tracking fed into pre-trained SyncNet models, compared by Euclidean distance against a threshold. | Python, TensorFlow, OpenCV, Mediapipe, Flask, Docker |
| [Intrusion Detection System](https://github.com/avinashrajavarapugit/Intrusion-Detection-System-IDS-using-Signature-based-and-Anomaly-based-Approaches) | Classifies network traffic as normal or malicious two different ways and compares them directly: a Decision Tree signature detector and a CNN–LSTM anomaly detector, each with its own training and evaluation pipeline. | Python, scikit-learn, TensorFlow |
| [Rule Engine with AST](https://github.com/avinashrajavarapugit/Rule-Engine-with-AST-and-Weather-Data-Monitoring) | 3-tier engine that decides user eligibility from attributes like age, department and salary. Rules are represented as an abstract syntax tree with AND/OR operators and stored in MongoDB, so they can be created and combined at runtime instead of hardcoded. | JavaScript, Node.js, MongoDB |
| [Business Web Application](https://github.com/avinashrajavarapugit/SaaS-based-business-web-application) | Full-stack business app with a pricing module, authenticated user accounts, a news feed and contact/support flows. | React, Node.js, MongoDB |

More: [Weather Forecast Monitoring](https://github.com/avinashrajavarapugit/Weather-Forecast-Monitoring) · [HR Churn Rate Analysis](https://github.com/avinashrajavarapugit/HR-Churn-Rate-Analysis) · [Hand-Gesture Game Controller](https://github.com/avinashrajavarapugit/Hill-Climb-Racing-Hand-Gesture-Controller) · [Windows Domain Hardening](https://github.com/avinashrajavarapugit/Windows-Domain-Hardening)

---

## Competitive Programming

| Platform | Result |
| :--- | :--- |
| **LeetCode** | Guardian — contest rating **2310**, top **0.51%**, 1,122 problems solved |
| **Codeforces** | Max **Expert (1734)**, currently Specialist (1492), 364 problems solved |
| **Meta Hacker Cup 2025** | Round 1 — **AIR 101** (global 666) among 9,000+ participants |
| **IICPC Quantfest 2025** | **AIR 48** among 8,000+ participants |
| **IICPC Codefest 2026** | Problem setter, 10,000+ participants |
| **CodeChef** | 4★ |

Solutions and notes: [LeetCode](https://github.com/avinashrajavarapugit/Leetcode) · [Codeforces](https://github.com/avinashrajavarapugit/CodeForces) · [CSES](https://github.com/avinashrajavarapugit/CSES_Sheet) · [Meta Hacker Cup](https://github.com/avinashrajavarapugit/Meta-Hackercup-Practice) · [Algorithms](https://github.com/avinashrajavarapugit/Algorithms) · [Templates](https://github.com/avinashrajavarapugit/Templates)

---

## Tech

**Languages**  
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**iOS**  
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=uikit&logoColor=white)
![XCTest](https://img.shields.io/badge/XCTest-1575F9?style=flat-square&logo=xcode&logoColor=white)
![Core ML](https://img.shields.io/badge/Core%20ML-000000?style=flat-square&logo=apple&logoColor=white)

**Backend & Data**  
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**ML & Cloud**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Writing

A. Pramod Kumar, K. Cherukuri, V. T. Chintala, K. P. Saffronia and **A. Rajavarapu**, "Automated Cloud Auditing and Remediation System," *Computer Research and Development*, vol. 25, no. 10, 2025.

## Education & Teaching

**B.Tech, Computer Science and Engineering (Cyber Security)** — VNR Vignana Jyothi Institute of Engineering and Technology, Hyderabad · 2021–2025

---

## Elsewhere

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/avinash6302/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=framer&logoColor=white)](https://avinashrajavarapu.framer.website/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/avinashrajav/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/rajavarapu.avinas)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rajavarapu.avinash@gmail.com)
