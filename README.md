# latex-templates
Personal Templates for LaTeX documents

## Available Templates
----

### 1. Article Template   

```bash
article_template/
├── content
│   ├── appendix.tex
│   ├── content.tex
│   └── frontmatter.tex
├── customisation
│   └── custom.sty  *custom latex commands go here*
├── main.tex
└── references.bib
```

### 2.Report Template
```bash
report_template
├── assets
│   └── <non tex assets go here like images>
├── chapters
│   ├── chapterone.tex
│   └── chaptertwo.tex
├── customisation
│   └── mptikz.sty
├── frontmatter
│   ├── appendix.tex
│   └── frontmatter.tex
├── references
│   └── references.bib
├── main.tex  
```



### Device Info:
----
- device: wsl2 ubuntu 20.04
- latex version: texlive 2022 installed using linuxbrew
- compile pipeline: lualatex -> biber -> lualatex -> lualatex
  