# Tools used for StatEasy

## Communication

### Discord

[linkToDiscord](https://discordapp.com/)

- For text chat and vocal chat 
  - It uses a limited version of the markup language Markdown [more informations here](https://support.discordapp.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)
  - It supports webhooks with github [more informations here](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks), see also #githubnotifications text channel in Discord server StatEasy

## Reports

### Quick reports

#### Mardown

For the redaction of "quick" reports or README files in StatEasy repository we use the markup language Markdown

- Mardown is an easy markup language [more informations here](https://daringfireball.net/projects/markdown/syntax)
- With [Pandoc](#pandoc) it can be easily converted to HTML, LaTeX, PDF, etc
- README.md are directly compiled and shown on Github
- Github officially support it [more informations here](https://guides.github.com/features/mastering-markdown/)

### Good quality reports

#### LaTeX
For the redaction of "heavy", complexe, reports we use [LaTeX](https://www.latex-project.org/about/)

- It permit to do high quality reports.
- *We may use tools as Sharelatex if we need to do collaborative work on reports redaction [more about Sharelatex](https://www.sharelatex.com/)*

## Converter

### pdflatex

pdflatex is a converter/compiler for LaTeX to PDF.
It comes with TeX/LaTeX distributions like [TeX Live](https://www.tug.org/texlive/) on Linux systems of [MikTeX](https://miktex.org/) on Windows.

### Pandoc

Pandoc a universal document converter.
It can easily convert markdown to HTML or LaTeX or PDF (using pdflatex) [more informations here](http://pandoc.org/).

## Versioning and project management

### Git

For the versioning we use [Git](https://git-scm.com/).

### Github

For storage of repositories we use [Github](https://github.com).
StatEasy repository is [here](https://github.com/bdelseny/StatEasy).
Github provide a lot of tools for project management like issues, projects, milestones, labels, etc.
[More informations here](https://github.com/features).