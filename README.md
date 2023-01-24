# Template for response to peer review of scientific article

The template source is the markdown file `response.md`, which uses a minimal preamble provided in `preamble.tex` that makes quote blocks pop out, which is nice for the response.

To render the response into a PDF file, you can use this command (or whatever you usually do to render markdown files):
```bash
Rscript -e "library(rmarkdown);  library(utils); render('response.md')"
```
