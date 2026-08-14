# xyanncat — GitHub Profile Documentation & Maintenance Guide

This profile is engineered to showcase **xyanncat's** technical depth in **Agentic AI Systems**, **Multi-Agent DAG Orchestration**, **Autonomous Memory Engines**, and **Full-Stack MLOps Tooling**.

---

## 🎨 Asset Architecture

The profile utilizes adaptive, SVG-based assets that render seamlessly in both dark and light modes:

* **Dark Banner**: [`assets/profile-banner-dark.svg`](file:///d:/Github/github%20profile/assets/profile-banner-dark.svg)
  * Resolution: `1280 × 360`
  * Theme: Cyberpunk Deep Indigo, Cyan, and Crimson with Neural DAG node topology.
* **Light Banner**: [`assets/profile-banner-light.svg`](file:///d:/Github/github%20profile/assets/profile-banner-light.svg)
  * Resolution: `1280 × 360`
  * Theme: High-contrast Slate, Indigo, and Sky Cyan.
* **Footer Divider**: [`assets/profile-footer.svg`](file:///d:/Github/github%20profile/assets/profile-footer.svg)
  * Resolution: `1280 × 100`
  * Theme: Gradient glowing vector dividing line with central glowing node.
* **Avatar Artwork**: [`assets/494410865363954085.jfif`](file:///d:/Github/github%20profile/assets/494410865363954085.jfif)
  * Rendered as an avatar element with custom border and drop shadow.

---

## 🚀 Featured Repositories Matrix

The profile highlights 6 key open-source repositories:

| Repository | Focus Area | Key Highlights |
| :--- | :--- | :--- |
| **`agent-orchestration-system`** | Multi-Agent DAG Orchestrator | Planner/Researcher/Coder/Reviewer/Executor DAG, NVIDIA NIM + OpenRouter multi-LLM router, SSE streaming. |
| **`Noa`** | Autonomous AI Engine | 5-Layer Memory (Working, Short, Long, Semantic, Episodic), Liquid Glass UI, Desktop (Tauri v2 + Rust), Android APK. |
| **`Model-regression-detection-system`** | MLOps Regression Engine | 1.5x σ noise thresholding, cheapest-first root cause isolator, strict Zod schemas, auto-rollback hooks. |
| **`Failure-forensics-tool-for-AI-pipelines`** | Pipeline Diagnostics | `Forensic-0` CLI, zero-dependency Python stdlib Phase 1–2 engine, secret-redacted LLM reasoning. |
| **`Eternity.`** | Discord Bot & Web Dashboard | Next.js 16 App Router, Tailwind CSS v4, Prisma ORM, PostgreSQL, Redis, Stripe subscriptions. |
| **`Makima`** | Groq Live Stream Chatbot | Multi-platform (Twitch, YouTube Live, Kick), ultra-fast Groq Llama 3.1 70B/8B fallback, telemetry dashboard. |

---

## 🛠️ Maintenance & Future Updates

1. **Adding a New Pinned Repository**:
   - Add a new `<td width="50%" valign="top">` card block in the `## 🚀 Flagship Systems & Engineering Portfolio` table in `README.md`.
   - Maintain the standardized label badge (`FEATURED`, `BUILDING`, `OPEN SOURCE`, `EXPERIMENT`, `ARCHIVED`).

2. **Customizing the Animated Header**:
   - The typing SVG in `README.md` uses `readme-typing-svg.demolab.com`.
   - Edit the `lines` query parameter to add or alter dynamic title cycles.

3. **Verifying Asset Integrity**:
   - Run Python XML validation on all SVG files whenever updating vector assets:
     ```bash
     python -c "import xml.etree.ElementTree as ET, glob; [ET.parse(f) for f in glob.glob('assets/*.svg')]; print('All SVGs Valid!')"
     ```
