# Resume

My resume and cover letter, writen in latex.

## Dependencies

```bash
brew install basictex
sudo tlmgr install enumitem
```

## Build instructions

```bash
# Resume
pdflatex resume.tex

# Cover letter
pdflatex "\\def\\company{Company Name}\\def\\position{Job Title}\\input{letter}"
```
