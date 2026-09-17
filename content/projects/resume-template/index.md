---
title: "Resume Template"
date: 2026-03-03
slug: "resume-template"
tags: ["resume", "template", "latex"]
github: "https://github.com/hem4nt-kum4r/my-resume"
summary: "Most of the resume template available online looked a little too fancy, cramped with a lot of information and less structured. I have tried to keep a formal and simple format with focus on make the information gathering linear and predictable."
thumbnails: ["preview.jpg"]
---

The template provides a formal and professional appearance while making relevant information easy to scan and consume. Its clean and minimal design is ATS-friendly, achieving an **ATS score of 9/10**.

### Structure of the Template

The template offers a flexible structure that allows sections to be rearranged and important information to be highlighted based on the requirements of the role.

Professional Summary
: A concise overview of professional experience, with an emphasis on domain expertise and key technical competencies.

Experience
: A detailed account of professional experience, including company and designation details, followed by concise bullet points high: lighting key projects, responsibilities, and their impact on the organization.

Education
: A summary of the candidate's academic background and educational journey.

Technical Skills
: A categorized list of technical skills across relevant domains, making key competencies easy to identify.

Academic Projects
: A selection of significant academic projects completed during the candidate's education, highlighting relevant technical experience and practical application.

Achievements
: A list of notable awards, accomplishments, and other recognitions earned throughout the academic or professional journey.

### Getting Started

The template consists of two files:

* `fara-resume.sty` — the LaTeX style file that defines the resume's layout and formatting.
* `main.tex` — the content file containing the resume information.

To create your own resume, copy both files into a new LaTeX project and update the content in `main.tex` with your details.

One of the easiest ways to get started is with [Overleaf](https://www.overleaf.com). Create a new blank project, add both files, and edit `main.tex` to customize the resume.

The document font can be customized using the fonts available in `fontenc` package. Following are the fonts which I like and the documents looks profressional and polished.

```tex {linenos=inline style=monokailight}
\usepackage[default]{raleway}
\usepackage[sfdefault,light]{roboto}
\usepackage[sfdefault]{overlock}
\usepackage[defaultfam,light,tabular,lining]{montserrat}
\usepackage[default]{sourcesanspro}
```

{{< pdf src="resume.pdf" >}}