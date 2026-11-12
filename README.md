# Lucid Jungles Bazaar Pilot Report

This repository contains the LaTeX source and supporting material for the theoretical part of the group project. The report treats Metasploitable 2 as an isolated training target representing a small hypothetical legacy-service pilot associated with Lucid Jungles' Bazaar. It does not claim that a real city service was tested.

This repository copy omits group members' names and student numbers. Use the separately retained, identified submission copy for the course submission; this sanitized repository copy is for project documentation and source.

## Files

- `report.pdf`: compiled theoretical report
- `report.tex`: report source
- `references.bib`: author-date bibliography
- `literature_matrix.csv`: comparison matrix for the related-work section
- `rubric_traceability.md`: checklist mapping the draft to the Part 1 criteria
- `.gitignore`: excludes LaTeX build intermediates

## Build

With Tectonic installed, run:

```sh
tectonic report.tex
```

Alternatively, compile with a standard LaTeX installation that includes BibTeX:

```sh
pdflatex report.tex
bibtex report
pdflatex report.tex
pdflatex report.tex
```

## Scope and evidence

This Part 1 package stores the report, its source, research comparison, bibliography, and rubric mapping. It contains no completed practical scan results. No scan, vulnerability validation, exploit test, or mitigation retest is represented as completed.

When the approved practical lab work is performed, add the actual service inventory, tool versions and settings, carefully redacted evidence, validated findings, risk register, mitigations, and retest results. Keep the target isolated and use synthetic data only.

## Online repository

The Part 1 report and supporting documentation are stored in this private GitHub repository: https://github.com/gosi-dev/lucid-jungles-bazaar-security-assessment. The report includes this link because the Moodle submission form has no text field. The repository copy omits group members' names and student numbers.

The instructor must be granted access to the private repository for review. Do not publish credentials, genuine personal data, unredacted scan output, or private network details.

No practical scan results are included because the lab assessment has not yet been performed. When the approved practical lab work is performed, add the actual service inventory, tool versions and settings, carefully redacted evidence, validated findings, risk register, mitigations, and retest results. Keep the target isolated and use synthetic data only.
