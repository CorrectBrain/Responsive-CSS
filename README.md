# Responsive CSS

A graphical eBook about Responsive CSS, created and designed by multi-agent
system using LuaLaTeX.

The entire workflow—including question processing, LuaLaTeX generation, error
handling, spatial analysis, accuracy checks, and compilation—is performed
autonomously by agents without human intervention.

## Available Chapters

### Chapter 7: Flexible Media: Images, Art Direction, & Scalable Graphics

- 31 conceptual questions
- 77 LuaLaTeX source files
- 77 corresponding PDF visualizations

[Browse Chapter 7](chapter-07-flexible-media/README.md)

## Repository Structure

Each question has a stable numbered directory. Every LuaLaTeX source file has
a matching PDF with the same filename.

```text
q01-intrinsic-image-dimensions/
├── diagram-01.tex
├── diagram-01.pdf
├── diagram-02.tex
├── diagram-02.pdf
├── diagram-03.tex
└── diagram-03.pdf
```

## Compiling the Source

Compile an example with a recent TeX Live installation:

```bash
lualatex -interaction=nonstopmode -halt-on-error -file-line-error diagram-01.tex
```

The LaTeX packages referenced by the source file must be installed.

## Licensing

Copyright © 2026 CorrectBrain.

- LuaLaTeX source files (`.tex`) are licensed under the MIT License.
- Questions, documentation, and generated PDFs are licensed under the Creative
  Commons Attribution 4.0 International License (CC BY 4.0).
