# Omar Olivares - CV

[![Build CV](https://github.com/ofou/cv/actions/workflows/main.yml/badge.svg)](https://github.com/ofou/cv/actions/workflows/main.yml)

This repository contains my professional CV in LaTeX format.

## Automatic Builds

The CV is automatically compiled into a PDF whenever changes are pushed to the main branch. The latest PDF is available as:

1. A GitHub release - check the [Releases](../../releases) page
2. A build artifact in the latest workflow run

## Manual Building

To build the CV locally, you need LaTeX installed. Then run:

```bash
# Using pdflatex directly
pdflatex cv.tex

# Or using latexmk (recommended)
latexmk -pdf cv.tex
```

## Structure

- `cv.tex` - The main LaTeX source file
- `photo.jpeg` - Profile photo
- `.github/workflows/main.yml` - GitHub Actions workflow for automatic building
