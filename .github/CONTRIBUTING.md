# 🚀 Contributing to TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension

Thank you for your interest in contributing to **TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension**! We welcome all contributions, from bug reports to new features and documentation improvements.

## 1. Our Guiding Principles

This project adheres to the highest standards of software engineering, inspired by the **Apex Technical Authority** directives:

*   **Zero-Defect:** Strive for the highest quality and stability.
*   **High-Velocity:** Enable rapid development and iteration.
*   **Future-Proof:** Design for scalability and adaptability.

We follow industry best practices, including **SOLID**, **DRY** (Don't Repeat Yourself), and **YAGNI** (You Ain't Gonna Need It) principles.

## 2. Getting Started

### 2.1. Prerequisites

*   **Node.js:** Version 18 or higher is recommended.
*   **npm** or **yarn** or **pnpm**: Package manager.
*   **Git:** For version control.

### 2.2. Setting Up Your Development Environment

1.  **Fork the Repository:** Create your own fork of the `chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension` repository.
    bash
    git clone https://github.com/<your-username>/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension.git
    cd TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension
    

2.  **Install Dependencies:**
    bash
    npm install
    # or
    # pnpm install
    

3.  **Set up Browser Development Mode:** Follow the specific instructions for your target browser (Chrome, Firefox, Edge) to load the extension in development mode. This typically involves navigating to the browser's extension management page and loading the unpacked extension from the project's `dist` or build output directory.

## 3. Contribution Workflow

We use a standard GitHub pull request workflow:

1.  **Create a Branch:** Branch off the `main` branch for your feature or bug fix.
    bash
    git checkout -b feat/your-feature-name
    # or
    git checkout -b fix/your-bug-description
    

2.  **Make Your Changes:** Implement your code, ensuring it follows the project's coding standards and architectural patterns.

3.  **Add Tests:** Write unit or integration tests to cover your changes. All new code should be accompanied by relevant tests.

4.  **Lint and Format:** Ensure your code adheres to the project's linting and formatting rules.
    bash
    npm run lint
    npm run format
    # or
    # pnpm lint
    # pnpm format
    

5.  **Test Thoroughly:** Run all tests to ensure no regressions are introduced.
    bash
    npm run test
    # or
    # pnpm test
    

6.  **Commit Your Changes:** Use conventional commits for your messages.
    bash
    git commit -m "feat: Add new YouTube playback control"
    # or
    git commit -m "fix: Resolve issue with content discovery filters"
    

7.  **Push to Your Fork:**
    bash
    git push origin feat/your-feature-name
    

8.  **Open a Pull Request:** Create a pull request from your branch to the `main` branch of the `chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension` repository.

## 4. Code Style & Standards

*   **Language:** TypeScript (Strict Mode enabled).
*   **Framework/Libraries:** Vite, TailwindCSS v4 (if applicable for UI/config), Biome (linting/formatting), Vitest (unit tests), Playwright (E2E tests).
*   **Architecture:** Feature-Sliced Design (FSD) principles are encouraged for structuring frontend code.
*   **Linting/Formatting:** We use **Biome** for both linting and formatting. Ensure your code passes `biome check --apply` and `biome format --write`.
*   **Testing:** All new code must have corresponding tests in the `tests/` directory. Aim for high code coverage.

## 5. AI AGENT DIRECTIVES

This project utilizes AI for specific tasks, as outlined in `AGENTS.md`. Ensure your contributions are compatible with these directives. For browser extensions, AI might be used for analyzing user behavior patterns, suggesting UI improvements, or optimizing content processing, but always with a strong emphasis on privacy and user consent.

## 6. Reporting Issues

Before reporting a bug, please:

1.  **Search Existing Issues:** Check if the issue has already been reported.
2.  **Reproduce:** Try to reproduce the issue consistently.
3.  **Provide Details:** Use the `ISSUE_TEMPLATE` to provide a clear and detailed description, including:
    *   Steps to reproduce.
    *   Expected behavior vs. actual behavior.
    *   Browser and OS version.
    *   Any relevant screenshots or console logs.

## 7. Suggesting Enhancements

We appreciate feature requests! Please use the `ISSUE_TEMPLATE` to propose new features, clearly explaining the problem it solves and the proposed solution.

## 8. Code of Conduct

This project adheres to a Code of Conduct. By participating, you are expected to uphold these standards. Please refer to the [CODE_OF_CONDUCT.md](https://github.com/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension/blob/main/CODE_OF_CONDUCT.md) file for details.

## 9. License

This project is licensed under the **CC BY-NC 4.0** license. See the [LICENSE](https://github.com/chirag127/TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension/blob/main/LICENSE) file for more details.

---

We look forward to your contributions to make **TubeEnhancer-Advanced-YouTube-Toolkit-Browser-Extension** even better!
