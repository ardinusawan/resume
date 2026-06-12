# Ardi Nusawan Resume

Professional resume in LaTeX format optimized for international job applications.

## Preparation

### Install TeX Live (macOS)
If you have **basictex** installed:
```bash
sudo tlmgr update --self
sudo tlmgr install titlesec marvosym enumitem fancyhdr geometry
```

If you don't have TeX Live, install the minimal version:
```bash
brew install basictex
```

Note: The `fullpage` package is obsolete and has been replaced with `geometry`.

## Build

Generate the PDF:
```bash
pdflatex resume.tex
```

This will create `resume.pdf` in the current directory.

## Features

- **Single-page layout** optimized for quick scanning
- **International-friendly** with expanded acronyms and company names
- **Professional formatting** with proper margins and spacing
- **Action-oriented descriptions** highlighting achievements

## License

MIT
