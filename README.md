# 👑 TubeEnhancer: Advanced YouTube Toolkit Browser Extension

![Hero Banner Placeholder - High-Fidelity YouTube UI Augmentation](https://img.shields.io/static/v1?label=Apex+Architecture&message=Future-Proofed+Design&color=007ACC&style=for-the-badge&logo=Vite)

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension/ci.yml?style=flat-square&logo=github)](https://github.com/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension?style=flat-square&logo=codecov)](https://codecov.io/gh/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension)
[![License](https://img.shields.io/github/license/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension?style=flat-square&color=success)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension?style=flat-square&color=yellow)](https://github.com/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension)
[![Tech Stack](https://img.shields.io/badge/TypeScript%20%7C%20Vite%20%7C%20Tailwind%20v4-0064ff?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)

**Star ⭐ this Repo** if you believe in reclaiming control over your digital content consumption experience.

---

## 🎯 BLUF (Bottom Line Up Front)

**TubeEnhancer** is a professionally architected browser extension providing over 180 granular features to optimize, customize, and de-clutter the YouTube interface across all supported browsers. It serves as the definitive toolkit for power users demanding granular control over playback, quality, and content filtering.

## 🏛️ Architectural Blueprint (FSD Compliant)

This project adheres to the **Feature-Sliced Design (FSD)** methodology, ensuring maintainability, scalability, and clear separation of concerns suitable for a large-feature browser extension codebase.

mermaid
graph TD
    subgraph Browser Runtime
        A[Manifest/Entry Point] --> B(State Management Layer - Signals)
        B --> C{Features Slice}
        C --> D[Shared/UI Components]
    end

    subgraph Features Slice
        C --> C1[PlaybackControl] 
        C --> C2[DistractionBlocker] 
        C --> C3[QualityEnhancer] 
        C --> C4[UI Customization]
    end

    D --> E[YouTube DOM Interactors]
    E --> F[API Service Layers]


## 📜 Table of Contents

1.  [🎯 BLUF (Bottom Line Up Front)](#-bluf-bottom-line-up-front)
2.  [🏛️ Architectural Blueprint (FSD Compliant)](#️-architectural-blueprint-fsd-compliant)
3.  [📜 Table of Contents](#-table-of-contents)
4.  [✨ Key Features](#-key-features)
5.  [🤖 AI Agent Directives (Apex Configuration)](#-ai-agent-directives-apex-configuration)
6.  [🛠️ Development & Setup](#-development--setup)
7.  [📜 License](#-license)

---

## ✨ Key Features

TubeEnhancer consolidates numerous essential functionalities into one streamlined package:

*   **Playback Mastery:** Precision speed control (0.1x steps), frame-by-frame navigation, forced high-quality codecs (where supported).
*   **Distraction Elimination:** Advanced ad-skipping logic, removal of ephemeral elements (comments, suggested feeds), and customizable focus modes.
*   **UI Harmonization:** Complete overhaul of the visual presentation layer using TailwindCSS v4 for performance and aesthetic consistency.
*   **Cross-Browser Synergy:** Built using WXT (Web Extension Toolkit) for seamless deployment across Chromium-based browsers (Chrome, Edge, Brave) and Firefox.

## 🤖 AI Agent Directives (Apex Configuration)

<details>
<summary><strong>System Architecture & Verification Protocol (Mandatory for Future Iteration)</strong></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

--- 

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. 
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

--- 

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension`, is a **TypeScript/JavaScript Extension** project.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project utilizes **TypeScript 6.x (Strict)** compiled via **Vite 7** (using the Rollup backend for optimized bundling). Styling is governed by **TailwindCSS v4**. The extension structure is managed by **WXT (Web Extension Toolkit)** for maximum cross-browser compatibility (Manifest V3).
    *   **Architecture:** Adheres strictly to **Feature-Sliced Design (FSD)**. Components are separated into `pages`, `features`, `entities`, `shared`, and `processes` layers. Logic isolation is mandatory.
    *   **State Management:** Implements **Signals** (e.g., Preact Signals or similar atomic reactive primitives) for fine-grained, high-performance state updates within the DOM controllers, minimizing unnecessary re-renders.
    *   **Testing Mandate:** **Biome** for lightning-fast linting/formatting, **Vitest** for Unit/Component testing, and **Playwright** for end-to-end regression testing against live YouTube page structures.

## 4. VERIFICATION COMMANDS (CI/CD Alignment)
*   **Dependency Resolution:** `npm install` or `uv sync` (if applicable, but prioritize NPM for JS).
*   **Lint & Format Check:** `npx @biomejs/biome check --no-config"
*   **Unit/Component Tests:** `npx vitest run --coverage`
*   **E2E Validation:** `npx playwright test`
*   **Build Extension Package:** `npx wxt build`

## 5. PRINCIPLES IN FORCED ADHERENCE
*   **SOLID:** Enforced via clear interface definitions in TypeScript.
*   **DRY:** Mandatory utilization of shared FSD layers. No duplicated DOM manipulation logic.
*   **YAGNI:** Features must solve demonstrable user pain points; avoid speculative complexity.

</details>

## 🛠️ Development & Setup

This project uses the modern WXT build system integrated with Vite for superior TypeScript compilation and cross-browser manifest generation.

### Prerequisites

1.  Node.js (v18.0+)
2.  npm or yarn/pnpm

### Initialization Sequence

bash
# 1. Clone the repository
git clone https://github.com/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension.git
cd TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension

# 2. Install dependencies using npm (Apex Standard for JS projects)
npm install

# 3. Run the development server (starts watch mode, enabling hot reloading)
npm run dev


### Execution Scripts

| Script | Description | Standard | Velocity Index |
| :--- | :--- | :--- | :--- | 
| `dev` | Start local development server with HMR/Hot Reloading. | Vite/WXT | High |
| `build` | Compile production-ready, optimized extension bundles for all targets. | WXT | Medium |
| `lint` | Check code quality using Biome formatter and linter rules. | Biome | Ultra-High |
| `test:unit` | Run Vitest unit and component tests, generating coverage reports. | Vitest | High |
| `test:e2e` | Execute Playwright end-to-end validation scripts. | Playwright | Medium |

## 📜 License

This repository is governed by the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](LICENSE) file for full details.

*You are free to share and adapt the material for non-commercial purposes, provided you give appropriate credit.*