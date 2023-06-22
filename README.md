# Resume

Write your resume in Markdown and then use pandoc to turn it
into a pdf.

## How to use

```sh
$ brew install pandoc
$ brew install --cask mactex-no-gui
```

Add a `.md` doc and then convert it to PDF with

`$ pandoc -H header.tex -s resume.md -o resume.pdf`

### header.tex

Sets the top margin of the doc and uses a san-serif font rather than the default serif font pandoc would normally use.

### NOTE

This probably should have been a gist, but oh well :)
