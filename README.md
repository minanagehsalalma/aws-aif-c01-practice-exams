# AWS Certified AI Practitioner (AIF-C01) — Strict Practice Exam Suite

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Online-brightgreen?logo=github)](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/)
[![Questions](https://img.shields.io/badge/Questions-446%20Unique%20Items-blue?logo=amazon-aws)](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/)
[![Exams](https://img.shields.io/badge/Exam%20Forms-7%20Interactive%20Exams-orange)](#-exam-forms--direct-links)
[![Offline Ready](https://img.shields.io/badge/Client--Side-100%25%20Offline%20Ready-success)](#-running-locally--offline)

A complete, self-contained, interactive practice exam suite for the **AWS Certified AI Practitioner (AIF-C01)** certification. Built from strictly community-verified and deduplicated ExamTopics source questions, featuring full keyboard-first controls, an iterative mistake-mastery redo loop, fullscreen focus mode, and scaled scoring.

---

## 🌐 Live Online Access (GitHub Pages)

You can launch and practice the entire exam suite directly in your browser:

### 🚀 **[Open the Exams Portal](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/)**

### 📝 Exam Forms & Direct Links

| Exam Form | Questions | ExamTopics Coverage | Direct Launch Link |
| :--- | :---: | :---: | :--- |
| **Exam Form A** | 65 | Q1 – Q65 | [Launch Form A →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-1.html) |
| **Exam Form B** | 65 | Q66 – Q130 | [Launch Form B →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-2.html) |
| **Exam Form C** | 65 | Q131 – Q196 | [Launch Form C →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-3.html) |
| **Exam Form D** | 65 | Q197 – Q262 | [Launch Form D →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-4.html) |
| **Exam Form E** | 65 | Q263 – Q328 | [Launch Form E →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-5.html) |
| **Exam Form F** | 65 | Q329 – Q393 | [Launch Form F →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-6.html) |
| **Exam Form G** | 56 | Q394 – Q452 | [Launch Form G →](https://minanagehsalalma.github.io/aws-aif-c01-strict-exams/AWS-AIF-C01-ExamTopics-Strict-Exam-7.html) |

---

## ✨ Key Features & Improvements

### 🔁 Smart Mastery Redo Mode
- After submitting your exam, you can immediately enter **Redo Mode** to practice only your incorrect questions.
- Redo mode operates in an **iterative mastery loop**: any questions you get wrong in a redo round are repeated in subsequent rounds until you achieve **100% mastery**.
- **Continuous Practice**: Even after achieving *100% Mastery*, you can re-drill your original mistakes anytime directly from the scorecard or the review view.

### ⌨️ Complete No-Mouse Keyboard Navigation
You can complete entire 65-question exams without touching the mouse:
- **`↑` / `↓` / `←` / `→`**: Move choice focus and select options.
- **`1` – `4` / `A` – `D`**: Direct single-key choice selection.
- **`Space`**: Toggle selection on the currently highlighted option.
- **`Enter` / `N`**: Jump to the next question.
- **`P`**: Jump to the previous question.
- **`F`**: Toggle review flag on current question.
- **`C`**: Clear choice selection.
- **`U`**: Jump directly to the next unanswered question.
- **`S`**: Submit exam.
- **`D` / `M`**: Toggle Dark / Light theme.
- **`Z`**: Toggle Fullscreen Focus mode.
- **`?`**: Open the keyboard shortcut modal.

### ⛶ Fullscreen Clean Focus Mode
- Press `Z` or click the `⛶` icon in the top header to enter an immersive fullscreen focus mode.
- Eliminates page clutter, centers questions, and provides an on-demand slide-out questions drawer (`G` key).
- High-contrast, accessibility-checked colors in both dark and light modes.

### ⏱️ Real Exam Countdown & Timed Mode
- 90-minute authentic exam countdown timer.
- Visual warning when time remaining is 10 minutes or less.
- Automatic exam submission on timer expiration.

### 📊 Scaled Standardized Scoring & Domain Analytics
- Computes standard AWS scaled score from **100 to 1000** (passing threshold: **700**).
- Comprehensive domain-by-domain performance bars for all 5 exam domains.
- Full post-exam answer review with verified community consensus notes and discussions.

### 💾 100% Client-Side & LocalStorage Persistence
- Zero tracking, zero backend, and zero dependencies.
- All answers, flagged questions, elapsed time, and redo progress automatically persist in browser `localStorage`.
- Safe to refresh or close the tab—your active session resumes instantly.

---

## 📚 Exam Domain Breakdown

The questions are classified into the official 5 AWS Certified AI Practitioner domains:

| Domain | Domain Title | Question Count | Exam Share |
| :---: | :--- | :---: | :---: |
| **Domain 1** | Fundamentals of AI and Machine Learning | 146 | 32.7% |
| **Domain 2** | Fundamentals of Generative AI | 166 | 37.2% |
| **Domain 3** | Applications of Foundation Models | 58 | 13.0% |
| **Domain 4** | Guidelines for Responsible AI | 41 | 9.2% |
| **Domain 5** | Security, Compliance, and Governance for AI Solutions | 35 | 7.8% |
| **Total** | **Strict Community-Verified Bank** | **446** | **100%** |

---

## 🛠️ Deduplication & Rigorous Quality Assurance

- **Deduplication**: Duplicate stems present in raw source dumps (e.g., Q138/Q261 and Q201/Q378) were deduplicated to ensure no repeated stems across exams.
- **Consensus-Verified**: Every single question has an answer key cross-checked against recorded community consensus votes. Questions lacking clear community consensus (Q404, Q415, Q446) were purged.
- **Restored Matching Prompts**: Hotspot and matching-type questions (such as Bedrock guardrail policies in Q144 and model customization methodologies in Q155) have their full use-case and mitigation-action descriptions restored.

---

## 💻 Running Locally / Offline

This suite is 100% self-contained and requires no Node.js, Python, or web server.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/minanagehsalalma/aws-aif-c01-strict-exams.git
   cd aws-aif-c01-strict-exams
   ```

2. **Open the portal:**
   - Double-click `index.html` or `AWS-AIF-C01-ExamTopics-Strict-Portal.html` in any web browser (Chrome, Edge, Firefox, Safari).
   - Alternatively, open any of the individual `AWS-AIF-C01-ExamTopics-Strict-Exam-*.html` files directly.

---

## 📄 License & Disclaimer

This project is created for educational and study purposes. AWS and Amazon Web Services are registered trademarks of Amazon.com, Inc. or its affiliates.
