# OpenAI UI Discrepancy Report

## 🧭 Overview

This repository documents temporary or unexpected discrepancies between the **Web version** and the **Desktop App version** of ChatGPT, particularly relating to:

- **Google Drive integration**
- **Deep Search appearance**
- **MyGPT visibility and behavior**

It is part of a structural investigation framework called `D2Ai` — **Dynamic Deployment Analysis & inspection**.

> "Even seasoned professionals can sense something is off. This isn't just a bug — it's a live rollout."  
> — Author's Note

---

## 📁 Repository Structure

```
OpenAI_UI_Discrepancy_Report
├─ Connectors        # Google Drive integration evidence
├─ DeepSearch        # UI behavior screenshots
└─ MyGPT             # Personal GPT visibility discrepancy
```

Each folder contains:
- Screenshot evidence (`.png` files)
- Timestamped filenames for traceability

---

## 🎯 Objectives

- Clarify the nature of version-specific behaviors
- Assist other users encountering similar UI inconsistency
- Archive empirical evidence for future correlation

This is **not** a complaint repository — it is a constructive diagnostic archive.

---

## 📡 Deployment Behavior Hypothesis

The inconsistencies observed are likely due to a:

- **Phased rollout (段階的展開)** model
- Temporarily staggered update across platforms

### Observations

| Feature             | Web (1.2025.153) | Desktop (1.2025.153) | Status            |
|--------------------|------------------|-----------------------|-------------------|
| Google Drive       | ✅ Available      | ❌ Not Visible        | In Rollout        |
| Deep Search        | 🔍 Customizable  | 🔎 Fixed UI Only      | Behavior Diverges |
| MyGPT UI View      | 💬 Expanded      | 💭 Missing/Compact    | Layout Diverges   |

---

## 🛡️ License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
- **Attribution** — You must give appropriate credit (e.g., to "the repository author" or "GitHub user: blanctex"),
  provide a link to the license, and indicate if changes were made.

---

## 🔄 Future Work

- Monitor future ChatGPT desktop updates
- Compare update cycles and changelogs
- Submit findings to OpenAI support if necessary

---

## 📌 Notes

- This repository avoids personal identifiers — only public observations are included.
- The screenshots are taken from the same account on the same machine.

---

## 🙋 Contact

To discuss structural UX inconsistencies or AI diagnostic frameworks (D2Ai), please reach out via [GitHub Discussions](https://github.com/blanctex/OpenAI_UI_Discrepancy_Report/discussions).

---

**This repository was created to assist all ChatGPT users in understanding platform-specific rollouts.**

---
