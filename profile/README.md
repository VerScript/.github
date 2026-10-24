<div align="center">

<img src="https://verscript.github.io/favicon.svg" alt="VerScript Logo" width="110" height="110" />

# VerScript Organization
### Modern, Strongly Typed, Declarative Programming Language & Ecosystem

[![Website](https://img.shields.io/badge/Website-verscript.github.io-00FFCC?style=for-the-badge&logo=googlechrome&logoColor=black)](https://verscript.github.io)
[![Documentation & Academy](https://img.shields.io/badge/Documentation-74_Chapters-7928CA?style=for-the-badge&logo=bookstack&logoColor=white)](https://verscript.github.io/docs/)
[![Help & Keyword Index](https://img.shields.io/badge/Help_Center-247_Topics_(151_Keywords)-BD00FF?style=for-the-badge&logo=gitbook&logoColor=white)](https://verscript.github.io/help/)
[![Project & Roadmap](https://img.shields.io/badge/Interactive_Project-Kanban_(31_Issues)-0077FE?style=for-the-badge&logo=github&logoColor=white)](https://verscript.github.io/project/)
[![Language Version](https://img.shields.io/badge/VerScript-v2.0.0_Stable-00FFCC?style=for-the-badge&logo=rust&logoColor=black)](https://github.com/VerScript/VerScript/releases/tag/v2.0.0)

<br/>

**VerScript** is a modern programming language designed for precision, expressive pipeline composition, and zero-friction execution. It features first-class reactive channels, matrix-vector mathematics, dynamic foreign function interfaces (FFI), declarative data constraints, and a unified toolchain across desktop, mobile, and web.

</div>

---

## 🏛️ Ecosystem Overview & Project Directory

The VerScript organization maintains eight integrated repositories across language design, runtimes, developer tooling, documentation, and cloud infrastructure:

| Repository | Scope & Purpose | Active Version | Build & Health | Links |
| :--- | :--- | :--- | :--- | :--- |
| **[`VerScript/VerScript`](https://github.com/VerScript/VerScript)** | Core native C compiler, VM, AST lexer/parser (151 keywords), Win32 dynamic FFI, and 21 standard libraries. | `v2.0.0` | ![GCC Native](https://img.shields.io/badge/GCC-Win64_Passed-0e8a16?style=flat-square) | [Releases](https://github.com/VerScript/VerScript/releases) • [Source](https://github.com/VerScript/VerScript) |
| **[`VerScript/verscript-studio-desktop`](https://github.com/VerScript/verscript-studio-desktop)** | Standalone desktop IDE built on Electron, Monaco editor, split-view layout, and embedded Help Center. | `v1.3.0` | ![Electron 31](https://img.shields.io/badge/Electron-Windows_x64-0077FE?style=flat-square) | [Releases](https://github.com/VerScript/verscript-studio-desktop/releases) • [Source](https://github.com/VerScript/verscript-studio-desktop) |
| **[`VerScript/verscript-studio-android`](https://github.com/VerScript/verscript-studio-android)** | Standalone mobile IDE for Android with touch-first explorer, InstantVM engine, and PWA capabilities. | `v1.0.0` | ![Android PWA](https://img.shields.io/badge/PWA-Online_&_APK-34A853?style=flat-square) | [Live Mobile App](https://verscript.github.io/mobile) • [Releases](https://github.com/VerScript/verscript-studio-android/releases) |
| **[`VerScript/VerScript.github.io`](https://github.com/VerScript/VerScript.github.io)** | Official website, 74-chapter documentation Academy, interactive REPL playground, and Project Kanban. | `v2.0.0` | ![GitHub Pages](https://img.shields.io/badge/Pages-Deployed-0e8a16?style=flat-square) | [Website](https://verscript.github.io) • [Source](https://github.com/VerScript/VerScript.github.io) |
| **[`VerScript/help`](https://github.com/VerScript/help)** | Official language reference, multi-functionality keyword encyclopedia (all 151 keywords), standard library API docs, and error remedies (247 topics). | `v2.0.0` | ![Documentation](https://img.shields.io/badge/Topics-247_Indexed-BD00FF?style=flat-square) | [Help Center](https://verscript.github.io/help) • [Releases](https://github.com/VerScript/help/releases) |
| **[`VerScript/IDE`](https://github.com/VerScript/IDE)** | Browser-based Web IDE featuring InstantVM client-side execution, virtual file tree, and code share. | `v1.0.0` | ![Vite WebApp](https://img.shields.io/badge/WebIDE-Production-7928CA?style=flat-square) | [Web IDE](https://verscript.github.io/ide) • [Source](https://github.com/VerScript/IDE) |
| **[`VerScript/polyserver`](https://github.com/VerScript/polyserver)** | Unified Node.js backend proxy and multi-protocol service orchestrator. | `v1.0.0` | ![Node.js](https://img.shields.io/badge/Node-Active-0e8a16?style=flat-square) | [Source](https://github.com/VerScript/polyserver) |
| **[`VerScript/VS-Sharp`](https://github.com/VerScript/VS-Sharp)** | AI assistant (LLM) and pair-programmer tightly integrated into VerScript Studio. | `v0.5.0` | ![Experimental](https://img.shields.io/badge/Status-Experimental-f59e0b?style=flat-square) | [Source](https://github.com/VerScript/VS-Sharp) |

---

## 📊 Live Project Tracking & Roadmap

We actively track milestones, epics, bug fixes, and feature requests across all repositories.

👉 **View the Live Interactive Project Board**: **[https://verscript.github.io/project](https://verscript.github.io/project)**

### Active Milestones

```mermaid
gantt
    title VerScript Organization Roadmap (2026)
    dateFormat  YYYY-MM-DD
    section Language Core
    v2.0.0 Universal Foundation (Released)       :done,    des1, 2026-09-01, 2026-10-22
    v2.1.0 Concurrency & Package Manager (vrspm) :active,  des2, 2026-10-23, 2026-12-15
    section Desktop Studio
    v1.3.0 Help Modal, Split-Pane, Updater       :done,    des3, 2026-10-01, 2026-10-22
    v1.4.0 Git Source Control & Debugger         :active,  des4, 2026-10-23, 2026-12-01
    section Mobile Android
    v1.0.0 Android Studio PWA Launch             :done,    des5, 2026-10-10, 2026-10-21
    v1.1.0 Touch Keyboard & Symbol Palette       :active,  des6, 2026-10-23, 2026-11-30
    section Web & Docs
    Help Center & Academy v2.0.0                 :done,    des7, 2026-10-15, 2026-10-22
    Interactive Project Board & Code Sharing     :active,  des8, 2026-10-22, 2026-11-15
```

---

## 🛠️ Key Language Pillars & Quickstart

```verscript
# 1. Foreign Function Interface (Dynamic Win32 Call)
extern "kernel32.dll" GetCurrentProcessId()
pid : GetCurrentProcessId()
display "Process ID: " + pid ?color=#00FFCC

# 2. Pipeline Operators & Range Iteration with 'step'
numbers : [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
for i in 0 .. 10 step 2:
    display "Step: " + i

# 3. Native Matrix Mathematics
matA : [[1, 2], [3, 4]]
matB : [[5, 6], [7, 8]]
matC : matA * matB
display "Matrix Product: " + matC
```

Install the native toolchain in PowerShell:
```powershell
# Clone and install VerScript runtime into %LOCALAPPDATA%\VerScript
git clone https://github.com/VerScript/VerScript.git
cd VerScript
.\tooling\installer\install.ps1
```

To update an existing installation to the latest version at any time:
```powershell
verscript update
```

---

## 🤝 Contributing & Community
- **Issue Tracker**: Check out open issues labeled [`status:todo`](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3AVerScript+label%3Astatus%3Atodo) or [`priority:high`](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3AVerScript+label%3Apriority%3Ahigh).
- **Contributing Guide**: Read our [Contributing Guidelines](https://github.com/VerScript/.github/blob/main/CONTRIBUTING.md).
- **Security Policy**: Read our [Security Policy](https://github.com/VerScript/.github/blob/main/SECURITY.md).
- **Code of Conduct**: We adhere to the [Contributor Covenant](https://github.com/VerScript/.github/blob/main/CODE_OF_CONDUCT.md).

---

<div align="center">
<sub>Maintained with ❤️ by the VerScript Core Team. Licensed under the MIT License.</sub>
</div>
