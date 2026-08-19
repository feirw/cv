# Eleni Zafeiri — Resume

LaTeX source for my software engineering resume.

- [GitHub](https://github.com/feirw)
- [LinkedIn](https://www.linkedin.com/in/elenizafeiri)
- [Website](https://elenizafeiri.com)

## Build

You need a TeX distribution with `pdflatex` ([TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)).

```bash
pdflatex cvvv.ltx
```

This writes `cvvv.pdf` in the same folder. Run it twice if links or references look stale.

## Files

| File | Role |
| --- | --- |
| `cvvv.ltx` | Resume source |
| `.github/workflows/static.yml` | Deploy to GitHub Pages |

## Template

Based on [sb2nov/resume](https://github.com/sb2nov/resume) (MIT).
