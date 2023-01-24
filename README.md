# Template for response to peer review of scientific article

The template source is the markdown file `response.md`, which uses a minimal preamble provided in `preamble.tex` that makes quote blocks pop out, which is nice for the response.

To render the response into a PDF file, you can use this command:
```bash
Rscript -e "library(rmarkdown);  library(utils); render('response.md')"
```
See the provided `response.pdf` for the expected output.

There are many other ways to render markdown files that may work as well.
However, `pandoc response.md -o response.pdf` does not work, since it appears to ignore the preamble, therefore it does not highlight the quote blocks correctly (so don't use that).
