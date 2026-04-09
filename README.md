# CV LaTeX Template

This project converts your existing CV into an editable LaTeX structure.

## Project Structure

```text
cv-latex-template/
  main.tex
  latexmkrc
  data/
    personal.tex
  sections/
    01_objective.tex
    02_work_experience.tex
    03_technical_skills.tex
    04_projects.tex
    05_education_awards.tex
    06_soft_skills.tex
```

## What To Edit

- `data/personal.tex`: your name, role, phone, email, links.
- `sections/`: each CV section is isolated so you can update content quickly.
- `main.tex`: global style, spacing, colors, layout.

## Build Commands

### Option 1: `latexmk` (recommended)

```bash
latexmk -xelatex -pdf main.tex
```

### Option 2: plain `xelatex`

```bash
xelatex main.tex
xelatex main.tex
```

## Quick Personalization Checklist

1. Update personal info in `data/personal.tex`.
2. Replace project bullets with measurable outcomes where possible.
3. Keep dates consistent (`Mon YYYY -- Mon YYYY`).
4. Limit each bullet to one result-focused statement.
5. Rebuild and review spacing after each major edit.
