# Engineering Challenges

A collection of 30 English-language engineering case studies for **Section Européenne – Sciences de l’Ingénieur**.

The chapters combine technical reading, engineering vocabulary, quantitative applications, graphical interpretation, design challenges and speaking activities. The current publication target is **Version 4.0 (July 2026)**.

## Contents

- EC01 to EC30: `work_ec08/chapters/`
- Main LaTeX source: `work_ec08/main.tex`
- Shared style package: `work_ec08/engineeringchallenges.sty`
- Data files for PGFPlots figures: `work_ec08/data/`
- Compiled PDF: `work_ec08/main.pdf`

## Build locally

From the `work_ec08` directory, run:

```bash
latexmk -pdf -file-line-error -halt-on-error -interaction=nonstopmode main.tex
```

The generated publication file is `work_ec08/main.pdf`.

## Build with GitHub Actions

After the workflow is merged into `main`, open:

**Actions → Compile Engineering Challenges PDF → Run workflow**

Choose the branch to compile, then launch the workflow. The generated PDF is available at the bottom of the workflow run as the artifact **Engineering-Challenges-PDF**.

The workflow also runs automatically on pull requests and pushes that modify the LaTeX project.

## Version history

| Version | Date | Main scope |
|---|---|---|
| V1 | Initial release | First collection and initial chapter structure. |
| V2 | Earlier revision | Layout, illustrations and graphical presentation improved. |
| V3 | Earlier revision | Collection expanded and engineering orientation strengthened. |
| **V4.0** | **July 2026** | Complete editorial revision of EC01–EC30 for Terminale SI, with B2/C1 technical English, measurable objectives, quantitative work and harmonised figures. |

### V4.0 editorial programme

| Pull request | Chapters | Scope |
|---|---|---|
| [#7](https://github.com/TholusSII/Engineering-Challenges/pull/7) | EC01–EC05 | First V4 editorial lot. |
| [#8](https://github.com/TholusSII/Engineering-Challenges/pull/8) | EC06–EC10 | Second V4 editorial lot. |
| [#9](https://github.com/TholusSII/Engineering-Challenges/pull/9) | EC11–EC15 | Third V4 editorial lot. |
| [#10](https://github.com/TholusSII/Engineering-Challenges/pull/10) | EC16–EC20 | Fourth V4 editorial lot. |
| [#11](https://github.com/TholusSII/Engineering-Challenges/pull/11) | EC21–EC25 | Fifth V4 editorial lot. |
| [#12](https://github.com/TholusSII/Engineering-Challenges/pull/12) | EC26–EC30 | Final V4 editorial lot. |
| [#13](https://github.com/TholusSII/Engineering-Challenges/pull/13) | Publication metadata | Version history and V4 identification. |
| [#14](https://github.com/TholusSII/Engineering-Challenges/pull/14) | CI prototype | First PDF compilation workflow, merged outside `main`. |

### Main V4 improvements

- technical English targeted at B2/C1 level;
- clearer and measurable learning objectives;
- stronger links between physical principles and engineering decisions;
- systematic quantitative applications and order-of-magnitude reasoning;
- increased emphasis on modelling, measurement, uncertainty and validation;
- engineering challenges including specifications, trade-offs, safety and lifecycle analysis;
- harmonised TikZ and PGFPlots figures;
- consistent chapter organisation across the complete collection.

## Publication status

The LaTeX source identifies the manual as **Version 4.0 – July 2026** and includes a revision-history page before the table of contents. The PDF must be regenerated from the source whenever a publication version changes.
