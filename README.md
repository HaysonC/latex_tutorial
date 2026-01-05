# LaTeX tutorials and snippets

This repository contains various LaTeX tutorials, snippets, and templates to help you get started with LaTeX document preparation.

## Contents

### 1. **install_latex/** - Installation Guide
A step-by-step guide for installing LaTeX on your system. Start here if you're new to LaTeX and need help setting up your environment.

### 2. **getting_started/** - Complete LaTeX Learning Guide
A comprehensive educational document covering 14 essential parts of LaTeX:

- **Part 1:** Essential Packages and Preamble Setup
- **Part 2:** Formatting Text (bold, italic, sizing, fonts)
- **Part 3:** Headings and Document Structure
- **Part 4:** Creating Tables
- **Part 5:** Inserting Images (placement, sizing, layouts)
- **Part 6:** Mathematical Equations
- **Part 7:** Theorems, Definitions, and Proofs
- **Part 8:** Hyperlinks
- **Part 9:** Citations and Bibliography (APA/MLA Style)
- **Part 10:** Converting Word Documents to LaTeX with ChatGPT
- **Part 11:** Labels and References
- **Part 12:** Table of Contents
- **Part 13:** Title Pages
- **Part 14:** Fancy Headers and Page Numbering

Each part includes working code examples in verbatim blocks and live output demonstrations.

### 3. **first_latex/** - Minimal Example
A minimal LaTeX template to get you started quickly with basic structure and formatting.

## Getting Started

1. **New to LaTeX?** Start with `install_latex/` to set up your environment
2. **Learning LaTeX?** Work through `getting_started/main.tex` - it teaches practical skills with examples
3. **Need a template?** Check `first_latex/` for a simple starting point

## Building Documents

To compile a LaTeX document:

```bash
cd getting_started/
latexmk -pdf main.tex
```

Or with pdflatex:

```bash
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```
