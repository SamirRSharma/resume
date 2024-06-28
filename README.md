
A single-page, one-column resume for software developers. This is a fork I made. I also added my cover letter to this. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The four main sections in the resume are education, experience, projects, and skills.

### Motivation

I thought this would be a unique way to show off my skills while recreating my resume. Also allows me to customize it in ways a Google Docs resume cannot.

 -------------------------
**Info if you want to make your own!** (everything below this is from Sourabh Bajaj with slight changes from me)

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
