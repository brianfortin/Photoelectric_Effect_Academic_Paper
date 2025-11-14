# PH250: Photoelectric Effect Academic Paper

This repository contains all files required to reproduce an academic paper on the photoelectric effect and the experimental determination of Planck's constant.

## Overview

The paper, "**A Thorough Examination of the Photoelectric Effect and its Consequences on Classical Theory of Light**," details the experimental procedure, results, and analysis used to derive Planck's constant ($h$). The findings are discussed in the context of validating quantum theory over the classical wave theory of light.

## Main Document Details

| Parameter | Value |
| :--- | :--- |
| **Title** | A Thorough Examination of the Photoelectric Effect and its Consequences on Classical Theory of Light |
| **Author** | Brian Fortin |
| **Institution** | Department of Physics, Colby College |
| **Date** | October 26, 2025 |
| **Key Finding** | Experimental determination of Planck's constant ($h$) |
| **Calculated $h$** | $(5.13 \pm 0.28) \times 10^{-34} \, \mathrm{J \cdot s}$ |
| **Accepted $h$ (CODATA)** | $6.626 \times 10^{-34} \ \mathrm{J \cdot s}$ |
| **95% Confidence Interval** | $[4.23, 6.03] \times 10^{-34} \, \mathrm{J \cdot s}$ |
| **Deviation from Accepted Value** | 22.66% |

## Main Files and Directory Structure

| Main Files | Description |
| :--- | :--- |
| `ph250_paper.pdf` | Pre-compiled PDF output of the paper. |
| `README.md` | This file. |
| `ph250_academic_paper_1/` | LaTeX source folder. |
| `ph250_paper.tex` | Main LaTeX source file containing text, equations, and document structure. |
| `references.bib` | Bibliography file in BibTeX format. |

### Prerequisites

- LaTeX distribution (e.g., **TeX Live**) providing `pdflatex` and `bibtex`.
- Editor or IDE (e.g., **TeXstudio**) for editing and compiling LaTeX files.

## Compilation Instructions

Run the following commands from the project root to generate the PDF with citations and cross-references:

```bash
pdflatex ph250_paper.tex
bibtex ph250_paper
pdflatex ph250_paper.tex
pdflatex ph250_paper.tex
```
