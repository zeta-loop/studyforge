# 🔥 StudyForge

**Turn any study material into a beautiful, interactive HTML course — in one prompt.**

No frameworks. No build step. No server. Just one self-contained HTML file with quizzes, progress tracking, and a scored final exam.

![Claude Code Skill](https://img.shields.io/badge/Claude_Code-Skill-blueviolet?style=for-the-badge)
![Any Subject](https://img.shields.io/badge/Works_With-Any_Subject-gold?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-green?style=for-the-badge)

---

## What It Does

Give StudyForge a topic, a PDF, or lecture notes → get back a **complete interactive course** as a single `.html` file you can open in any browser.

```
/studyforge Photosynthesis for AP Biology
/studyforge ./lecture-slides.pdf
/studyforge "Contract Law — offer, acceptance, consideration"
/studyforge "Linear Algebra midterm prep, focus on eigenvalues"
```

### What You Get

| Feature | Description |
|---------|-------------|
| 📚 **8-12 structured sections** | Concepts ordered simple → complex |
| 🧠 **Active recall quizzes** | Multiple choice, true/false, fill-in-the-blank |
| 👣 **Step-by-step reveals** | Progressive walkthroughs for complex topics |
| ⚠️ **Exam trap warnings** | Common mistakes and trick questions highlighted |
| 🏆 **Scored final exam** | 12-20 questions with ranked results |
| 💾 **Progress saved locally** | Pick up where you left off (localStorage) |
| 📱 **Responsive design** | Works on desktop, tablet, and mobile |
| 🌙 **Dark theme** | Easy on the eyes during late-night study sessions |
| 🎨 **Creative themes** | Each course gets a unique metaphor to aid memory |

### Works With ANY Subject

- **Computer Science** — syntax-highlighted code, "will this compile?" quizzes, code tracing
- **Sciences** — formula breakdowns, "what would happen if?" scenarios, unit analysis
- **Mathematics** — step-by-step solutions, calculation traps, formula fill-in-the-blanks
- **Humanities** — timeline reveals, source analysis, perspective matching
- **Law & Business** — case scenarios, principle application, term matching
- **Languages** — grammar exercises, translation quizzes, vocabulary matching
- **Medicine** — clinical scenarios, process ordering, symptom-diagnosis matching

---

## Install

### Recommended: npx skills
```bash
npx skills add zeta-loop/studyforge
```
This uses the [Vercel Skills](https://github.com/vercel-labs/skills) ecosystem — works with Claude Code, Cursor, Codex, and 30+ other agents.

### Alternative: git clone
```bash
# macOS / Linux
git clone https://github.com/zeta-loop/studyforge.git ~/.claude/skills/studyforge

# Windows
git clone https://github.com/zeta-loop/studyforge.git %USERPROFILE%\.claude\skills\studyforge
```

Then use `/studyforge` in any Claude Code session.

---

## Examples

### Programming
```
/studyforge Java Generics for my Data Structures exam
```
→ Generates an interactive course with compile quizzes, type erasure walkthroughs, and a 15-question final exam

### Biology
```
/studyforge Cellular respiration — glycolysis, Krebs cycle, electron transport chain
```
→ Step-by-step pathway reveals, "what molecule is produced?" fill-in-the-blanks, ATP counting exercises

### Law
```
/studyforge Contract Law fundamentals — formation, terms, breach, remedies
```
→ Case scenario analysis, "which principle applies?" matching, courtroom-themed progression

### Math
```
/studyforge Linear Algebra eigenvalues and eigenvectors
```
→ Calculation walkthroughs, matrix operation tracing, common sign-error traps

---

## How It Works

1. **You provide** a topic, file, or description
2. **StudyForge analyzes** the material and identifies core concepts + exam traps
3. **Generates** a single `.html` file with full interactivity
4. **Open in browser** → start learning immediately

The output is a completely self-contained HTML file. No server needed. Share it with classmates by just sending the file.

---

## Why StudyForge?

Most AI study tools give you **flashcards or summaries** — passive content you skim and forget.

StudyForge generates **active recall exercises**: quizzes that make you think, fill-in-the-blanks that test understanding, and step-by-step reveals that build intuition. It deliberately uses **different examples** from your source material so you can still practice the originals.

Research shows active recall is [2-3x more effective](https://en.wikipedia.org/wiki/Testing_effect) than re-reading. StudyForge automates the hardest part — creating good practice questions.

---

## License

MIT — use it, share it, fork it.
