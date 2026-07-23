# Engineering Challenges

A collection of 30 English-language engineering case studies for **Section Européenne – Sciences de l’Ingénieur**.

The chapters combine technical reading, engineering vocabulary, quantitative applications, graphical interpretation, design challenges and speaking activities. The current publication target is **Version 4.0 (July 2026)**.

## Contents

- EC01 to EC30 in `work_ec08/chapters/`
- Main LaTeX source: `work_ec08/main.tex`
- Shared style package: `work_ec08/engineeringchallenges.sty`
- Data files for PGFPlots figures: `work_ec08/data/`

## Building the manual

Compile `work_ec08/main.tex` from the `work_ec08` directory with a recent LaTeX distribution. A typical command is:

```bash
latexmk -pdf main.tex
```

The generated publication file is `work_ec08/main.pdf`.

## Version history

| Version | Date | Main scope |
|---|---|---|
| V1 | Initial release | First collection and initial chapter structure. |
| V2 | Earlier revision | Layout, illustrations and graphical presentation improved. |
| V3 | Earlier revision | Collection expanded and engineering orientation strengthened. |
| **V4.0** | **July 2026** | Complete editorial revision of EC01–EC30 for Terminale SI, with B2/C1 technical English, measurable objectives, quantitative work and harmonised figures. |

### V4.0 editorial programme

The complete V4 revision was delivered in six chapter lots:

| Pull request | Chapters | Scope |
|---|---|---|
| [#7](https://github.com/TholusSII/Engineering-Challenges/pull/7) | EC01–EC05 | First V4 editorial lot. |
| [#8](https://github.com/TholusSII/Engineering-Challenges/pull/8) | EC06–EC10 | Second V4 editorial lot. |
| [#9](https://github.com/TholusSII/Engineering-Challenges/pull/9) | EC11–EC15 | Third V4 editorial lot. |
| [#10](https://github.com/TholusSII/Engineering-Challenges/pull/10) | EC16–EC20 | Fourth V4 editorial lot. |
| [#11](https://github.com/TholusSII/Engineering-Challenges/pull/11) | EC21–EC25 | Fifth V4 editorial lot. |
| [#12](https://github.com/TholusSII/Engineering-Challenges/pull/12) | EC26–EC30 | Final V4 editorial lot. |

Main V4 improvements:

- technical English targeted at B2/C1 level;
- clearer and measurable learning objectives;
- stronger links between physical principles and engineering decisions;
- systematic quantitative applications and order-of-magnitude reasoning;
- increased emphasis on modelling, measurement, uncertainty and validation;
- engineering challenges including specifications, trade-offs, safety and lifecycle analysis;
- harmonised TikZ and PGFPlots figures for the two-column layout;
- consistent chapter organisation across the complete collection.

## Publication status

The LaTeX source identifies the manual as **Version 4.0 – July 2026** and includes a revision-history page before the table of contents. The PDF should be regenerated from the source whenever a publication version changes.
