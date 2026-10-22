# Contributing to VerScript

Thank you for your interest in contributing to VerScript! Whether you are proposing a new language keyword, submitting a patch to the C compiler, extending standard libraries, or enhancing our desktop/mobile IDEs, we welcome your collaboration.

---

## 🏛️ Ecosystem Overview
VerScript is developed across several key repositories under the `VerScript` organization:
- **`VerScript/VerScript`**: Language compiler, VM, bytecode engine, standard libraries, and tooling.
- **`VerScript/verscript-studio-desktop`**: Electron-based desktop IDE.
- **`VerScript/verscript-studio-android`**: Mobile Android IDE (PWA & APK).
- **`VerScript/VerScript.github.io`**: Official documentation, interactive 34-chapter Academy, and live REPL playground.
- **`VerScript/help`**: Official language reference, keyword index, and offline help database.

---

## 🚀 Development Workflow

### 1. Setting Up the Language Compiler
Requirements: GCC (MinGW-w64 on Windows), Git, Node.js.

```bash
git clone https://github.com/VerScript/VerScript.git
cd VerScript

# Build the compiler binary
gcc -Iinclude -Isrc src/main.c src/compiler/lexer.c -o verscript.exe -lm

# Run tests
.\verscript.exe tests\test_step.vrs
```

### 2. Synchronizing Metadata & Tooling
Whenever you add a new keyword, token, or standard library:
1. Update `include/lexer.h` and `src/compiler/lexer.c`.
2. Run `node tooling/scripts/sync_meta.js` to automatically synchronize TextMate grammars, IDE extension configs, and auto-scaffold help database entries.
3. Test your changes with the test suite.

### 3. Submitting Changes
1. Fork the respective repository.
2. Create a topic branch: `git checkout -b feat/my-feature`.
3. Commit your changes using Conventional Commits: `feat(compiler): ...`, `fix(runtime): ...`, `docs(help): ...`.
4. Ensure all tests pass.
5. Open a Pull Request referencing any related issues.

---

## 🏷️ Issue & Project Tracking
We track project progress across all repositories on our [Interactive Project Board](https://verscript.github.io/project).
Please check the board before starting major feature work to see current milestones and assigned tasks.
