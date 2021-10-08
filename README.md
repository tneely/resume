# resume

An unnecessarily complicated resume generator.

## Basics

On commit, this repository uses the `resume.tex` LaTeX file to build the resume into a PDF, image for the README, and webpage for GitHub pages.

## Development

If you want to develop locally, pick your favorite mode to get started.

### Easy Mode

Install Docker and run the following commands to generate a PDF from `resume.tex`:

```shell
docker run --rm --volume "`pwd`:/data" --user `id -u`:`id -g` pandoc/latex resume.tex -o resume.pdf --quiet
```

### Hardish Mode

Install your favorite LaTex distribution (I recommend [TeX Live](https://www.tug.org/texlive/)) and run `latexmk` to generate a PDF of the resume.

Once installed, you can also leverage tools like the LaTeX Workshop extension in VSCode to quickly preview the doc.

## Result

![A photo of a resume](dist/resume.jpg)

Check out the [PDF](dist/resume.pdf) and [page](https://tneely.github.io/resume/) too!
