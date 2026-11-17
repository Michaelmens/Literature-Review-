# Literature Review

This repository holds source material associated with a life-cycle-related literature review. It currently contains research/reference files rather than a documented, buildable manuscript.

## Files

- `Lifecycle .txt` — a large text file. Its contents, source, and extraction method should be documented so it can be interpreted and reproduced.
- `new 1.bib` — a BibTeX bibliography file.
- `savedrecs.bib` — a BibTeX bibliography file.

The bibliography files may overlap. Before using them as the review’s canonical references, compare and deduplicate their records and document how each export was generated.

## Getting started

There is no manuscript source or automated build command in the repository at present. To work with the bibliography files, open them in a text editor or import them into a reference manager that supports BibTeX. Keep an untouched copy of source exports before cleaning or merging them.

## Suggested organization

As the review develops, consider separating materials by purpose, for example:

```text
references/   cleaned and documented bibliography
source-data/  text extracts and other research inputs
manuscript/   the review source files and figures
```

Add a README note for each dataset describing its source, date, format, and any usage or redistribution restrictions. If the manuscript is written in LaTeX, include its `.tex` sources and document the build command here.
